# Fact-check — Chapter 1: Creating Alien Minds

*Book published April 2024, checked against live sources on 2026-08-18. Sources
cited here are cataloged in this folder's `sources.md`.*

## Scoreboard

| Claim | Verdict | Evidence |
|---|---|---|
| Training is an apprentice chef learning from everyone else's recipes, then refined by human feedback (pp. 12–17) | **SUPERSEDED** | The recipe gained a third phase after publication: large-scale RL against automatically checkable rewards. DeepSeek-R1 ([Nature, Sept 2025](https://www.nature.com/articles/s41586-025-09422-z)) showed reasoning behavior can be incentivized by RL alone, with no human-annotated reasoning traces. |
| Frontier models cost over $100 million to train (p. 12) | **HELD UP** | True, and now an understatement. Gemini Ultra is estimated near $191M, with 2026-class runs cited at $200–500M and costs growing 2–3x a year. [Epoch AI](https://epoch.ai/blog/how-much-does-it-cost-to-train-frontier-ai-models) |
| High-quality public text will be exhausted (p. 13, Villalobos et al.) | **CONTESTED** | The prediction has receded rather than failed. Epoch has pushed the front of its exhaustion window from 2026 to roughly 2028, citing high-quality sources still untapped. [Epoch AI](https://epoch.ai/publications/will-we-run-out-of-data-limits-of-llm-scaling-based-on-human-generated-data) |
| Training on AI-generated text degrades models (p. 13, Shumailov et al.) | **CONTESTED** | It reached [Nature](https://pubmed.ncbi.nlm.nih.gov/39048682/) in July 2024, but the result assumes each generation *replaces* the last one's data. Where real data accumulates alongside synthetic, collapse does not occur ([arXiv:2404.01413](https://arxiv.org/html/2404.01413v2)), and the effect has been read as a sampling artifact ([arXiv:2410.12954](https://arxiv.org/abs/2410.12954)). |
| Emergent abilities may be an artifact of metric choice (p. 26, Schaeffer et al.) | **HELD UP** | Best paper at NeurIPS 2023, not overturned. The literature now treats emergence as a contested reading of evaluation curves rather than a settled property of scale. [arXiv:2304.15004](https://arxiv.org/abs/2304.15004) |
| Nobody can explain why scaled-up models develop the abilities they do | **SUPERSEDED** | Partially. Anthropic's March 2025 circuit tracing and *On the Biology of a Large Language Model* build attribution graphs that trace intermediate computation causally. Nowhere near a complete account, but no longer "we have no idea." [Anthropic](https://www.anthropic.com/research/tracing-thoughts-language-model) |
| Hallucination is structural to prediction, not a bug to be patched out (the framing in this folder's `questions.md`) | **CONTESTED** | OpenAI's Sept 2025 paper argues hallucination persists because benchmarks reward confident guessing over admitted uncertainty, and concludes it is inevitable *only for base models*. That makes it substantially an incentive problem. [arXiv:2509.04664](https://arxiv.org/abs/2509.04664) |
| The imitation game as a standing open challenge (p. 4, Turing) | **SUPERSEDED** | Jones and Bergen (March 2025) report GPT-4.5 judged human 73% of the time in a three-party test, more often than the real humans, and describe it as the first empirical pass of a standard Turing test. [arXiv:2503.23674](https://arxiv.org/abs/2503.23674) |
| Mollick's account of image models and Stable Diffusion | **UNVERIFIED** | Not checked in this pass. Flagged because Keith's notes raise it directly, and it deserves its own look rather than a guess. |

## The most consequential update since 2024

The meeting shortlist's first question asks whether the chef story still
describes how these models are built. It does not, and that is the largest
single change.

In April 2024 the honest summary was two phases: predict the next token across
an enormous corpus of human writing, then polish with human feedback. Since
late 2024 the frontier has added a phase the metaphor has no room for,
reinforcement learning against answers a machine can check, run at scale.
DeepSeek-R1 is the clearest public demonstration, and it makes the stronger
claim that reasoning behavior emerges from RL without human demonstrations of
reasoning at all.

That bears on the chapter's central move. Mollick's chef learns everything from
us. A model shaped by RL on verifiable rewards learns a real share of its
behavior from having its own attempts graded, so the corpus is no longer
obviously the ceiling.

## What this does to the chapter's argument

The **alien mind** metaphor comes out stronger. The more of a model's
competence originates in practice against a grader, the less it resembles a
very well-read person, which is exactly the work "alien" was doing. The
**amateur chef** is now an accurate description of one phase out of three, and
worth treating as that rather than as the account of training.

Two warnings aged well: the caution that high test scores can come from
contaminated benchmarks, and the instruction to assume this is the worst AI you
will ever use. Two claims aged into "it depends," data exhaustion and model
collapse, which is less quotable but more accurate.

## The question for the group

If a growing share of frontier capability now comes from reinforcement learning
rather than from reading us, does the training-data ethics question get weaker,
or does it only move? The scraped corpus is still the foundation every one of
these systems is built on, and we sit at a publisher.

*— written by Claude (Opus 5) as **the Fact-Checker**, run by Kevin, 2026-08-18*
