# Lab-05: Exercise 1, Task 3 — Use Copilot Chat to Analyze a Potential Acquisition

## Lab Overview

In this lab, you use **Microsoft 365 Copilot Chat** to analyze a business perspective document for a potential acquisition target — **Relecloud, Ltd.** — and generate a structured analysis that Finance leadership can act upon. You will learn how the level of detail in your prompt dramatically affects the quality of Copilot's output, and you will practice building progressively more detailed prompts to generate comprehensive, multi-section financial reports.

**Estimated Duration:** 15 minutes  
**Difficulty Level:** 100 (Beginner)

---

## Learning Objectives

By the end of this lab, you will be able to:

- Use **Microsoft 365 Copilot Chat in Work mode** to analyze an internal business document uploaded to OneDrive.
- Understand the difference between high-level prompts and detailed, structured prompts, and explain how prompt quality affects output quality.
- Generate a multi-section acquisition analysis covering financial data, operations, and integration planning.
- Download and save a Copilot-generated analysis document for future use in Lab-06.

---

## Prerequisites

- Completion of **Lab-01** (resource files uploaded to OneDrive).
- Completion of **Lab-02** (understanding of the Fabrikam scenario and the Relecloud acquisition context).

---

## Background and Scenario

### The Relecloud Acquisition Opportunity

Fabrikam's executive team is evaluating whether to acquire **Relecloud, Ltd.**, a technology company that would expand Fabrikam's digital product portfolio. Robin Kline, Fabrikam's Finance Manager, has provided you with a detailed **Relecloud Business Perspective** document that covers:

- Market position and industry analysis
- Financial performance history
- Customer and sales insights
- Operations and capabilities
- Intellectual property and product roadmap
- Risks and challenges
- Future outlook

Robin has tasked you with analyzing this document and summarizing it into three concise areas for leadership review:

| Section | Focus |
|---------|-------|
| **Financial Data** | Key financial figures and trends |
| **Operations Analysis** | Efficiency, scalability, and organizational structure |
| **Integration Plan** | Main steps and dependencies for merging Relecloud into Fabrikam |

### Why This Exercise Matters

This task demonstrates a critical Copilot skill: **how the level of detail in your prompt determines the quality of the output**. You will first write a high-level prompt, review what Copilot produces, and then write a much more detailed prompt to see the dramatic improvement in results. This exercise builds the habit of investing time in prompt quality — a skill that pays dividends in every finance analysis task.

---

## Understanding Copilot Chat Modes

Copilot Chat has two operating modes:

| Mode | When to Use | Response Selector |
|------|-------------|-------------------|
| **Work** | Analyzing internal organizational content (OneDrive files, SharePoint, Teams, Outlook) | Not shown — automatically managed |
| **Web** | Searching external sources (public websites, industry news, research) | Visible — lets you choose response depth |

> ✅ **For this task, use Work mode** because you are analyzing a file stored in your OneDrive. The Web mode would search public internet sources, which is not appropriate here.

---

## Exercise Overview

| Step | Activity |
|------|----------|
| 1 | Download the Relecloud Business Perspective document |
| 2 | Open Copilot Chat in Work mode |
| 3 | Submit a high-level prompt and review the output |
| 4 | Submit a detailed, structured prompt and compare the results |
| 5 | Review and download the enhanced analysis document |

---

## Task Instructions

### Step 1: Download and Upload the Source Document

1. Select the following link to download the source file:  
   [**Relecloud Business Perspective.docx**](https://go.microsoft.com/fwlink/?linkid=2347813)

2. Save the file to your **OneDrive** account so it is accessible to Copilot.

---

### Step 2: Open Copilot Chat in Work Mode

1. In Microsoft Edge, navigate to the **Microsoft 365 home page**: `https://www.microsoft365.com`

2. Open **Copilot Chat** from the Microsoft 365 experience.
   - Exact path: **Microsoft 365 home** → **Copilot**.
   - If **Copilot** is not pinned in the navigation, select **Apps** → search for **Copilot** → open **Copilot**.

3. On the Microsoft 365 home page, ensure you have selected the **Work** option in Copilot Chat. This mode is required for analyzing files stored in OneDrive.
   - Use the mode selector in the Copilot pane and choose **Work** rather than **Web**.

> **📸 Screenshot placeholder:** Capture Copilot Chat with the mode selector set to **Work**.
> Suggested filename: `M05-Lab05-Step01-CopilotChatWorkMode.png`

> ✅ **Checkpoint:** You are in **Work** mode, which is optimized for internal document analysis.

> ✅ **Validation checkpoint:** Confirm the Copilot chat experience is open and the mode selector shows **Work** before you attach the document.

> **🔧 Troubleshooting:**
> - If Copilot searches the web instead of your file, confirm you are in **Work** mode (not Web mode). The mode selector appears at the top or bottom of the Copilot Chat pane.
> - If the Relecloud document is not found, open it once from OneDrive in Word, then return to Copilot Chat and try attaching it again.
> - If the "Download" option does not appear after the response, ask Copilot in a follow-up prompt: "Please compile this analysis into a downloadable Word document."
> - If Copilot returns a very short response, your prompt may have been truncated — try splitting it into two prompts.

---

### Step 3: Submit a High-Level Prompt (First Attempt)

In the Copilot prompt field:

1. Attach the **Relecloud Business Perspective.docx** file.

> **📸 Screenshot placeholder:** Capture the Copilot prompt field with **Relecloud Business Perspective.docx** attached.
> Suggested filename: `M05-Lab05-Step02-RelecloudDocAttached.png`

2. Write and submit a prompt based on Robin's request: ask Copilot to review the attached document and create a **business perspective summary** with three sections:
   - Relecloud's financial data
   - Operations analysis of Relecloud
   - Integration plan for the acquisition

**After Copilot responds:**
- Read the summary carefully.
- Note what is included and, more importantly, **what is missing**.

> **📸 Screenshot placeholder:** Capture the first Copilot response produced from your high-level prompt.
> Suggested filename: `M05-Lab05-Step03-HighLevelPromptResponse.png`

> ✅ **Validation checkpoint:** Confirm the response includes all three requested sections—financial data, operations analysis, and integration plan—even if the content is still fairly general.

> 💡 **Reflection:** Does Copilot's summary go into the level of detail you would need to present to Finance leadership? If it feels shallow, that is intentional — high-level prompts produce high-level results. You'll improve this in the next step.

> ✅ **Expected Outcome:** A three-section summary that provides a general overview of Relecloud's finances, operations, and integration planning, but may lack specific data points, visuals, or analytical depth.

> **📊 Prompt Comparison:** Use the table below to compare what the two prompt styles are designed to produce.

| Aspect | Draft 1: High-level prompt | Draft 2: Detailed prompt |
|--------|----------------------------|--------------------------|
| Scope | General summary of the three requested sections | Expanded report with detailed subsections and requested visuals |
| Financial detail | Broad statements about performance | Ratios, valuation, ARR dynamics, cash flow, and concentration analysis |
| Operations detail | High-level overview of capability and efficiency | Cost structure, SWOT, benchmarking, and scalability analysis |
| Integration output | Simple integration summary | Post-merger integration plan, risks, synergies, leadership review, and timeline |
| Visuals | Often none or only light descriptions | Explicit charts, matrices, and timeline visuals requested in the prompt |
| Leadership readiness | Good for a quick draft | Better suited for decision support and presentation-ready analysis |

---

### Step 4: Submit a Detailed, Structured Prompt (Second Attempt)

Now you will improve your output by writing a much more detailed prompt. This time, ask Copilot to create an **expanded version** of the previous report that retains all information from the first version and adds the following:

**Financial Analysis Section** — add:
- **Valuation and deal structure**: valuation multiples and deal structure implications
- **Financial health and ratios**: liquidity and solvency, profitability trends, gross-to-net retention by cohort, regional ARR (Annual Recurring Revenue) dynamics, and cash flow analysis
- **Revenue and customer concentration**: revenue breakdown, customer concentration risk, customer concentration by sector/vertical, and churn and retention drivers
- **Visual**: Line or Bar Charts showing Revenue, EBITDA, and net income trends over time, plus gross margin and operating margin trends

**Operations Analysis Section** — add:
- **Cost structure and efficiency**: COGS and OpEx analysis, efficiency metrics, and scalability assessment
- **Competitive positioning**: SWOT analysis and peer benchmarking
- **Visuals**:
  - SWOT Matrix: visual grid summarizing strengths, weaknesses, opportunities, and threats
  - Scalability Assessment Diagram: illustrates DevSecOps practices, infrastructure, and organizational scalability

**Integration Planning Section** — add:
- **Synergy and integration modeling**: synergy realization, integration risks, and a post-merger integration plan
- **Leadership and Organizational Review**: management track record and organizational structure
- **Visual**: Integration Timeline (Gantt Chart) visualizing phases and milestones of the post-merger integration plan

> 💡 **Guidance:** Write this as a single, comprehensive prompt. Be explicit about each section and the specific details and visuals you want included. The more specific and structured your prompt, the more precise and complete Copilot's output will be.

**After Copilot responds:**
- Review the expanded analysis.
- Compare it carefully to your first summary. Note:
  - Additional data points and context that appear in the second version.
  - The visual elements Copilot attempted to generate or describe.
  - How the extra prompt detail produced a significantly more comprehensive analysis.

> **📸 Screenshot placeholder:** Capture the second Copilot response created from your detailed prompt.
> Suggested filename: `M05-Lab05-Step04-DetailedPromptResponse.png`

> ✅ **Validation checkpoint:** Confirm the second draft is meaningfully richer than Draft 1 by including added subsections, more data points, and at least some reference to the requested visuals or timelines.

> ✅ **Expected Outcome:** A detailed, multi-section analysis with financial ratios, valuation details, SWOT analysis, and integration timeline — substantially more comprehensive than the first attempt.

---

### Step 5: Explore Suggested Prompts and Download the Document

1. Review any **suggested follow-up prompts** that Copilot displays at the end of the response. If any are of interest to you, feel free to submit them to further refine the analysis.

2. When you are satisfied with the analysis, ask Copilot to **compile all the information into a single downloadable document**.

3. **Download the generated file** and save it to your **OneDrive** account.
   - If the download control is not immediately visible, open the response actions menu (**...**) and select **Download**.

> **📸 Screenshot placeholder:** Capture the Copilot response area showing the **Download** option for the generated document.
> Suggested filename: `M05-Lab05-Step05-DownloadDocumentOption.png`

> ⚠️ **Important:** Save this document to OneDrive. You will use it in **Lab-06** (Excel what-if scenario modeling) as the source for the acquisition financial analysis.

> ✅ **Validation checkpoint:** Confirm the downloaded file opens successfully and is saved to OneDrive where you can retrieve it again in Lab-06.

> ✅ **Expected Outcome:** A downloadable Word document containing the complete, expanded Relecloud acquisition analysis, saved to your OneDrive.

---

## Task Summary

In this task, you used **Microsoft 365 Copilot Chat** to analyze a complex business document and extract structured acquisition insights. Key takeaways:

| Lesson | Why It Matters |
|--------|---------------|
| **High-level prompts produce high-level results** | Vague requests lead to generic summaries |
| **Detailed prompts drive analytical depth** | Specifying sections, data types, and visuals yields comprehensive reports |
| **Work mode is essential for internal documents** | Ensures Copilot searches your OneDrive, not the web |
| **Downloadable outputs preserve your work** | Enables you to use Copilot-generated content in downstream tasks |

---

## Exercise Summary

You have completed **Exercise 1, Task 3**. You demonstrated how Copilot Chat can:
- Extract and categorize complex financial information from business documents into actionable summaries.
- Produce significantly different results based on prompt quality — reinforcing the importance of detailed, four-element prompts.
- Generate comprehensive acquisition analyses that would otherwise take hours of manual document review.

---

*Previous Lab: [Lab-04 — Task 2: Teams Meeting Notes](./Lab-04.test.md)*  
*Next Lab: [Lab-06 — Task 4: Use Copilot in Excel to Model What-If Scenarios](./Lab-06.test.md)*
