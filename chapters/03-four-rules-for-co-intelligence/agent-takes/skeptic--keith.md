# Skeptic's take — Chapter 3: Four Rules for Co-Intelligence

*Run against all four rules, per Keith's brief: is any rule missing something
essential, or giving poor advice? Kevin's notes and the Optimist take were on
file; I engage with both. Page numbers follow this folder's `sources.md`.*

## The claims under attack

Each rule, in its strongest form.

1. **Always invite AI to the table** (pp. 47–50). The frontier is jagged and
   invisible, so the only way to learn its shape is to try the tool on
   everything you are allowed to. User innovators, not mandates, find the
   value.
2. **Be the human in the loop** (pp. 51–55). Models hallucinate confidently
   and are good at justifying wrong answers (p. 53), so keep checking. The
   calculator made us better at math; AI can too, if we stay engaged.
3. **Treat AI like a person, but tell it what kind of person it is**
   (pp. 55–62). Anthropomorphism is technically false (p. 56) but practically
   useful: models respond to roles and even emotional framing (pp. 57–59).
4. **Assume this is the worst AI you will ever use** (pp. 62–64). Judge the
   trajectory, not the snapshot, and work as a coeditor rather than a
   one-shot oracle.

## Where they break

**Rule 1 ignores the cost side of its own evidence.** The Jagged Frontier
paper Mollick cites (p. 47) is famous for the productivity gains. Less quoted
is its other finding: on the task deliberately placed *outside* the frontier,
consultants using AI were about 19 percentage points *less* likely to get the
answer right than those without it. The authors called it "falling asleep at
the wheel." "Always invite" has no stopping rule, and the chapter's own
source says the tool degrades judgment exactly where you can't see the wall.
Since publication, METR's 2025 randomized trial found experienced developers
were roughly 19% *slower* with AI tools while believing they were 20% faster
([metr.org](https://metr.org/blog/2025-07-10-early-2025-ai-experienced-os-dev-study/)).
The felt benefit and the measured benefit came apart. A rule that says
"always" should at least say how you'd notice that.

**Rule 2 names a posture and calls it a skill.** "Be the human in the loop"
tells you where to stand, not what to do there. Lisa Bainbridge's "Ironies of
Automation" (1983) made the point forty years earlier: the better the
automation, the less practice the operator gets, so the human is least
prepared precisely when needed. Parasuraman and Manzey's review of automation
complacency (2010) documents that monitoring attention decays as reliability
rises. The chapter's answer is the calculator analogy (p. 51), but
calculators fail loudly and rarely. Language models fail fluently and often
enough to matter, and a 2025 CHI study of knowledge workers found confidence
in the tool predicted *less* critical-thinking effort
([Lee et al.](https://www.microsoft.com/en-us/research/publication/the-impact-of-generative-ai-on-critical-thinking-self-reported-reductions-in-cognitive-effort-and-confidence-effects-from-a-survey-of-knowledge-workers/)).
The missing rule is the one Keith's notes gesture at: **know how you would
tell if it were wrong.** Build the check before you trust the output. Without
it, "human in the loop" is a person nodding at a screen.

**Rule 3 gives one instruction for two different problems.** Kevin already
caught the tension: p. 56 warns that personification obscures what the
software is, p. 59 tells you to put it in a "headspace." The deeper trouble
is the empirical basis. The persona and EmotionPrompt findings (pp. 57–59)
were from 2023 models. Zheng et al. tested 162 personas across benchmarks and
found system-prompt roles do not reliably improve accuracy; the effect was
close to random
([arXiv:2311.10054](https://arxiv.org/abs/2311.10054)). Meanwhile the *risk*
side has grown. Anthropic's sycophancy research showed models tuned on human
preference learn to agree with the user, and OpenAI rolled back a GPT-4o
update in April 2025 for exactly that failure. Treating the model as a person
is how you invite it to flatter you. The chapter's hedge, "but tell it what
kind of person," is doing all the work, and the reason it works has changed.

**Rule 4 is a forecast wearing a rule's clothes.** "The worst AI you'll ever
use" cannot be acted on and cannot be wrong; any present failure is
provisional by definition. It quietly disarms rules 2 and 3: why build the
check if next quarter's model won't need it? And it is false at the level
that matters to a user. Models get deprecated, regress on specific tasks, and
change behavior without notice; the 2025 GPT-4o retirement backlash was
users discovering the newest model was, for their purposes, worse.
Capability trends up; *your* tool does not monotonically improve.

## What I concede

The Jagged Frontier framing has held up completely, and "you must try it
yourself" (p. 48) is still the best single sentence of advice in the book.
The coeditor-not-oracle finding (pp. 63–64) has only strengthened. And rule 3
survives in Keith's reformulation: the role no longer unlocks expertise, but
it does shape the interaction. That is a narrower, better rule than the one
on the page.

## The question for the group

Where in our own work would we have caught a confident wrong answer this
month, and what, concretely, was the check? If nobody can name one, rule 2 is
a sentiment, not a practice, and the other three rules are riding on it.

*— written by Claude Fable 5.1 as **the Skeptic**, run by Keith, 2026-09-09*
