# Lab-06: Exercise 1, Task 4 — Use Copilot in Excel to Model What-If Scenarios

## Lab Overview

In this lab, you use **Microsoft Copilot in Excel** to model a series of **what-if financial scenarios** for the potential Relecloud acquisition. Your Finance Manager, Robin Kline, needs to understand how changes in key assumptions — such as valuation multiples, synergy savings, and operating expenses — would affect Fabrikam's projected returns. You will use Copilot to dynamically update the financial model and generate comparative charts that visualize the impact of each scenario.

**Estimated Duration:** 15 minutes  
**Difficulty Level:** 100 (Beginner)

---

## Learning Objectives

By the end of this lab, you will be able to:

- Use **Microsoft Copilot in Excel** with **Edit with Copilot** to perform dynamic financial scenario modeling.
- Apply multiple what-if scenarios to an acquisition financial model by adjusting valuation multiples, synergy savings timelines, and operating expenses.
- Generate comparative charts (column charts, line charts, stacked column charts) that visualize the financial impact of scenario changes.
- Interpret how changes in key assumptions affect EBITDA, cash flow, ROI, and net income.

---

## Prerequisites

- Completion of **Lab-01** (resource files uploaded to OneDrive).
- Completion of **Lab-05** (Relecloud acquisition analysis) is recommended for context.
- Familiarity with Excel for the web and the Edit with Copilot functionality (introduced in Lab-03).

---

## Background and Scenario

### The Request from Robin Kline

Your Finance Manager, Robin Kline, has asked you to update the **Relecloud Acquisition Financials** model to reflect new assumptions about the deal. Specifically, Robin wants you to:

1. **Update the acquisition numbers** based on a series of what-if scenarios that reflect different valuations and synergy outcomes.
2. **Create charts** that visualize the effect of these changes to support leadership discussions.

### Why What-If Modeling Matters

What-if analysis is one of the most valuable tools in a financial analyst's toolkit. It allows Finance teams to:
- Test the sensitivity of a financial model to changes in key assumptions.
- Prepare for best-case, worst-case, and most-likely scenarios before presenting recommendations.
- Support leadership in understanding the range of possible outcomes before committing to a major financial decision.

Copilot in Excel makes this process significantly faster by automatically recalculating models, creating new scenario sheets, and generating charts — tasks that would otherwise take hours of manual work.

---

## Exercise Overview

| Step | Scenario | Charts Generated |
|------|----------|-----------------|
| 3–4 | EBITDA multiple +1x and synergy savings +20% | Column chart + Line chart |
| 5–6 | Synergy savings delayed 12 months, only 75% realized | Stacked Column chart + Line chart |
| 7–8 | Operating expenses +10% due to integration challenges | Line chart + Column chart |

---

## Task Instructions

### Step 1: Download and Upload the Source File

1. Select the following link to download the source file:  
   [**Relecloud Acquisition Financials.xlsx**](https://go.microsoft.com/fwlink/?linkid=2347812)

2. Save the file to your **OneDrive** account.

---

### Step 2: Open the File in Excel and Enable Edit with Copilot

1. In Microsoft Edge, navigate to the **Microsoft 365 home page**: `https://www.microsoft365.com`

2. Select **Apps** → **Excel**.

3. In Excel for the web, select **Upload a file**, navigate to your OneDrive, and open the **Relecloud Acquisition Financials** spreadsheet.

4. Select **Copilot** on the **Home** tab ribbon.

5. In the Copilot pane:
   - Leave the response mode selector set to **Auto**.
   - Verify the **Edit with Copilot** icon (✏️) appears in the prompt field.
   - If not visible, select **(+)** → **Edit with Copilot**.

6. Verify you are in the **Financial Analysis** sheet before proceeding.

> ✅ **Checkpoint:** You are in the Financial Analysis sheet with Edit with Copilot active.

---

### Step 3: Scenario 1 — Increased EBITDA Multiple and Synergy Savings

Robin wants to see how the financial model changes if Fabrikam negotiates a better deal structure.

**Write and submit your own prompt** asking Copilot to:
- Perform a **what-if scenario** by updating the Relecloud acquisition financials to reflect:
  - A **1x increase** in the EBITDA multiple
  - A **20% increase** in synergy savings
- Return the results in a **new sheet**.

> 💡 **Guidance:** Use the Edit with Copilot mode to ensure changes are applied directly to a new worksheet. Specify both assumptions clearly in a single prompt.

**After Copilot responds:**
- Review the new what-if scenario sheet.
- Remain in this sheet for Step 4.

> ✅ **Expected Outcome:** A new sheet showing updated financial projections reflecting the increased EBITDA multiple and higher synergy savings.

---

### Step 4: Charts for Scenario 1

Now create visualizations to make the Scenario 1 impact easy to see and present.

**Write and submit your own prompt** asking Copilot to:
- Generate the following **two charts** in a new sheet based on the Scenario 1 results:
  - **Column Chart**: comparing original vs. updated EBITDA and total synergy savings over time.
  - **Line Chart**: showing EBITDA trend before and after the change.

**After Copilot responds:**
- Review both charts in the new sheet.
- Confirm that the column chart clearly shows the before/after comparison and the line chart shows the EBITDA trajectory.

> ✅ **Expected Outcome:** A new sheet with two charts visualizing the EBITDA and synergy savings impact of Scenario 1.

---

### Step 5: Scenario 2 — Delayed and Reduced Synergy Savings

One risk in any acquisition is that synergies take longer to realize than planned. Robin wants to model this risk explicitly.

1. Select the **Financial Analysis** sheet to return to the original dataset.

2. **Write and submit your own prompt** asking Copilot to:
   - Perform a **what-if scenario** that updates the acquisition financial model with the following assumptions:
     - Synergy savings are **delayed by 12 months**
     - Only **75% of synergy savings** are realized
   - Return the results in a **new sheet**.

**After Copilot responds:**
- Review the new scenario sheet showing the timing and reduction impacts.
- Remain in this sheet for Step 6.

> ✅ **Expected Outcome:** A new sheet modeling the acquisition financials with delayed and reduced synergy realization, showing reduced or shifted benefits compared to the baseline.

---

### Step 6: Charts for Scenario 2

**Write and submit your own prompt** asking Copilot to:
- Generate the following **two charts** in a new sheet that show both the **timing** and **reduction** in benefits, highlighting the impact on cash flow and ROI:
  - **Stacked Column Chart**: showing annual synergy savings (original vs. delayed/reduced).
  - **Line Chart**: showing cumulative synergy savings over time.

**After Copilot responds:**
- Review both charts to confirm they clearly show the delayed timing and reduced magnitude of synergy savings.

> ✅ **Expected Outcome:** A new sheet with a stacked column chart and line chart illustrating how the 12-month delay and 75% realization reduce and postpone the financial benefits.

---

### Step 7: Scenario 3 — Higher Operating Expenses Due to Integration Challenges

Integration activities often introduce unexpected costs. Robin wants to understand how Fabrikam's profitability would be affected if operating expenses rise during integration.

1. Select the **Financial Analysis** sheet to return to the baseline.

2. **Write and submit your own prompt** asking Copilot to:
   - Perform a **what-if scenario** that updates the financial model assuming:
     - **Operating expenses are 10% higher** due to integration challenges
   - Return the results in a **new sheet**.

**After Copilot responds:**
- Review the new scenario sheet.
- Remain in this sheet for Step 8.

> ✅ **Expected Outcome:** A new sheet showing updated financials with higher OpEx, and the resulting impact on EBITDA and net income compared to the baseline.

---

### Step 8: Charts for Scenario 3

**Write and submit your own prompt** asking Copilot to:
- Generate the following **two charts** in a new sheet that highlight the effect on profitability and expense trends:
  - **Line Chart**: for operating expenses and EBITDA over time (original vs. scenario).
  - **Column Chart**: comparing net income before and after the change.

**After Copilot responds:**
- Review both charts to confirm they clearly illustrate the profitability impact of increased integration costs.
- Feel free to explore any of Copilot's suggested follow-up prompts to further enhance the workbook.

> ✅ **Expected Outcome:** A new sheet with a line chart showing OpEx and EBITDA trajectories and a column chart comparing net income under the original and scenario assumptions.

---

## Task Summary

In this task, you used **Copilot in Excel with Edit with Copilot** to perform three distinct what-if scenarios for the Relecloud acquisition:

| Scenario | Assumption Changes | Output |
|----------|-------------------|--------|
| **Scenario 1** | EBITDA multiple +1x, synergy savings +20% | Updated financials + 2 charts |
| **Scenario 2** | Synergy savings delayed 12 months, only 75% realized | Updated financials + 2 charts |
| **Scenario 3** | Operating expenses +10% | Updated financials + 2 charts |

Each scenario produced a dedicated sheet with updated financial projections and a companion sheet with visualizations — giving leadership a clear, visual understanding of how changing assumptions affect the deal's financial attractiveness.

---

## Exercise 1 Summary

You have now completed all four tasks in **Exercise 1: Optimize Financial Reporting and Acquisition Modeling**. Across these four labs, you:

| Task | Tool | Outcome |
|------|------|---------|
| Task 1 (Lab-03) | Excel | Analyzed EcoSmart COGS data and identified cost drivers |
| Task 2 (Lab-04) | Teams / Copilot Chat | Summarized Finance meeting notes and generated action items |
| Task 3 (Lab-05) | Copilot Chat | Produced a comprehensive Relecloud acquisition analysis |
| Task 4 (Lab-06) | Excel | Modeled three what-if acquisition scenarios with charts |

Together, these tasks demonstrate how Copilot transforms an analyst's entire workday — from data validation and meeting follow-up, to acquisition due diligence and financial scenario modeling — enabling faster, higher-quality insights for leadership.

---

*Previous Lab: [Lab-05 — Task 3: Copilot Chat Acquisition Analysis](./Lab-05.test.md)*  
*Next Lab: [Lab-07 — Exercise 2 Overview: Streamline Contract Analysis and Negotiation](./Lab-07.test.md)*
