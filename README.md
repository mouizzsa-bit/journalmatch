# 🌱 JournalMatch

**Live tool → https://mouizzsa-bit.github.io/journalmatch/**

A free tool that helps **plant & crop scientists in Africa and other low- and middle-income countries (LMICs)** decide where to submit a manuscript. Paste a title (optionally an abstract, keywords, and your country) and get a shortlist of indexed, credible journals ranked by:

1. **Topical fit** — how well the journal's scope matches your manuscript.
2. **Real cost after waivers** — what *you* would actually pay once APC waivers/discounts for your country are applied.
3. **Turnaround** — an honest fast / medium / slow bucket.

Each result also shows impact factor, indexing (Scopus / Web of Science), open-access model, review type, a predatory-risk flag, and a link to the publisher's own policy so you can **verify every figure**.

## Why it exists

Existing journal finders match a title to similar journals but ignore the two things that decide whether an LMIC author can actually publish there: whether the fee will be **waived for their country**, and whether the journal's **open-access model** (fully-OA vs hybrid) even allows that waiver. JournalMatch is built around exactly that.

## How the waiver logic works

Wiley, Elsevier, Springer Nature and Taylor & Francis waive APCs **only on fully open-access journals, never on hybrid ones**. Tier-A countries (Kenya, Benin + 75 others, from the Research4Life / Wiley lists) typically get a **100% waiver + open access** on a participating fully-OA journal. A **hybrid** journal offers no waiver on its OA option — so the tool shows its **free subscription (non-OA) route** as the headline and notes the paid OA price beneath.

## What's in this repo

- `index.html` — the complete tool (single self-contained file; the journal data is embedded).

The curated journal database (spreadsheet), the OpenAlex/DOAJ refresh pipeline, and a concept note live alongside the project files.

## Important

This is a **research preview**. Impact factors, APCs, and waiver percentages are approximate and change often — they must be confirmed on each journal's own page (every card links to it) before you rely on them. JournalMatch is a guide, not a substitute for checking the journal directly.

---
*Concept by Abdou · waiver logic based on publisher & Research4Life policies.*
