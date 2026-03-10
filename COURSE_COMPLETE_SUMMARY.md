# Course Package Summary — Copilot in Edge Essentials v2.0

**Status:** Production Ready | **Date:** March 2026

---

## What Was Built

A 65-minute hands-on lab (+ optional bonus tasks) teaching Microsoft Copilot in Edge through a realistic banking scenario. Participants play a Product Manager at a regional bank evaluating the **ClearSpend** personal finance dashboard.

---

## File Structure

```
CopilotEdge/
│
├── README.md                        ← Quick start and overview
├── Lab_Action_Guide.md              ← Full lab guide (all tasks, prompts, outputs)
├── COURSE_COMPLETE_SUMMARY.md       ← This file
│
├── Inputs/
│   ├── Engineering_Notes.pdf        ← Lab 1: PDF with feature specs and launch plan
│   ├── Strategic_Connections.html   ← Lab 2: Styled HTML market research report
│   └── Financial_Projections.xlsx   ← Lab 3: 4-sheet Excel workbook
│
├── Lab1/
│   ├── Lab1_Team_Email.md
│   ├── Lab1_Executive_Summary.md
│   └── Lab1_Feature_Blog.md
│
├── Lab2/
│   ├── Lab2_Implementation_Challenges.md
│   ├── Lab2_Risk_Briefing.md
│   └── Lab2_Market_Analysis.md
│
└── Lab3/
    ├── Lab3_Strategic_Memo_Draft.md
    ├── Lab3_CFO_Memo.md
    ├── Lab3_GoNoGo_Summary.md
    ├── Lab3_Hallucination_Test_Log.md
    └── Lab3_Strategic_Memo_Final.md
```

**Total files:** 17 (3 inputs + 11 output placeholders + 3 guide/summary docs)

---

## Lab Design

### Lab 1 — Engineering Deep-Dive (20 min)
**Input:** `Engineering_Notes.pdf` (PDF format)
**Skills:** Open PDF in Edge, Copilot reads active tab, short analysis prompts, RIFCC writing

| Task | What Participants Do |
|------|---------------------|
| 1.1 | Ask Copilot what ClearSpend does (analysis) |
| 1.2 | List top 3 technical risks (analysis) |
| 1.3 | Summarize launch timeline (analysis) |
| 1.4 | Write a team email using RIFCC (writing) |
| 1.5 | Write an executive summary (writing) |
| 1.6 | Write a feature blog post (writing) |

---

### Lab 2 — Market Research (20 min core + bonus)
**Input:** `Strategic_Connections.html` (styled HTML report)
**Skills:** HTML in Edge, citation links, Compose tab, risk table, market analysis

| Task | What Participants Do |
|------|---------------------|
| 2.1 | Identify top market trends (analysis) |
| 2.2 | Summarize competitive landscape (analysis) |
| 2.3 | Ask Copilot about financial outlook (analysis) |
| 2.4 | Write risk briefing table (RIFCC writing) |
| 2.5 | Write market analysis memo (RIFCC writing) |
| 2.A | Bonus: Compose tab tone rewrite |
| 2.B | Bonus: YouTube fintech video analysis |

---

### Lab 3 — Financial Analysis (25 min core + bonus)
**Input:** `Financial_Projections.xlsx` (4-sheet Excel workbook)
**Skills:** Excel in Edge, multi-sheet navigation, hallucination detection, CFO-level writing

| Task | What Participants Do |
|------|---------------------|
| 3.1 | Summarize Executive Summary sheet (analysis) |
| 3.2 | Identify cost overruns (analysis) |
| 3.3 | Explain ROI scenarios (analysis) |
| 3.4 | Draft strategic memo (RIFCC writing) |
| 3.5 | Write CFO recommendation memo (RIFCC writing) |
| 3.A | Bonus: Go/No-Go decision table |
| 3.B | Bonus: Stakeholder Q&A prep |

---

## Input Files Detail

### `Engineering_Notes.pdf`
- Created with fpdf2 Python library
- Blue cover block, section headers, colour-coded launch table, footers
- Contains: feature overview, technical specs, implementation risks, timeline
- Key fix: Unicode em-dashes replaced with `--` for Helvetica compatibility

### `Strategic_Connections.html`
- Full styled HTML (2026 Digital Banking & Fintech Innovation Report)
- CSS: blue headers, stat callout boxes, colour-coded risk rows
- Contains: 5 market trends, risk table, competitor landscape, financial outlook
- Demonstrates: Copilot reading styled web content, citation link generation

### `Financial_Projections.xlsx`
- 4 sheets: Executive Summary, Cost Breakdown, ROI & Projections, Risk Register
- Colour coding: red for cost overruns, green/yellow/red for risk severity
- Contains: 3 break-even scenarios, 3-year revenue forecast
- Demonstrates: Copilot navigating multi-sheet Excel in Edge

---

## Key Features

| Feature | Where |
|---------|-------|
| **RIFCC prompt pattern** | All writing tasks (1.4, 1.5, 1.6, 2.4, 2.5, 3.4, 3.5) |
| **Short analysis prompts** | All analysis tasks (1.1–1.3, 2.1–2.3, 3.1–3.3) |
| **Citation links [1][2]** | Taught in Lab 2 Task 2.1 |
| **Compose tab** | Lab 2 Bonus 2.A |
| **Human-in-the-Loop checklist** | End of each lab before saving |
| **Hallucination detection** | Lab 3 Task 3.A, hallucination test log |
| **Copilot Toolkit** | 6 reusable prompt templates at end of Lab_Action_Guide.md |
| **Multimodal (video)** | Lab 2 Bonus 2.B |

---

## Concepts Taught

### RIFCC Pattern
```
Role        — Define Copilot's perspective
Input       — Reference the open document
Task        — Specify what to produce
Format      — Table / bullets / paragraphs / memo
Constraints — Length, tone, audience, scope
```

### Browser-Based Workflow
```
Open file in Edge → Copilot sidebar → Copilot reads active tab → Prompt → Save output
```
No copy-pasting document content into prompts.

### Human-in-the-Loop Review (per lab)
Before saving: verify facts, check for invented data, confirm tone, confirm you read it.

### Citation Links
`[1]`, `[2]` in Copilot responses are clickable — they jump to the source sentence in the document. Primary hallucination-check tool.

---

## Timing

| Section | Time |
|---------|------|
| Lab 1 (core) | 20 min |
| Lab 2 (core) | 20 min |
| Lab 3 (core) | 25 min |
| **Core Total** | **65 min** |
| Bonus tasks (2.A, 2.B, 3.A, 3.B) | +20–30 min optional |

---

## What Changed from v1.0

| v1.0 | v2.0 |
|------|------|
| Healthcare scenario | Banking / ClearSpend scenario |
| Module 2/3/4 | Lab 1/2/3 |
| .md input files only | PDF + HTML + XLSX inputs |
| Exercises/ and Outputs/ folders | Lab1/ Lab2/ Lab3/ output folders |
| Input A/B/C/D/E/F | Engineering_Notes, Strategic_Connections, Financial_Projections |
| No writing tasks | RIFCC writing tasks in every lab |
| No bonus structure | Bonus 2.A, 2.B, 3.A, 3.B |
| No Compose tab | Compose tab taught in Lab 2 Bonus |
| No citation link teaching | Citation links introduced in Lab 2 |
| No Human-in-the-Loop | Checklist at end of each lab |
| No prompt library | Copilot Toolkit (6 templates) at end of guide |

---

**Course Package Version:** 2.0
**Last Updated:** March 2026
**Status:** Production Ready
