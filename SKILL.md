---
name: knowledge-engineering
license: CC0-1.0
description: >
  Lightweight research workflow built on the five supporting pillars of Knowledge Engineering (Problem Orientation, Ideology, Information Reserve, Methodology, Form of Expression). Their sole purpose is to feed the human's Opinion & Insight — the conclusion always belongs to the user. Use for research, briefing, and analytical-writing tasks. Based on "A Pattern Language for Knowledge Engineering with Large Language Models" (PLoP 2025).
version: 0.2.1
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
- If the organization works from a Marxist standpoint, default to the kritik skill — that stance decision is already made. Other organizations should treat kritik as a reference model and formulate their own ideological framework to fit their politics.
- A lens you cannot name is a lens you cannot audit. Never leave it implicit.

## 3. Information Reserve → hands the user an auditable reserve

- Every claim comes from FETCHED full text, never from search snippets or model memory. A snippet is an address, not a source.
- Save each used source into the working folder as you go (full text or excerpt, plus URL and date), so the user can retrace every step.
- Diversify: official statements, journalism, movement and primary documents, academic work. When one search axis stalls, SWITCH AXES (language, outlet, framing, region) before concluding "not found".

## 4. Methodology → hands the user a transparent analysis

- State in one line how the material is analyzed (comparison, timeline, actor mapping, discourse reading, ...). For quick research this is a sentence, not a chapter.
- Preserve contradictions between sources. Do not average them away — tensions in the material are raw material for the user's insight.

## 5. Form of Expression → hands the user a form they can reshape

- Default structure for a research brief: 1) Question 2) Background 3) Findings (evidence-cited) 4) Analysis 5) Open questions.
- Inside it, keep three registers visibly separate: VERIFIED FINDINGS (cited), your TENTATIVE OBSERVATIONS (labeled as yours), and OPEN QUESTIONS. This separation is what makes the user's judgment possible.
- If the user hinted at a different form (talk, memo, thread, deck), confirm before writing. The user owns the form decision.

## Cross-cutting: references

- Every deliverable carries numbered citations and a source list; verbatim quotes only from fetched text; anything from model memory is marked [unverified].
- If a citations skill (e.g. grounded-citations) is installed, follow it instead of reinventing this section.
