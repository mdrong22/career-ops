# Mode: deep — Deep Research Prompt

Generates a structured research prompt for Perplexity/Claude/ChatGPT across 6 axes. Read `cv.md` and `config/profile.yml` first to personalize Section 6.

```
## Deep Research: [Company] — [Role]

Context: I'm evaluating an application for [role] at [company]. I need actionable intel for the interview.

### 1. Engineering culture
- How do they ship? (deploy cadence, CI/CD practices)
- Mono-repo or multi-repo?
- What languages and frameworks do they use?
- Remote-first or office-first?
- Glassdoor/Blind reviews about eng culture?

### 2. Recent moves (last 6 months)
- Notable hires in engineering or product?
- Acquisitions or partnerships?
- Product launches or pivots?
- Funding rounds or leadership changes?

### 3. Tech stack signals
- What does their job postings reveal about their stack?
- Do they have an engineering blog? What do they publish?
- Any open-source projects or conference talks?

### 4. Likely challenges
- What scaling problems do they have?
- Reliability, cost, or latency challenges?
- Are they migrating anything? (infra, platforms, languages)
- What pain points do people mention in reviews?

### 5. Competitors and differentiation
- Who are their main competitors?
- What is their moat / differentiator?
- How do they position themselves vs. competition?

### 6. Candidate angle
Given my profile (read from cv.md and profile.yml):
- What unique value do I bring to this team?
- Which of my projects are most relevant?
- What story should I tell in the interview?
```

Personalize each section with context from the evaluated offer and the candidate's profile.
