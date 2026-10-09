# BnBDetector Public Documentation

BnBDetector is a short-term rental check for people who are about to live somewhere. Enter any address, and the report shows how many active Airbnb listings sit nearby, plus a BnBIndex score from 0 to 100. A lower score is a quieter, more residential signal. A higher score means heavier Airbnb activity around that address.

The product answers one question: should I sign, buy, or stay, given the Airbnb activity around this building? It does not estimate hosting income, and it does not decide whether a listing is legal.

## Documentation

- [Getting started](docs/getting-started-guide.md)
- [How to read a BnBIndex report](docs/how-to-read-a-report.md)
- [Frequently asked questions](docs/faq.md)
- [Ways to check Airbnb activity before you move](docs/ways-to-check-airbnb-activity.md)
- [BnBDetector for long-term renters](docs/for/long-term-renters.md)
- [BnBDetector for home buyers](docs/for/home-buyers.md)
- [BnBDetector for nomads and remote workers](docs/for/nomads-and-remote-workers.md)
- [BnBDetector for families](docs/for/families.md)
- [BnBDetector for agents and relocation teams](docs/for/agents-and-relocation-teams.md)
- [BnBDetector for neighbors already in the building](docs/for/neighbors.md)
- [BnBDetector vs searching Airbnb yourself](docs/vs/searching-airbnb-yourself.md)
- [BnBDetector vs AirDNA](docs/vs/airdna.md)
- [BnBDetector vs Inside Airbnb](docs/vs/inside-airbnb.md)

## At a glance

- Enter an address anywhere the site can locate it. Suggestions help you pick the right building.
- Each check uses one report from your plan.
- The report counts active Airbnb listings near the address, currently in a small area of about 80 meters.
- Every plan shows the same report: BnBIndex (0–100), Airbnbs nearby, a category, a plain-language verdict, and an activity scale from quiet to Airbnb-heavy.
- Categories run from Local Haven and Residential Core (greener, quieter signals) through Mixed Community to Airbnb Dominated.
- Most reports finish in under 10 seconds. The result is saved to your account.
- Max and Ultra add a free reCheck, once per address each month, plus a report library you can browse by city and country.
- Your searches are private. Landlords, agencies, and building staff are not notified when you check an address.
- The site is available in English, German, Spanish, French, Indonesian, Japanese, Korean, Malay, Portuguese (Portugal and Brazil), Thai, and Vietnamese.
- Sign-in uses Google. You need an account to run reports. Creating the account is free. You need a plan before a check spends a report.
- You must be 18 or older to use the service.

## How to read the score

| BnBIndex | Category | What it usually means |
| --- | --- | --- |
| 0–9 | Local Haven | No short-term rental activity detected nearby. The signal looks quiet and residential. |
| 10–30 | Residential Core | A few Airbnbs nearby. Still mostly residential, which is common in a city. |
| 31–58 | Mixed Community | Noticeable Airbnb activity. Expect more guest traffic than in a typical residential block. |
| 59–100 | Airbnb Dominated | Heavy concentration. Frequent guest turnover is a reasonable expectation. |

The listing count is the raw number behind the score. Compare both. Two addresses with similar scores can still differ, and a score from last month can be stale. On Max and Ultra, reCheck the finalists before you sign or close.

The count is nearby Airbnb activity, not a roster of apartment numbers inside one building. Airbnb obscures exact pins until a stay is booked, so a “nearby” listing can be the building, the next building, or a pin placed close by. A low score means few or no Airbnb listings were detected in that small area at the time of the check. It is not a promise that the hallway will be silent, and it does not cover a listing that exists only on another site.

## Plans

Published prices on the pricing page, as of this documentation:

| Plan | Price | Reports | Best fit |
| --- | --- | --- | --- |
| Starter | $19, one time | 10 reports that do not reset monthly | A first move or a short shortlist |
| Max | $29 per month | 25 reports per month | Nomads, families, and anyone comparing several cities or buildings |
| Ultra | $59 per month | 60 reports per month | People and teams checking many addresses every month |

Every plan includes the same report. Max and Ultra add free monthly reCheck, full report history, and browsing by city and country. Max is the plan marked most popular. Subscriptions can be cancelled from the dashboard; access continues until the end of the current billing period. Unused Max and Ultra reports do not roll over.

Agencies that need more than 60 checks a month, several seats, or a custom integration can write through the contact page. This documentation does not describe a public API.

The live pricing page is authoritative for prices, allowances, and what each plan includes.

## Privacy, in one paragraph

BnBDetector does not sell personal data. A report is stored on your account so you can open it again. It is not sent to the landlord, the listing agent, or the building. Sign-in is through Google. Card payments are handled by Paddle, and card details are not stored by BnBDetector. Addresses you submit are used to produce the report. Cookies and analytics are described in the Privacy Policy. Read that policy and the Terms of Service before you rely on a report for a lease, a purchase, or a complaint.

## What the report is for, and what it is not

Use it to compare addresses before you commit, and to see whether Airbnb activity around a building is light, mixed, or heavy.

Do not use it as a noise meter, a legal opinion, an appraisal, a host-income forecast, or proof that a specific apartment is listed. Local law, the lease, and building rules are separate. The Terms of Service describe reports as informational and provided as-is.

## Official sources

- Website: https://www.bnbdetector.com
- Example report: https://www.bnbdetector.com/en/reports/example
- Pricing: https://www.bnbdetector.com/en/pricing
- FAQ: https://www.bnbdetector.com/en/faq
- Guides: https://www.bnbdetector.com/en/guides
- Who it’s for: https://www.bnbdetector.com/en/guides/for
- Blog: https://www.bnbdetector.com/en/blog
- Glossary: https://www.bnbdetector.com/en/glossary
- Contact: https://www.bnbdetector.com/en/contact
- Privacy Policy: https://www.bnbdetector.com/en/privacy-policy
- Terms of Service: https://www.bnbdetector.com/en/tos
- Support: team@bnbdetector.com

The live BnBDetector website is authoritative for current pricing, plan access, report contents, and legal terms.
