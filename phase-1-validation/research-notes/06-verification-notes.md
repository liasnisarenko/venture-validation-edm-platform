# Verification Notes & Corrections

This document records spot-checks against publicly verifiable sources for the most load-bearing claims in the Phase 1 research. Where the underlying research notes contain figures or framings that should be tightened before going into investor materials, the corrections are recorded here.

## Confirmed claims

### Aslice shutdown (cited in 02-competitive-landscape and 04-wedge-analysis)

Verified accurate. Aslice announced its closure on September 3, 2024, citing the failure of top-tier DJs to participate in the voluntary revenue-share model. The platform had distributed ~$422K to 27,000+ producers across 57 countries during its 2022–2024 run. Direct quote from public communications: "If just 40 more DJs at the level of Aslice's current top 10 users had participated, the platform would have been financially viable." This validates the lesson in the wedge analysis: voluntary mechanisms that take money from DJs do not sustain.

Sources: [DJ Mag](https://djmag.com/news/aslice-software-platform-fought-income-imbalance-between-producers-and-djs-shutting-down), [Music Ally](https://musically.com/2024/09/09/dj-revenue-sharing-startup-aslice-shuts-down-but-may-sell-its-tech/), [Mixmag](https://mixmag.net/read/aslice-ceases-operations-music-revenue-sharing-dvs1-closure-news).

## Corrections / nuances

### RealPage DOJ settlement (cited in 03-regulatory-legal-assessment and 05-risk-register)

The Phase 1 docs frame the RealPage settlement as a near-existential antitrust precedent that should make the Platform abandon platform-suggested pricing. The actual settlement is more nuanced and slightly more permissive than that framing implies.

Verified facts (DOJ proposed settlement, November 24, 2025):
- The settlement included **no financial penalties** and no findings of wrongdoing.
- It does **not treat algorithmic pricing as inherently illegal**. Multiple law-firm summaries (Wilson Sonsini, Paul Weiss, Hogan Lovells, Duane Morris, Fenwick) explicitly note this.
- The restrictions target **nonpublic competitor data sharing** specifically: RealPage can no longer aggregate nonpublic price data from competing landlords; can no longer report data more granular than state-level; can use historical data only if it is 12+ months old and stripped of price-level and locality data.
- Effective for 7 years (DOJ may end after 4).

Implication for the Platform: the antitrust risk on pricing is real, but the path to a compliant pricing-suggestion feature is **clearer than the original Phase 1 framing suggested**. The recommendation in the wedge analysis (defer pricing engine to Phase 2; engage antitrust counsel; reframe as informational guidance from public/aggregated data; avoid hub-and-spoke coordination signals) is consistent with the DOJ's framework. The pricing engine is not impossible — it just has to be designed with the RealPage settlement's principles in mind: aggregated, public/historical, not granular by venue or DJ, no proprietary cross-competitor data sharing.

The Phase 1 risk register should be read with this nuance: severity remains Critical-if-implemented-wrong, but Medium-if-designed-correctly. Antitrust counsel sign-off before launch is the gate.

Sources: [DOJ press release](https://www.justice.gov/opa/pr/justice-department-requires-realpage-end-sharing-competitively-sensitive-information-and), [Wilson Sonsini](https://www.wsgr.com/en/insights/doj-settles-its-algorithmic-price-fixing-case-against-realpage.html), [Paul Weiss client memo](https://www.paulweiss.com/insights/client-memos/practical-takeaways-from-the-doj-s-algorithmic-pricing-settlement), [Duane Morris commentary](https://www.duanemorris.com/articles/realpage_settlement_shows_doj_not_treating_algorithmic_pricing_as_inherently_illegal_1225.html).

### Cameo peak revenue (cited in 02-competitive-landscape and 04-wedge-analysis)

The Phase 1 competitive landscape note quotes Cameo at "$100M+ revenue at peak." This appears to be too high.

Verified facts:
- Cameo was valued at $1B in 2021 (SoftBank Vision Fund round).
- Peak estimated revenue (per third-party industry estimates) was around **$60M in 2022**, not $100M+.
- SoftBank wrote the valuation down to $100M in 2022 and ~$50M by 2023.
- Cameo went through multiple rounds of layoffs: May 2022 (~87 people), November 2022 (~80 people), July 2023 (cut to ~33 employees), with further reductions in 2024 bringing staff to fewer than 50.
- A 2024 multi-state regulatory action involved a $600K settlement that the company couldn't fully pay; settled at $100K.

Implication for the Platform: the Cameo lesson is even stronger than originally framed. The model worked — Cameo proved meaningful WTP for paid creator attention — but at a smaller revenue scale than the original framing implied, and with a more brutal post-peak collapse. This reinforces, rather than weakens, the recommendation to design the paid-DM model with sustainable creator-side economics from the start (avoid race-to-bottom pricing, avoid burning out the supply side, avoid scaling burn ahead of demand).

The wedge analysis recommendation does not change. The framing in any future investor pitch should be: "Cameo proved the model at ~$60M peak, then suffered for being too consumer/celebrity-narrow. We're applying the same mechanic to a B2B EDM industry with structurally higher WTP per transaction and a denser network." That's a tighter and more defensible narrative.

Sources: [Sacra](https://sacra.com/c/cameo/), [Tech Startups](https://techstartups.com/2024/07/26/cameo-a-unicorn-tech-startup-once-valued-at-over-1-billion-is-now-broke-and-cant-pay-a-600000-fine/), [The Information — layoffs](https://www.theinformation.com/articles/cameo-cuts-staff-to-fewer-than-50-after-financial-stumble), [Variety — 2022 layoffs](https://variety.com/2022/digital/news/cameo-layoffs-celebrity-video-shout-out-1235258625/).

## Other notes

### Industry research figures (file 01)

Several specific figures in the industry research note are synthesized estimates rather than primary published data:

- Beatport per-stream rate ($0.108) — this is on the high end of public reporting; the platform does not publish official rates and individual deals vary. Some industry sources quote $0.05–$0.10 range; $0.108 is plausible but not a documented constant.
- Global EDM market size ($12.9B 2025) — derives from IMS Business Report estimates; methodology is public but the figure is industry-internal, not audited.
- Stakeholder counts (1.5M–3M DJs globally; 75K–240K professional) — best-effort extrapolations; no primary census exists.
- Festival economics (Tomorrowland $250M, Ultra $180M, EDC $250M+) — partially disclosed publicly, partially estimated from ticket pricing assumptions.

For Phase 2 sizing work and any investor materials, these figures should either be (a) re-validated against fresh primary sources at the time of use, or (b) framed as ranges with the underlying assumption disclosed.

### Competitor user-base and funding figures (file 02)

Many of the competitor figures (e.g., specific Series rounds and dollar amounts) in the competitive landscape file are best-effort estimates synthesized from public sources, Crunchbase, and industry reporting. They are correct in directional magnitude but should be re-validated before being quoted in investor materials. In particular: Cameo Series figures, GigSalad funding history, RA acquisition specifics, and SubmitHub user-base figures are all approximations.

### Regulatory citations (file 03)

A few specific case-law citations and statutory section numbers in the regulatory assessment should be re-verified by counsel before being relied upon in compliance work. The directional analysis is sound; specific case names and dates may need updating.

## Verification methodology

This verification pass spot-checked the three highest-load-bearing claims (Aslice closure, RealPage antitrust settlement, Cameo financials) against multiple recent independent sources. The directional conclusions of the Phase 1 work are unaffected by the corrections noted; the Phase 1 recommendations remain valid. Where corrections meaningfully refine the framing — particularly on the RealPage settlement — they will inform how Phase 2 (Strategy & Sizing) and Phase 3 (Investor Materials) frame the same risks.
