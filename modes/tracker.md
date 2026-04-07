# Mode: tracker — Application Tracker

Read and display `data/applications.md`.

**Tracker format:**
```markdown
| # | Date | Company | Role | Score | Status | PDF | Report |
```

Canonical statuses: `Evaluated` → `Applied` → `Responded` → `Interview` → `Offer` / `Rejected` / `Discarded` / `SKIP`

- `Applied` = candidate submitted the application
- `Responded` = a recruiter/company reached out and the candidate responded (inbound)
- `Interview` = actively in an interview process

If the user asks to update a status, edit the corresponding row in `data/applications.md`.

Also display statistics:
- Total applications
- Breakdown by status
- Average score
- % with PDF generated
- % with report generated
