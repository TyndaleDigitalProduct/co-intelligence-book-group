# Aligning the Alien — notes from Keith

_Read on: 2026-08-25 · **In progress** — running observations while reading;
will reorganize into the group template when the chapter is done._

## Running observations (by page)

### pp. 31–32 — the two poles need theological nuance

At the end of the chapter's first section, Mollick describes the two poles —
apocalyptic doom and techno-utopia — that make thinking about alignment lack
clarity. As Christians, I think we need to add nuance here. On the one hand,
if we hold a biblical view, we can likely dismiss the apocalyptic concerns;
on the other hand, we should be just as careful to bring nuance to the
techno-utopian direction. How do we think through this theologically, in
addition to the lenses Mollick is using?

### Pretraining ethics after the Anthropic settlement (page ref TBD)

The chapter's discussion of training data reads differently now that we've
sat with the Anthropic settlement (~$1.5B, driven by the *pirated-library*
finding, not by training itself) and the pending publishing-industry suits.
The courts have converged on: training on lawfully acquired material is
transformative fair use; the liability lives in acquisition. Questions I want
to press on:

- Does the fact that pretraining goes into weights rather than a retrievable
  database materially change it from plagiarism to fair use? Two cautions:
  models do memorize and regurgitate (the spine of the NYT suit), so "just
  statistics, not storage" is leaky; and plagiarism is an attribution ethic,
  not a storage question — the courts have essentially extended the
  "human who reads 500 books isn't plagiarizing" analogy to machines, and
  whether that analogy holds at industrial scale is an ethical question the
  law resolved by fiat.
- Is the legal line the ethical line? Judge Chhabria (Meta case) flagged
  "market dilution" as a way fair use could still fail — and even where
  fair use holds, whether authors' labor was justly compensated is a
  different test than the four factors ("the worker deserves his wages").
- Is artwork different from text? Probably harder: style mimicry targets a
  specific living artist's market, and one artist's corpus is a bigger share
  of what an image model can do than one author's is for a text model. No
  clean art ruling yet (*Getty v. Stability* mostly fizzled on jurisdiction).

### Theological bias in LLMs — and why "tuned" fixes may be worse (page ref TBD)

The chapter's bias discussion, focused through the lens that matters for our
work: theological bias. Three layers to distinguish:

1. **Pretraining corpus** — online Christian content skews toward popular
   apologetics and hot-take discourse; serious theology (patristics,
   academic work, confessional distinctives) is underrepresented.
2. **Post-training** — RLHF and rater pools push toward a proceduralist
   secular neutrality: hedging on truth-claims, flattening denominational
   distinctives into a generic mainline-evangelical blend. That neutrality
   is itself a worldview, not the absence of one.
3. **Harness/tuning** — where efforts like Gloo operate.

My view: I have not seen a good approach to addressing theological bias.
Gloo's attempt is itself significantly biased — it bakes a particular
parachurch-evangelical framework into the tuning layer, where it can't be
seen or contested. I prefer the frontier models: their biases are legible
and steerable by explicit prompting, and they're capable enough to steelman
a tradition accurately when asked. "Debiasing" is always re-biasing toward
someone's baseline; the honest questions are whose baseline and how visible.

Sketch of a better approach (unexecuted, as far as I know): measure fidelity
to a tradition rather than agreement with it; retrieval over trusted texts
instead of fine-tuning, so commitments live in an inspectable corpus; and
explicit confessional framing. Connects to my pp. 31–32 note: the demand for
an "unbiased" model is a view-from-nowhere, and Christians shouldn't believe
neutral ground exists — we believe in confessed commitments.

### The paperclip AI vs. *Mrs. Davis*

The paperclip-maximizer illustration of the alignment problem is a classic,
but I actually found the TV show *Mrs. Davis* a more interesting way of
thinking through alignment: it walks a middle way between the apocalypse
narrative and the salvation narrative, rather than forcing a choice between
the two poles.

### Prompt injection as the alignment problem in miniature (page ref TBD)

I haven't personally encountered prompt injection, but I've seen Reddit
posts from people hitting it while scraping the web or running deep
research — instructions embedded in pages (sometimes hidden in white-on-white
text or HTML comments) aimed at the agent reading them, not the human.
Frontier models (Fable/Opus/Sonnet) seem better at sniffing it out and
calling it out rather than falling prey to it. Two threads worth pulling in
discussion:

- Injection is the alignment problem scoped down from "humanity's values"
  to a single delegation relationship: whose instructions does the model
  treat as authoritative — its principal's, or whoever shouts loudest in the
  context window? More concrete than the paperclip story.
- Resistance appears to scale with capability: recognizing "this text inside
  my data is addressing *me*" is a discrimination task stronger models do
  better. Another case (cf. the theological-bias note) where frontier
  capability is itself the safety feature.

(When I asked my agent directly, it reported no injection attempts in our
sessions, but noted its harness marks fetched web content and tool results
as untrusted — guardrails at every seam show how seriously the vector is
taken.)

### Government release restrictions ≠ alignment (p. 44)

Key quote (p. 44): "Government regulation is likely to continue to lag the
actual development of AI capabilities, and might stifle positive innovation
in an attempt to stop negative outcomes."

This year's US interventions give us a live test case for Mollick's
prediction — written in 2024, reading almost prophetically now. Two
to distinguish: the June 2026 executive order creating a *voluntary*
framework for pre-release government access to frontier models (30-day
national-security review, classified cyber benchmarking, explicitly no
licensing requirement), and the sharper June move where Commerce ordered a
developer to suspend foreign-national access to two frontier models on
export-control grounds — plus broader calls from some politicians and
activists for licensing, pauses, or hard caps.

Is this a good solution to the alignment problem? My take: mostly a category
slip. These interventions target *misuse* — who gets access, cyber
capabilities, foreign nationals — which is weapons-style regulation. But the
alignment problem is precisely the ways a model is not like a weapon: it
doesn't just do what its holder intends. A model that clears a 30-day cyber
review is not thereby aligned. Gating buys review time; it aligns nothing.

The deeper problem with restriction-as-solution: it doesn't answer "aligned
to what, decided by whom?" — it relocates the answer into fewer, less
contestable hands (labs + classified benchmarks). Same instinct as the Gloo
note: less legible ≠ more trustworthy. Mollick argues alignment can't be
left to the labs alone; restriction regimes arguably concentrate it further.
And theologically: salvation-by-regulation is as much a false eschatology as
salvation-by-market — a tool, not a telos.

Context links: [Skadden on the June EO](https://www.skadden.com/insights/publications/2026/06/new-ai-executive-order),
[IAPP on the forced suspension](https://iapp.org/news/a/thought-for-the-week-us-government-order-forces-commercial-suspension-of-two-fronteir-ai-models).

## Parking lot

<!-- Things to do once the chapter is finished: -->
- Reshape these observations into the group template (what stuck / pushback /
  connections / passages).
- Add the strongest questions to the shared `questions.md`, signed —
  candidate so far: the theological-nuance question from pp. 31–32.
- Read-aloud candidate: the p. 44 quote on regulation lagging capabilities —
  pairs with the June 2026 executive order as a then-vs-now moment.
