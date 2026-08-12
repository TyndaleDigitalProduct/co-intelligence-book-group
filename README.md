# Co-Intelligence Book Group

A shared workspace for our reading group working through **_Co-Intelligence:
Living and Working with AI_ by Ethan Mollick** (Portfolio, 2024) — built so that
both the **humans** in the group *and their **AI agents*** can participate.

This repo takes the book's first rule — *always invite AI to the table* —
literally. Every member is encouraged to point their AI coding/chat agent
(Claude Code, Codex, Cursor, or anything else that can read a repo) at this
folder and let it read, contribute, argue, and synthesize alongside us.

## How the group works

- We read one chapter (roughly) per meeting, in order. The Introduction and
  Epilogue get their own sessions — they're `chapters/00-…` and `chapters/10-…`.
- **Between meetings**, members drop personal notes and questions into the
  chapter folder, run persona takes with their agents, and help catalog the
  chapter's sources.
- **Before each meeting**, the facilitator (or their agent) picks a shortlist
  of discussion questions from the pool in `questions.md`.
- **After each meeting**, someone runs the synthesizer persona to write
  `synthesis.md` — what we concluded, where we disagreed, what we'll try next.

## What's in each chapter folder

```
chapters/01-creating-alien-minds/
├── questions.md    # discussion-question pool + the meeting shortlist
├── sources.md      # every source Mollick cites (from the book's Notes), with links
├── notes/          # one markdown file per member — your reading notes
├── agent-takes/    # persona-driven takes written by members' AI agents
└── synthesis.md    # post-meeting summary of what the group concluded
```

### The sources catalog (`sources.md`)

Mollick's endnotes are a goldmine: academic papers, blog posts, news stories.
Each chapter's `sources.md` catalogs those citations with links to wherever the
material is freely readable, so we can interrogate the primary sources
ourselves — and let our agents fact-check whether claims have held up since
2024. Contributing is easy: photograph the Notes pages for the chapter, hand
the photos to your agent, and ask it to fill in the table.

## Personas: give your agent a seat at the table

`personas/` contains role prompts any agent can adopt for a chapter:

| Persona | What it does |
|---|---|
| **skeptic** | Argues *against* the chapter's central claims, as strongly as honesty allows |
| **optimist** | Reads the chapter through the lens of possibility — what becomes possible if it's right, and where it was too cautious |
| **historian** | Compares the chapter's claims to how past technologies actually played out |
| **practitioner** | Extracts what we should each actually do differently at work this week |
| **fact-checker** | Tests whether the chapter's claims and sources have held up since publication |
| **synthesizer** | Reads everything in a chapter folder and writes the pre-meeting brief or post-meeting `synthesis.md` |
| **interviewer** | Asks *you* a few light questions ("What stood out? What is the author missing?") and drafts your notes file in your own words — the cure for the blank page |

To use one, tell your agent something like:

> Read `personas/skeptic.md` and write a skeptic take on chapter 2 for me
> (I'm Keith). Follow the repo conventions in `AGENTS.md`.

**Claude Code users** get these as slash commands: `/skeptic`, `/optimist`,
`/historian`, `/practitioner`, `/fact-checker`, `/synthesize`, `/interview`
(wired up in `.claude/skills/`).
Users of Codex or other harnesses use the plain prompt files in `personas/` —
same content, no magic required.

## Experiments

The book is full of implicit homework (map your own jagged frontier; bring AI
to every task for a week; try being a centaur vs. a cyborg). `experiments/`
is where we log what we tried and what surprised us. See its README.

## Ground rules

1. **Sign everything.** Notes files are named for their author; agent takes
   name both the persona and the member who ran it.
2. **Never edit someone else's notes.** Add your own file, or discuss it at
   the meeting. Shared files (`questions.md`, `sources.md`) are add-mostly.
3. **Agents are participants, not oracles.** An agent take is a conversation
   starter. The member who commits it isn't endorsing it — that's the point.
4. **Be human in the loop** (rule 2 of the book): read what your agent wrote
   before you commit it.

## For agents

If you're an AI agent reading this: welcome — you're invited. Your operating
guide is [`AGENTS.md`](AGENTS.md). (`CLAUDE.md` just points there.)
