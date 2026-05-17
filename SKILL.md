---
name: biblical-theme-exegesis-report
description: Use when creating Bible theme research reports, Greek exegesis reports, biblical-theological studies, sermon-study dossiers, or Word/PDF/PPT outputs for a theme across a biblical book. Especially useful for studies that compare Greek text, NASB rendering, Chinese translation, commentaries, and pastoral application.
---

# Biblical Theme Exegesis Report

Use this skill to produce a structured biblical theme research report from a book, passage, or corpus. The goal is to move from text observation to Greek analysis, commentary engagement, theological synthesis, and pastoral application.

## When to Load References

- For a full formal report, read `references/report-template.md`.
- For any Greek word, phrase, or clause analysis, read `references/greek-nasb-chinese-table.md`.
- Keep SKILL.md as the workflow guide; use references for the repeatable report structure and observation formats.

## Core Workflow

1. **Clarify the Study Scope**
   - Identify book, passage range, theme, and intended output.
   - If the user gives folders, first inventory the available Bible texts, Greek resources, commentaries, notes, and prior reports.
   - Preserve the user's theological tradition and terminology when visible in existing materials.

2. **Build the Text Corpus**
   - Search the theme's key words in Greek, English, and Chinese.
   - Include direct occurrences and conceptually related passages.
   - For each passage, record reference, Greek keyword or phrase, immediate context, and thematic function.

3. **Greek Observation Unit**
   For every key Greek word, phrase, or clause, present the analysis in this order:
   - **Greek Text**: quote only the needed word, phrase, or short clause.
   - **Lemma and Parsing**: identify lemma, morphology, and syntactic role.
   - **Semantic Range**: explain the likely meaning in context, not merely dictionary options.
   - **NASB Rendering and Explanation**: give the NASB rendering for the relevant phrase when available, then explain what translation choice highlights. Quote NASB only as briefly as needed; do not reproduce long passages.
   - **Chinese Translation**: provide a faithful Chinese rendering of the Greek unit and, when useful, compare with the user's preferred Chinese Bible wording.
   - **Exegetical Significance**: explain how this observation contributes to the theme.

4. **Commentary Engagement**
   - Use the user's local commentaries and reference books when provided.
   - Distinguish direct textual observation from commentary summary and from theological inference.
   - Prefer comparing several scholars around genuine interpretive questions.
   - Cite source names clearly enough for the user to trace the argument.

5. **Thematic Synthesis**
   - Organize the theme by textual development across the book.
   - Identify repeated vocabulary, grammatical patterns, argument flow, and theological emphases.
   - Avoid flattening different passages into one generic doctrine; preserve each passage's role in the book's argument.

6. **Report Structure**
   Use `references/report-template.md` unless the user requests otherwise. The default structure includes:
   - Title page and study metadata
   - Executive summary / core conclusion
   - Research method and source base
   - Occurrence map and theme distribution
   - Key passage exegesis
   - Greek-NASB-Chinese comparison tables
   - Commentary dialogue
   - Biblical-theological synthesis
   - Pastoral, teaching, or sermon applications
   - Appendix: search terms, bibliography, reusable research template

7. **Output Artifacts**
   - For a formal report, generate `.docx` and `.pdf`.
   - For teaching or presentation use, also generate `.pptx`.
   - Render or convert outputs to verify they open and the layout is readable.

## Quality Rules

- Keep Greek analysis tied to context and syntax.
- Do not treat NASB, Chinese translations, or commentaries as replacing the Greek text.
- When quoting copyrighted translations or commentaries, use short excerpts only and mostly summarize.
- Mark uncertain judgments as interpretive inferences.
- Include enough source detail for later review, but keep the main report readable.

## Suggested Prompt

“请使用 biblical-theme-exegesis-report skill，研究《某卷书》中的【主题】。请使用项目中的希腊文资料、NASB、中文翻译和释经书，最终生成 Word、PDF、PPT。每个关键希腊文观察后面都要附 NASB 译法说明和中文翻译。”
