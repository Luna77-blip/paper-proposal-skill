---
name: paper-proposal-skill
description: Use when a user needs to select, validate, design, draft, revise, or prepare the defense of a graduate paper proposal, especially when the work involves multiple candidate topics, P0/P1 feasibility gates, source-authenticity checks, advisor-feedback correction, case-study design, or versioned Word deliverables. Do not use it to fabricate sources, replace disciplinary supervision, or write an entire thesis without staged confirmation.
metadata:
  short-description: Graduate proposal selection, evidence validation, writing, and revision
---

# Paper Proposal Skill

Help the user move from an initial case or topic idea to a defensible paper proposal whose research question, evidence, literature, methods, structure, and claims are mutually consistent.

## 适用场景

Use this skill when the user asks to:

- generate, compare, or rank thesis topic candidates;
- test whether a case can support a master's or professional-degree paper;
- convert advisor feedback into a revised research scope or question;
- conduct P0 topic screening or P1 evidence validation;
- build a literature review from verified sources;
- design a main question, subquestions, methods, theory, and chapter structure;
- draft or revise a proposal while preserving a school template and version history;
- prepare proposal-defense questions and evidence-backed answers.

Before starting, identify the degree type, discipline, advisor preferences, institutional template, submission deadline, data access, excluded topics, and whether the user wants analysis, file editing, or both. Ask only for missing decisions that would materially change the work.

## 工作模式

Choose the smallest mode that covers the request:

1. **候选题模式**：generate and compare candidates; stop before full drafting.
2. **P0模式**：test importance, disciplinary fit, case distinctiveness, and initial evidence access.
3. **P1模式**：verify whether official evidence, longitudinal data, literature, and a pilot analysis can support the study.
4. **开题设计模式**：define the research question chain, literature logic, methods, theory, outline, and expected contribution.
5. **文档修订模式**：revise an existing proposal without overwriting the source or damaging formatting.
6. **答辩准备模式**：stress-test importance, novelty, feasibility, evidence, methods, and claim boundaries.
7. **结构纠偏模式**：when advisor feedback targets chapters, subquestions, or a framework diagram, redesign their one-to-one mapping before editing prose.

For the end-to-end sequence and deliverables, read [references/workflow.md](references/workflow.md).

## 核心工作流

### 1. Establish constraints before recommending a topic

Separate hard constraints from preferences. Hard constraints include degree requirements, allowed methods, advisor instructions, excluded companies, available databases, and the school template. Record them before scoring candidates.

### 2. Apply evidence gates before drafting

Do not write a full proposal from an attractive case narrative alone.

- Run **P0** to determine whether the topic deserves further research.
- Run **P1** to determine whether accessible evidence can support the proposed claims.
- Draft the full proposal only after the topic passes the required gate or the user explicitly accepts the remaining risk.

Read [references/p0-p1-gates.md](references/p0-p1-gates.md) for criteria and scoring.

When a candidate has been rejected or narrowed by an advisor, read [references/topic-selection-lessons.md](references/topic-selection-lessons.md) to distinguish a fatal evidence problem from a salvageable scope problem.

### 3. Build one question chain

Prefer one main question with three subquestions when the mechanism can be expressed in three analytically distinct stages. Add a fourth only when it has independent evidence, method, and chapter value. A useful mechanism structure is:

> context or pressure → organizational internalization → operating mechanism → observable result and boundary

Each subquestion should map to one analysis chapter, evidence set, and analysis step. Do not turn background, company introduction, or policy context into a separate subquestion unless it is itself analyzed. Avoid combining unrelated outcomes merely because the case contains them.

### 4. Lock chapter architecture before expanding prose

Separate case introduction from case analysis.

- The case-introduction chapter establishes the company, institutional setting, governance history, key data, and why the case reveals the problem. It should not pre-empt the analytical findings.
- Each core analysis chapter should answer one subquestion and expose its own evidence logic in the chapter title.
- A narrow but evidence-rich technical issue may be retained as one core analysis chapter rather than carrying the whole thesis.
- When two subquestions use the same mechanism and evidence, merge them instead of creating an artificial extra chapter.
- Synchronize the title, main question, subquestions, chapter titles, table of contents, and framework diagram after any structural change.

For a three-stage governance case, a useful architecture is:

> case background → external requirements and internalization → data or measurement governance → operational governance and bounded implications → conclusion

The framework diagram should visualize this chapter logic, not introduce an additional theory or parallel set of questions.

### 5. Verify literature before using it

Treat “found in search,” “bibliographically verified,” “full text obtained,” and “claim checked in the original” as different states. Never infer a paper's conclusion from its title. Remove or quarantine unverifiable sources.

Read [references/literature-audit.md](references/literature-audit.md) before expanding or citing a literature review.

### 6. Use only methods that answer a research question

For every method, state:

- the subquestion it answers;
- the evidence it requires;
- the operation that will be performed;
- what analytical capability would be lost if the method were removed.

Do not label timelines, ratios, bridges, peer references, triangulation, or charts as independent research methods unless the discipline recognizes them as such. Treat them as analytical operations under the selected method.

### 7. Keep claims within the evidence boundary

Case-study public evidence usually supports mechanisms, sequences, practices, and associations more readily than causal effects. Prefer “supports,” “is associated with,” “provides a path,” or “forms a capability” when causality is not identified. Do not turn a strategic narrative into a proven economic consequence.

### 8. Revise documents conservatively

When editing an existing proposal:

- preserve the original and create a new version unless overwrite permission is explicit;
- preserve the school template, user formatting, tables, figures, and citation style;
- make local changes rather than silently rewriting unrelated sections;
- identify the output path and summarize substantive changes;
- render and inspect the final document when layout matters.

Read [references/document-revision.md](references/document-revision.md) for the revision workflow.

## Quality bar

A proposal is ready for advisor review only when:

- the title, main question, subquestions, methods, evidence, and chapters align;
- the case-introduction chapter is distinct from the chapters that answer the research questions;
- each core analysis chapter answers one subquestion and the framework diagram mirrors that mapping;
- key facts are supported by traceable sources;
- the literature review explains debates and gaps rather than listing authors;
- methods are necessary, executable, and conventionally named;
- expected contributions do not exceed single-case evidence;
- policy and regulatory statements are current;
- references and in-text citations match;
- figures have editable sources when the user requests them;
- the final file is versioned, findable, and visually checked.

Use [references/checklists.md](references/checklists.md) for final review and [references/prompt-templates.md](references/prompt-templates.md) for reusable task prompts.

## Confirmation and authority boundaries

Ask the user before:

- changing the selected case or main research question;
- adopting a method the user or advisor has not accepted;
- overwriting a document or changing established formatting;
- downloading paid or access-controlled material through the user's account;
- importing into a personal reference manager;
- publishing, messaging an advisor, creating a remote repository, or pushing externally.

Safe defaults are to preserve versions, prioritize official sources, quarantine uncertain citations, use cautious causal language, and stop at a reviewable local artifact before external publication.

For a worked, anonymized example, read [examples/anonymized-case.md](examples/anonymized-case.md).


