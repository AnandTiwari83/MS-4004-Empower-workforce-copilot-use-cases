# Lab-10: Exercise 2, Task 3 — Use Copilot in Loop to Turn Insights into Actionable Content

## Lab Overview

In this lab, you use **Microsoft Copilot in Loop** to transform the insights from your Finance presentation into structured, collaborative content that your team can review and act upon together. You will create a Loop workspace with three pages — one for negotiation strategy, one for risk mitigation ideas, and one for a communication plan — drawing directly from the PowerPoint presentation you created in Lab-09.

**Estimated Duration:** 15 minutes  
**Difficulty Level:** 100 (Beginner)

---

## Learning Objectives

By the end of this lab, you will be able to:

- Create and organize a **Microsoft Loop workspace** with multiple pages for collaborative Finance work.
- Use **Copilot in Loop** to extract structured content from a PowerPoint presentation and transform it into collaborative workspace components.
- Build a Loop table, checklist, and communication plan from AI-generated insights.
- Obtain the Loop workspace link for sharing with colleagues in the next task.

---

## Prerequisites

- Completion of **Lab-09** (Smart Sensor contract comparison - Finance.pptx saved to OneDrive).
- Access to **Microsoft Loop for the web**.
- The file **Smart Sensor contract comparison - Finance.pptx** must be saved in your OneDrive.

---

## Background and Scenario

### Why Collaborate Before Presenting?

Before presenting the **Smart Sensor contract comparison - Finance** PowerPoint to Finance leadership, you want to gather diverse perspectives from your Finance team — particularly from colleagues with procurement and legal experience. Their input could strengthen your negotiation strategy, improve your risk mitigation recommendations, and sharpen your communication approach.

**Microsoft Loop** is the ideal tool for this collaborative review. Rather than sending a static document by email and waiting for responses, Loop allows your team to view, edit, and contribute to shared content in real time, with everyone working in the same workspace simultaneously.

### What You'll Build

You will create a Loop workspace with three collaborative pages:

| Page | Content Type | Purpose |
|------|-------------|---------|
| **Negotiation Strategy** | Structured table (Action, Priority, Owner, Deadline) | Plan and assign negotiation actions |
| **Risk Mitigation Ideas** | Checklist with status fields | Track risk mitigation steps and progress |
| **Communication Plan** | Structured plan with timeline and channels | Coordinate how recommendations are shared |

---

## Exercise Overview

| Step | Activity |
|------|----------|
| 1 | Open Microsoft Loop and create a new workspace |
| 2 | Create the Negotiation Strategy page using Copilot |
| 3 | Create the Risk Mitigation Ideas page using Copilot |
| 4 | Create the Communication Plan page using Copilot |
| 5 | Copy the workspace link for use in Lab-11 |

---

## Task Instructions

### Step 1: Open Loop and Create a New Workspace

1. In Microsoft Edge, navigate to the **Microsoft 365 home page**: `https://www.microsoft365.com`

2. Select **Apps** in the left navigation pane, then select **Loop**.

3. In Loop for the web, create a **new workspace** titled:  
   **Adatum/Contoso contract comparison**

> **📸 Screenshot placeholder:** Capture the new Loop workspace immediately after creation.  
> Suggested filename: `M05-Lab10-Step01-LoopWorkspaceCreated.png`

> ✅ **Checkpoint:** You have a new Loop workspace named **Adatum/Contoso contract comparison** with an initial unnamed page.

> **🔧 Troubleshooting:**
> - If you cannot find Microsoft Loop in the Apps list, navigate directly to https://loop.microsoft.com in Microsoft Edge.
> - If the "/" shortcut does not show file attachment options, look for the (+) button at the left of the Loop text area instead.
> - If the PowerPoint file is not found when attaching, open it once from OneDrive in PowerPoint for the web, then return to Loop and try again.
> - If Copilot in Loop doesn't generate a table (only text), add "format this as a table" to your prompt.
> - Copy the URL from the browser bar immediately after creating all three pages — navigating away may make it harder to locate the workspace URL again.

---

### Step 2: Build the Negotiation Strategy Page

The first page will capture the presentation's negotiation recommendations in a format that makes it easy to assign ownership and track progress.

1. Change the title of the first page from **Untitled** to:  
   **Negotiation Strategy**

> **📸 Screenshot placeholder:** Capture the first Loop page after renaming it to **Negotiation Strategy**.  
> Suggested filename: `M05-Lab10-Step02-NegotiationStrategyPage.png`

2. Open the **Copilot pane** within this Loop page.

3. **Write and submit your own prompt** asking Copilot to:
   - Review the attached **Smart Sensor contract comparison – Finance.pptx** file.
   - Turn its **negotiation recommendations** into a **structured Loop table** with the following columns:
     - **Action** — the specific negotiation action to take
     - **Priority** — importance level (e.g., High, Medium, Low)
     - **Owner** — the team member responsible
     - **Deadline** — target completion date
   - Attach the file by typing a forward slash (`/`) and selecting the **Smart Sensor contract comparison – Finance.pptx** file from the **Files** tab.
   - If the slash menu offers multiple choices, type `/` in the Loop page body, select **File** or **Attachment**, and then choose the presentation from OneDrive.

> **📸 Screenshot placeholder:** Capture the Loop Copilot prompt area with the PowerPoint file attached from OneDrive.  
> Suggested filename: `M05-Lab10-Step03-PowerPointAttachedInLoop.png`

> 💡 **Guidance:** Use the forward slash (`/`) shortcut in Loop to attach your PowerPoint file directly from OneDrive. Make sure you reference the correct file name.
> Additional navigation detail: Type `/` in the Loop page body, select **File** or **Attachment**, and then select the presentation from OneDrive.

**After Copilot responds:**
1. Review the table results in the Copilot pane.
2. Select the **Copy** icon that appears below the table.
3. **Paste** the copied content into your **Negotiation Strategy** Loop page.
4. Delete any extraneous text that was pasted along with the table (such as introductory phrases from the Copilot response).

> ✅ **Expected Outcome:** A structured negotiation strategy table embedded in the Loop page with Action, Priority, Owner, and Deadline columns populated from the presentation's negotiation recommendations.

> **📸 Screenshot placeholder:** Capture the completed negotiation strategy table on the Loop page.  
> Suggested filename: `M05-Lab10-Step04-NegotiationTableGenerated.png`

---

### Step 3: Build the Risk Mitigation Ideas Page

The second page will transform the presentation's risk mitigation content into a trackable checklist.

1. **Add a new page** under your **Adatum/Contoso contract comparison** workspace.

2. Change the page title from **Untitled** to:  
   **Risk mitigation ideas**

3. Open the **Copilot pane** within this new page.

4. **Write and submit your own prompt** asking Copilot to:
   - Review the attached **Smart Sensor contract comparison – Finance.pptx** file.
   - Turn the **risk mitigation ideas** from the presentation into a **checklist with status fields** for tracking progress.
   - Attach the PowerPoint file using the forward slash (`/`) shortcut.

**After Copilot responds:**
1. Review the checklist results.
2. **Copy and paste** the content into your **Risk mitigation ideas** Loop page.
3. Delete any extraneous text that was copied and pasted along with the checklist.

> ✅ **Expected Outcome:** A checklist embedded in the Loop page listing each risk mitigation action with a status field (e.g., Not Started, In Progress, Complete) that team members can update collaboratively.

> **📸 Screenshot placeholder:** Capture the **Risk mitigation ideas** page showing the generated checklist content.  
> Suggested filename: `M05-Lab10-Step05-RiskMitigationIdeasPage.png`

---

### Step 4: Build the Communication Plan Page

The third page will establish how and when the contract comparison findings should be communicated to stakeholders.

1. **Add a new page** under your **Adatum/Contoso contract comparison** workspace.

2. Change the page title from **Untitled** to:  
   **Communication plan**

3. Open the **Copilot pane** within this new page.

4. **Write and submit your own prompt** asking Copilot to:
   - Review the attached **Smart Sensor contract comparison – Finance.pptx** file.
   - Draft a **communication plan** for sharing the presentation's recommendations with stakeholders.
   - Include a **timeline** specifying when each communication will occur.
   - Include **communication channels** (e.g., email, Teams meeting, formal presentation).
   - Attach the PowerPoint file using the forward slash (`/`) shortcut.

**After Copilot responds:**
1. Review the communication plan results.
2. **Copy and paste** the content into your **Communication plan** Loop page.
3. Delete any extraneous text that was copied and pasted along with the plan.

> ✅ **Expected Outcome:** A structured communication plan embedded in the Loop page, listing each stakeholder group, the communication timeline, and the channel/format for sharing the contract comparison findings.

> **📸 Screenshot placeholder:** Capture the **Communication plan** page showing the generated stakeholder communication content.  
> Suggested filename: `M05-Lab10-Step06-CommunicationPlanPage.png`

---

### Step 5: Copy the Loop Workspace Link

In Lab-11, you will send an email to your Finance colleagues that includes a link to this Loop workspace for real-time collaboration.

1. With your **Adatum/Contoso contract comparison** workspace open in Loop, copy the **URL from your browser address bar**.

2. Save this link somewhere accessible (e.g., a temporary note, the browser clipboard) so you can paste it into your Outlook email in Lab-11.

> ⚠️ **Important:** Keep the Loop workspace open or note its URL before navigating away. You will need this link in Lab-11.

> **📸 Screenshot placeholder:** Capture the browser address bar with the Loop workspace URL visible.  
> Suggested filename: `M05-Lab10-Step07-LoopWorkspaceURL.png`

---

## Task Summary

In this task, you used **Microsoft Copilot in Loop** to transform the findings from your Finance presentation into three structured collaborative pages:

| Page | Type | Content |
|------|------|---------|
| Negotiation Strategy | Table | Action items with Priority, Owner, and Deadline |
| Risk Mitigation Ideas | Checklist | Risk mitigation steps with status tracking |
| Communication Plan | Structured plan | Stakeholder communications with timeline and channels |

---

## Exercise Summary

You have completed **Exercise 2, Task 3**. You demonstrated how Copilot in Loop can:
- Extract structured, actionable content from a PowerPoint presentation without manual retyping.
- Transform analytical insights into collaborative workspace components that teams can work with in real time.
- Bridge the gap between individual analyst work products and team-based review and decision-making.

---

*Previous Lab: [Lab-09 — Task 2: PowerPoint Executive Presentation](./Lab-09.test.md)*  
*Next Lab: [Lab-11 — Task 4: Use Copilot in Outlook to Create a Feedback Request Email](./Lab-11.test.md)*
