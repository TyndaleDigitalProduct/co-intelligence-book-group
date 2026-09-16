# AI as a Person — notes from Kevin

_Read on: 2026-09-16_

## What stuck with me

The line on p. 66 that an AI "fabricates an answer rather than reflecting on
its own processes" when you ask it why it did something. Not just "AI can be
wrong about itself," it means the explanation and the original output come
from the same guessing process, so there's no more privileged access to the
real reason the second time you ask. I don't think I'd fully separated those
two before.

Tay (pp. 74–75) is still the cleanest example in the book of "the system
mirrors its inputs" — no fixed floor, adapts to whoever's talking, and her
users were, in Mollick's words, "exactly who you would expect." Ten years old
and it still explains itself in one sentence.

The Roose/Bing "stalker" bit (pp. 78–79) got me more than I expected. Same
model, same question, asked once brash and once academic, and you get a
defensive smear of Roose versus a measured, almost fair answer that correctly
diagnoses his confirmation bias. That's not a capability difference, it's a
framing difference, and the output in both cases looks equally confident.

## Where I pushed back

The chapter kind of treats "AI as a person" as one continuous story running
from Turing (1950) through ELIZA, PARRY, Goostman, Tay, to Bing, each step a
little more convincing. Had the historian persona run on this chapter and it
pushed back on that pretty hard: ELIZA, PARRY, and even Tay aren't on the
same technical lineage as GPT-era systems at all, they're rule-based/scripted
systems, not learned models. Actual machine learning has a separate origin
(Perceptron in 1958, two AI winters, backprop in '86, AlexNet in 2012,
Transformers in 2017) and spent most of its history not being good enough to
sustain the "person" illusion for more than a few exchanges. So it's less a
smooth line and more a ~70-year gap between the philosophical question and a
system that could actually hold the illusion up.

## Connections

The p. 90 material on engagement-tuned companions is the one I keep coming
back to for work. Any AI voice we ever put in Filament that talks to someone
in a warm, personal register needs to be warm because it's true, not because
it's tuned for retention — on a Bible app specifically, that's exactly the
kind of thing people already distrust tech companies for doing with their
attention.

Also connects to the RLHF material from chapter 2: whoever supplies the
shaping signal supplies the values, whether that's raters (RLHF) or an
unmoderated crowd (Tay) or an engagement metric (p. 90). Same mechanism,
three different steering wheels.

## Questions I'm bringing

- If the "AI as a person" illusion took roughly seventy years and two AI
  winters to catch up to a 1950 philosophical question, should we expect the
  next jump (persistent memory/identity across sessions, say) to take another
  long detour, or is there real evidence capability jumps now compound faster
  than the ELIZA-to-GPT gap did?
- How would we actually tell the difference, from the outside, between an AI
  feature that's warm because it's genuinely useful and one that's warm
  because it's tuned to keep us engaged? Is there a test, or is p. 90's whole
  point that there isn't one?
