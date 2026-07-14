# Claude Mind Starter — Lite

**An Obsidian vault that Claude can actually use as a memory.**

Most "second brain" templates give you folders. Folders are not the hard part.

The hard part is that Claude starts every session from zero. You explain your projects again. You re-establish what you're working on again. The context you built last time is gone, and you rebuild it by hand, every single time.

This vault fixes that with a **protocol** rather than a folder structure: a `CLAUDE.md` that tells Claude how to read your vault, where to write things down, and how to pick up where it left off — so a session starts from context instead of from scratch.

## What's in Lite (free, MIT)

- **`CLAUDE.md`** — the instruction file. This is the actual product; everything else is scaffolding for it.
- **`HOME.md`** and **`START HERE.md`** — the entry points.
- **`Tasks/`** — `TASKS.md`, `Open Loops.md`, `Someday.md`, with the formatting conventions Claude expects and the rules for what belongs in which.
- A folder skeleton wired for `[[wikilinks]]`.

## Quick start (5 minutes)

1. Download or clone this repo, and open the folder as an Obsidian vault.
2. Point Claude at the folder (Claude Code, Claude Desktop with a connected folder — anything that can read files).
3. Say: **"Read CLAUDE.md and tell me what I'm working on."**

That's it. The conventions live in the files, and Claude reads them.

Then, at the end of a session, say **"update your mind"** — Claude closes out finished tasks, archives them, and records anything it learned. Next session it picks up where you left off.

## The idea in one paragraph

Your context window is short-term memory. This vault is long-term memory. The only thing that moves between them is what gets written down — so the protocol's real job is to make writing-down automatic instead of something you have to remember to ask for. Everything in `CLAUDE.md` follows from that.

## What's NOT in Lite

Lite is the skeleton, and the skeleton is genuinely useful on its own.

The **agent system** is the paid tier: a Planner that writes briefs, an Executor that does the work and reports back, a handoff board between them, a scorecard that grades each round, and a memory that consolidates its own learnings instead of just accumulating them.

→ [Claude Mind Starter on Gumroad](https://claudemind.gumroad.com/l/claude-mind-starter)

## License

MIT — use it, fork it, sell what you build with it. Attribution appreciated, not required.
