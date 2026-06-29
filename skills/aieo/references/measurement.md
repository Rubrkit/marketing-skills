# Measuring AI visibility

AIEO without measurement is guessing. AI answers are non-deterministic and personalized, so you measure _tendencies_ across a fixed prompt set over time, not a single rank.

## 1. Build a prompt set (10–30 questions)

Cover the funnel with questions a real customer would type into an AI engine:

- **Informational** — "how does X work", "what is the best way to Y"
- **Commercial / evaluation** — "best tools for X", "X vs Y", "top alternatives to Z"
- **Brand** — "is [brand] any good", "[brand] reviews", "what does [brand] do"

Keep the set fixed so results are comparable run-to-run. Add new prompts over time, but don't churn the core set.

## 2. Run them across engines

At minimum ChatGPT, Perplexity, and Google AI Mode/Overviews. For each prompt record:

- **Presence** — did you appear / get cited at all? (yes/no)
- **Share of voice** — of the sources cited, how many are you vs each competitor?
- **Citation position** — were you the lead source or a footnote?
- **Sentiment / framing** — is how the engine describes you accurate and positive?
- **Who beat you** — which domains were cited instead (these are your AIEO targets to earn presence on or out-cite).

Perplexity is the easiest to read because it always lists citations; use it as your primary measurement surface, then spot-check the others.

## 3. Cadence

- Baseline before any changes.
- Re-run ~2–4 weeks after a batch of changes (engines need time to re-crawl/refresh; Perplexity reflects changes fastest).
- Track the trend, not a single snapshot — one run is noisy.

## 4. Tooling

- **Manual** is fine to start: run the prompt set by hand and log results in a sheet. High effort, zero cost, full fidelity.
- **AI-visibility platforms** automate prompt runs, share-of-voice, and sentiment tracking across engines (e.g. dedicated AI-visibility trackers; some traditional SEO suites now include AI-citation/visibility reports). Evaluate against your prompt set before committing.

## 5. Close the loop

For every prompt where you're absent or losing: identify the page that _should_ win it, apply the Gate 1–3 fixes from `SKILL.md`, note the date, and re-measure on the next run. Keep what moves share of voice; drop what doesn't.
