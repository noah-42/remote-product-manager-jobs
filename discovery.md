# Jobscout discovery coverage

[All job listings](https://github.com/noah-42/job-listings) · [Screened Europe](europe.md) · [Screened USA](usa.md)

First pass: 27 pages exhausted, 5,307 raw global records for active remote Product Manager title tokens with a 200+ character description. Final cursor: null. This is NOT 5,307 eligible jobs. Query title tokens also return product marketing and other false positives.

1,236 clear title/junior/exact-URL exclusions; 4,071 title-triaged candidates, including 1,695 USA-hint, 684 Europe-hint and 1,692 other/unknown. Region hints do not establish hiring eligibility. Full-detail screening and semantic dedup continue. The second pass omitted complete=true and exhausted 28 pages, returning 5,540 records. [233 additional raw matches](catalogue/additional-233.md) are separate and unassessed; this closes the missing-description discovery gap for this query, not eligibility screening.

[Raw summaries CSV/JSON and title exclusions (ZIP)](1-discovery-data.zip)

| API geography hint | Candidate page | Rows |
| :--- | :--- | ---: |
| USA | [Part 1](catalogue/catalogue/usa-1.md) | 300 |
| USA | [Part 2](catalogue/catalogue/usa-2.md) | 300 |
| USA | [Part 3](catalogue/catalogue/usa-3.md) | 300 |
| USA | [Part 4](catalogue/usa-4.md) | 300 |
| USA | [Part 5](catalogue/usa-5.md) | 300 |
| USA | [Part 6](catalogue/usa-6.md) | 195 |
| Europe | [Part 1](catalogue/catalogue/europe-1.md) | 300 |
| Europe | [Part 2](catalogue/catalogue/europe-2.md) | 300 |
| Europe | [Part 3](catalogue/catalogue/europe-3.md) | 84 |
| Other or unknown | [Part 1](catalogue/other-or-unknown-1.md) | 300 |
| Other or unknown | [Part 2](catalogue/other-or-unknown-2.md) | 300 |
| Other or unknown | [Part 3](catalogue/other-or-unknown-3.md) | 300 |
| Other or unknown | [Part 4](catalogue/other-or-unknown-4.md) | 300 |
| Other or unknown | [Part 5](catalogue/other-or-unknown-5.md) | 300 |
| Other or unknown | [Part 6](catalogue/other-or-unknown-6.md) | 192 |

No salary estimates invented. API salary periods may be missing. Catalogue is candidate evidence, not employer validation. No new recurring refresh.

## Detail-screening increment, Nov 12, 17:40

40 rows now retained in human pages and current exports (13 Europe, 27 USA), up from 32. Eight additional detail-screened IDs: 3371403, 456587, 3269338, 3345918, 3331980, 3369020, 3274563, 3305031. Openprovider geography unresolved and Indeed deadline conflict remain visible. 63 full details are held; 23 not yet published, including uncertain and excluded candidates. Raw catalogue totals are not eligibility totals.
