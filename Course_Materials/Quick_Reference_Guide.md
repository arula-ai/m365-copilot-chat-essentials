# Quick Reference Guide: Copilot on Edge Essentials

**Print this page and keep it at your desk for quick reference!**

---

## The RIFCC Pattern for Better Prompts

Use this framework every time you prompt Copilot:

| Element | Question to Ask Yourself | Example |
|---------|-------------------------|---------|
| **R - Role** | Who should Copilot act as? | "Act as a senior business analyst..." |
| **I - Input** | What raw material am I providing? | "[Paste data, notes, or document]" |
| **F - Format** | What output format do I need? | "Email with bullet points" or "Executive summary" |
| **C - Context** | What's the situation and audience? | "For Board of Directors, quarterly review" |
| **C - Constraints** | What are the boundaries? | "Under 200 words, professional tone, no jargon" |

---

## The 5-Step Review Process

**ALWAYS review AI outputs before using them:**

✓ **1. ACCURACY** - Are facts correct and verifiable?
✓ **2. SOURCE** - Can I trace each claim to a reliable source?
✓ **3. TONE** - Is language appropriate for my audience?
✓ **4. POLICY** - Does this comply with company guidelines?
✓ **5. LOGIC** - Does reasoning make sense? Any unsupported leaps?

**Rule of Thumb:** If you wouldn't put your name on it, don't send it.

---

## Common Copilot Tasks - Quick Prompts

### 1. Summarize a Long Document

```
Based on the document currently open in this tab, provide a 5-sentence executive summary highlighting:
1. Main purpose/goal
2. Key findings
3. Critical risks or concerns
4. Recommendations
5. Next steps

Use bullet points and keep under 150 words.
```

---

### 2. Draft a Professional Email

```
Role: Professional communications assistant
Context: I need to send an update to my team about [TOPIC]
Task: Draft a concise email that:
- Opens with a clear subject line
- Summarizes the key update in 2-3 sentences
- Lists action items (if any)
- Closes professionally

Tone: Professional but approachable
Constraints: Under 150 words
```

---

### 3. Extract Key Insights from Research

```
Based on the document open in this tab, identify the top 3 [trends/risks/opportunities/challenges]. For each one, provide:
- A one-sentence summary
- Why it matters for [your industry/project]
- A specific recommendation

Format as a numbered list.
```

---

### 4. Transform Technical Content for Non-Technical Audience

```
Take the following technical content and rewrite it for a non-technical executive audience:
[PASTE CONTENT]

Requirements:
- Remove all technical jargon
- Focus on business impact
- Use analogies where helpful
- Keep under 200 words
```

---

### 5. Prepare for a Meeting

```
I have a meeting about [TOPIC] in 30 minutes. Based on the document currently open, provide:
1. 3 key points I should know
2. 2 potential questions I might be asked
3. 1 recommendation I should be prepared to give

Keep this concise—I need to review it quickly.
```

---

### 6. Compare and Contrast Information

```
Compare [OPTION A] and [OPTION B] based on the following criteria:
- Cost
- Implementation time
- Risks
- Benefits

Present as a table with columns for each option and rows for each criterion.
```

---

### 7. Identify Risks or Red Flags

```
Review the following [project plan/financial data/proposal]:
[PASTE CONTENT]

Identify the top 3 risks or potential issues. For each risk, provide:
- Description of the risk
- Potential impact (high/medium/low)
- Suggested mitigation strategy
```

---

### 8. Refine and Improve AI Output (Follow-Up Prompt)

Use these follow-up prompts when the first output isn't quite right:

**Make it more concise:**
```
This is good, but too long. Reduce this to under [X] words while keeping the key points.
```

**Make it more specific:**
```
This is too general. Provide more specific details and concrete examples.
```

**Change the tone:**
```
Rewrite this with a more [formal/casual/urgent/optimistic] tone.
```

**Simplify language:**
```
Rewrite this for someone with no technical background. Replace jargon with plain language.
```

**Add more detail:**
```
Expand on point #2 with more detail and supporting evidence.
```

---

## Warning Signs of AI Hallucinations

⚠️ **Watch out for these red flags:**

| Red Flag | What It Looks Like | What to Do |
|----------|-------------------|------------|
| **Overly specific statistics** | "67.3% of healthcare organizations..." without citation | Ask: "Where did this number come from?" |
| **Citations you can't verify** | "According to the WHO 2026 report..." (report doesn't exist) | Search for the source independently |
| **Definitive answers with uncertainty** | Confident tone about something ambiguous | Ask: "How confident are you in this?" |
| **Information not in your sources** | Copilot mentions facts not in documents you provided | Ask: "Is this from the document I shared?" |
| **Logical leaps** | Conclusions that don't follow from premises | Ask: "Walk me through the logic of this." |

**Test for Hallucinations:**
- Ask Copilot to cite specific sources
- Verify key facts independently
- Ask follow-up questions about edge cases
- Request: "Quote directly from the document to support this claim"

---

## Keyboard Shortcuts for Copilot in Edge

| Action | Shortcut (Windows) | Shortcut (Mac) |
|--------|-------------------|----------------|
| Open Copilot sidebar | `Ctrl + Shift + .` | `Cmd + Shift + .` |
| Close Copilot sidebar | `Esc` | `Esc` |
| Focus on Copilot input | Click in chat box | Click in chat box |
| Start new conversation | Click "New topic" button | Click "New topic" button |

---

## Best Practices Checklist

**Before You Start:**
- [ ] Do I have a clear goal for what I need Copilot to do?
- [ ] Have I gathered all necessary input materials (documents, data, notes)?
- [ ] Do I know my target audience and tone?
- [ ] Have I checked if this content is appropriate to share with AI (company policy)?

**While Working with Copilot:**
- [ ] Am I using the RIFCC pattern for structured prompts?
- [ ] Am I asking follow-up questions to refine the output?
- [ ] Am I testing for hallucinations by asking for sources?
- [ ] Am I saving prompts that work well for future reuse?

**Before Using the Output:**
- [ ] Have I applied the 5-Step Review Process (Accuracy, Source, Tone, Policy, Logic)?
- [ ] Have I edited and personalized the content (not just copy-paste)?
- [ ] Would I be comfortable putting my name on this?
- [ ] Have I verified any key facts or statistics independently?

---

## Common Mistakes to Avoid

❌ **DON'T:**
- Copy-paste Copilot's output without reviewing
- Use vague prompts like "Help me with this"
- Trust statistics without verifying sources
- Share confidential/regulated data (check your policy first!)
- Accept the first output (iterate and refine!)
- Forget to specify tone and audience
- Skip the 5-Step Review Process to save time

✅ **DO:**
- Review and edit all AI-generated content
- Use specific, structured prompts (RIFCC pattern)
- Verify facts and sources independently
- Follow company data-handling policies
- Ask follow-up questions to improve outputs
- Clearly define format and constraints
- Always apply the 5-Step Review Process

---

## Troubleshooting Guide

### Problem: Copilot gives generic or unhelpful responses

**Solutions:**
1. Make your prompt more specific (use RIFCC pattern)
2. Provide more context about your goal
3. Ask follow-up questions to drill deeper
4. Ensure Copilot has access to relevant documents

**Example Fix:**
- ❌ Bad: "Summarize this document"
- ✅ Good: "Summarize the top 3 financial risks from this Q3 report in bullet points under 100 words"

---

### Problem: Copilot can't access the document I have open

**Solutions:**
1. Ensure document is open in Microsoft Edge (not another browser)
2. Refresh the Copilot sidebar (close and reopen)
3. Try pasting relevant sections directly into the prompt
4. Check if the document is password-protected or restricted

---

### Problem: Copilot's output is too long/short

**Solutions:**
1. Add a word/sentence limit to your prompt: "Keep under 200 words"
2. Use a follow-up prompt: "Expand on this with more detail" or "Condense this to under 150 words"
3. Specify format: "Provide as a 3-bullet summary" vs. "Provide as a detailed 2-page analysis"

---

### Problem: Copilot's tone doesn't match my audience

**Solutions:**
1. Specify tone in your prompt: "Professional and formal" or "Conversational and approachable"
2. Use a follow-up prompt: "Rewrite this with a more [formal/casual/urgent] tone"
3. Provide an example: "Write in a style similar to how [person/company] communicates"

---

### Problem: I'm not sure if Copilot's information is accurate

**Solutions:**
1. Ask Copilot to cite sources: "Where did this information come from?"
2. Verify key facts independently (Google, company databases, etc.)
3. Ask Copilot for confidence level: "How confident are you in this analysis?"
4. Request direct quotes: "Quote the document to support this claim"
5. Run a "hallucination test" by asking about something you know doesn't exist

---

## When to Use Copilot (and When Not To)

### ✅ Great Use Cases for Copilot

- **Drafting first versions** of emails, reports, memos
- **Summarizing** long documents, articles, or web pages
- **Extracting insights** from research or data
- **Reformatting** content for different audiences
- **Brainstorming** ideas, options, or approaches
- **Translating** technical content to business language
- **Preparing** for meetings by analyzing pre-read materials

---

### ⚠️ Use with Caution

- **Financial decisions** - Verify numbers independently
- **Legal content** - Consult legal team, don't rely solely on AI
- **Medical/health information** - Requires professional review
- **Sensitive communications** - Review tone and wording carefully
- **Technical specifications** - Verify accuracy with subject matter experts

---

### ❌ Don't Use Copilot For

- **Confidential/regulated data** (unless company policy explicitly allows)
- **Final decisions** without human review and accountability
- **Content used verbatim** without editing or personalization
- **Real-time legally binding** information (contracts, compliance filings)
- **Tasks requiring emotional intelligence** (performance reviews, conflict resolution)

---

## Prompt Templates by Role

### For Project Managers

**Weekly Status Update:**
```
Role: Project Manager
Context: Weekly update to stakeholders about [PROJECT NAME]
Input: [Paste notes on progress, blockers, risks]
Task: Draft a status update email covering:
- Progress this week
- Upcoming milestones
- Current blockers and mitigation plans
- Action items

Tone: Professional and transparent
Format: Email with bullet points
Constraints: Under 250 words
```

---

### For Analysts

**Data Synthesis:**
```
Role: Senior Business Analyst
Context: Analyzing [TOPIC] for executive decision-making
Input: [Paste data or link to document]
Task: Provide an executive summary including:
- Key findings (top 3)
- Trends or patterns identified
- Recommended actions
- Data limitations or gaps

Format: Structured report with headers
Constraints: Under 400 words, include supporting data points
```

---

### For Managers

**Performance Feedback Preparation:**
```
Role: People Manager
Context: Preparing for quarterly performance review with team member
Input: [Paste notes on performance, accomplishments, areas for growth]
Task: Help me structure feedback covering:
- Specific accomplishments and impact
- Areas of strength
- Constructive development areas
- Goals for next quarter

Tone: Supportive and balanced
Constraints: Specific examples, no generic statements
```

---

### For Communications Professionals

**External Announcement:**
```
Role: Corporate Communications Specialist
Context: Announcing [NEWS] to external stakeholders
Input: [Paste internal facts/data]
Task: Draft an external announcement that:
- Clearly states what's being announced
- Explains why it matters
- Provides relevant context
- Includes a forward-looking statement

Tone: Professional, confident, and positive
Format: Press release style
Constraints: Under 300 words, no internal jargon
```

---

## Additional Tips for Success

### Tip 1: Build a Personal Prompt Library
Save prompts that work well for your recurring tasks. Store them in:
- A Word/Google Doc
- Note-taking app (Evernote, OneNote)
- Email draft to yourself
- Company knowledge base

### Tip 2: Iterate Relentlessly
Your first prompt rarely gives the best result. Plan for 2-3 rounds of refinement.

### Tip 3: Share What Works
When you discover a great prompt or technique, share it with your team. Collaboration accelerates learning.

### Tip 4: Stay Curious
Experiment with different phrasings, formats, and approaches. Copilot improves over time, and so will you.

### Tip 5: Remember the Human Element
Copilot is a tool, not a replacement for your judgment, creativity, and accountability. Use it to amplify your skills, not replace them.

---

## Company-Specific Resources

**AI Usage Policy:** [Insert Link]
**IT Support for Copilot Issues:** [Insert Contact]
**Data Security Guidelines:** [Insert Link]
**Training Materials:** [Insert Link]
**Questions or Feedback:** [Insert Contact]

---

## Quick Reference Summary

**Golden Rules:**
1. **Never copy-paste-send** - Always review and verify
2. **Use RIFCC pattern** - Structure your prompts
3. **Iterate and refine** - First output is rarely the best
4. **Apply 5-Step Review** - Accuracy, Source, Tone, Policy, Logic
5. **Verify, then trust** - Check facts independently

---

**Remember:** AI is a powerful assistant, but human judgment, verification, and accountability are irreplaceable.

---

**Version 1.0 | March 2026**
**Questions? Contact:** [Training Team Email]
