# Copilot in Edge Essentials — Hands-On Lab

**Version 2.0 | March 2026**

A practical, hands-on lab that teaches you to use Microsoft Copilot in Edge to analyze multi-format documents, write professional business communications, and verify AI outputs responsibly.

---

## Quick Start

**Requirements:**
- Microsoft Edge (latest) with Copilot sidebar enabled
- Microsoft account (free at microsoft.com)
- The three input files in the `Inputs/` folder

**To begin:** Open `Lab_Action_Guide.md` and follow Lab 1 → Lab 2 → Lab 3.

---

## Scenario

You are a **Product Manager at a regional bank** evaluating the **ClearSpend** personal finance dashboard — a new feature being considered for the bank's mobile app. Across three labs, you'll use Copilot to read engineering notes, research the market, and analyze financial projections to form a recommendation.

---

## Lab Structure

| Lab | Topic | Input File | Core Time | Bonus |
|-----|-------|-----------|-----------|-------|
| **Lab 1** | Engineering Deep-Dive (PDF) | `Inputs/Engineering_Notes.pdf` | 20 min | — |
| **Lab 2** | Market Research (HTML) | `Inputs/Strategic_Connections.html` | 20 min | 2.A, 2.B |
| **Lab 3** | Financial Analysis (Excel) | `Inputs/Financial_Projections.xlsx` | 25 min | 3.A, 3.B |

**Core lab total: 65 minutes.** Bonus tasks are optional extensions for faster participants.

---

## Folder Structure

```
CopilotEdge/
│
├── README.md                        ← You are here
├── Lab_Action_Guide.md              ← Main lab guide (start here!)
│
├── Inputs/                          ← Open these files in Edge before prompting
│   ├── Engineering_Notes.pdf        ← Lab 1 input
│   ├── Strategic_Connections.html   ← Lab 2 input
│   └── Financial_Projections.xlsx   ← Lab 3 input
│
├── Lab1/                            ← Save your Lab 1 outputs here
│   ├── Lab1_Team_Email.md
│   ├── Lab1_Executive_Summary.md
│   └── Lab1_Feature_Blog.md
│
├── Lab2/                            ← Save your Lab 2 outputs here
│   ├── Lab2_Implementation_Challenges.md
│   ├── Lab2_Risk_Briefing.md
│   └── Lab2_Market_Analysis.md
│
└── Lab3/                            ← Save your Lab 3 outputs here
    ├── Lab3_Strategic_Memo_Draft.md
    ├── Lab3_CFO_Memo.md
    ├── Lab3_GoNoGo_Summary.md
    ├── Lab3_Hallucination_Test_Log.md
    └── Lab3_Strategic_Memo_Final.md
```

---

## How the Lab Works

**The browser-based workflow:**

```
1. Open the input file in Microsoft Edge (drag & drop or File > Open)
2. Open the Copilot sidebar (icon in top-right or Ctrl+Shift+.)
3. Make sure Copilot shows the file as the active page context
4. Type your prompt — Copilot reads the open document automatically
5. Copy the output into the matching file in Lab1/ Lab2/ or Lab3/
```

You do not need to paste document content into your prompts. Copilot reads the active tab.

---

## Key Skills Taught

### RIFCC Prompt Pattern (for writing tasks)
```
Role        — "You are a product manager writing to..."
Input       — "Based on the open document..."
Task        — "Write a..."
Format      — "Use a table / bullet list / 3 paragraphs"
Constraints — "Under 200 words, avoid jargon, formal tone"
```

### Short Analysis Prompts (for reading tasks)
For document questions, use plain 1–2 sentence prompts:
```
"What are the top 3 technical risks in this document?"
"Summarize the key cost drivers from the financial projections."
```

### Citation Links
When Copilot adds `[1]`, `[2]` links, click them to jump to the source sentence in the document. This is your fastest hallucination check.

### Human-in-the-Loop Review
Before saving any Copilot output, verify:
- [ ] Facts match the source document
- [ ] No invented numbers or names
- [ ] Tone fits the intended audience
- [ ] You have read and understood the output

---

## Learning Outcomes

After completing this lab you will be able to:

- Open multi-format files (PDF, HTML, Excel) in Edge and query them with Copilot
- Write professional business documents using the RIFCC pattern
- Use follow-up prompts to iterate and improve Copilot outputs
- Identify AI hallucinations by checking citation links
- Apply a Human-in-the-Loop review before using any AI output

---

## Compose Tab vs. Chat Tab

| Chat Tab | Compose Tab |
|----------|-------------|
| Conversational Q&A | Structured document drafts |
| Analysis and summaries | Emails, memos, blog posts |
| Follow-up questions | Tone/length/format controls |

Both tabs read the active page. Switch between them depending on your task.

---

## Bonus Tasks

**Lab 2 Bonus:**
- **2.A** — Compose tab: rewrite your risk briefing in a different tone
- **2.B** — Multimodal: ask Copilot to analyze a YouTube fintech video

**Lab 3 Bonus:**
- **3.A** — Go/No-Go decision table (Task 3.6)
- **3.B** — Stakeholder Q&A prep (Task 3.7)

Bonus tasks are in the Lab 2 and Lab 3 sections of `Lab_Action_Guide.md`.

---

## Your Copilot Toolkit (Prompt Library)

Six reusable templates included at the end of `Lab_Action_Guide.md`:

1. **Risk Table** — Identify and rank risks from a document
2. **Executive Summary** — Summarize a document for leadership
3. **CFO Memo** — Financial recommendation with cost/benefit
4. **Team Email** — Translate technical findings for a general audience
5. **Go/No-Go Decision** — Structured recommendation table
6. **Competitive Snapshot** — Market positioning summary

---

## Version History

| Version | Date | Changes |
|---------|------|---------|
| 2.0 | March 2026 | Rebuilt: ClearSpend banking scenario, Lab 1/2/3 structure, multi-format inputs (PDF/HTML/XLSX), bonus tasks, RIFCC writing tasks, Copilot Toolkit |
| 1.0 | March 2026 | Initial release (healthcare scenario, Module 2/3/4) |

---

**Ready to begin? Open `Lab_Action_Guide.md`.**
