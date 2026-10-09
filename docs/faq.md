# BnBDetector FAQ

## Product basics

### What is BnBDetector?

BnBDetector (https://www.bnbdetector.com) shows how much active Airbnb activity surrounds an address. You enter a building, and the report returns a BnBIndex from 0 to 100, the number of active Airbnb listings nearby, a category, a short verdict, and an activity scale from quiet to Airbnb-heavy.

People use it before they sign a lease, buy, renew, or advise a client. A lower score is the quieter residential signal.

### How does a check work?

1. Sign in and choose a plan. Each new address uses one report.
2. Enter the address and pick the matching suggestion.
3. BnBDetector locates the address and counts active Airbnb listings nearby. The current search area is about an 80-meter radius.
4. That count is turned into a BnBIndex and a category.
5. The report appears, usually in under 10 seconds, and is saved to your account.

### Who is it for?

Anyone who will live with the result: long-term renters, buyers, families, nomads, remote workers, relocating professionals, students, retirees, expats, neighbors, and the agents or relocation teams helping them.

It is a weak fit if you need hosting revenue, occupancy, or nightly pricing. Those are host-analytics questions. See [BnBDetector vs AirDNA](vs/airdna.md).

### Does BnBDetector work worldwide?

You can enter addresses worldwide. The check depends on being able to locate the address and on Airbnb listing data near it. A rural or incomplete address may not resolve. Use the suggestion list.

The interface is available in English, German, Spanish, French, Indonesian, Japanese, Korean, Malay, Portuguese (Portugal and Brazil), Thai, and Vietnamese.

### How long does a report take?

Most reports finish in under 10 seconds. A few take longer. There is no queue you join.

## The score

### What is the BnBIndex?

The BnBIndex is BnBDetector’s 0–100 score for nearby Airbnb activity. It is calculated from the count of active Airbnb listings detected around the address, so you can compare buildings without interpreting raw counts alone.

- **0–9, Local Haven.** No short-term rental activity detected nearby.
- **10–30, Residential Core.** A few listings. Still mostly residential.
- **31–58, Mixed Community.** Noticeable activity.
- **59–100, Airbnb Dominated.** Heavy concentration. Some pages say “BnB Dominated” for this same band.

Full reading notes: [How to read a BnBIndex report](how-to-read-a-report.md).

### What does “Airbnbs nearby” mean?

It is the count of active Airbnb listings in a small area around the address, about 80 meters in the current product. That includes the immediate surroundings, so a listing next door can be part of the number. It does not list apartment numbers, and it is not a count for the whole neighborhood.

### Does a high score mean my exact unit is an Airbnb?

No. It means listing activity was detected nearby. Airbnb does not publish exact pins before a booking, so the report cannot certify that one apartment is the listing. Use the score to judge pressure on the address. Use a visit, photos, and the building’s own records when you need a specific unit.

### Does the score include Vrbo, Booking.com, or other sites?

The report counts Airbnb listings. A place that is listed only on another platform can be missing. If that matters, search those sites for the same block as a second pass. Expect that to be slower and less comparable.

### Is a low score a promise of quiet?

No. Local Haven means no Airbnb activity was detected nearby at the time of the check. Construction, bars, thin ceilings, house parties, and other platforms are outside the score. New Airbnb listings can appear later.

### Is a high score proof that hosting there is illegal?

No. The score is detected listing activity. Whether those listings are allowed depends on local law, the lease, and building or HOA rules. BnBDetector does not check permits and does not give legal advice. Background guides: https://www.bnbdetector.com/en/guides/regulations

### How accurate are the results?

The report is based on live Airbnb listing data near the address, summarized as a count and a 0–100 score. Accuracy has the limits above: approximate pins, Airbnb-only coverage, and data that changes. The Terms of Service do not guarantee complete accuracy and tell you to verify important decisions independently. Check again close to the day you commit. Max and Ultra can reCheck a saved address once a month without spending a report.

### Can I compare several buildings?

Yes. Run each address and compare the scores and counts. A band change matters more than a few points inside the same band. Max and Ultra keep a report history and let you browse it by city and country, which helps when the search is large. Starter is a 10-report pack without that library.

### What if there is no score?

The address may not have been located. Try a fuller street address from the suggestions. A score needs a place the product can pin.

## Plans, reports, and billing

### How much does it cost?

Three plans. Prices below are the published prices when this FAQ was written. Confirm them at https://www.bnbdetector.com/en/pricing.

- **Starter:** $19 one time, 10 reports. For a first move or a short list.
- **Max:** $29 per month, 25 reports per month. The plan marked most popular.
- **Ultra:** $59 per month, 60 reports per month. The highest monthly allowance.

Every plan shows the same report.

### What is the difference between Starter, Max, and Ultra?

Volume and workflow.

- Starter: 10 reports, no monthly reset. No full report history and no browse-by-city or browse-by-country.
- Max: 25 reports each billing cycle, free reCheck once per address each month, full history, browse by city and country.
- Ultra: 60 reports each billing cycle, with the same tools as Max.

### What is reCheck?

reCheck refreshes a saved address with current listing data. It is included on Max and Ultra, it does not spend a report, and you can use it once per address each month. Use it in the last days before you sign or close.

### Do unused reports roll over?

Starter reports are a one-time pack and are not reset each month. The pricing page and Terms of Service describe them as not expiring. Max and Ultra balances reset when the billing cycle renews. Unused subscription reports do not roll over.

### Does checking the same address twice cost two reports?

A new address costs one report. Checking that same address again soon may show the recent result without spending another report. A deliberate refresh is reCheck, on Max and Ultra, once per address each month.

### Can I cancel?

Yes. Cancel a monthly plan from dashboard settings or from the customer portal link in your payment email. You keep access until the end of the period you have paid for. You can resubscribe later. Saved reports remain available under the rules of the plan.

You can switch between Max and Ultra from dashboard settings.

### Are payments secure?

Payments go through Paddle. BnBDetector does not store your card details. Paddle’s own terms apply alongside BnBDetector’s.

### Do you offer refunds?

Refund requests are reviewed case by case. Submit them within 14 days of purchase to team@bnbdetector.com. Once report generation starts, the digital service is treated as delivered and the statutory right to cancel ends. Refunds may be refused where there is fraud, manipulation, or abuse. The Terms of Service control: https://www.bnbdetector.com/en/tos

### Is there a public API or a team plan?

This documentation does not describe a public API. Agencies that need more than 60 checks a month, several seats, or an integration can write through https://www.bnbdetector.com/en/contact.

### Do I need an account?

Yes. Sign in with Google. The account is free. A plan is required to generate reports. You must be 18 or older.

## Privacy

### Can landlords or agencies see my searches?

No. The report stays on your account. Checking an address does not notify the owner, the manager, the agent, or the building.

### Do you sell my data?

No. BnBDetector does not sell or trade personal data. The account stores your sign-in details, the addresses you check, the reports, and subscription status so the service can run. Cookies and analytics are described in the Privacy Policy: https://www.bnbdetector.com/en/privacy-policy

The address is submitted in order to create the report. Do not assume the check happens entirely on your device.

### Who handles sign-in and payments?

Google handles sign-in. Paddle handles payments. Both are named in the public Privacy Policy and Terms.

## Already living there

### How do I tell if a neighbor is hosting?

Visible clues include rotating guests with luggage, a lockbox, cleaners between stays, and weekend-heavy noise. None of those alone proves a listing. A BnBDetector report adds the nearby Airbnb count and a score for the address. It still does not name the unit. Read [BnBDetector for neighbors](for/neighbors.md).

### Can I use a report in a complaint?

You can attach it as a dated description of detected nearby activity: address, date, score, and count. It is not a government finding and not proof of a specific illegal unit. Pair it with your own log of dates and times, the lease or house rules, and the city’s complaint process. BnBDetector does not file complaints for you.

### Can an HOA ban short stays?

In many places, yes, through the building’s governing documents. Whether a ban exists, and whether it is being followed, are questions for those documents and for local law. The report only shows detected Airbnb activity nearby.

## Support

Product, billing, and refund questions: team@bnbdetector.com or https://www.bnbdetector.com/en/contact. Signed-in users can also use the in-app chat.

For how to run the first check, use the [getting started guide](getting-started-guide.md).
