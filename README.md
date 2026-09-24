# knowledge-engineering

A lightweight research skill for LLM agents: five pillars of knowledge engineering, organized to feed the human's Opinion & Insight — the conclusion always belongs to the user.

![A chibi whale-girl maid climbing a library ladder to reach a book — searching for knowledge, one book at a time.](meme.png)

LLM agents fail at research in predictable ways: the question never gets sharpened, search snippets are trusted as sources, fetched material gets lost, facts and interpretations blur together, and a conclusion arrives without showing its work. Frontier models have the competence; what they lack is a checklist that makes the failure modes explicit and keeps the human in the loop at the right moments.

This skill is that checklist — small enough to finish a quick research task in one sitting, structured enough that the result can be audited.

## The five pillars

Method source: Xiong Jie, *A Pattern Language for Knowledge Engineering with Large Language Models*, PLoP 2025 ([DOI 10.64346/PLoP2025p02](https://doi.org/10.64346/PLoP2025p02)). The pillars are supporting scaffolding; at the center sits the human's Opinion & Insight.

1. **Problem Orientation** → a confirmed question. Vague asks get a fast overview scan first, then 1–3 candidate questions to pick from; deep collection waits until the question is confirmed.
2. **Ideology** → a named analytical lens. As Marxists, we default to the [kritik](https://github.com/eXtremeProgramming-cn/kritik) skill ([site](https://extremeprogramming-cn.github.io/kritik/)); other organizations should treat kritik as a reference model and craft their own framework.
3. **Information Reserve** → an auditable source folder. Full text is fetched, never snippets; every used source is saved with URL and date; search axes switch before concluding "not found". Implements POMASA pattern [BHV-05 Grounded Web Research](https://github.com/eXtremeProgramming-cn/pomasa/blob/main/skills/pomasa/pattern-catalog/BHV-05-grounded-web-research.md).
4. **Methodology** → a detailed analysis. Work from the question, on the material, through the lens; contradictions stay visible — they are raw material for the user's insight.
5. **Form of Expression** → a reshapable deliverable. Executive summary, question, background, findings and analysis (footnoted, interpretations labeled), conclusions and open questions. The user owns the form decision.

## Install

With the [skills CLI](https://skills.sh):

```bash
npx skills add eXtremeProgramming-cn/knowledge-engineering
```

Or copy this directory into any [agentskills.io](https://agentskills.io)-compatible agent: `~/.hermes/skills/knowledge-engineering/` (Hermes Agent), `~/.claude/skills/knowledge-engineering/` (Claude Code), or just read `SKILL.md` — the skill is one file.

## Related

- [kritik](https://github.com/eXtremeProgramming-cn/kritik) — the ideological framework this skill defaults to ([site](https://extremeprogramming-cn.github.io/kritik/))
- [POMASA](https://github.com/eXtremeProgramming-cn/pomasa) — the heavyweight pattern language + generator this skill is the lightweight counterpart of ([pattern catalog](https://github.com/eXtremeProgramming-cn/pomasa/tree/main/skills/pomasa/pattern-catalog))

## License

[CC0-1.0](LICENSE) — public domain, no attribution required. ![CC0](cc-zero.svg)
