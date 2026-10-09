# How to Read a BnBIndex Report

A BnBDetector report is a short document on purpose. It tells you how much active Airbnb activity was detected around one address, and it puts that activity on a 0–100 scale you can compare.

Read the count and the score together. The count is the evidence. The score is the summary.

## The parts of the report

Every plan shows the same fields.

**Airbnbs nearby.** The number of active Airbnb listings detected around the address. In the current product that area is about an 80-meter radius: the building and its immediate surroundings. It is not the neighborhood, and it is not an inventory of flats inside one entrance.

**BnBIndex.** A number from 0 to 100 derived from that nearby listing count. Lower means less detected Airbnb activity. Higher means more. The number exists so a 14 and a 76 can be compared without interpreting raw counts from scratch every time.

**Category.** The band the score falls into.

**Verdict.** One or two sentences in plain language for that band.

**Activity scale.** A bar from Quiet to Airbnb heavy, with the address marked on it.

**Last checked.** The date of the data, when the report has one. Treat an old date as a reason to refresh, not as a current fact.

An annotated example is at https://www.bnbdetector.com/en/reports/example.

## The four bands

| Score | Category | Verdict you will see | How to use it |
| --- | --- | --- | --- |
| 0–9 | Local Haven | Quiet place. No short-term rental activity detected nearby. This looks like a stable residential area. | Strong residential signal. Still visit, and still read the lease. |
| 10–30 | Residential Core | Looks good. Only a few Airbnbs nearby. This is still mostly residential. | A normal urban result. Fine for most long stays if the rest of the apartment works. |
| 31–58 | Mixed Community | Heads up. There is noticeable short-term rental activity in this area. | You should expect more strangers and weekend traffic than in a quiet building. Compare it with a lower score before you accept it. |
| 59–100 | Airbnb Dominated | High BnB zone. This area is packed with short-term rentals. Expect frequent guest turnover. | A poor fit when the goal is a stable home. Some buyers want this on purpose because they plan to host. BnBDetector is not the tool that prices that plan. |

Site guides sometimes say “BnB Dominated” for the top band. On the report the label is Airbnb Dominated. The range is 59–100 either way.

Color follows the band: green through Local Haven and Residential Core, orange for Mixed Community, red for Airbnb Dominated.

## What the nearby count is actually saying

A listing count is more concrete than the score, and it has limits you should keep in mind.

**It is local.** About 80 meters is a short walk, not a district. Checking “Lisbon” or “the Gothic Quarter” does not answer the building question. Two addresses a few streets apart can land in different bands. That is the feature. Run each address.

**It can spill past the front door.** A listing pinned next door sits inside the same small area. A high count means Airbnb pressure on that spot. It does not, by itself, prove that your future unit is one of the listings.

**Pins are approximate.** Airbnb hides the exact address until a stay is booked. The detector is counting listings placed near the address, which is the right public signal, and it is not a floor plan.

**It is Airbnb.** A flat listed only on another site may not be in the number. If that gap matters, search the other site yourself for the same block. The tradeoff is covered in [BnBDetector vs searching Airbnb yourself](vs/searching-airbnb-yourself.md).

**It is a moment in time.** Hosts list, pause, and delist. A check from six weeks ago is background. ReCheck on Max or Ultra, or run the address again, close to the day you pay.

**Zero is “none detected,” not “none possible.”** Local Haven means the check found no Airbnb activity nearby. It does not mean the building has a written ban, that a host could not list next month, or that the street is quiet for other reasons.

## How to compare two addresses

Use the same three questions for each:

1. Which score is lower?
2. Is the gap a band change, or a small move inside one band? A 22 and a 28 are both Residential Core. A 28 and a 62 are different kinds of buildings.
3. Which count is lower? If the scores are close, the counts tell you whether one address simply had a few more listings.

Then add the things the report ignores: price, light, commute, the actual flat, the lease, and what you saw in person. A 15 in a flat you hate is still a bad lease. A 40 can be acceptable when every alternative in your budget is a 70 and you have seen the building on a Saturday night.

Sort a shortlist like this:

- Prefer 0–30 when you can.
- Treat 31–58 as a conscious compromise. Know which compromise you are making: more lobby traffic, less stable neighbors.
- Treat 59–100 as a reason to keep searching, unless you have a specific reason to live in a tourist building and you have confirmed you can tolerate it.

## What a score does not measure

Say these out loud before you forward a report to someone else.

- It does not measure decibels. A quiet score can sit over a bar. A high score can be well-managed hosts with firm rules. The score is listing presence.
- It does not know who is in the building tonight.
- It does not identify the host, the unit, or the listing URL as a legal exhibit.
- It does not say the activity is allowed. Permits, night caps, lease clauses, and HOA bans are separate documents.
- It does not appraise the property or predict your rent.
- It does not estimate what the owner could earn by hosting. That is a different product category. See [BnBDetector vs AirDNA](vs/airdna.md).
- It does not get more precise because you paid for a larger plan. Starter, Max, and Ultra show the same report. Larger plans change how many addresses you can check and whether you can refresh and file them.

The Terms of Service are explicit: reports are informational, provided as-is, and not a guarantee of complete accuracy. Link: https://www.bnbdetector.com/en/tos

## How to talk about a report

Useful:

> I checked 14 Example Street on BnBDetector on 2 October. BnBIndex 71, Airbnb Dominated, 40 active Airbnb listings detected nearby.

Less useful:

> This building is illegal.
> Apartment 4B is an Airbnb.
> The city confirmed this.
> It will be quiet because the score is 8.

If you are writing to a manager, a board, or a partner, include the date, the score, the count, and the address you typed. Offer to reCheck if the date is old. Do not present the report as a government record.

## When to run it again

- You are about to pay a deposit or waive a condition.
- Tourist season is starting and the first check was in the off season. Seasonal pressure is real in many cities. The site’s seasonal guides are context: https://www.bnbdetector.com/en/guides/seasonal
- Someone tells you “that was last year.”
- You widened the search to a new street.

Max and Ultra: reCheck is free once per address each month and does not use a report. Starter: a new check uses one of the 10 reports.

## Related reading

- [Getting started](getting-started-guide.md)
- [FAQ](faq.md)
- [Ways to check Airbnb activity](ways-to-check-airbnb-activity.md)
- Glossary entry for the score: https://www.bnbdetector.com/en/glossary/bnbindex
