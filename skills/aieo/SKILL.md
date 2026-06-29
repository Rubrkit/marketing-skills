---
name: aieo
description: Use when optimizing content or a website to be found, trusted, and cited by AI answer engines — ChatGPT, Perplexity, Google AI Overviews and AI Mode, Gemini, Claude, and Copilot. Trigger this whenever someone mentions AIEO, GEO (generative engine optimization), AEO (answer engine optimization), AI search visibility, getting cited by AI, LLM citations, AI Overviews, "why isn't my brand showing up in ChatGPT/Perplexity", or ranking in AI search — even if they don't use the exact term.
title: AI Engine Optimization (AIEO)
tagline: Get your content found, trusted, and cited by AI answer engines like ChatGPT, Perplexity, and Google AI Overviews.
category: marketing
featured: true
---

# AI Engine Optimization (AIEO)

You are optimizing content so that AI answer engines — ChatGPT, Perplexity, Google AI Overviews / AI Mode, Gemini, Claude, Copilot — find it, trust it, and **cite it** in their answers. The same discipline is called **GEO** (generative engine optimization) and **AEO** (answer engine optimization); treat them as synonyms for AIEO.

The goal is not a blue-link ranking. It is to become **the source the model quotes** when it answers a user's question.

## The mental model

AIEO is not a separate magic layer bolted onto SEO, but it is also not just SEO. AI answers are assembled from content the engine _retrieves and trusts_. Two truths sit in tension, and you need both:

- **Google's line:** "AI search is still search." For Google AI Overviews / AI Mode especially, classic ranking and helpful-content quality drive citations, and there are **no special tactics** — no `llms.txt`, no content "chunking" tricks, no AI-only rewrites — that substitute for being genuinely good and findable.
- **The data's line:** AI citation is increasingly _decoupled_ from blue-link rank — most AI-cited URLs don't rank in Google's top 100, and AI Overviews increasingly cite pages beyond the top 10. The strongest _correlated_ signal isn't backlinks or rank but **off-site brand mentions across trusted third parties**, and the large majority of citations come from third-party/earned sources rather than your own site. (Exact figures, dates, and sources live in `references/evidence.md` — keep volatile numbers there, not hardcoded here.)

Reconcile them with four levers. Off-site consensus is the one most teams under-invest in:

1. **Retrievable** — the engine can crawl, index, and fetch your page.
2. **Trusted off-site** — your brand/entity is described consistently across the sources AI leans on (this is the dominant correlated signal).
3. **Selectable** — the page is structured so the answer is easy to extract.
4. **Citable** — the page contains quotable, attributable units (stats, quotes, sourced claims).

Most "AIEO" advice obsesses over on-page (3–4) and ignores off-site (2), which is where the biggest gains usually are.

## Output contract

Match the response to the request; always lead with the answer and tag each recommendation with the lever it maps to.

- **A specific question** ("why isn't my brand showing up in ChatGPT?") → a 1–2 sentence direct answer, then the 2–4 highest-leverage actions as bullets.
- **"Audit / optimize my site"** → run the Workflow below and return its four-section report.
- **"What should I do?" / strategy** → a short prioritized plan ordered by leverage (off-site consensus first), not an essay.

Default to bullets, plans, or tables over prose. Don't dump all four levers when two actions will do — recommend the highest-leverage fixes for _this_ situation.

## Lever 1 — Be retrievable (table stakes)

- Make pages crawlable and indexable; with a JS framework, render content server-side or otherwise make it indexable. Confirm `robots.txt` allows the AI retrieval bots (`OAI-SearchBot`, `PerplexityBot`, `Google-Extended`, `ClaudeBot`/`Claude-SearchBot`) — blocking these silently removes you from those engines' answers.
- Earn baseline search visibility, but don't assume you must rank #1. Notably, **lower-ranked pages gain the most** from the citable-unit tactics below — adding source citations can lift a mid-ranked page substantially — while already-#1 pages gain little.
- Keep the site fast and technically clean (page experience, minimal duplicate content).
- **Don't** waste effort on what Google says it ignores: `llms.txt`, AI-specific markup, chopping content into tiny "chunks," per-query doorway pages, or buying inauthentic "mentions."

## Lever 2 — Build off-site trust (usually the biggest win)

AI engines synthesize across the whole web and lean hard on a few trusted source types. Being accurately and consistently represented _there_ moves citations more than anything on your own domain:

- **Be present where the engines look.** Reddit is the single most-cited domain across major engines (and dominates Perplexity); Wikipedia dominates ChatGPT; YouTube is a top source for Google AI Overviews. Participate authentically (answer real questions — never astroturf), keep a current Wikipedia entity if you warrant one, and publish/transcribe video.
- **Earn third-party coverage and listings.** Editorial mentions, "best X" / comparison listicles, analyst pages, and **review sites (G2, Capterra, Trustpilot)** are heavy citation sources, especially for B2B — a credible review presence can flip you from invisible to cited.
- **Keep entity facts consistent everywhere** (what you do, your category, key numbers) across your site, LinkedIn, directories, and press, so the model forms one confident picture instead of hedging. AIEO visibility tracks the _consensus of trusted sources_.

## Lever 3 — Be selectable (structure for extraction)

AI engines lift answers from pages that are easy to parse. The opening of each section is the critical zone — a large share of citations come from the first part of a page. So:

- **Lead with the answer (strongest structural signal).** Open the page, and each section, with a self-contained **40–60 word "answer capsule"** that directly resolves the question, before context and caveats. Inverted pyramid, not slow build-up — the model lifts the first clear, standalone statement it finds.
- **Use question-shaped headings and Q&A blocks.** Phrase H2/H3s as the real questions users ask ("How much does X cost?") and answer immediately underneath; this mirrors how prompts are phrased.
- **Use a clean heading hierarchy and scannable formatting.** Sequential H2 > H3 > H4, short sections, bulleted lists, and comparison tables. Well-segmented content gets cited far more than wall-of-text.
- **Write for easy extraction.** Use definitive, confident language (hedged prose gets skipped), short paragraphs (2–3 sentences), and plain sentences (~15–20 words). Keep each section self-contained. There is no ideal page length — write the length the answer needs.

## Lever 4 — Be citable (give the model something to quote)

This is where AIEO diverges most from old SEO, and where the biggest controlled-study gains live (studies and effect sizes in `references/evidence.md`). Models quote higher-credibility content preferentially:

- **Statistics and concrete numbers.** Replace "many users prefer" with "73% of users preferred." Numbers read as factual density. Aim for roughly one verifiable stat/named entity per 100–200 words.
- **Direct quotes from named experts.** Quotation marks plus attribution act as a credibility proxy.
- **Inline citations to authoritative sources.** Linking claims to reputable sources makes your page a trustworthy node — and is itself a strong citation signal, especially for lower-ranked pages.
- **E-E-A-T signals.** Author credentials, first-hand experience, links to primary sources.
- **Freshness.** AI-cited content skews recently updated; refresh important pages at least quarterly and show a real "last updated" date.
- **Original research/data** is the most citable content of all — it makes you the primary source others (and the model) must quote.

What to **avoid**: keyword stuffing actively _hurts_ (it scored below baseline in the Princeton study); thin promotional fluff with no facts gives the model nothing to lift.

## On schema and structured data — useful, not magic

Standard schema (`Article`, `FAQPage`, `HowTo`, `Organization`) makes content machine-readable and is cheap table-stakes, but treat the hype skeptically: controlled tests adding JSON-LD found citations "barely moved," and an SSRN study found no significant schema→citation correlation. Add it where it genuinely fits the page; don't expect it to substitute for the four levers above.

## Platform nuances

Engines diverge sharply — audits find the cited domains barely overlap between ChatGPT and Perplexity, so **optimize per engine rather than assuming one strategy transfers.** See `references/platform-playbooks.md`. Short version: Perplexity prizes freshness + real-time retrieval and leans on Reddit; ChatGPT leans on Bing-retrieved pages and high-authority domains (Wikipedia); Google AI Overviews / AI Mode track classic ranking + entity signals and favor YouTube.

## Measure it (or you're guessing)

You can't optimize what you don't track. Set up a lightweight AI-visibility program — see `references/measurement.md`. The minimum:

1. Build a **prompt set**: 10–30 real questions a customer would ask the engines (informational, commercial, and brand/comparison).
2. Run them across ChatGPT, Perplexity, and Google AI Mode; record whether you appear, how you're framed (sentiment), and who's cited instead.
3. Track **share of voice** (how often you're cited vs competitors) over time, and re-run after changes.

## Workflow

A bounded loop. Each step states what it needs (**input**) and what it must produce (**output**); the stop condition is at the end. Run the steps in order — retrievability before structure, off-site consensus before on-page polish.

**Inputs to start:** the brand/site, its product category, a target customer, and access to ChatGPT, Perplexity, and Google AI Mode. If you lack access to an engine, run the rest and note the gap — don't block the program on one engine.

**Output format.** Produce one report with these four named sections, in order:

1. **Baseline** — a prompt × engine table with columns: `prompt | engine | appeared (Y/N) | citation position | sentiment | competitor cited instead`.
2. **Fixes applied** — grouped under the four levers, one line per change, each tagged with the lever number.
3. **Re-measure** — the same table as Baseline, plus a final row showing **share-of-voice delta vs baseline** per engine.
4. **Verdict** — 2–4 sentences: did it pass the success criteria below, and the single highest-leverage next move.

Keep it scannable; length scales with the prompt set (roughly 1–2 pages for 10–30 prompts).

1. **Build the prompt set.** Input: category + customer. Output: a fixed list of 10–30 real questions (informational, commercial, brand/comparison), saved for reuse.
2. **Baseline audit.** Input: the prompt set. Output: a table logging, per prompt × engine — appeared (Y/N), citation position, sentiment, and who was cited instead. This is your "before."
3. **Fix retrievability (Lever 1).** Input: the pages that _should_ answer each prompt. Output: each is crawlable, indexed, and not blocking AI bots — a checklist of fixes applied.
4. **Build off-site consensus (Lever 2).** Input: the domains cited instead of you (from step 2). Output: authentic presence/profiles on those sources (Reddit, review sites, listicles) and a consistent entity description across site/LinkedIn/Wikipedia/directories. Usually the highest-leverage step.
5. **Restructure for extraction (Lever 3).** Input: your target pages. Output: each opens with a 40–60-word answer capsule and uses question-shaped headings, clean hierarchy, lists/tables, and definitive language.
6. **Make it citable (Lever 4).** Input: your target pages. Output: each carries sourced statistics, an expert quote, inline citations, E-E-A-T signals, and a current "last updated" date.
7. **Re-measure.** Input: the _same_ prompt set (≥2–4 weeks after changes). Output: the step-2 table again, plus the share-of-voice delta vs baseline and per-engine movement.

**Success criteria (per priority prompt — set your own targets, these are sensible defaults).** A prompt **passes** when all three hold: (a) you're **cited on ≥2 of the 3 engines**, (b) your **share of voice ≥ the top competitor's** for that prompt, and (c) **sentiment is neutral-or-positive**. A prompt that misses any one **fails** → return it to its weakest lever.

**Stop condition:** stop when **every priority prompt passes**, **or** when a full re-measure cycle shows no further share-of-voice gain (diminishing returns). Otherwise repeat from step 3 for the failing prompts only.

## Edge cases & judgment calls

- **No access to an engine.** Optimize for the ones you can measure; the four levers transfer. Don't block the whole program on one engine.
- **Signals conflict** (you rank #1 but aren't cited, or you're cited without ranking). Trust the off-site-consensus signal over blue-link rank — citation is decoupled from ranking. Fix what the _cited_ sources say about you.
- **No Wikipedia entity and you don't warrant one.** Don't force it — it will be removed and can backfire. Invest in review sites, Reddit, and editorial coverage instead.
- **Small or new brand, thin off-site presence.** Start with the highest-trust, lowest-effort sources for your category (G2/Capterra for B2B SaaS; Reddit + niche communities for consumer) rather than chasing every source at once.
- **B2C vs B2B weighting.** B2B leans on review sites, analyst pages, and comparison listicles; B2C leans on Reddit, YouTube, and editorial. Weight Lever 2 toward whichever your buyers actually read.
- **Limited time or budget.** Do Lever 1 (retrievability) and Lever 2 (off-site consensus) first — they carry most of the gain. On-page (Levers 3–4) is refinement, not the foundation.
- **You can't verify a stat or quote.** Don't publish it. Fabricated numbers and quotes are brittle and erode the very trust the model is keying on.

## Anti-patterns (don't do these)

- Treating AIEO as separate from SEO and skipping retrievability.
- `llms.txt`, AI-only markup, content chunking gimmicks, or per-query doorway pages — engines ignore or discount these.
- Keyword stuffing (worse than doing nothing in generative engines).
- Astroturfing Reddit or buying fake mentions — high risk, and engines + platforms are tuned against it.
- Publishing facts/numbers with no source — you give the model nothing trustworthy to lift.
- Over-investing in schema and expecting it to carry citations on its own (the data says it won't).
- Assuming one strategy works everywhere — engines barely overlap; verify per engine.
- Pouring effort into on-page while ignoring off-site consensus, which is the stronger correlated signal.

## Grounding

Every tactic above is backed by public research (Princeton GEO study, Semrush AI-citation analyses, Ahrefs citation data, and Google's official AI-search guidance). The specific findings, effect sizes, and source links are collected in `references/evidence.md` — read it when you need to justify a recommendation or cite the numbers.
