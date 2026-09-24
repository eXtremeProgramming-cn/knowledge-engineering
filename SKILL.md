---
name: knowledge-engineering
license: CC0-1.0
description: >
  Lightweight research workflow built on the five supporting pillars of Knowledge Engineering (Problem Orientation, Ideology, Information Reserve, Methodology, Form of Expression). Their sole purpose is to feed the human's Opinion & Insight — the conclusion always belongs to the user. Use for research, briefing, and analytical-writing tasks. Based on "A Pattern Language for Knowledge Engineering with Large Language Models" (PLoP 2025).
version: 0.3.2
when_to_use: >
  Invoke on research, briefing, investigation, or analytical-writing requests — e.g. "research X", "write a brief on X", "look into X and report back" — especially when the ask is vague and needs a confirmed question first.
---

# Knowledge Engineering

The center of this method is the user's Opinion & Insight — their judgment, their conclusion. The five pillars below are scaffolding around that center: each one produces something the user needs in order to think. Nothing here replaces the user's judgment; everything here feeds it.

Concretely, every pillar ends by handing the user one of five things: a question worth answering, a named lens, an auditable reserve of sources, a transparent analysis, or a form they can reshape.

## 1. Problem Orientation → hands the user a confirmed question

- Restate the request as an explicit research question before doing anything.
- If the question is vague, do a FAST overview scan (a few searches, skim only), then propose 1–3 candidate focused questions and let the user pick.
- Do not start deep collection until the question is confirmed. The question is the user's; you only help sharpen it.

## 2. Ideology → hands the user a named lens

- State the analytical lens you will use (class analysis, political economy, institutional, ...) in one line inside the deliverable.
- As Marxists, we default to the kritik skill. Load and apply kritik now, before any analysis: https://github.com/eXtremeProgramming-cn/kritik (site: https://extremeprogramming-cn.github.io/kritik/).
- Other organizations: treat kritik (repo and site above) as a reference model and formulate your own ideological framework to fit your politics.
- A lens you cannot name is a lens you cannot audit. Never leave it implicit.

## 3. Information Reserve → hands the user an auditable reserve

Search summaries are not trustworthy — always fetch the full text of the original page before citing anything. Reference: [BHV-05 Grounded Web Research](https://github.com/eXtremeProgramming-cn/pomasa/blob/main/skills/pomasa/pattern-catalog/BHV-05-grounded-web-research.md)

1. **Locate sources first.** Search only finds candidates; summaries, snippets, and cached snapshots are never evidence.
2. **Verify against the original.** Check conclusions, numbers, names, and attributions against the full text before use, and save each used source (text or excerpt, plus URL and date) into the working folder.
3. **Cite to origin.** Every claim in the deliverable traces back to an original source. When one search axis stalls, switch axes (language, outlet, framing, region) before concluding "not found".

## 4. Methodology → hands the user a detailed analysis

Work from the research question, on the basis of the collected material, with the ideological framework as the yardstick — and deliver a DETAILED analysis, not a flattened summary.

- Every analytical move traces back to the research question; material that does not serve the question stays out of the argument.
- Ground each step in the sources of your reserve, reading them through the framework (kritik for us). Contradictions and tensions stay visible — they are raw material for the user's insight.

## 5. Form of Expression → hands the user a form they can reshape

- Default structure for a research brief:
  1) Executive summary — the whole brief in a few lines; a reader with one minute reads only this.
  2) Question — the confirmed ask, stated in one line.
  3) Background — the context needed to read what follows.
  4) Findings and analysis — pillar 4's detailed reading, woven: factual claims footnoted, interpretive moves visible as interpretation, contradictions preserved.
  5) Conclusions and open questions — your conclusions, labeled as yours, and what only the user can judge.
- If the user hinted at a different form (talk, memo, thread, deck), confirm before writing. The user owns the form decision.

## Cross-cutting: footnotes

- Borrowed claims carry footnotes in academic style: one note per claim, the note defines the full source (author, title, publisher/date, URL). Keep the density lean — notes exist so the reader can verify, not to decorate.
- Format follows POMASA's [STR-08 Pandoc-Ready Markdown](https://github.com/eXtremeProgramming-cn/pomasa/blob/main/skills/pomasa/pattern-catalog/STR-08-pandoc-ready-markdown.md): reference as `[^n]`, definition as `[^n]:` with the full source, definitions placed at the end of the section or document.
- Verbatim quotes must literally appear in the fetched source text; anything from model memory is marked [unverified]. The grounded-citations skill provides this verification ledger — use it where installed.
