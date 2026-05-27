# Venture Validation: B2B EDM Booking Platform

An AI-augmented venture validation run on an early-stage B2B platform idea in the electronic dance music industry. Two phases, ~80 pages of structured analysis, a working financial model with 1,166 validated formulas, a conditional-YES verdict with named kill criteria.

The platform idea isn't the point of this repo. **The methodology is.** This is what AI-augmented venture validation looks like when it's done with operator rigor: source-cited research, explicit kill criteria, regulatory analysis, comparable benchmarks, financial modeling, and a verification pass against primary sources.

---

## TL;DR

**The idea evaluated.** A multi-sided B2B platform connecting EDM DJs, venues, event organizers, producers, and labels. Originally scoped with 10+ products (booking, contracts, algorithmic pricing, paid track review, immigration referrals, music sales, sponsored ads, travel, social feeds).

**The verdict.** Conditional YES. Strip the 10-product vision down to a single wedge: **paid booking-inquiry with guaranteed-response SLA** ($99-$499 per inquiry, 30-40% platform take). Defer everything else. Specific willingness-to-pay thresholds set as kill criteria.

**Why this verdict held up.** The wedge solves the highest-WTP pain in the industry (organizers can't get DJs to respond to bookings) with single-sided supply economics, the cleanest legal posture in the full vision, and a clear data-generation path toward the bigger platform later.

**What got cut.** Algorithmic pricing (antitrust exposure under Sherman §1, EU Art 101, RealPage settlement principles), contract generation (unauthorized practice of law risk across jurisdictions), reviews system (Section 230 erosion plus FTC fake-review enforcement plus UAE criminal defamation exposure), immigration attorney marketplace (ABA Model Rule 7.2 referral-fee restrictions).

---

## Why this is in a portfolio

If you're hiring an AI Ops person and you want to know whether they can:

- Run structured AI-augmented research across multiple verticals (industry, competitive, regulatory, financial) and synthesize it into a single coherent verdict.
- Pick the right primary sources, not just the easy ones — IMS Business Report, MIDiA Research, IFPI, Pollstar, Billboard, plus DOJ filings and EU regulatory texts.
- Spot-check AI output against primary sources and tighten findings before the work goes to investors. (See [06-verification-notes.md](phase-1-validation/research-notes/06-verification-notes.md) for the Phase 1 corrections.)
- Build a working financial model with internal-consistency checks (1,166 formulas validated, $25M GMV ambiguity flagged in Phase 2 verification before it reached the investor deck).
- Convert a 10-feature vision into a 1-feature wedge with named criteria, not vibes.

This repo shows the full body of work that produced a conditional-YES verdict. The framework transfers to any early-stage venture decision.

---

## Methodology

The validation runs in two phases, gated. Phase 2 only happens if Phase 1 lands at YES or CONDITIONAL YES.

### Phase 1: Validation (does this venture deserve a yes?)

Six research notes, each with explicit source citations and a structured deliverable.

1. **Industry research.** Market size, growth, geographic split, pain-point inventory. Sourced from IMS, MIDiA, IFPI, Pollstar, Billboard, Statista.
2. **Competitive landscape.** 40+ competitors across 10 functional categories, mapped for overlap with each proposed product.
3. **Regulatory and legal assessment.** Per-feature legal-risk analysis across US, EU, UAE, Brazil, plus EU AI Act, DSA, GDPR exposure.
4. **Wedge analysis and MVP.** Six-axis scoring rubric (WTP, cold-start friction, legal risk, solo-founder feasibility, strategic fit, defensibility) applied to all 12 candidate features. One primary wedge, defer everything else.
5. **Risk register.** Top 10 risks with severity and likelihood ratings, plus concrete mitigations.
6. **Verification notes.** Spot-checks against primary sources. Where the AI-augmented research bent the truth or missed nuance, the corrections live here.

Output: the [Phase 1 Validation Report](phase-1-validation/Phase-1-Validation-Report.docx) and a [one-page summary](phase-1-validation/Phase-1-One-Page-Summary.pdf).

### Phase 2: Strategy and sizing (now that the answer is yes, how big and how soon?)

Three research notes plus four working deliverables.

- **Comparable platform benchmarks.** 20 most-relevant data points across Cameo, Intro.co, Superpeer, SubmitHub, GigSalad, Thumbtack, HoneyBook, Stripe Connect, Eventbrite, Bubble, Beatport.
- **Funding landscape.** Music-tech and creator-economy VC, angel networks, strategic corporate partners with a solo-founder outreach sequence.
- **Verification notes.** Post-build spot-check on the four Phase 2 deliverables. Internal consistency checks across sizing, financial model, GTM, and exec summary.

Deliverables:

- **Market-sizing model** (Excel, 97 formulas) — TAM/SAM/SOM under Conservative / Base / Bull scenarios.
- **Financial model** (Excel, 1,166 formulas) — 36-month revenue build, cost stack, P&L, cash flow, funding scenarios.
- **GTM strategy** — launch geography (Miami + LA + Ibiza), supply acquisition plan, demand activation, KPI framework.
- **Funding evaluation** — bootstrap vs. F&F bridge vs. pre-seed vs. seed, with cash-runway implications and recommended sequence.
- **Phase 2 executive summary** — the 5-page wrap that ties everything together.

---

## What's in this repo

### Phase 1 - Validation

| File | What it is |
|------|------------|
| [`phase-1-validation/Phase-1-Validation-Report.docx`](phase-1-validation/Phase-1-Validation-Report.docx) | The full validation report. ~40 pages. |
| [`phase-1-validation/Phase-1-One-Page-Summary.pdf`](phase-1-validation/Phase-1-One-Page-Summary.pdf) | One-page executive summary. |
| [`phase-1-validation/research-notes/`](phase-1-validation/research-notes) | The six research notes that fed the report. |

### Phase 2 - Strategy and Sizing

| File | What it is |
|------|------------|
| [`phase-2-strategy-and-sizing/Phase-2-Executive-Summary.docx`](phase-2-strategy-and-sizing/Phase-2-Executive-Summary.docx) | Executive summary of Phase 2. ~5 pages. |
| [`phase-2-strategy-and-sizing/Market-Sizing-Model.xlsx`](phase-2-strategy-and-sizing/Market-Sizing-Model.xlsx) | TAM/SAM/SOM model. 97 formulas. |
| [`phase-2-strategy-and-sizing/Financial-Model.xlsx`](phase-2-strategy-and-sizing/Financial-Model.xlsx) | 36-month P&L, cash flow, funding scenarios. 1,166 formulas. |
| [`phase-2-strategy-and-sizing/GTM-Strategy.docx`](phase-2-strategy-and-sizing/GTM-Strategy.docx) | Launch geography, supply and demand activation, KPIs. |
| [`phase-2-strategy-and-sizing/Funding-Evaluation.docx`](phase-2-strategy-and-sizing/Funding-Evaluation.docx) | Funding-path comparison and recommended sequence. |
| [`phase-2-strategy-and-sizing/research-notes/`](phase-2-strategy-and-sizing/research-notes) | The three research notes that fed Phase 2. |

---

## How to read this repo

For a recruiter or hiring manager, the most useful entry points (in order of time investment):

- **5 minutes:** Read this README plus the [Phase 1 one-page summary](phase-1-validation/Phase-1-One-Page-Summary.pdf).
- **20 minutes:** Add [04-wedge-analysis-and-mvp.md](phase-1-validation/research-notes/04-wedge-analysis-and-mvp.md). That's where the conditional-YES verdict gets its reasoning.
- **40 minutes:** Add [06-verification-notes.md (Phase 1)](phase-1-validation/research-notes/06-verification-notes.md) and [B3-verification-notes.md (Phase 2)](phase-2-strategy-and-sizing/research-notes/B3-verification-notes.md). These show the rigor pass against primary sources and the corrections that didn't make it into the AI's first draft.
- **2 hours:** Read everything.

---

## What this work demonstrates for AI-Ops roles

Five capabilities, each load-bearing for any AI-augmented analytical work:

1. **Domain decomposition.** A 10-product platform vision is decomposed into 12 candidate features, each scored independently against a six-axis rubric. The wedge falls out of the scoring, not out of a hunch.

2. **Source rigor.** Primary sources are named throughout (IMS, MIDiA, IFPI, Pollstar, DOJ press releases, law-firm client memos). AI is good at producing confident-sounding output; the work of grounding that output in primary sources is what separates research from generation.

3. **Verification as a first-class step.** Both phases include a verification pass that compares AI-augmented findings against primary sources and records corrections. The RealPage settlement correction in Phase 1 is a representative example: the AI's first draft treated the settlement as a near-existential precedent; the verified facts are more nuanced and the implication for the platform is materially different.

4. **Quantitative model integrity.** The financial model's 1,166 formulas all validate. The market-sizing model's geographic split sums to 100% exactly. Inconsistencies between documents (the $25M GMV figure in GTM vs. the wedge GMV in the financial model) are flagged in the verification notes before the materials go to investors.

5. **Kill criteria over advocacy.** The verdict is conditional, not unconditional. Specific WTP thresholds ($99 minimum, $499 ceiling per inquiry, 30-40% platform take) are set as kill criteria. If the wedge doesn't hit those numbers in pilot, the venture stops, regardless of how compelling the deck was.

---

## License

The methodology and structure are MIT-licensed for reuse. The research findings are licensed for reading and reference, not for republication.

---

*Maintained by [Lia Snisarenko](https://github.com/liasnisarenko). AI Workflow Operator based in Los Angeles. Available for AI-augmented venture validation engagements.*
