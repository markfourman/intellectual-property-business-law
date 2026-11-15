# Who Owns It? Who's Bound?

**Live page: https://markfourman.github.io/intellectual-property-business-law/**

A 5-minute, mobile-friendly interactive on Canadian business law. Guess the ruling in three real patent cases and one agency scenario, then see what happens when a deal crosses a border. Built for supply chain students, HR and business professionals, and instructors.

Made for **SCM850 International Business Law**, Seneca Polytechnic (Supply Chain Management).

## What's inside

| # | Topic | Case or scenario | Lesson |
|---|-------|------------------|--------|
| 1 | Patents (tech) | *Amazon.com, Inc. v. Canada (Attorney General)*, 2011 FCA 328 | Business methods are not automatically excluded from patents |
| 2 | Patents (biotech) | *Harvard College v. Canada (Commissioner of Patents)*, 2002 SCC 76 | Higher life forms (plants, animals) cannot be patented in Canada |
| 3 | Patents (agri-biotech) | *Monsanto Canada Inc. v. Schmeiser*, 2004 SCC 34 | The plant is unpatentable, but the gene and cell inside it are protected |
| 4 | Agency | Monster Road Equipment (textbook hypothetical, **not a real case**) | An internal limit on an agent only protects you if outsiders know about it |
| 5 | Private international law | Same scenario, across the border | Name the law, the court, and the arbitration route in the contract |

Each case has a plain-language story, a "You're the judge" question, a supply chain angle, and a "Use this in class" discussion prompt. The page ends with a score, a patentability ladder, an actual vs apparent authority recap, and links to my other interactives.

## Design and accessibility

Styled with a Seneca-inspired red, Canadian touches, and tech and biology motifs (DNA, circuits, binary). No official logos are used; this is a student project, not an official Seneca Polytechnic publication.

Built to WCAG 2.1 AA targets: semantic HTML, real buttons, full keyboard use, visible focus, announced reveals (`aria-live`), 4.5:1 contrast, no colour-only cues, 44px+ tap targets, and reduced-motion support. Not yet tested with a screen reader, so please report any issues.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The whole app (inline CSS and JavaScript, no libraries) |
| `preview.png` | LinkedIn and social preview image (1200 x 627) |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |
| `README.md` | This file |

## Run locally

Open `index.html` in a browser. No build step.

## Deploy on GitHub Pages

1. Put all files in the repo root on the `main` branch.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute or two, the page is live at the link above.
5. To refresh the LinkedIn preview, paste the link into the [LinkedIn Post Inspector](https://www.linkedin.com/post-inspector/).

## Fact check (November 15, 2026)

| Claim on the page | Status | Source |
|-------------------|--------|--------|
| *Harvard Mouse* decided 5-4; mouse and higher life forms not patentable | Confirmed | Siebrasse (2004); Naiberg & Roy (2002) |
| *Schmeiser* decided 5-4; infringement found; no profits owed | Confirmed | Siebrasse (2004); The Western Producer (2004) |
| Schmeiser never signed the licence | Confirmed | The Western Producer (2004) |
| US mouse patent granted in 1988 (No. 4,736,866, issued April 12, 1988) | Confirmed | WIPO (2006); Leder & Stewart (1988) |
| Amazon patent allowed December 23, 2011 | Confirmed | Osgoode (2012) |
| Australia and Canada are CISG members; both are New York Convention members | Confirmed | UNCITRAL; WIPO Lex |
| Monster Road Equipment details (Cdn$400,000 limit, 8 units, Cdn$824,000) | From the textbook, Box 9.2 | Iskra & Nicholson (2020) |

Still worth a read of the full judgments on CanLII before citing in graded work. The textbook year (2020) comes from the publisher's author listings, so confirm it against your copy's copyright page.

## References (APA)

Amazon.com, Inc. v. Canada (Attorney General), 2011 FCA 328.

Convention on the Recognition and Enforcement of Foreign Arbitral Awards, June 10, 1958, 330 U.N.T.S. 3.

Harvard College v. Canada (Commissioner of Patents), 2002 SCC 76.

Iskra, E., & Nicholson, M. J. (2020). *Legal aspects of international business: A Canadian perspective* (4th ed.). Emond Publishing.

Leder, P., & Stewart, T. A. (1988). *Transgenic non-human mammals* (U.S. Patent No. 4,736,866). U.S. Patent and Trademark Office.

Monsanto Canada Inc. v. Schmeiser, 2004 SCC 34.

Naiberg, R., & Roy, I. (2002). Harvard oncomouse unpatentable: Supreme Court delivers on long-awaited ruling on patentability of higher life forms. Mondaq. https://mondaq.com/canada/patent/20057/harvard-oncomouse-unpatentable-supreme-court-delivers-on-long-awaited-ruling-on-patentability-of-higher-life-forms

Siebrasse, N. (2004). Comment on *Monsanto Canada Inc. v. Schmeiser*. *Canadian Bar Review, 83*(3), 967. https://cbr.cba.org/index.php/cbr/article/download/4020/4013/4020

The Western Producer. (2004, June 10). Split decision on gene case: The law. https://www.producer.com/farm-family/split-decision-on-gene-case-the-law/

United Nations Convention on Contracts for the International Sale of Goods, April 11, 1980, 1489 U.N.T.S. 3.

World Intellectual Property Organization. (2006, June). Bioethics and patent law: The case of the Oncomouse. *WIPO Magazine*. https://www.wipo.int/web/wipo-magazine/articles/bioethics-and-patent-law-the-case-of-the-oncomouse-35278

York University, Osgoode Hall Law School. (2012, January 19). Amazon's one-click patent granted in Canada: A case comment on the Federal Court of Appeal decision. *The Court*. https://yorku.ca/osgoode/thecourt/2012/01/19/amazons-one-click-patent-granted-in-canada-a-case-comment-on-the-federal-court-of-appeal-decision

CISG membership: https://uncitral.un.org/en/node/3389 and New York Convention membership: https://www.wipo.int/wipolex/en/treaties/parties/973

## Disclaimer

Educational summary, not legal advice. The Monster Road Equipment scenario is adapted from a textbook and is fictional.

## Author

Mark Fourmanovskis
[LinkedIn](https://www.linkedin.com/in/mark-fourmanovskis/) · [GitHub](https://github.com/markfourman)
