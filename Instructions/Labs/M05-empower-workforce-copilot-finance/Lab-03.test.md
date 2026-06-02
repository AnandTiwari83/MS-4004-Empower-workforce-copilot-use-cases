# Lab-03: Exercise 1, Task 1 — Use Copilot in Excel to Analyze New Product Line COGS

## Lab Overview

In this lab, you take on the role of **Lead Financial Analyst at Fabrikam, Inc.** and use **Microsoft Copilot in Excel** to analyze the Cost of Goods Sold (COGS) estimates for the new **EcoSmart product line**. Rather than manually sorting and filtering spreadsheet data, you will use Copilot's AI-powered analysis to identify cost patterns, flag anomalies, and generate a management-ready summary with charts — all within minutes.

**Estimated Duration:** 15 minutes  
**Difficulty Level:** 100 (Beginner)

---

## Learning Objectives

By the end of this lab, you will be able to:

- Use **Microsoft Copilot in Excel** with the **Edit with Copilot** functionality to make direct, in-place changes to a spreadsheet.
- Analyze a financial dataset to identify the structure, patterns, and anomalies in COGS data.
- Generate multiple analysis sheets within a workbook, including a cost driver summary and a bar chart visualization.
- Write effective Copilot prompts that produce actionable financial insights.

---

## Prerequisites

- Completion of **Lab-01** (resource files uploaded to OneDrive).
- Familiarity with Microsoft Excel for the web.
- Understanding of the four elements of an effective Copilot prompt (Goal, Context, Sources, Expectations).

---

## Background: Understanding Copilot in Excel

Excel provides two ways to interact with Copilot:

### Standard Copilot Prompts (Chat Mode)
Use this mode when you want **quick insights, simple summaries, or one-off analysis** about the data in the workbook. In chat mode, Copilot suggests content but does not automatically change your worksheet.

### Edit with Copilot
Use this mode when you want Copilot to **work directly within the worksheet** — cleaning data, adding formulas, restructuring tables, creating new sheets, or making iterative in-place changes. This mode understands the structure of the sheet and applies changes directly.

> 💡 **This task uses the Edit with Copilot functionality.** This means Copilot will propose specific changes (new sheets, formulas, charts) and, once you confirm, will apply those changes directly to the workbook.

### Response Mode Selector
Copilot in Excel includes a **response control selector** that lets you choose which AI model Copilot uses. Leave this set to **Auto** (the default) to let Copilot select the best model. This task uses the default **Auto** mode.

---

## Exercise Overview

| Step | Activity |
|------|----------|
| 1 | Download the EcoSmart COGS Estimates file and upload to OneDrive |
| 2 | Open the file in Excel for the web and enable Edit with Copilot |
| 3 | Ask Copilot to describe the dataset and identify data quality issues |
| 4 | Identify COGS patterns and cost trends |
| 5 | Detect anomalies and outliers in the data |
| 6 | Generate a cost driver summary |
| 7 | Create a bar chart of the top five cost drivers |

---

## Task Instructions

### Step 1: Download and Upload the Source File

1. Select the following link to download the source file:  
   [**EcoSmart COGS Estimates.xlsx**](https://go.microsoft.com/fwlink/?linkid=2347616)

2. Save the downloaded file to your **OneDrive** account so it is accessible to Copilot in your Microsoft 365 tenant.

---

### Step 2: Open the File in Excel for the Web

1. In Microsoft Edge, navigate to the **Microsoft 365 home page**: `https://www.microsoft365.com`

2. Select **Apps** in the left navigation pane, then select **Excel**.

3. In Excel for the web, select the **Upload a file** button.

4. Navigate to your **OneDrive** account and select the **EcoSmart COGS Estimates** spreadsheet.

5. Once the file opens, select **Copilot** on the **Home** tab ribbon.

6. In the Copilot pane:
   - Leave the response mode selector set to **Auto**.
   - Verify that the **Edit with Copilot** icon (✏️) appears in the prompt field next to the plus (+) sign.
   - If you do not see this icon, select the **(+) sign** → **Edit with Copilot** from the drop-down menu.

> ✅ **Checkpoint:** The Edit with Copilot icon should now be visible in the Copilot prompt field.

---

### Step 3: Describe the Dataset and Identify Data Quality Issues

Ask Copilot to analyze the overall structure of the dataset and flag any data quality concerns.

**Submit the following prompt exactly as written:**

> **I'm a financial analyst for Fabrikam. I was asked to analyze the EcoSmart COGS Estimates spreadsheet for Fabrikam's new EcoSmart product line. Can you please review the dataset in this spreadsheet and provide two things in a new sheet: (1) a clear description of each key column and its purpose, and (2) a list of any missing or inconsistent data points that could affect accuracy. Present your findings in a concise, structured format in a new sheet.**

> 💡 **Note:** This prompt is provided in full as a model. Notice how it incorporates all four key elements: **Goal** (describe columns and flag issues), **Context** (financial analyst at Fabrikam reviewing EcoSmart data), **Sources** (the spreadsheet you have open), and **Expectations** (concise, structured format in a new sheet). Use this as a template for the prompts you write in subsequent steps.

**After Copilot responds:**
- Review the new sheet Copilot created with the dataset description and data quality notes.
- Select **Sheet1** to return to the original data.

> ✅ **Expected Outcome:** A new sheet appears describing each column and listing any missing or inconsistent data points.

---

### Step 4: Identify Cost Trends and Patterns

Your next goal is to understand which product features or components have the highest average COGS.

**Write and submit your own prompt** asking Copilot to:
- Find patterns in the data.
- Summarize which product features or components have the highest average COGS.
- Return the results in a **new sheet**.

> 💡 **Guidance:** Your prompt should specify the analysis goal (cost patterns), mention the context (EcoSmart COGS data), reference the current spreadsheet as the source, and request a new sheet for the output.

**After Copilot responds:**
- Review the new sheet containing the COGS pattern analysis.
- Remain in this sheet for the next step.

> ✅ **Expected Outcome:** A new sheet appears with a summary of cost patterns, identifying which product features or materials contribute most to COGS.

---

### Step 5: Detect Anomalies and Outliers

While reviewing the pattern analysis, you want to identify any data points that may indicate errors or unusually high material costs.

**Write and submit your own prompt** asking Copilot to:
- Look for **outliers or anomalies** in the COGS data.
- Indicate which anomalies could suggest data errors or unusually high material costs.
- Return the results in a **new sheet**.

**After Copilot responds:**
- Review the outlier analysis in the new sheet.
- Select **Sheet1** to return to the original dataset.

> ✅ **Expected Outcome:** A new sheet appears identifying statistical outliers or data points that deviate significantly from expected COGS ranges.

---

### Step 6: Generate a Cost Driver Summary

Now that you have identified patterns and anomalies, your Finance Manager needs a concise summary of the most impactful cost areas.

**Write and submit your own prompt** asking Copilot to:
- Generate a **brief summary report** of the **top three cost drivers**.
- Identify any **opportunities to reduce costs**.
- Return the results in a **new sheet**.

**After Copilot responds:**
- Review the cost driver summary in the new sheet.
- Select **Sheet1** to return to the original dataset.

> ✅ **Expected Outcome:** A new sheet appears with a clear summary of the top three cost drivers and suggested cost reduction opportunities.

---

### Step 7: Create a Bar Chart of Top Cost Drivers

Visual clarity is important when presenting data to leadership. Create a chart that makes the COGS data immediately understandable.

**Write and submit your own prompt** asking Copilot to:
- Create a **bar chart** showing the **top five product features** by average COGS.
- Return the chart in a **new sheet**.

**After Copilot responds:**
- Review the bar chart in the new sheet.

> ✅ **Expected Outcome:** A new sheet appears containing a bar chart that visually ranks the top five product features by their average cost of goods sold.

---

## Task Summary

In this task, you used **Microsoft Copilot in Excel** with **Edit with Copilot** to perform a complete COGS analysis of the EcoSmart product line. Specifically, you:

| Step | What You Did | Output |
|------|-------------|--------|
| 3 | Described dataset and identified data quality issues | Data quality report sheet |
| 4 | Found cost trends and patterns | COGS pattern analysis sheet |
| 5 | Detected anomalies and outliers | Outlier analysis sheet |
| 6 | Generated cost driver summary | Cost driver summary sheet |
| 7 | Created a bar chart | Top 5 cost drivers chart sheet |

These findings will be referenced in a future meeting with your Finance Manager (Robin Kline) to discuss supplier optimization and cost reduction strategies for the EcoSmart product line.

---

## Exercise Summary

You have completed **Exercise 1, Task 1**. You have demonstrated how Copilot in Excel can:
- Replace hours of manual data analysis with AI-powered insights.
- Automatically generate structured analysis across multiple sheets in a workbook.
- Produce management-ready visualizations from raw financial data.

---

*Previous Lab: [Lab-02 — Exercise 1 Overview](./Lab-02.test.md)*  
*Next Lab: [Lab-04 — Task 2: Use Copilot in Teams to Summarize Meeting Notes](./Lab-04.test.md)*
