# Evidence base

The tactics in this skill are grounded in public research. Effect sizes vary by study methodology, engine, and date — treat them as **directional, not guarantees**, and re-check the fast-moving numbers before quoting them.

## Tier 1 — peer-reviewed / official

### Princeton GEO study (KDD 2024) — the foundational paper

"GEO: Generative Engine Optimization," Princeton / Georgia Tech / IIT Delhi / Allen AI. 9 content tactics tested across a 10,000-query benchmark; headline: visibility up to **+40%** from content changes alone.

- Adding **statistics** ≈ +21–41%; **expert quotations** ≈ +28–41%; **citing authoritative sources** ≈ +30% (and **+115% for lower-ranked ~5th-place pages**).
- **Keyword stuffing scored ~0 / below baseline (≈−10%)** — a classic SEO trick that backfires.
- Effects vary by domain (cite-sources best for factual/legal; quotes for people/history).
- Paper: https://arxiv.org/abs/2311.09735 · https://dl.acm.org/doi/10.1145/3637528.3671900

### Google Search Central — official AI-search guidance

- "AI search is still search." Generative features run on core ranking + quality systems.
- Explicitly **not needed**: `llms.txt`, AI-specific markup, content "chunking," AI-only rewrites, per-query doorway pages. No ideal page length.
- https://developers.google.com/search/docs/fundamentals/ai-optimization-guide

## Tier 2 — large-sample industry data (well-attributed)

### Off-site brand mentions > backlinks (the headline 2025–26 finding)

- Ahrefs (75,000 brands): branded **web mentions correlate ≈0.66** with AI visibility vs **≈0.22 for backlinks** — ~3× stronger. Independently re-reported (Loganix 2026). Domain Authority alone correlates only ~0.18.
- ~**82–85% of AI citations come from third-party / earned media**, not owned pages (Muck Rack Dec 2025; corroborated by Discovered Labs ~82.9% for B2B).
- Ahrefs (Aug 2025): ~**80% of AI-cited URLs don't rank in Google's top 100**; only ~12% rank top-10 — AI citation is largely decoupled from blue-link rank.

### Platform divergence

- Only ~**11% of cited domains overlap between ChatGPT and Perplexity** (Profound, 680M+ citations; Qwairy, 669k citations) — optimize per engine.
- Citation volume differs: Perplexity ≈ 21.9 citations/answer vs ChatGPT ≈ 7.9 (Qwairy Q3 2025).
- Top sources by engine: ChatGPT → Wikipedia (~48% of its top citations) + Reddit; Perplexity → Reddit (~47%) + YouTube; Google AI Overviews → YouTube, Reddit, LinkedIn.

### Structure & freshness

- ~**44% of LLM citations come from the first ~30% of the page** (SparkToro Jan 2026) — front-load the answer in a 40–60 word capsule.
- Cited pages skew **recently updated** (multiple practitioner datasets report content refreshed within ~30 days cited materially more); refresh important pages at least quarterly.
- Sequential heading hierarchy and lists/tables recur as citation-correlated across ChatGPT/Perplexity analyses.

## Tier 3 — counter-evidence worth heeding (keeps the skill honest)

- **Schema is contested.** Ahrefs tracked **1,885 pages adding JSON-LD** and found citations "barely moved" (https://ahrefs.com/blog/schema-ai-citations/); an SSRN cross-platform study found no significant schema→citation correlation. FAQ/Article schema is cheap table-stakes, not a citation lever on its own.
- **Some widely-quoted coefficients are single-source / undocumented** (e.g. r-values from Wellows/"AI Mode Boost," and implausibly high figures like r=0.92 for "multi-modal integration"). Don't lean on them.
- **The Princeton tactics include "fabricated stats/quotes" critiques** (SandboxSEO replication): use real, sourced stats and quotes — manufacturing them is both unethical and brittle.
- **Readability** helps but the specific numbers are thin: one 18k-prompt vendor dataset found Flesch 60–75 content cited ~31% more; treat "plain, confident, ~15–20-word sentences" as sound practice, not a precise dial.
