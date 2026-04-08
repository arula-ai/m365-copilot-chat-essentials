# Lab Action Guide

**Microsoft 365 Copilot App for Business Professionals**

- Version: 2.1 (M365 Stage 2 Update)
- Updated: April 2026
- Duration: 60 minutes core (+ bonus)
- Audience: Business professionals (no technical background required)
- Format: 3 sections, self-paced

## About This Lab

This lab uses the Microsoft 365 Copilot app across 3 scenarios:

1. Section 1: Executive communication writing (Meridian Analytics)
2. Section 2: Teams meeting recap and governance workflow (regional bank / ClearSpend)
3. Section 3: ROI analysis (DevFlow internal engineering product)

### Input Files

- `Meridian_Weekly_Notes.docx` (Section 1)
- `Meridian_Release_Log.docx` (Section 1)
- `ClearSpend_Product_Brief.txt` (Section 2)
- `Strategy_Review_Transcript.txt` (Section 2)
- `Project_Financial_Projections.xlsx` (Section 3)
- `Engineering_Notes.pdf` (Bonus)
- `Strategic_Connections.html` (Bonus)

### Required Setup (M365 App)

Complete these setup steps before starting Section 1:

1. Sign in to the Microsoft 365 Copilot app with your assigned lab account.
2. Confirm Copilot license access is active for your account.
3. Upload all lab files to your OneDrive under a single folder (recommended: `Lab_Inputs`).
4. In each section conversation, use the attach control (or `/`) to attach the required file(s) to that chat.
5. Verify attached file chips are visible in the prompt before sending analysis requests.

## How the Lab Works

In each section:

- Open the Microsoft 365 Copilot app
- Attach the required file(s) to the current conversation
- Ask short questions first
- Use follow-ups to refine output

### Prompt Labels Used in This Guide

- **Main prompt:** "COPY & PASTE INTO COPILOT"
- **Follow-up prompt:** "FOLLOW-UP — COPY & PASTE INTO COPILOT"

## Data Sensitivity Policy (Training Reminder)

All files in this lab are fictional.

Do **not** submit real sensitive data to AI tools unless policy explicitly permits it, including:

- Employee names/performance details
- Unpublished financials or forecasts
- Customer PII
- Internal security details, vulnerabilities, private endpoints
- Confidential strategy/M&A or unreleased plans

---

## Section 1: Writing an Executive Communication Summary

**Time:** 20 minutes

**Scenario:** You are a team lead at Meridian Analytics. Your VP needs a weekly executive update email.

**Important:** Keep the same Copilot conversation across all Section 1 tasks.

### Task 1.1 — Set Up Input Files

1. Start a new Copilot conversation for Section 1.
2. Attach `Meridian_Weekly_Notes.docx` to the conversation.

### Task 1.2 — Extract Key Stories

Use these prompts:

- Summarize this document in 5 bullet points.
- Which 3 points matter most to leadership?
- Are there any risks or issues leadership should know about?

### Task 1.3 — Translate the Release Notes

1. Attach `Meridian_Release_Log.docx` in the same conversation
2. Continue in the same conversation

Prompts:

- Summarize the key updates in this release log.
- Which of these updates matter most to the business (not engineers)?
- Rewrite these in simple, non-technical language and flag any risks.

### Task 1.4 — Business Impact Reflection

Continue in the same conversation.

Prompts:

- What milestone was achieved based on this work?
- Make this more specific and business-relevant.
- Who (which business units) benefited from this work?
- Explain briefly how each business unit benefits.
- What value was delivered (time saved, risk reduced, efficiency gained, cost savings)?
- Quantify the value where possible (hours saved, % improvement, cost impact).

### Task 1.5 — Write the Executive Email

Prompt:

Using the insights from the weekly notes, release log, and the business impact reflection we just completed, write a weekly executive update email.
Include:
- A clear subject line with the week ending date (Oct 18, 2024)
- A short opening summary (2-3 sentences)
- 3-5 key highlights
- What we shipped (simple business language)
- Business impact (milestone, business units, value delivered)
- Key risks or watch items
- Next steps for the coming week
Audience: VP-level, non-technical
Tone: Professional, concise, easy to scan
Length: Under 300 words

Optional follow-up:

- Make this more concise and ensure the biggest risk is clearly highlighted.

### Section 1 Checks

- Subject line reflects the most important story
- Key risks are explicit and honest
- Business impact includes specific, quantified value
- Filler/AI-isms removed
- Final draft is truly send-ready

---

## Section 2: Teams Meeting Recap + Governance Workflow

**Time:** 20 minutes

**Scenario:** You are a Product Strategy Analyst at a regional bank evaluating `ClearSpend`. You need to combine the written product brief with insights from a strategy review meeting and produce governance-ready outputs leadership can act on.

**Important:** Start a **new Copilot conversation** for Section 2.

### Section 2 Runtime Structure

- **Core path (recommended for 20 min):** Tasks 2.1 to 2.4
- **Advanced extension (+8 to 12 min):** Tasks 2.5 and 2.6

### Section 2 Required Setup (Do First)

1. Start a new conversation named `Section 2 - ClearSpend Governance`.
2. Attach both files to the same prompt context:
   - `ClearSpend_Product_Brief.txt`
   - `Strategy_Review_Transcript.txt`
3. Confirm both file chips are visible before sending prompts.
4. If a response references only one source, re-run with: `Use both attached files as sources and cite source type for each finding.`

### Task 2.1 — Open Sources and Set Grounding Rules

Ask:
   - Summarize what is confirmed versus still under discussion.
   - Separate decisions into: Approved, Proposed, Pending.
   - For each item, cite which source it came from (brief or transcript).

### Task 2.2 — Build a Decision Register (Governance Layer)

Use a structured prompt to produce a decision register.

Prompt:

- Role: You are a Product Governance Analyst preparing a decision log for leadership review.
- Input: ClearSpend product brief and strategy meeting transcript.
- Format: Table with columns: Decision | Status (Approved/Proposed/Pending) | Decision Owner | Approver | Decision Date | Effective Date | Dependency | Confidence (High/Medium/Low).
- Constraints: Use only content present in the two sources. Mark unknown fields as "TBD".

Follow-up:

- List any decision items that are ambiguous or conflicting across sources.

### Task 2.3 — Build an Action Register (Execution Layer)

Prompt:

- Create an action register table with columns: Owner | Action | Due Date | Success Criteria | First Milestone (within 7 days).
- Include only actions explicitly committed in the source content.
- If owner or due date is missing, flag it as a governance gap.

Follow-up:

- Rewrite the same register as short numbered actions for Teams/Planner update format.

### Task 2.4 — Create a Prioritized Risk Register (Scoring Required)

Use this scoring rubric so all participants produce comparable outputs:

- **Impact (1-5):**
   - 1 = Negligible customer or business impact
   - 2 = Minor friction, no launch risk
   - 3 = Moderate impact, requires mitigation before scale
   - 4 = Major impact, may delay launch or trigger compliance concern
   - 5 = Critical impact, launch blocker or material regulatory exposure
- **Likelihood (1-5):**
   - 1 = Rare
   - 2 = Unlikely
   - 3 = Possible
   - 4 = Likely
   - 5 = Almost certain
- **Priority Score:** Impact × Likelihood
- **Escalation rule:** Escalate any score >= 16

Prompt:

- Build a risk register from the brief and transcript with columns: Risk | Impact (1-5) | Likelihood (1-5) | Priority Score (Impact x Likelihood) | Mitigation | Mitigation Owner | Review Date.
- Order rows from highest to lowest Priority Score.
- Include an "Escalate" tag for any risk with score >= 16.

### Task 2.5 — Generate Two Audience Outputs

Create both outputs from the same source set:

1. **Executive Brief (leadership):**
   - 1-page summary with decision status, top 3 risks, and required executive decisions.
2. **Execution Brief (delivery team):**
   - concise action plan with owners, deadlines, and next 7-day milestones.

Constraint: Keep both outputs factual and traceable to source; no assumptions unless labeled ASSUMPTION.

### Task 2.6 — Verification and Quality Gate

Run this check before finalizing output:

- For each decision, risk, and action in your previous response, indicate: Source Found (Yes/No), Source Type (Brief/Transcript), Confidence (High/Medium/Low).
- Flag anything we should not use in a VP briefing.
- List missing owner/date fields as blockers.

### Section 2 Checks

- Decision register includes status, owner, approver, and confidence
- Action register has owners, due dates, and measurable success criteria
- Risk register includes impact, likelihood, and priority score
- Executive and execution briefs are both present and audience-specific
- All key outputs pass the source verification gate

### Section 2 Completion Rule

- A participant is considered complete at **Core** when Tasks 2.1 to 2.4 are finished.
- A participant is considered complete at **Advanced** when Tasks 2.5 and 2.6 are also completed.

---

## Section 3: Project Financial Projections — Calculating ROI

**Time:** 20 minutes

**Scenario:** You own DevFlow (internal CI/CD product) and must present ROI to leadership.

**Important:** Start a **new Copilot conversation** for Section 3.

### Task 3.1 — Open ROI Workbook

Open `Project_Financial_Projections.xlsx` and copy the key figures into Copilot prompts for analysis.

Sheets:

- Executive Summary
- Cost Breakdown
- ROI & Projections
- Risk Register

### Task 3.2 — Assess ROI

Use provided figures to ask Copilot for interpretation, risk impact, and scenario reasoning.

Key sample values in guide:

- Total investment: $412,000
- Productivity value: $707,000/year
- Year 1 ROI: 125%
- Payback: 7 months
- Monthly run cost: $22,200 vs $11,700 budget

### Task 3.3 — Identify What Could Go Wrong

Use risk data and ask Copilot for consequence analysis and prioritization.

### Task 3.4 — Verification Test (Hallucination Check)

Run a deliberate fabricated benchmark prompt to test if Copilot pushes back.

Goal: build a verification habit before sharing any Copilot-generated number.

### Task 3.5 — Write Engineering ROI Summary

Generate a formal leadership summary including:

- Header (To/From/Date/Re)
- 2-sentence executive summary
- ROI highlights
- Cost concerns
- Risk table
- Recommendation with condition and consequence

Then produce a concise briefing-note variant.

### Section 3 Checks

- All figures trace to source data
- Recommendation matches risk reality
- Wording is precise and defensible

---

## Bonus Tasks (Optional)

### B.1 — Legacy Stage 2: Analyzing Documents — PDF and HTML

**Time:** 20 minutes

**Scenario:** You are a Product Manager at a regional bank evaluating `ClearSpend`.

#### Task B.1.1 — Open Product Brief and Get Oriented

1. Attach `Engineering_Notes.pdf` to the conversation
2. Ask:
   - Summarize this page in 4 bullet points
   - What problem is this feature solving for customers?
   - What are the main risks or concerns mentioned?

#### Task B.1.2 — Team Email Using RIFCC

RIFCC = Role, Input, Format, Constraints, Checks.

Prompt (condensed):

- Role: Product Manager at a regional bank
- Input: ClearSpend brief on this page
- Format: Team email (subject, 2-sentence opening, 3 bullets, 1-sentence close)
- Constraints: under 150 words, warm/professional, no cost figures, no jargon

Follow-up:

- Make it more energized while keeping same structure.

#### Task B.1.3 — Executive Summary (Two Formats)

Prompt for Version 1 (bullets):

- 4 sections: What We Are Building, Why This Matters, Key Risks, Recommended Next Step
- Under 200 words
- Business language only

Follow-up for Version 2:

- Rewrite same content as short paragraphs (same sections, same word limit).

#### Task B.1.4 — Switch to Market Research Report

1. Attach `Strategic_Connections.html` to the same conversation
2. Ask:
   - What are the top 3 trends in this report?
   - Which trend is most relevant to launching a personal finance dashboard?
   - If we launch in Q1 2027, are we early, on time, or late?

#### Task B.1.5 — Find Numbers and Verify

Ask:

- What statistics support investing in a personal finance dashboard now?
- What does the report say customers expect from digital products in 2026?

Then verify citations in source before reusing numbers.

#### Task B.1.6 — Write a Risk Briefing Table

Prompt:

- Role: Risk Analyst briefing VP of Digital Banking
- Input: 2026 Digital Banking & Fintech Innovation Report
- Output:
  - 1-sentence intro
  - Table: Risk | Severity | Business Impact | Recommended Action
  - Up to 6 rows, ordered high to low severity
  - 1-sentence conclusion naming most urgent action
- Constraint: Use only risks explicitly in the report

Follow-up:

- Add Timeline column (Immediate / Short-term / Long-term).

### B.2 — Go/No-Go Decision Summary

Create RAG decision table with 8 factors and final go/no-go condition.

### B.3 — Compose Tab vs RIFCC

Compare a quick Compose-generated draft vs a structured RIFCC output for same announcement.

### B.4 — Video Analysis

Use Copilot on a YouTube video, summarize key points, and identify roadmap implications.

---

## Core Takeaways

- Stage prompts for complex writing (extract -> translate -> reflect -> draft)
- Use short prompts for extraction, RIFCC for professional outputs
- Format instructions drive quality
- Verify every number before reuse
- Follow-up prompts are where quality improves most
- Data protection must be default behavior

---

## Quick Prompt Reference

### Weekly Executive Email Sequence

1. Extract top highlights + risks
2. Translate technical release notes into business language
3. Draft VP-ready email under 300 words
4. Personalize opening and sign-off

### Meeting Prep Prompt

I have [X] minutes before a meeting about [topic]. Give me:
1) the 3 most important things to know,
2) one question I should ask,
3) one risk I should be ready to address.
Under 150 words.

### Risk Spotter

Review the document on this page. Identify:
- top 3 risks/problems,
- easy-to-miss commitments/deadlines,
- one key question before proceeding.
Under 150 words.

### Product ROI Check

- Assess whether ROI is strong based on provided metrics
- Stress-test with optimistic/base/conservative scenarios
- Evaluate impact if top risks remain unresolved

### Verification Check

Look only at the document on this page.
For each fact/number in your previous response: Yes / No / Partially present in source.
Flag anything I should not rely on.
Do not add new information.
