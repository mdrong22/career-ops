# Mode: offers — Multi-Offer Comparison

Weighted scoring matrix across 10 dimensions:

| Dimension | Weight | Criteria 1-5 |
|-----------|--------|--------------|
| North Star alignment | 25% | 5=exact target role, 1=unrelated |
| CV match | 15% | 5=90%+ match, 1=<40% match |
| Level fit | 15% | 5=perfect level match, 4=one level up, 3=reachable stretch, 2=significant gap, 1=wrong level |
| Estimated comp | 10% | 5=top quartile, 1=below market |
| Growth trajectory | 10% | 5=clear path to next level, 1=dead end |
| Remote quality | 5% | 5=full remote async, 1=onsite only |
| Company reputation | 5% | 5=top employer, 1=red flags |
| Tech stack modernity | 5% | 5=cutting edge, 1=legacy |
| Speed to offer | 5% | 5=fast process, 1=6+ months |
| Cultural signals | 5% | 5=builder culture, 1=bureaucratic |

For each offer: score per dimension, weighted total score.
Final ranking + recommendation with time-to-offer considerations.

Ask the user for the offers if not already in context. Can be text, URLs, or references to already-evaluated offers in the tracker.
