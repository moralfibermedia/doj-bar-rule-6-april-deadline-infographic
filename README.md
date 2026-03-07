# DOJ Bar Rule — April 6 Deadline Infographic

**An interactive civic journalism tool built to drive public comment on a proposed federal rule that would shield DOJ attorneys from independent state bar oversight.**

🔗 **[View the live infographic →](https://doj-bar-rule-6-april-deadline.netlify.app)**  
📅 **Comment deadline: April 6, 2026 — Midnight Eastern / 9 PM Pacific**  
📬 **Submit directly: [regulations.gov/commenton/DOJ-OAG-2026-0001-0001](https://www.regulations.gov/commenton/DOJ-OAG-2026-0001-0001)**

---

## What This Is

The Department of Justice published a proposed rule on March 5, 2026 — **28 CFR Part 77, Docket No. OAG199** — that would give the Attorney General the right to intercept and review every state bar ethics complaint filed against a DOJ attorney before any independent investigation can proceed. State bars that refuse to stand down face active DOJ opposition under the rule's own language.

This infographic was built to make that rule legible to ordinary citizens — and to lower the friction of public participation to near zero.

**Features:**
- Live countdown clock to the April 6 comment deadline (Eastern + Pacific)
- Four-charge ethical analysis with legal citations
- Before/after comparison of independent vs. captured oversight
- Ready-to-submit comment — one tap to copy, paste directly into regulations.gov
- Step-by-step submission instructions with expected character count confirmation
- Direct link to the federal comment portal
- Dive Deeper section linking to the full Federal Register rule and the Administrative Procedure Act

---

## The Rule in Plain Language

The McDade Amendment (28 U.S.C. 530B) was enacted in 1998 to *subject* DOJ attorneys to state bar oversight — the same accountability that applies to every other lawyer in America. This proposed rule inverts that intent. It gives the AG's own office — which supervises the accused attorneys — the right to review, delay, and effectively control every ethics investigation before independent oversight can begin.

The DOJ cannot ethically police itself. The proposed §77.5(b) would authorize the Department to take "appropriate action" against any state bar that refuses to stand down.

**The public comment window closes April 6, 2026.** Under the Administrative Procedure Act, the DOJ is legally required to read and respond to every substantive objection before this rule can be finalized. Your comment enters the official federal record.

---

## How to Use This

### View the live infographic
Open `index.html` in any browser, or visit the live Netlify deployment linked above.

### Submit a comment
1. Visit [regulations.gov/commenton/DOJ-OAG-2026-0001-0001](https://www.regulations.gov/commenton/DOJ-OAG-2026-0001-0001)
2. Use the copy button in the infographic to copy the ready-made comment
3. Paste into the comment box — the character counter should drop from 5000 to ~3490
4. Submit as Individual, Organization, or Anonymous

### Update or redeploy
This is a single self-contained `index.html` file — no build tools, no dependencies, no npm. Edit the file and push to `main`. Netlify redeploys automatically in under 60 seconds.

---

## Technical Notes

- **Single file:** All HTML, CSS, and JavaScript is contained in `index.html`
- **No dependencies:** No npm, no build step, no external frameworks
- **Clipboard:** Uses `textarea.select()` + `execCommand('copy')` for reliable iOS Safari support
- **Countdown:** Targets `2026-04-07T04:00:00Z` (midnight EDT, April 6)
- **Responsive:** Mobile-optimized with orientation-change textarea resize handling
- **Fonts:** Playfair Display, Source Serif 4, JetBrains Mono via Google Fonts

---

## Source & Context

This infographic was produced by **[Moral Fiber Media](https://moralfibermedia.com)** — civic journalism that makes complex legislative and governmental proceedings accessible to ordinary citizens.

**Primary source:** [Federal Register, 91 FR 10780 — March 5, 2026](https://www.federalregister.gov/documents/2026/03/05/2026-04390/review-of-state-bar-complaints-and-allegations-against-department-of-justice-attorneys)  
**Full rule PDF:** [regulations.gov/document/DOJ-OAG-2026-0001-0001](https://www.regulations.gov/document/DOJ-OAG-2026-0001-0001)  
**Administrative Procedure Act:** [5 U.S.C. §§ 551–559 via Cornell LII](https://www.law.cornell.edu/uscode/text/5/part-I/chapter-5/subchapter-II)

---

## License

[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This project is licensed under the **[Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)**.

**You are free to:**
- **Share** — copy and redistribute in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially

**Under the following terms:**
- **Attribution** — You must give appropriate credit to Moral Fiber Media, provide a link to the license, and indicate if changes were made

The civic record matters more than the credit. Share it, adapt it, embed it — just say where it came from.

---

*Built with moral fiber. Deadline: April 6, 2026.*
