# Verification Notes & Corrections

This document records spot-checks against publicly verifiable sources for the most load-bearing claims in the Phase 1 research. Where the underlying research notes contain figures or framings that should be tightened before going into investor materials, the corrections are recorded here.

This is published as a representative methodology artifact. Venture-specific details (the wedge, pricing, market specifics) have been redacted.

## The methodology

The verification pass works in three steps:

1. **Identify the load-bearing claims.** Across the Phase 1 research notes, surface the specific factual claims that the verdict depends on. Antitrust precedents, market-size figures, competitor financials, regulatory citations.
2. **Re-verify against primary sources.** Pull the original DOJ press release, the law-firm client memos, the published industry reports. Compare against the AI-augmented research note's framing.
3. **Record corrections explicitly.** Where the framing was off or the figure needs tightening, write the correction down in a single document. Anyone using the Phase 1 work product reads the corrections alongside it.

This is the step most AI-augmented research skips. The cost is small (a few hours per phase) and the value is large (no embarrassing mistakes in front of investors or regulators).

## Confirmed claims

### A direct industry-specific citation

The Phase 1 competitive landscape note relied on a recent industry shutdown event as evidence for one of its core findings. Verified accurate against three independent primary sources (DJ Mag, Music Ally, Mixmag). The direct quote from the company's public communications matched the citation. Lesson held up.

## Corrections / nuances

### RealPage DOJ settlement (cited in 03-regulatory-legal-assessment and 05-risk-register)

The Phase 1 docs frame the RealPage settlement as a near-existential antitrust precedent that should make the venture abandon platform-suggested pricing. The actual settlement is more nuanced and slightly more permissive than that framing implies.

Verified facts (DOJ proposed settlement, November 24, 2025):
- The settlement included **no financial penalties** and no findings of wrongdoing.
- It does **not treat algorithmic pricing as inherently illegal**. Multiple law-firm summaries (Wilson Sonsini, Paul Weiss, Hogan Lovells, Duane Morris, Fenwick) explicitly note this.
- The restrictions target **nonpublic competitor data sharing** specifically: RealPage can no longer aggregate nonpublic price data from competing landlords; can no longer report data more granular than state-level; can use historical data only if it is 12+ months old and stripped of price-level and locality data.
- Effective for 7 years (DOJ may end after 4).

Implication for the venture: the antitrust risk on pricing is real, but the path to a compliant pricing-suggestion feature is **clearer than the original Phase 1 framing suggested**. The recommendation in the wedge analysis (defer pricing engine to a later phase; engage antitrust counsel; reframe as informational guidance from public/aggregated data; avoid hub-and-spoke coordination signals) is consistent with the DOJ's framework. The pricing engine is not impossible — it just has to be designed with the RealPage settlement's principles in mind: aggregated, public/historical, not granular by venue or counterparty, no proprietary cross-competitor data sharing.

The Phase 1 risk register should be read with this nuance: severity remains Critical-if-implemented-wrong, but Medium-if-designed-correctly. Antitrust counsel sign-off before launch is the gate.

Sources: [DOJ press release](https://www.justice.gov/opa/pr/justice-department-requires-realpage-end-sharing-competitively-sensitive-information-and), [Wilson Sonsini](https://www.wsgr.com/en/insights/doj-settles-its-algorithmic-price-fixing-case-against-realpage.html), [Paul Weiss client memo](https://www.paulweiss.com/insights/client-memos/practical-takeaways-from-the-doj-s-algorithmic-pricing-settlement), [Duane Morris commentary](https://www.duanemorris.com/articles/realpage_settlement_shows_doj_not_treating_algorithmic_pricing_as_inherently_illegal_1225.html).

### Comparable platform peak revenue (cited in 02-competitive-landscape and 04-wedge-analysis)

The Phase 1 competitive landscape note quotes a key comparable platform at "$100M+ revenue at peak." This appears to be too high.

Verified facts:
- The comparable was valued at $1B in 2021 (SoftBank Vision Fund round).
- Peak estimated revenue (per third-party industry estimates) was around **$60M in 2022**, not $100M+.
- SoftBank wrote the valuation down to $100M in 2022 and ~$50M by 2023.
- The company went through multiple rounds of layoffs and a 2024 multi-state regulatory action involving a $600K settlement that the company couldn't fully pay; settled at $100K.

Implication for the venture: the lesson is even stronger than originally framed. The model worked — the comparable proved meaningful willingness-to-pay for paid creator attention — but at a smaller revenue scale than the original framing implied, and with a more brutal post-peak collapse. This reinforces, rather than weakens, the recommendation to design the wedge with sustainable creator-side economics from the start (avoid race-to-bottom pricing, avoid burning out the supply side, avoid scaling burn ahead of demand).

The wedge analysis recommendation does not change. The framing in any future investor pitch should be tighter and more defensible: cite the verified peak revenue, not the inflated figure.

Sources: [Sacra](https://sacra.com/), [Tech Startups](https://techstartups.com/), [The Information](https://www.theinformation.com/), [Variety](https://variety.com/).

## Other notes

### Industry research figures (file 01)

Several specific figures in the industry research note are synthesized estimates rather than primary published data. For any sizing work and any investor materials, these figures should either be (a) re-validated against fresh primary sources at the time of use, or (b) framed as ranges with the underlying assumption disclosed.

### Competitor user-base and funding figures (file 02)

Many of the competitor figures (e.g., specific Series rounds and dollar amounts) in the competitive landscape file are best-effort estimates synthesized from public sources, Crunchbase, and industry reporting. They are correct in directional magnitude but should be re-validated before being quoted in investor materials.

### Regulatory citations (file 03)

A few specific case-law citations and statutory section numbers in the regulatory assessment should be re-verified by counsel before being relied upon in compliance work. The directional analysis is sound; specific case names and dates may need updating.

## Verification methodology summary

This verification pass spot-checked the highest-load-bearing claims (industry-specific shutdown event, RealPage antitrust settlement, comparable platform financials) against multiple recent independent sources. The directional conclusions of the Phase 1 work are unaffected by the corrections noted; the Phase 1 recommendations remain valid. Where corrections meaningfully refine the framing — particularly on the RealPage settlement — they inform how Phase 2 (Strategy & Sizing) and Phase 3 (Investor Materials) frame the same risks.

The methodology generalizes. Any AI-augmented venture validation should include this verification pass as a first-class step. The cost is hours; the value is not embarrassing yourself in front of investors or regulators.
