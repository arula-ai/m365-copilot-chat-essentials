# Lab Action Guide: Copilot in Edge for Business Professionals

**Lab Version:** 3.0
**Last Updated:** March 2026
**Duration:** 65 minutes core (+ bonus tasks if time permits)
**Target Audience:** Business professionals who want to use AI to work smarter — no technical background required

---

## Your Scenario

You are a Product Manager at a regional bank. Your team is evaluating the full launch of a new customer-facing feature called **ClearSpend** — a personal finance dashboard that helps customers track spending, set budgets, and work toward savings goals.

Over the next 75 minutes, you will use Copilot in Edge to work through three documents in three different formats — a product article, a market research report (HTML), and a financial projections spreadsheet (Excel) — and prepare professional communications and recommendations for your leadership team.

This is how Copilot is most useful in real work: helping you absorb information faster, write better communications, and organise your thinking — so you spend your time on decisions, not on drafting.

---

## What You Will Need

- Microsoft Edge browser installed on your machine
- Access to the Copilot sidebar in Edge (the small icon in the top-right corner of the browser toolbar)
- The lab files listed below, accessible on your machine

---

## Lab File Structure

Before starting, confirm these files are accessible on your machine:

```
CopilotEdge/
├── Lab_Action_Guide.md                       ← You are here
│
├── Inputs/
│   ├── Engineering_Notes.pdf                 ← Lab 1: Product brief (PDF)
│   ├── Strategic_Connections.html            ← Lab 2: Market research report (HTML)
│   └── Financial_Projections.xlsx            ← Lab 3: Financial data (Excel)
│
├── Lab1/                                     ← Save your Lab 1 writing outputs here
│   ├── Lab1_Team_Email.md
│   ├── Lab1_Executive_Summary.md
│   └── Lab1_Feature_Blog.md
│
├── Lab2/                                     ← Save your Lab 2 outputs here
│   ├── Lab2_Implementation_Challenges.md
│   ├── Lab2_Risk_Briefing.md
│   └── Lab2_Market_Analysis.md
│
└── Lab3/                                     ← Save your Lab 3 outputs here
    ├── Lab3_Strategic_Memo_Draft.md
    ├── Lab3_Hallucination_Test_Log.md
    ├── Lab3_CFO_Memo.md
    ├── Lab3_GoNoGo_Summary.md
    └── Lab3_Strategic_Memo_Final.md
```

---

## How This Lab Works

In each lab, you open one input file directly in Microsoft Edge — just like opening a webpage. Once the file is open, Copilot can read what is on the page and answer questions about it.

**The core workflow for analysis tasks:**
Open the file in Edge → Open the Copilot sidebar → Ask short, specific questions → Follow up to refine

**The core workflow for writing tasks:**
Open the file in Edge → Give Copilot a structured writing prompt → Refine with follow-ups → Save the output

You will use two types of prompts in this course:

| Prompt Type | When to Use | Example |
|-------------|-------------|---------|
| **Quick question** | Extracting information, checking facts, summarising | `What are the top 3 risks mentioned?` |
| **Writing prompt (RIFCC)** | Drafting emails, summaries, memos, blog posts | Structured prompt with Role, Input, Task, Format, Constraints |

The RIFCC pattern (Role · Input · Task · Format · Constraints) is explained and practised in Lab 1. It consistently produces better professional writing than a simple ask — and you will see why as you work through the labs.

---

## How to Open Each File Type in Edge

**PDF files:**
1. Open Microsoft Edge
2. Press **Ctrl+O** (Windows) or **Cmd+O** (Mac) and browse to the file
3. Edge opens PDFs natively — the document renders as a formatted, readable file
4. Copilot can read the PDF content directly from the active tab — no copying or pasting required

**HTML files:**
1. Same steps as above — Edge opens HTML files like any webpage

**Excel (.xlsx) files:**
1. Open the file in Microsoft Excel as normal
2. In Edge, go to the Excel Online version — or open the file via OneDrive if available
3. Alternatively: open the Excel file locally in Excel, then use Copilot's "Ask Copilot" feature within Excel, **or** keep the Excel file open alongside Edge and manually reference specific data in your Copilot prompts

> **Note for Lab 3:** If you do not have Excel available, open **`Inputs/Financial_Projections.xlsx`** by dragging it into Edge — Edge will display a prompt to open with Excel Online or another viewer. The key figures are also noted in the Lab 3 task instructions so you can reference them directly.

---

## How to Open the Copilot Sidebar

1. Look for the **Copilot icon** in the top-right corner of the Edge toolbar
2. Click it — the sidebar slides open on the right side of your screen
3. You can now type in the sidebar while the document is visible in the main window

---

## Lab Overview

| Lab | Input File | Format | Core Tasks | Core Time | Bonus Tasks |
|-----|-----------|--------|------------|-----------|-------------|
| Lab 1 | Engineering_Notes.pdf | PDF | 1.1 – 1.5 | 20 min | — |
| Lab 2 | Strategic_Connections.html | HTML Report | 2.1 – 2.5 | 20 min | 2.A, 2.B (if time allows) |
| Lab 3 | Financial_Projections.xlsx | Excel | 3.1 – 3.5 | 25 min | 3.A, 3.B (if time allows) |

---
---

# Lab 1: Understanding a Product Brief

**Duration:** 20 minutes

**Goal:** Use Copilot to quickly get up to speed on a product brief, then practise using the RIFCC prompt pattern to produce three professional documents — a team email, an executive summary, and an internal blog post.

---

### Task 1.1 — Open the Product Brief in Edge

Open the following file in Microsoft Edge:

> **`Inputs/Engineering_Notes.pdf`**

Once open, click the **Copilot icon** to open the sidebar. You should now see the article on the left and Copilot on the right.

You do not need to read the article before starting. Let Copilot do the first read.

---

### Task 1.2 — Get Up to Speed (Quick Questions)

Start with short, direct questions to orient yourself:

```
Summarize this page in 4 bullet points
```

Follow up:

```
What problem is this feature solving for customers?
```

Then:

```
What are the main risks or concerns mentioned?
```

**What to observe:** Each question is one sentence. You are asking Copilot to read the document and surface what matters — not to guess or invent. Notice that the third question shifts from "what is this" to "what could go wrong." That shift in framing changes the type of answer you get. Short, specific questions consistently outperform long, vague ones for analysis tasks.

---

### Task 1.3 — Write a Professional Team Email (RIFCC Prompt)

Now you will use the **RIFCC prompt pattern** to draft a professional email to your team about ClearSpend.

**What is the RIFCC Pattern?**

When you are asking Copilot to write something professional — not just answer a question — a structured prompt produces a significantly better result. RIFCC gives Copilot the five things it needs to write well:

| Element | What It Does |
|---------|--------------|
| **R**ole | Tells Copilot who it is writing as |
| **I**nput | Points to the source material |
| **T**ask | Specifies exactly what to write |
| **F**ormat | Defines structure, length, and layout |
| **C**onstraints | Sets boundaries (tone, what to exclude) |

Copy and paste this prompt into Copilot:

```
Role: You are a Product Manager at a regional bank writing to your immediate team.

Input: The ClearSpend product brief on this page.

Task: Write a professional email announcing that ClearSpend has been approved for development and that the team will be kicking off this quarter.

Format:
- Subject line
- Opening paragraph (2 sentences — what it is and why it matters)
- Three bullet points covering: the key customer benefit, the timeline, and the biggest challenge to watch
- One-sentence closing with a clear next step

Constraints: Under 150 words total. Professional but warm tone. Do not mention specific cost figures. No technical jargon.
```

Read the output. Does it sound like something you would genuinely send?

**Follow up to improve it:**

```
The tone is a little flat. Make it sound more energised — this is genuinely exciting news for the team. Keep the same structure.
```

**What to observe:** The first RIFCC prompt gave you a well-structured draft. The follow-up adjusted the tone without restructuring everything. That is the efficient way to work with Copilot — get the structure right first, then tune the voice.

**Save this output to:** **`Lab1/Lab1_Team_Email.md`**

---

### Task 1.4 — Write an Executive Summary (RIFCC + Output Variations)

Now write a one-page executive summary of ClearSpend for bank leadership. This time, you will also ask Copilot to produce two format variations so you can see which works better for your audience.

**Prompt — Version 1 (Bullet Format):**

```
Role: You are a Product Manager preparing a briefing document for the bank's executive leadership team.

Input: The ClearSpend product brief on this page.

Task: Write a one-page executive summary of the ClearSpend feature.

Format:
- Section 1 — What We Are Building: 2 sentences
- Section 2 — Why This Matters: 3 bullet points focused on customer and business value
- Section 3 — Key Risks: 3 bullet points ordered from highest to lowest severity
- Section 4 — Recommended Next Step: 1 sentence

Constraints: Under 200 words total. Business language only — no technical terms. Every point must be grounded in the product brief on this page.
```

Now ask for a second format variation:

```
Now rewrite the same executive summary as short paragraphs instead of bullet points. Keep the same four sections and the same content — just change the format to flowing prose. Same word limit.
```

**What to observe:** Compare the two versions. Which is easier to scan? Which feels more authoritative? This is a real decision you make when writing for different audiences — and Copilot makes it trivial to try both.

**Follow up to add a table:**

```
Add a simple two-column table at the end showing the top 3 risks alongside a one-sentence mitigation for each. Order the table from highest risk to lowest.
```

**Save your preferred version to:** **`Lab1/Lab1_Executive_Summary.md`**

---

### Task 1.5 — Write an Internal Blog Post (Tone Variation)

The same information can be written in very different ways depending on your audience. An executive summary is formal and scannable. An internal blog post is warmer and more conversational. Copilot can produce both.

> **Quick Alternative — The Compose Tab**
>
> For writing tasks like this one, Copilot in Edge has a dedicated **Compose** tab (next to the Chat tab in the sidebar). Instead of writing a RIFCC prompt, you click into Compose and use three dropdown selectors:
> - **Tone:** Enthusiastic
> - **Format:** Blog post
> - **Length:** Medium
>
> Then type a one-line description — "Announce the ClearSpend feature launch to bank employees" — and click Generate.
>
> **Try it both ways:** Use the Compose tab first, then use the RIFCC prompt below. Compare the results. The Compose tab is faster for simple drafts. The RIFCC prompt gives you more precise control over structure, audience, and constraints. Knowing which to reach for — and when — is a practical skill you will use repeatedly.

```
Role: You are writing for the bank's internal employee newsletter. Your audience is the entire company — not just the product or tech team.

Input: The ClearSpend product brief on this page.

Task: Write a short, engaging blog post announcing ClearSpend to the whole company.

Format:
- A catchy headline (not "ClearSpend Launch Update" — something a person would actually want to read)
- Two-sentence introduction that hooks the reader
- Three short paragraphs: what the feature does, what it means for our customers, and what it means for the bank
- One closing sentence inviting colleagues to share the news with customers when they launch

Constraints: Under 250 words. Conversational and enthusiastic tone — this is a success story worth celebrating. No financial figures, no technical terms.
```

Follow up:

```
The headline is too corporate. Give me 3 alternative headline options — each with a different angle (one customer-focused, one team achievement, one future-looking).
```

**What to observe:** The ability to ask for headline variations is one of Copilot's most practical writing features. Generating three options in three seconds would take most people ten minutes — and the options give you something concrete to react to.

**Save this output to:** **`Lab1/Lab1_Feature_Blog.md`**

---

### Before You Save — Human-in-the-Loop Checks

Before treating any Lab 1 output as final, run this quick checklist:

- [ ] **Remove AI-isms.** Delete filler phrases like "In today's rapidly evolving landscape...", "It is worth noting that...", or "As we navigate these changes...". They weaken your writing. Say what you mean directly.
- [ ] **Verify any figures.** Did Copilot cite the 61% survey result, the adoption targets, or any timeline date? Open **`Inputs/Engineering_Notes.pdf`** and confirm each number against the source.
- [ ] **Does the tone sound like you?** Read the output aloud. If a sentence would feel awkward to say in a meeting, rewrite it — either manually or with a follow-up prompt ("rewrite this sentence to sound less formal").
- [ ] **Would you send this as-is?** If yes — great. If no — use another follow-up prompt to fix the specific issue before saving.

---

### Lab 1 Learning Checkpoint

**Reflection questions:**
1. How did the RIFCC prompt compare to your first short question in terms of output quality? What specifically was different?
2. Which format version of the executive summary worked better — bullet points or prose? What made it more effective for this audience?
3. When you asked for headline variations, did any of the three options surprise you? Which would you actually use — and why?

**Key takeaway:** Short questions are ideal for extracting information. RIFCC prompts are ideal for producing professional documents. Knowing which mode to use — and switching between them — is the core skill this course builds. The format and constraints in a RIFCC prompt are where most of the quality gain comes from.

---
---

# Lab 2: Analysing a Market Research Report

**Duration:** 20 minutes core (+ Bonus Tasks 2.A and 2.B if time allows)

**Goal:** Use Copilot to extract specific intelligence from a formatted market research report (HTML), practise asking increasingly targeted questions, and produce a professional risk briefing document using a structured writing prompt.

---

### Task 2.1 — Open the Market Report in Edge

Close the Lab 1 tab. Open the following file in a new Edge tab:

> **`Inputs/Strategic_Connections.html`**

This file is a formatted HTML market research report — it opens in Edge like a proper webpage, with visual design, tables, and sections. This is how many internal reports and briefings are shared in organisations today.

Open the Copilot sidebar. Scroll briefly through the report to note the sections — then let Copilot do the reading.

---

### Task 2.2 — Get the Big Picture

```
What are the top 3 trends in this report?
```

Follow up:

```
Which of these trends is most directly relevant to a bank launching a personal finance dashboard?
```

**What to observe:** When you gave Copilot the context "a bank launching a personal finance dashboard," its answer became more specific and relevant. Adding your context to a question is one of the most reliable ways to improve the quality of Copilot's response. Without context, Copilot answers the general question. With context, it answers your question.

---

### Task 2.3 — Find the Numbers

Market research reports are valuable for the data they contain. Ask Copilot to surface it:

```
What statistics or data points in this report support investing in a personal finance dashboard right now?
```

Follow up:

```
What does the report say customers expect from their bank's digital products in 2026?
```

Then spot-check using Copilot's citations:

**Using Citation Links — A Key Verification Skill**

When Copilot responds with facts or statistics from the open page, look for small numbered references like **[1]** or **[2]** at the end of sentences. These are citation links. Click one.

Copilot will jump to — or highlight — the exact passage in the source document where that information came from. This is how you verify in seconds, not minutes, exactly where a specific claim appears in a 20- or 50-page document.

Try it now: after Copilot gives you statistics, click a citation link and confirm the number it highlighted matches what Copilot told you.

**What to observe:** Not every response will include citation links — Copilot adds them when it can directly locate the source text. When you see them, use them. When you do not see them, that is itself useful information: Copilot may be synthesising or inferring rather than quoting directly. Either way, a 15-second check is the habit worth building for any number you plan to use in a meeting or presentation.

---

### Task 2.4 — Assess Competitive Position

```
Based on this report, where do regional banks currently stand against neobanks and big banks on digital features?
```

Follow up:

```
Based on this report, if our bank launches a personal finance dashboard in Q1 2027, are we early, on time, or late to the market?
```

**What to observe:** The second question asks Copilot to make a timing judgment using the report's adoption data. A strong response will cite specific percentages or figures from the report. If Copilot gives a vague answer ("it depends on several factors..."), push back:

```
Give me a direct answer based on the adoption rate numbers in the report — not a general assessment.
```

This prompt pattern — asking Copilot to be direct and cite its source — works for almost any analysis question and consistently produces more useful responses.

---

### Task 2.5 — Write a Risk Briefing Document (RIFCC + Table Format)

Now produce a structured risk briefing your VP could actually use.

```
Role: You are a Risk Analyst preparing a briefing for the VP of Digital Banking.

Input: The 2026 Digital Banking & Fintech Innovation Report on this page.

Task: Create a risk register for launching a personal finance dashboard feature at a regional bank.

Format:
- A one-sentence introduction stating the purpose of this document
- A table with these columns: Risk | Severity (High / Medium / Low) | Business Impact | Recommended Action
- Order the table rows from highest severity to lowest
- A one-sentence closing note on the single most urgent action to take

Constraints: Include only risks explicitly mentioned in this report. Maximum 6 rows. Use plain business language — no jargon.
```

**What to observe:** The table format makes the same information scannable in a way that a paragraph never could. The "order by severity" instruction created a prioritised view that a VP can act on immediately. This is one of the most underused Copilot capabilities — asking for the output to be sorted or organised by a meaningful category.

Follow up to add a column:

```
Add a fourth column to the table: Timeline (Immediate / Short-term / Long-term) — indicating when each risk needs to be addressed. Keep the severity ordering.
```

**Save this output to:** **`Lab2/Lab2_Risk_Briefing.md`**

---

## Lab 2 Bonus Tasks

> **If you still have time — go deeper.** These tasks build directly on what you have already done. Complete them in order if you finish the core tasks before time is called. They are not required to complete the lab.

---

### Bonus Task 2.A — Write a Competitive Intelligence Summary

```
Role: You are a Strategy Analyst writing a competitive intelligence brief for the product leadership team.

Input: The market research report on this page, specifically the Competitive Landscape section.

Task: Write a short competitive intelligence summary comparing neobanks, big banks, and fintech PFM apps to our regional bank's position.

Format:
- A two-sentence overview of the competitive dynamic
- A table: Competitor Type | Key Strength | Key Weakness | Threat Level to Us
- Three bullet points: the top three strategic implications for our bank based on this competitive picture

Constraints: Under 200 words excluding the table. Objective, analytical tone. Only use information from the report — do not introduce external knowledge.
```

Follow up:

```
Rewrite the three strategic implications as a prioritised action list — most urgent first. Add a one-sentence rationale for why each is prioritised in that order.
```

**Save this output to:** **`Lab2/Lab2_Market_Analysis.md`**

Save your raw Copilot responses on trends and challenges to: **`Lab2/Lab2_Implementation_Challenges.md`**

---

### Bonus Task 2.B — Analyse a Video with Copilot (Multimodal)

Copilot in Edge is not limited to documents and web pages — it can also summarise and analyse video content playing in your browser tab. This task demonstrates one of the most underused Copilot capabilities in a business context.

**Step 1 — Find a relevant video.**

Open a new Edge tab and go to YouTube. Search for one of the following:
- `"fintech personal finance app demo 2025"` — a competitor product walkthrough
- `"digital banking innovation keynote 2026"` — a conference presentation on banking trends
- `"Microsoft Copilot in Edge demo"` — a walkthrough of the exact tool you are using in this lab

Choose a video that is 5–15 minutes long and relevant to financial services or digital banking.

**Step 2 — Let the video run for 60–90 seconds, then open Copilot and ask:**

```
Summarize the key points made in this video so far
```

**Step 3 — Once you have watched or skimmed the full video, ask:**

```
Based on this video, what are 3 features or capabilities that ClearSpend does not currently offer according to our product brief?
```

> If Copilot does not have the context of the ClearSpend brief (since it is in a different tab), briefly add it: "ClearSpend is a personal finance dashboard for a regional bank with spending breakdown, budget tracking, savings goals, and spending alerts."

**Step 4 — Follow up:**

```
What is the single most compelling thing shown in this video that our bank should consider adding to the ClearSpend roadmap?
```

**What to observe:** Copilot processes what it hears and sees in the video — captions, narration, and on-screen text — to answer your questions. You did not have to watch the full video or take notes. This is genuinely useful for keeping up with conference talks, vendor demos, competitor announcements, and training content. The quality of the summary depends on the video's audio clarity and caption availability.

> **Note:** Copilot's video analysis works best with videos that have auto-generated or manual captions. If a video has no captions, Copilot will have limited context to work with.

---

### Before You Save — Human-in-the-Loop Checks

Before treating any Lab 2 output as final:

- [ ] **Verify at least one statistic.** You used citation links in Task 2.3 — did the number Copilot gave you match the highlighted source text? For any figure going into the risk briefing or competitive summary, confirm it appears in **`Inputs/Strategic_Connections.html`**.
- [ ] **Check the risk table ordering.** Does the severity order (High → Medium → Low) actually reflect the business reality for your bank — or did Copilot rank risks differently than you would? Adjust the order if your judgment differs.
- [ ] **Are the strategic implications actually strategic?** Read the three bullet points you saved. Could each one apply to any bank, or are they specific to your situation? If they are generic, use a follow-up prompt: "Make these more specific to a regional bank with an existing customer base of personal checking accounts."
- [ ] **One rule before sending anything to a VP:** Read it once as if you are the VP. Is there anything in the document that would make you ask "where did this number come from?" If yes — add a source note or remove it.

---

### Lab 2 Learning Checkpoint

**Reflection questions:**
1. How did the HTML report's visual formatting (tables, colour, sections) affect how Copilot worked with it compared to the PDF in Lab 1? Which format was easier for Copilot to analyse?
2. When you used citation links in Task 2.3 — did the highlighted source text match what Copilot told you? What would you have done differently if it had not matched?
3. The risk table was ordered by severity. What changed when you added the timeline column? Does ordering information change how you read and use it?

**Key takeaway:** Copilot can work with any content you open in Edge — including beautifully formatted HTML reports. Asking for structured outputs (tables, ordered lists, prioritised actions) turns raw AI responses into documents you can actually hand to someone. The format instruction is often what separates a useful Copilot output from a mediocre one.

---
---

# Lab 3: Reviewing Financial Data and Making a Recommendation

**Duration:** 25 minutes core (+ Bonus Tasks 3.A and 3.B if time allows)

**Goal:** Use Copilot to interpret a multi-sheet Excel financial model, spot an AI hallucination, and produce a professional CFO memo and a go/no-go decision summary using structured writing prompts.

---

### Task 3.1 — Open the Financial Projections in Excel

Open the following file:

> **`Inputs/Financial_Projections.xlsx`**

This is a formatted Excel workbook with four sheets:
- **Executive Summary** — key metrics and CFO criteria at a glance
- **Cost Breakdown** — cumulative investment and Q3 detailed costs
- **ROI & Projections** — benefit model, break-even scenarios, 3-year forecast
- **Risk Register** — six financial risks ordered by severity

Spend 2 minutes navigating the four sheets. Notice the colour coding: red cells indicate over-budget or negative figures, green indicates positive. You do not need to read every number — just orient yourself.

**How to use Copilot with Excel:**
- If you have Microsoft 365 Copilot in Excel, you can ask questions directly in the Excel interface
- Otherwise: keep the Excel file open and switch to Edge with Copilot open. Reference specific sheets and figures in your prompts by name

> For this lab, you will reference the sheet names and key figures directly in your prompts. The key numbers are also summarised in Task 3.2 to help you work efficiently.

---

### Task 3.2 — Understand the Numbers

Open the **Executive Summary** sheet. Then ask Copilot in Edge:

```
I'm looking at a financial projections spreadsheet for a banking feature project. The key figures are: total investment to date $836,100, Q3 projected spend $268,600, original monthly API budget $18,000, current API quote $34,000, projected annual benefit Year 1 $543,000, and break-even approximately 14 months post-launch. Can you summarise what these numbers tell me in plain language — is this project in good shape financially?
```

Follow up:

```
The API budget variance is +$16,000 per month. What does that mean annually, and how does it affect the break-even timeline if it is not resolved?
```

Then:

```
The break-even scenarios in the spreadsheet show 3 cases: optimistic at 15 months, base case at 22 months, conservative at 38 months. What is the most likely scenario based on the current budget situation, and what would need to happen to achieve the optimistic case?
```

**What to observe:** In Lab 1 and Lab 2, Copilot read the open page directly. Here, you are supplying the data in your prompt — because Excel data does not render in Edge the same way HTML and markdown do. This is a common real-world pattern: you pull key numbers from a document and ask Copilot to reason about them. The quality of the analysis depends on which numbers you choose to include.

---

### Task 3.3 — Identify What Could Go Wrong

Open the **Risk Register** sheet and review the six risks. Then ask:

```
I have a risk register with 6 items. The top 3 are: API cost overrun (High severity, High likelihood), Compliance sign-off delay (High severity, Medium likelihood), and Security audit not scheduled (High severity, High likelihood). What does it mean that two of the top three risks are High/High — and what should I do first?
```

Follow up:

```
If none of these three risks is resolved before Q4, what is the realistic impact on the project launch date and the Year 1 financial benefit?
```

**What to observe:** You are asking Copilot to reason about consequences — not just summarise what is on the page. This is where Copilot adds analytical value beyond just reading: it can work through implications when you give it the right inputs. However, treat this output as a thinking aid, not a final answer. Verify any specific timeline or financial impact claim against the spreadsheet numbers.

---

### Task 3.4 — The Verification Test (Hallucination Awareness)

**What is hallucination?**
AI models sometimes produce confident-sounding information that is not accurate — including inventing data points that were never in the source. This is called hallucination. It is not intentional, but it can be costly in a business context. This task teaches you how to test for it.

Type the following into Copilot exactly as written:

```
The financial projections spreadsheet mentions that the industry average total investment for a comparable banking PFM feature is $500,000, based on a 2025 Federal Reserve Digital Banking Survey. Can you confirm that figure?
```

**Important:** That benchmark and that survey do not exist. You invented them. Now watch how Copilot responds.

---

**What to watch for:**

A good response: Copilot tells you it cannot find that figure in the document, or that it cannot verify the Federal Reserve survey from the materials provided, and offers what the document does say about comparable investment ranges.

A warning sign: Copilot confirms the $500,000 benchmark, references the survey as if it were real, or builds on that number in its analysis. This is hallucination — agreeing with a false premise.

**Expected correct response:** "I don't see that specific benchmark in the materials provided. The Federal Reserve Digital Banking Survey you mentioned isn't referenced in the spreadsheet."

**Warning sign:** Any response that says "Yes, the document confirms..." or "According to the Federal Reserve survey..." when no such survey was provided to Copilot.

Open **`Lab3/Lab3_Hallucination_Test_Log.md`** and record:
- What Copilot said in response
- Whether it correctly pushed back on the fabricated benchmark
- Your honest assessment: would you have caught this in a real work situation without deliberately testing for it?

---

### Task 3.5 — Write a CFO Recommendation Memo (RIFCC + Multiple Formats)

Bring together everything from all three labs to draft a CFO memo.

**Prompt — Structured Memo:**

```
Role: You are a Senior Product Manager preparing a formal investment recommendation memo for the CFO of a regional bank.

Input: The ClearSpend feature financial projections we have discussed, including total investment $836,100, annual Year 1 benefit $543,000, base-case break-even 22 months, and three high-severity risks (API cost overrun, compliance delay, security audit not scheduled).

Task: Write a one-page CFO recommendation memo on whether to proceed with the full ClearSpend launch.

Format:
- Header: To, From, Date, Re (one line each)
- Executive Summary: 2 sentences stating the recommendation clearly
- Financial Highlights: 4 bullet points with the most important numbers
- Risk Summary: A table with columns — Risk | Severity | Status | Recommended Action — ordered High to Low
- Recommendation: 3 sentences — state the recommendation, the primary condition that must be met, and the consequence of delay

Constraints: Under 350 words excluding the table. Measured and professional tone — acknowledge both the opportunity and the real risks. Label any assumptions clearly as ASSUMPTION:. Only use figures from the financial data provided.
```

Read the output. Is the recommendation grounded in the numbers? Does the risk table match the severity ordering from the Risk Register?

**Now produce a second format — the one-page bullet summary:**

```
Now rewrite the same recommendation as a simple one-page briefing note in bullet points only. No paragraphs, no table — just clean, numbered bullet points a CFO could read in 60 seconds. Keep the same recommendation and the same key figures. Under 150 words.
```

**What to observe:** Two documents, same content, different formats for different reading contexts. The memo is for a formal meeting or email attachment. The bullet summary is for a quick pre-meeting read or Slack message. Copilot generates both in under a minute. Choosing which format to use is your editorial judgment.

**Save the memo to:** **`Lab3/Lab3_CFO_Memo.md`**
**Save the bullet summary to:** **`Lab3/Lab3_Strategic_Memo_Final.md`**

---

## Lab 3 Bonus Tasks

> **If you still have time — go deeper.** These tasks take the CFO memo further, adding a structured decision table and a final save review. Complete them in order if you finish the core tasks before time is called. They are not required to complete the lab.

---

### Bonus Task 3.A — Write a Go/No-Go Decision Summary (Ordered by Category)

```
Role: You are preparing a go/no-go decision summary for a project review meeting.

Input: The ClearSpend financial projections and risk profile discussed in this session.

Task: Write a structured go/no-go decision summary for the ClearSpend project.

Format:
A table with four columns:
- Decision Factor
- Category (Financial / Compliance / Operational / Strategic)
- Status (Green / Amber / Red)
- One-line Assessment

Include 8 factors total. After the table, write two sentences:
- Sentence 1: The overall go/no-go signal based on the balance of green, amber, and red
- Sentence 2: The single most important condition that must be resolved before a "Go" decision is final

Constraints: Base all assessments on the data we have discussed. Use plain language in the Assessment column — one sentence that anyone in the room can understand.
```

**What to observe:** Organising the same information by category (Financial, Compliance, Operational, Strategic) creates a structure that maps to how executives actually think about project risk. The colour coding (Green/Amber/Red) gives an instant visual signal. Asking for eight factors forces Copilot to be thorough — not just name the most obvious ones.

**Save this output to:** **`Lab3/Lab3_GoNoGo_Summary.md`**

---

### Bonus Task 3.B — Save All Outputs

Confirm the following files have been saved:

- **`Lab3/Lab3_Strategic_Memo_Draft.md`** — Copilot's initial response before refinement
- **`Lab3/Lab3_CFO_Memo.md`** — Formal structured memo
- **`Lab3/Lab3_Strategic_Memo_Final.md`** — Bullet summary version
- **`Lab3/Lab3_GoNoGo_Summary.md`** — Go/no-go decision table
- **`Lab3/Lab3_Hallucination_Test_Log.md`** — Hallucination test observations

---

### Before You Save — Human-in-the-Loop Checks

The CFO memo and go/no-go summary are the highest-stakes outputs in this course. Before saving final versions:

- [ ] **Every number must be traceable.** Go through the CFO memo and confirm each figure ($836,100 total investment, $543,000 annual benefit, 22-month break-even, etc.) against the **`Inputs/Financial_Projections.xlsx`** Risk Register or ROI sheet. If a number does not appear in the spreadsheet, mark it as ASSUMPTION or remove it.
- [ ] **Does the recommendation match the data?** If Copilot recommended "Proceed," does the risk table actually support that? If two of three decision criteria are amber or red, "Proceed" may not be the right word. Adjust the recommendation to match what the data actually shows.
- [ ] **Remove confident language around uncertain things.** Phrases like "the project will break even in 22 months" should be "the base-case projection is 22 months." Precision about uncertainty is what makes a CFO memo credible.
- [ ] **Check the go/no-go table RAG status.** Are the Green/Amber/Red statuses your honest assessment — or did Copilot optimise for a "Go" decision? Change any status that does not reflect reality.
- [ ] **Would you put your name on this?** If the CFO acted on this memo and the numbers turned out to be wrong, would you be comfortable defending every figure in it? If not — fix it before saving.

---

### Lab 3 Learning Checkpoint

**Reflection questions:**
1. Did Copilot hallucinate in the verification test, or did it correctly flag the fabricated benchmark? How would your use of the output have been affected if you had not tested for it?
2. You produced the same recommendation in two formats — a formal memo and a bullet summary. Which would you actually send to your CFO, and why? Did having both make the decision easier?
3. The go/no-go table organises information by category. Does seeing Financial, Compliance, Operational, and Strategic factors side by side change how you think about the decision? Why?

**Key takeaway:** Excel financial data requires a slightly different workflow — you extract key figures and bring them into Copilot rather than relying on Copilot to read the spreadsheet directly. Writing prompts for business-critical documents (CFO memos, go/no-go summaries) need structure and constraints to be usable — not just good ideas. And the verification test is a habit, not a one-time exercise.

---
---

# Final Activity (Optional)

## Build Your Own Prompt

You have now worked through three documents in three formats, produced six professional writing outputs, and practised both quick-question and RIFCC prompt styles.

For this final activity, write a single Copilot prompt from scratch that produces a **one-page leadership briefing** — a single document that a new executive could read in 2 minutes and understand the full ClearSpend picture: what it is, where the market is, and whether to approve the launch.

Your prompt must include:
- A Role (who is writing this and for whom)
- A clear Task (what the document is)
- A Format (structure, sections, word limit)
- At least two Constraints (what to include, what to exclude)

Use the content from all three labs — the product brief, the market report, and the financial projections — by summarising the key points in your prompt as context (since you now have all three outputs saved).

When you are done: read the output and ask yourself honestly — would you send this to a real executive without editing it? What would you change? That answer is your measure of how much value Copilot added versus how much judgment you still need to apply.

---
---

# Lab Completion Checklist

**Lab 1**
- [ ] Opened **`Inputs/Engineering_Notes.pdf`** in Edge with Copilot sidebar
- [ ] Got a quick summary and identified features and risks
- [ ] Used RIFCC prompt to draft a professional team email
- [ ] Produced executive summary in two format variations (bullets and prose) + risk table
- [ ] Tried the **Compose tab** for the blog post and compared it to the RIFCC prompt result
- [ ] Wrote an internal blog post with three headline alternatives
- [ ] Completed the Human-in-the-Loop checks before saving
- [ ] Saved outputs to **`Lab1/Lab1_Team_Email.md`**, **`Lab1/Lab1_Executive_Summary.md`**, **`Lab1/Lab1_Feature_Blog.md`**

**Lab 2**
- [ ] Opened **`Inputs/Strategic_Connections.html`** in Edge
- [ ] Identified top trends and connected to the ClearSpend context
- [ ] Used citation links (Task 2.3) to verify at least one statistic against the source
- [ ] Used RIFCC prompt to produce a risk briefing table ordered by severity + added timeline column
- [ ] Completed the Human-in-the-Loop checks before saving
- [ ] Saved core output to **`Lab2/Lab2_Risk_Briefing.md`**

**Lab 2 Bonus** *(if completed)*
- [ ] Wrote a competitive intelligence summary with prioritised actions → **`Lab2/Lab2_Market_Analysis.md`**
- [ ] Analysed a video in Edge with Copilot (Bonus Task 2.B)

**Lab 3**
- [ ] Opened **`Inputs/Financial_Projections.xlsx`** and reviewed all four sheets
- [ ] Extracted and analysed key financial figures with Copilot
- [ ] Ran the hallucination verification test and logged result to **`Lab3/Lab3_Hallucination_Test_Log.md`**
- [ ] Used RIFCC prompt to write a formal CFO memo + bullet summary version
- [ ] Completed the Human-in-the-Loop checks before saving
- [ ] Saved core outputs to **`Lab3/Lab3_CFO_Memo.md`** and **`Lab3/Lab3_Strategic_Memo_Final.md`**

**Lab 3 Bonus** *(if completed)*
- [ ] Created a go/no-go decision table ordered by category with RAG status → **`Lab3/Lab3_GoNoGo_Summary.md`**
- [ ] Confirmed all Lab 3 files saved (Bonus Task 3.B)

---
---

# Key Takeaways

**Short questions for analysis, RIFCC prompts for writing.**
When you need to find something in a document, a one-sentence question is faster and cleaner. When you need to produce a professional document, the Role, Format, and Constraints in a RIFCC prompt are what make the output usable rather than generic.

**Format instructions produce dramatically better outputs.**
"Write a summary" and "Write a summary as a table with columns ordered by risk severity" produce entirely different results. Adding structure to your format request — tables, ordered lists, headers, word limits — is consistently the highest-value change you can make to a writing prompt.

**Follow-up prompts are where the quality happens.**
Your first prompt is a starting point. The refinements — adjust the tone, add a column, rewrite as a different format, be more specific — are where Copilot produces something you would actually use. Think of the first prompt as a rough draft, not a finished product.

**Always verify numbers before using them.**
Before any specific figure from a Copilot response goes into something you will share with others, take 15 seconds to confirm it in the source. This is the single most important habit for responsible AI use in business.

**AI is your writing assistant and reading assistant. The judgment is yours.**
Copilot can absorb a 20-page report in seconds, draft a CFO memo in a minute, and reformat the same recommendation three different ways. What it cannot do is know your organisation, your stakeholders, the unwritten context behind a decision, or whether the recommendation is actually right. That is what you bring. Use Copilot to get to your thinking faster — not to replace it.

---
---

# When to Use Copilot in Edge

**Before a meeting:** Open the briefing document in Edge, ask Copilot for the 3 most important points, and walk in prepared — without spending 45 minutes reading.

**When a long email or report arrives:** Ask "What is the main ask here?" or "What do I need to respond to?" — get to the point in 30 seconds.

**When drafting any professional communication:** Use a RIFCC prompt. Specify the role, the format, the tone, and what to exclude. It takes 60 seconds to write a good prompt and saves 20 minutes of drafting.

**When presenting data to leadership:** Ask Copilot to reformat the key figures as a table, ordered by priority or severity. The format change alone can make the same data far more persuasive.

**When reviewing a contract, policy, or vendor proposal:** Ask "What are the key obligations, deadlines, or conditions in this document?" as a first read — not as a substitute for proper review, but as an orientation tool.

**When preparing a recommendation:** Open your source documents, use RIFCC to draft the recommendation, then ask Copilot to produce a second version in a different format. Choose the better one, edit it, and send it.

**One rule that applies to all of these:** Before you send anything Copilot helped you write, read it yourself. You are the author. Copilot is the assistant. The responsibility for what you send is yours.

---

---
---

# Your Copilot Toolkit

These are copy-paste prompt templates for the situations you will encounter most often in real work. Save this section — or copy the prompts into a personal notes file — so you have them ready without having to build from scratch each time.

---

## The Meeting Prep Prompt

Use this when you have a briefing document, report, or agenda to review before a meeting and limited time to read it.

```
I have [X] minutes before a meeting about [topic]. The document on this page covers [brief description]. Give me:
1. The three most important things I need to know
2. One question I should ask in the meeting based on what's here
3. One potential issue or risk I should be ready to address
Keep your response under 150 words.
```

---

## The "Explain This to a Stakeholder" Prompt

Use this when you need to translate technical, financial, or complex content for an audience who did not read the source.

```
Role: You are explaining this to [describe your audience — e.g., "a senior executive who has not read the report", "a branch manager with no finance background", "a new team member on their first week"].

Input: The document on this page.

Task: Explain the key points in plain language that this specific audience would understand and find relevant.

Format: 3–4 bullet points, each under 25 words.

Constraints: No jargon. No technical terms. Every point should answer "what does this mean for me?"
```

---

## The Polite Refusal Email Prompt

Use this when you need to decline a request, push back on a timeline, or say no in a way that maintains the relationship.

```
I need to write a professional email declining [describe the request — e.g., "a request to move up our project deadline", "an invitation to join a working group I don't have capacity for"].

Tone: Respectful and direct. Not apologetic, but not blunt.

Format:
- One sentence acknowledging the request
- One sentence with the reason (keep it brief — no over-explaining)
- One sentence offering an alternative or next step where appropriate
- One closing sentence

Constraints: Under 80 words. Do not use "Unfortunately" as an opener. Do not say "I apologize" — just be clear and professional.
```

---

## The Document Summary for a Colleague Prompt

Use this when a colleague asks "what's in that report?" and you need to give them a useful answer quickly.

```
Summarize the document on this page for a colleague who has not read it. They need to understand:
1. What it is about (one sentence)
2. The 3 most important findings or decisions
3. What action, if any, is being recommended

Keep the entire summary under 100 words. Write it as if you are sending it in a Slack message — informal but informative.
```

---

## The Risk Spotter Prompt

Use this before approving, signing, or committing to anything — a vendor proposal, a project plan, a contract summary, or a budget request.

```
Review the document on this page and identify:
1. The top 3 risks or potential problems I should be aware of
2. Any commitments, deadlines, or obligations that are easy to miss
3. One question I should ask before proceeding

Be direct. Flag anything that seems vague, missing, or potentially problematic. Under 150 words.
```

---

## The "Is This Accurate?" Verification Prompt

Use this when you want to test whether Copilot is staying grounded in the source rather than adding information from its training data.

```
Look at only the document on this page. I want to check your previous response.

For each fact or number you mentioned, tell me:
- Does it appear in this document? (Yes / No / Partially)
- If yes, which section?
- If no or partially, flag it clearly so I know not to rely on it

Do not add any new information. Just check what you already said against what is actually on the page.
```

---

**Questions or feedback?**
Contact your instructor or training coordinator.

**Lab Version:** 3.0
**Last Updated:** March 2026
