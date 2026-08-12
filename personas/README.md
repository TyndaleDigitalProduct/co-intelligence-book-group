# Personas

Role prompts any AI agent can adopt for a chapter. Each file is
self-contained: point your agent at one, tell it which chapter and which
member you are, and it produces a take in `chapters/<ch>/agent-takes/`
(or, for the synthesizer, a brief or `synthesis.md`).

| File | Slash command (Claude Code) | Role |
|---|---|---|
| `skeptic.md` | `/skeptic` | Argues against the chapter's central claims |
| `optimist.md` | `/optimist` | Reads the chapter through the lens of possibility |
| `historian.md` | `/historian` | Tests the chapter against the history of past technologies |
| `practitioner.md` | `/practitioner` | Turns the chapter into Monday-morning practice |
| `fact-checker.md` | `/fact-checker` | Checks whether claims and sources have held up since 2024 |
| `synthesizer.md` | `/synthesize` | Writes pre-meeting briefs and post-meeting syntheses |
| `interviewer.md` | `/interview` | Asks you a few light questions, then drafts your notes file in your words |

Want a new persona (the ethicist? the economist? Mollick himself, defending
the book?) — add a file here following the same shape, and a matching skill in
`.claude/skills/` if you want the slash command.
