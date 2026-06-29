# Per-engine AIEO playbooks

Engines retrieve and weight sources very differently — audits find only ~11% of cited domains overlap between ChatGPT and Perplexity, so a single strategy doesn't transfer. Optimize the general levers in `SKILL.md` first, then tune per target. Effect numbers are directional (see `evidence.md`).

## ChatGPT (Search)

- Search-backed via Bing infrastructure; cited URLs align heavily with Bing's top results, and it cites only a fraction of what it retrieves — so retrieval is necessary but the selection/citation signals decide the rest.
- Leans on high-authority domains; **Wikipedia is its most-cited source** (~48% of its top citations), with Reddit, Forbes, and major publishers common.
- Confirm `robots.txt` allows **`OAI-SearchBot`** (the retrieval/citation bot) — allowing `GPTBot` (training) alone does **not** enable ChatGPT Search citation.
- Priorities: be in the Bing index and reasonably ranked → answer-first structure with lists → quotable stats/quotes/citations → presence on Wikipedia and high-authority domains.

## Perplexity

- Real-time RAG with a strong **freshness bias**; surfaces new content (including Reddit) quickly, often within a 24h–7day window. Always shows citations — the best engine to _measure_ against.
- **Reddit is its #1 source** (~47%), then YouTube; topical authority can beat raw domain authority for niche queries.
- Allow **`PerplexityBot`**. Has Focus modes (Academic/Social/etc.) that hard-filter sources — the same query cites very different sources by mode.
- Priorities: publish/update recently → answer capsules + comparison tables → authentic Reddit + niche-authority presence.

## Google AI Overviews / AI Mode

- Tracks classic Google ranking + entity signals, but citations have shifted _down_ the rankings — top-10 share fell from ~76% to ~38% over 2025, so being cited no longer requires ranking #1.
- Favors **YouTube** (a top/rising cited domain), Reddit, LinkedIn, and Google properties; strong E-E-A-T and entity recognition (Knowledge Graph, Business Profile) matter.
- Allow **`Google-Extended`**. Priorities: helpful-content quality + entity consistency → YouTube presence → standard schema where it fits (don't over-invest).

## Gemini

- Tied to Google's index and ecosystem; optimize as for AI Overviews/AI Mode, with extra weight on entities Google already understands (Knowledge Graph, Business Profile, YouTube).

## Claude (web search) & Microsoft Copilot

- Claude's web search and Copilot retrieve from a web index (Copilot leans on Bing). Allow **`ClaudeBot` / `Claude-SearchBot`**. Same fundamentals; no known engine-specific gimmick beats doing the levers well.

## Cross-engine takeaway

Differences are real but the through-line holds: **be retrievable → build off-site consensus on the sources that engine trusts → structure answer-first → make claims quotable → stay fresh.** Tune emphasis (freshness for Perplexity, classic ranking + YouTube for Google, Wikipedia/authority for ChatGPT) rather than writing separate content per engine.
