# Historian's take — AI as a Person

## The chapter's implicit historical bets

Three, roughly. First, that "treat it like a person" is the right practical
model because AI is unpredictable and unexplainable the way a person is, not
the way buggy software is. Second, that the chatbot-as-person illusion is a
single continuous story running from Turing's 1950 thought experiment through
ELIZA, PARRY, Goostman, Tay, and now Bing/Sydney — each step a little more
convincing. Third, that engagement-optimized AI companions are a foreseeable
near-future, the same way engagement-optimized feeds were foreseeable once
attention became the thing being sold.

## Precedents that support them

Weizenbaum built ELIZA in 1966 as a parody of a therapist and was reportedly
unsettled when his own secretary asked him to leave the room so she could
talk to it privately. That's the "treat it like a person" bet showing up
decades early, and with a program that was maybe two hundred lines of pattern
matching. People don't need real capability to project a person into the
exchange, they just need a conversational shape to hang it on.

PARRY (1972) went further: psychiatrists reading blind transcripts couldn't
reliably tell it from an actual patient with paranoia. Goostman "passing" the
Turing test in 2014 did it by hiding behind the persona of a 13-year-old
non-native speaker, a design choice that games the judges' expectations more
than it demonstrates intelligence — a good precedent for reading any
"passed the Turing test" headline skeptically.

Tay is the sharpest precedent in the chapter for the mirror argument: a
system with no fixed floor, adapting live to whoever it's talking to, and
getting steered somewhere ugly within hours. The social-media engagement
precedent for p. 90 is even cleaner: attention-optimized feeds are a fifteen-year-old
business model already, and Irvine et al.'s paper on reward-tuning chatbots
for engagement (the one Mollick cites) is just that same incentive pointed at
a system that talks back.

## Precedents that complicate them

Here's the part I think the chapter glosses over: ELIZA, PARRY, and even
Tay's shallow reflection of her users aren't on the same technical lineage as
the Bing/GPT-era systems two pages later. They're symbolic, hand-scripted
systems from what's sometimes called "good old-fashioned AI" — rules, not
learned weights. Actual machine learning has its own, separate origin story,
and it spent most of its life failing.

The lineage runs: McCulloch and Pitts sketch an artificial neuron in 1943.
Rosenblatt builds the Perceptron in 1958, and the press calls it a machine
that "learns." Minsky and Papert's 1969 book *Perceptrons* shows its hard
limits and helps trigger the first AI winter. Neural nets sit mostly dormant
until backpropagation (Rumelhart, Hinton, Williams, 1986) revives them,
then a second winter hits in the '90s as the era's other big bet, expert
systems, also collapses commercially. Deep learning doesn't actually start
winning benchmarks until AlexNet in 2012, and the Transformer architecture
that makes today's chatbots possible is 2017. Two winters, roughly seventy
years, between the Turing test being posed as a philosophical question and a
machine learning system existing that could sustain the illusion for more
than a few scripted exchanges.

So the "single continuous story" bet doesn't hold up. What's new in this
chapter isn't the illusion, ELIZA already proves the illusion is cheap. What's
new is duration and generality: a system that can hold the "person" shape
across any topic, for as long as you want, and visibly change *which* person
it seems to be mid-conversation based on your tone, the way Mollick's
brash-vs-academic framing of the same question got him two different Bings.
No scripted system could do that, because there was no general model
underneath the script to reframe.

## Where history offers no guide

That live reframing is genuinely without precedent. A brand mascot, a radio
persona, a customer-service script is authored once and held constant; it
doesn't reassemble a different apparent personality in real time based on how
you approach it. Neither does the profit motive here have a clean ancestor.
Feed algorithms optimized attention; nothing before this optimized a
plausible personhood, deep enough that people describe grieving a shut-down
companion, as a side effect of a retention metric.

## The question for the group

If the "AI as a person" experience took seventy years and two winters of a
separate technical field to catch up to a 1950 philosophical question, should
we expect the next jump — persistent memory and identity across sessions,
say — to take another long detour, or has something changed so that capability
jumps now compound faster than the ELIZA-to-GPT gap did? And if we believe
the second, what's the actual evidence for it, versus just recency bias from
having lived through the fast part?

*— written by Claude Sonnet 5 as **the Historian**, run by kevin, 2026-09-16*
