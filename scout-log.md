
## Scout run - 2026-03-01 02:46 EST
- Searches executed: 10 queries (5 strict site-filter + 5 fallback broad by source)
- Sources checked: LinkedIn, Indeed, Glassdoor, ZipRecruiter, Wellfound
- Candidates surfaced from search snippets: 41 total results
- New jobs queued: 0
- Notes: Applied strict gates (Summer 2026 + role family + not in log/queue + skip companies + recency <=3 days + direct apply/Easy Apply). Could not reliably validate posting recency (<=3 days) for candidates due anti-bot/JS walls and missing posted timestamps in fetched pages, so no unsafe queue inserts were made.

## Scout run - 2026-03-01 08:01 EST
- Searches executed: 10 queries (5 strict site-filter + 5 fallback broad by source)
- Sources checked: LinkedIn, Indeed, Glassdoor, ZipRecruiter, Wellfound
- Candidates surfaced from search results: 50
- New jobs queued: 0
- Duplicates skipped: 0
- Notes: Strict gate enforced (Summer 2026 + role family + skip companies + not in log/queue + direct apply/Easy Apply + posted <=3 days). Most source pages were blocked by JS/anti-bot (Wellfound/ZipRecruiter) or returned listing hubs without per-post recency; one direct LinkedIn SmartRecruiters posting was readable but did not expose a reliable posted timestamp, so it was not queued.

## Scout run - 2026-03-01 14:2x EST (subagent live)
- Discovery method: Brave web search + direct Lever/Greenhouse API verification
- Recency gate (<=3 days) enforced via Lever `createdAt`
- New jobs queued: 1
  - BHG Financial — Data Scientist Intern - Summer 2026
  - URL: https://jobs.lever.co/bhg-inc/1708cb0e-d713-4d4b-8ecf-1f71600a4e2a/apply
  - Created: 2026-02-26 UTC (within 3 days)
- Duplicates/company cap gate: enforced against existing queue+log
- Skip list gate: Qualcomm/Snowflake/Disney excluded
