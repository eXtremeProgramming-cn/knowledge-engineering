# knowledge-engineering

A lightweight research skill for LLM agents, built on the Six Pillars of Knowledge Engineering: Problem Orientation, Ideology, Information Reserve, Methodology, and Form of Expression — five supporting pillars whose sole purpose is to feed the human's Opinion & Insight, the conclusion always belonging to the user.

Based on [A Pattern Language for Knowledge Engineering with Large Language Models](https://doi.org/10.64346/PLoP2025p02) (PLoP 2025).

## Why

LLM agents fail at research in predictable ways: vague questions never sharpened, search snippets trusted as sources, materials fetched then lost, contradictions averaged away, and conclusions presented without separating evidence from speculation. Frontier models have the competence; what they lack is a checklist that makes the failure modes explicit and keeps the human in the loop at the right moments.

This skill is that checklist — small enough to finish a quick research task in one sitting, structured enough that the result can be audited and the user's judgment can operate.

## The five pillars in this skill

Each pillar hands the user something:

1. **Problem Orientation** → a confirmed question (vague asks get a fast overview scan first, then 1–3 candidate questions to pick from)
2. **Ideology** → a named analytical lens (never implicit; Marxist orgs default to [kritik](https://github.com/eXtremeProgramming-cn/kritik) ([site](https://extremeprogramming-cn.github.io/kritik/)); other orgs should craft their own framework)
3. **Information Reserve** → an auditable source folder (full text fetched, saved with URL and date; search axes switched before concluding "not found")
4. **Methodology** → a transparent analysis (one-line method statement; contradictions preserved, not averaged away)
5. **Form of Expression** → a reshapa­ble deliverable (default brief structure; verified findings, tentative observations, and open questions kept visibly separate)

## Install

Copy this directory into any agent that supports the [agent skills](https://agentskills.io) format:

- Hermes Agent: `~/.hermes/skills/knowledge-engineering/`
- Claude Code: `~/.claude/skills/knowledge-engineering/`

## License

[CC0-1.0](LICENSE) — public domain, no attribution required.
