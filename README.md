# TCSS 305 – Group Project: AI Agent Track

**UW Tacoma | Autumn 2026**

This repository holds your team's game for the AI Agent Track. Your team designs the game from a genre brief or an approved proposal, and builds it in Java Swing by directing a coding agent.

## Project Instructions

Track page, with the ground rules and the genre briefs: https://cfb3.github.io/TCSS305-26-AUTUMN/assignments/group-project/agent/

Sprint 0: https://cfb3.github.io/TCSS305-26-AUTUMN/assignments/group-project/agent/sprint-0/

Each sprint has its own page, linked from the track page. The sprint pages are the full instructions. This file is only a map of the project.

## Project Structure

```
src/edu/uw/tcss/
├── model/
│   └── package-info.java           (the model: the game's state and rules)
└── view/
    └── package-info.java           (the view: Swing classes that draw the game)

test/edu/uw/tcss/
├── model/
│   └── package-info.java           (tests for the model)
└── view/
    └── package-info.java           (tests for the view)

design/
└── requirements.md                 (your game's requirements, to fill in)

executive-summary.md                (your team's notes, one section per sprint)
README.md                           (this file)
```

`src` and `test` hold no game code. Each `package-info.java` names its package and describes it in one line of Javadoc. The `design/` folder also holds the design documents later sprints ask for, and `design/proposal.md` if your team proposes its own game.

## CLAUDE.md

Your team creates `CLAUDE.md` in Sprint 0, by running `/init` in Claude Code and then revising the draft. Sprint 0's Requirement 5 says what to add to it. Commit `CLAUDE.md`, because every agent session in the repository reads it.

Each member's personal `CLAUDE.local.md` and `.claude/settings.local.json` stay out of the repository, and `.gitignore` already excludes them.
