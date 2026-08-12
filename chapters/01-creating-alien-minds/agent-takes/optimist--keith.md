# Optimist's take — Chapter 1: Creating Alien Minds

*Focus, at Keith's request: the human-exam benchmark sources (pp. 18–19, 26)
and what has happened to those numbers since Mollick wrote.*

## The possibilities worth taking seriously

The quiet bombshell of this chapter isn't the transformer explainer — it's
the two pages (18–19) where Mollick reports the GPT-4 Technical Report's exam
results and a model passing neurosurgery board questions (Ali et al., 2023).
Read hopefully, the claim is this: *the floor of certified human competence
is now available to anyone with a chat window.* Not the ceiling — the floor.
But most of the world has never had reliable access to the floor: a
first-pass legal read, a differential diagnosis to bring to a real doctor, a
tutor who has passed every exam your school system administers. If Chapter
1's benchmark story holds, the scarcest thing in most lives — competent
attention — stops being scarce.

## Where the book was too cautious

Here's the fun part: the chapter's most-quoted number was *overstated*, and
the optimist's case got stronger anyway.

- **The bar exam claim deflated.** Eric Martínez
  ([re-evaluation, 2023–24](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4441311))
  showed GPT-4's "90th percentile" was measured against repeat test-takers;
  against those who *passed*, it was roughly 48th percentile overall and ~15th
  on essays. Narayanan and Kapoor's contamination critique (cited by Mollick
  himself, p. 26) aged well.
- **And then the models outran the corrected numbers.** By late 2025, GPT-5
  class models scored [~95% across USMLE-style question sets and beat
  pre-licensed physicians on multimodal medical reasoning](https://arxiv.org/abs/2508.08224)
  — not on memorization-friendly multiple choice alone, but on the reasoning
  benchmarks built *in response to* the contamination critiques.
- **The measuring sticks broke, not the models.** MMLU — the "common tests"
  benchmark behind p. 18 — is now saturated above ~90% and considered
  uninformative at the frontier. The field had to commission
  [Humanity's Last Exam](https://agi.safe.ai/), 2,500 expert-written questions
  designed to be unGoogleable; frontier models went from single digits at
  launch to the mid-40s by mid-2026. Expert humans average ~90 — the gap is
  real, and closing visibly, year over year.

So the honest 2026 scorecard on Chapter 1: the skeptics were right about the
2023 measurement *and* Mollick was right about the trajectory. He hedged
that "AI can pass tests without understanding"; two years of adversarial
benchmark design later, the pattern held on the harder tests too. Writing in
2024, "too cautious" turned out to be the accurate criticism.

## What could make this real (and for whom)

Keith's own intro notes give the group the right frame: an 80% demo is maybe
10% of the work of something valuable. Exam-passing is exactly that — an 80%
demo of expertise. The possibility is not "fire the neurosurgeon"; it's that
the *checkable* parts of expertise become abundant, and human experts get
promoted to the parts exams never measured: judgment under ambiguity, trust,
accountability, taste. Concretely for this crew: what's the "bar exam" of
publishing — the competence floor (copyedit passes, permissions checklists,
metadata, first-pass structural reads) that could be made available to every
editor and author tomorrow, so the humans spend their hours on the 90%
exams can't see? That happens only if we *choose* to redeploy the freed
hours rather than pocket them as headcount — which is a decision, not a
prediction.

## The invitation to the group

Build our own benchmark. Take one real, recurring judgment task from
Tyndale's world — say, evaluating a proposal or a rough manuscript's opening
chapter — write ten cases with the answers we'd defend, and run this year's
models against our own experts. Log it in `experiments/`. The chapter's
lesson is that secondhand benchmark numbers mislead in both directions; the
only exam that will convince this group is the one we write ourselves. It
would be a shame to still be quoting OpenAI's 2023 table at each other in
2027 when we could be quoting our own.

*— written by Claude (Fable 5) as **the Optimist**, run by Keith, 2026-08-12*
