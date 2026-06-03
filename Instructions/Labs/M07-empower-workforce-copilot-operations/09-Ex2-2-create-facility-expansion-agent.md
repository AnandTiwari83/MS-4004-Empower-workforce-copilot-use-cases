# Exercise 2: Manage Facility Expansion Operations with Microsoft 365 Copilot

## Task 2: Use Copilot Studio to Build a Facility Expansion FAQ Agent

### Scenario

Contoso recently began construction on the Fargo Distribution Center Expansion project. Project milestones, risks, responsibilities, and operational activities are already being tracked in Microsoft Loop.

As the Operations Leader, you are receiving a growing number of questions from frontline employees, supervisors, logistics teams, safety coordinators, vendors, and leadership stakeholders. Many of these questions are repetitive and require consistent, approved responses.

Examples include:

* Is Dock 3 open yet?
* What PPE is required in the new construction area?
* Which temporary evacuation route applies to the Packing area?
* When are inventory move waves scheduled?
* What vendor access restrictions are currently in place?

To provide accurate, consistent, and citation-based answers while reducing the burden on the Operations team, you will create a Microsoft Copilot Studio agent that serves as a centralized FAQ assistant for the Fargo expansion project.

The agent will:

* Answer natural language questions using approved documentation.
* Provide citations and references to source content.
* Avoid speculation and unsupported answers.
* Redirect users when information is unavailable.
* Support frontline workers, supervisors, coordinators, and leadership teams.

---

## Lab Overview

In this task, you will use the Copilot Studio Agent Builder experience to create a Facility Expansion FAQ Assistant.

You will:

* Create a new Copilot Studio agent.
* Define agent purpose and audience.
* Configure detailed operational instructions.
* Upload approved knowledge source documents.
* Generate and customize suggested prompts.
* Test the agent's responses.
* Publish the completed agent for personal use.

> **Note**
>
> This exercise uses the Copilot Studio Agent Builder experience designed for business users. No coding or development experience is required.

---

## Prerequisites

Before starting this task, ensure:

* You have access to Microsoft 365 Copilot and Copilot Studio.
* You can access Microsoft 365 through a supported browser such as Microsoft Edge.
* You have access to OneDrive.
* You are signed in with an account licensed for Microsoft 365 Copilot.
* Internet connectivity is available.

### Download Required Knowledge Files

Download the following files and save them to your OneDrive account:

| File                                     |
| ---------------------------------------- |
| Contoso_Expansion_Project_Overview.docx  |
| Contoso_Expansion_FAQ_Reference.docx     |
| Contoso_Expansion_Knowledge_Pack.docx    |
| Contoso_Inventory_Move_Schedule.xlsx     |
| Contoso_Safety_Protocol_Updates.docx     |
| Contoso_Temporary_Evacuation_Routes.docx |
| Contoso_Vendor_Access_and_Hours.docx     |

Verify all seven files are available in OneDrive before continuing.

---

## Steps

### Step 1: Open Copilot Studio Agent Builder

1. Open Microsoft Edge.

2. Navigate to:

   ```text
   https://www.microsoft365.com
   ```

3. Sign in using your Microsoft 365 credentials.

4. In the left navigation pane, select **New agent**.

5. Verify that the **Agent Builder** experience opens and displays the **New Agent** page.

---

### Step 2: Create the Facility Expansion FAQ Assistant

1. In the agent creation prompt, enter the following request:

   ```text
   Create an agent titled Facility Expansion FAQ Assistant. The purpose of this agent is to answer employee questions about Contoso’s Fargo distribution center expansion, such as construction timelines, safety protocols, temporary evacuation routes, inventory move waves, vendor access requirements, and operational impacts—using only approved documents that are assigned to this agent as knowledge sources.
   ```

2. Select the **Send** icon.

3. Wait for Copilot Studio to generate the agent.

4. Observe the following information in the Agent Preview pane:

   * Agent Name
   * Description
   * Purpose

5. Allow up to two minutes for generation to complete.

### Expected Outcome

A new agent named **Facility Expansion FAQ Assistant** is created and displayed in the Agent Builder.

---

### Step 3: Review the Generated Agent Configuration

1. Select the **Configure** tab.

2. Review the following fields:

   * Name
   * Description
   * Instructions

3. Scroll through the generated Instructions section.

4. Observe how Copilot translated the business description into detailed operating instructions.

> **Important**
>
> Copilot automatically converts natural language requirements into structured instructions, reducing the need to manually author detailed system prompts.

### Expected Outcome

The agent contains automatically generated instructions aligned to the Fargo expansion project.

---

### Step 4: Enhance Agent Instructions

1. Return to the **Describe** tab.

2. Enter the following prompt:

   ```text
   Update the Instructions to include the following items:

   - Don’t speculate. If information is missing or ambiguous, flag the gap and provide a polite fallback response, such as: “I don’t have a verified answer for that yet. Please check the Expansion Overview or contact Operations Intake.”

   - Politely decline sensitive topics (for example, budget breakdowns or contracts) with: “I’m unable to share that information. Please contact the Project Controller.”

   - Keep answers specific to the Fargo expansion and the current 24-week timeline.

   - Provide links/citations and highlight critical dates or zones in the response.
   ```

3. Submit the prompt.

4. Review Copilot's response.

5. Select the **Configure** tab.

6. Verify that the new instructions were added successfully.

### Expected Outcome

The agent now includes guardrails, fallback messaging, citation requirements, and scope restrictions.

---

### Step 5: Improve the Agent Further

1. Return to the **Describe** tab.

2. Ask Copilot:

   ```text
   What additional instructions would you recommend to improve this agent?
   ```

3. Review the recommendations.

4. If the suggestions appear useful, ask Copilot:

   ```text
   Add all recommended improvements to the instructions.
   ```

5. Wait for confirmation.

6. Return to the **Configure** tab.

7. Review the updated Instructions section.

### Expected Outcome

The instruction set is enhanced with additional best practices recommended by Copilot.

---

### Step 6: Configure Knowledge Sources

1. In the **Configure** tab, scroll to the **Knowledge** section.

2. Verify that **Search all websites** is disabled.

> **Note**
>
> The agent should only answer using approved project documentation.

3. If the toggle is enabled, disable it.

4. Select **Upload from device**.

5. Browse to your OneDrive location.

6. Select all seven previously downloaded files.

7. Upload the files.

8. Wait for indexing to complete.

### Expected Outcome

All project documents are attached as approved knowledge sources.

---

### Step 7: Generate Suggested Prompts with Copilot

1. Return to the **Describe** tab.

2. Enter the following request:

   ```text
   Generate three suggested prompts for this agent.
   ```

3. Submit the prompt.

4. Review the generated prompts.

5. Note the following components for each prompt:

   * Title
   * Message

### Expected Outcome

Copilot generates starter prompts relevant to facility expansion activities.

---

### Step 8: Add Additional Suggested Prompts

1. Select the **Configure** tab.

2. Scroll to the **Suggested prompts** section.

3. Verify that the Copilot-generated prompts are present.

4. Select **Add a suggested prompt**.

5. Add two or three additional prompts from the following examples.

#### Construction Timeline Check

**Title**

```text
Construction Timeline Check
```

**Message**

```text
What construction phase are we currently in for the Fargo distribution center expansion, and which areas of the building are affected this week?
```

#### PPE & Safety Requirements

**Title**

```text
PPE & Safety Requirements
```

**Message**

```text
What PPE is required in the construction-adjacent zones, and do these requirements change during the 24-week expansion?
```

#### Temporary Evacuation Route Guidance

**Title**

```text
Temporary Evacuation Route Guidance
```

**Message**

```text
What is the temporary evacuation route for the Packing area during the expansion, and where is the nearest assembly point?
```

#### Inventory Move Wave Details

**Title**

```text
Inventory Move Wave Details
```

**Message**

```text
Which SKUs are included in the next inventory move wave, and what are the start and end dates for that wave?
```

#### Vendor Access & Parking Instructions

**Title**

```text
Vendor Access & Parking Instructions
```

**Message**

```text
Where should vendors park during the expansion, and what are the temporary access hours and check-in rules?
```

#### Operational Impacts Summary

**Title**

```text
Operational Impacts Summary
```

**Message**

```text
What operational impacts should staff expect over the next few weeks due to the ongoing construction and dock upgrades?
```

### Expected Outcome

The agent contains both Copilot-generated and manually created starter prompts.

---

### Step 9: Test the Agent

1. Select several suggested prompts.

2. Review the responses generated by the agent.

3. Verify that responses:

   * Reference uploaded documents.
   * Provide citations when available.
   * Remain within the Fargo expansion scope.
   * Do not speculate.
   * Use approved information sources.

4. Optionally test additional custom prompts such as:

   ```text
   Is Dock 3 currently operational?
   ```

   ```text
   What safety updates affect warehouse staff this month?
   ```

   ```text
   When is the next inventory move wave scheduled?
   ```

### Expected Outcome

The agent answers questions using information from the uploaded knowledge sources and includes supporting references.

---

### Step 10: Create the Agent

1. When testing is complete, select **Create**.

2. Wait for agent creation to finish.

3. When the confirmation dialog appears, select:

   ```text
   Go to agent
   ```

4. Review the completed agent.

### Expected Outcome

The Facility Expansion FAQ Assistant is successfully created and available for use.

---

## Key Takeaways

By completing this task, you learned how to:

* Create a business-focused agent using Copilot Studio.
* Define agent behavior through natural language instructions.
* Enhance agent responses using guardrails and fallback guidance.
* Restrict answers to approved knowledge sources.
* Upload and manage enterprise knowledge documents.
* Create suggested prompts that improve usability.
* Test and validate agent responses before deployment.
* Build a scalable FAQ solution that reduces operational support requests.

This version is ready to paste directly into a GitHub `.md` file and matches the style and structure used in Microsoft Learn hands-on labs.
