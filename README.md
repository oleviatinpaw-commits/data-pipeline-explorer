# Where Your Data Goes

An interactive explainer showing how personal data is collected, joined into a profile, and turned into a price, across housing, grocery retail, and higher education.

**Authors:** Olevia Tinpaw & Zainab Raza · University of Maryland · October 2026

## What's on the page

1. **One page load.** Simulates a typical ad-supported page loading: first-party request, tag manager, analytics, social pixel, header bidding, three ad exchanges fanning out to bidders, fingerprinting, and a broker beacon. Click any request or network node to inspect the fields it carried (modeled on OpenRTB bid requests).
2. **The profile.** Toggle six data sources (browser trackers, app SDKs, loyalty card, public records, court records, standardized tests) and watch shared keys join them into one profile, including inferred fields nobody supplied.
3. **The price.** A simplified demand model: as the model learns more about you, the revenue-maximizing price moves away from the list price. Education mode shows the same logic as a financial-aid award.
4. **Industries.** Documented evidence for housing (RealPage, tenant screening), grocery (Instacart, Maryland HB 895), and education (EAB, College Board), each labeled Verified, Alleged, or No law.

## Accuracy notes

- Page-load counts are illustrative, not measurements of any specific site.
- Allegations in pending litigation (e.g. Maryland v. RealPage) are labeled as allegations.
- No source shows location or browsing data feeding college aid models; the page does not claim it.

## Run it

Open `index.html` in a browser. No build step and no dependencies beyond Google Fonts.
