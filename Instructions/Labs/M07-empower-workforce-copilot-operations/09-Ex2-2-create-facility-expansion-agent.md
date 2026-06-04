# Exercise 2, Task 2: Use Copilot Studio to Build a Facility Expansion FAQ Agent

Contoso recently began construction on the Fargo Distribution Center Expansion project. Project milestones, risks, responsibilities, and operational activities are already being tracked in Microsoft Loop.

As the Operations Leader, you are receiving a growing number of questions from frontline employees, supervisors, logistics teams, safety coordinators, vendors, and leadership stakeholders. Many of these questions are repetitive and require consistent, approved responses. Examples include:

- Is Dock 3 open yet?
- What PPE is required in the new construction area?
- Which temporary evacuation route applies to the Packing area?
- When are inventory move waves scheduled?
- What vendor access restrictions are currently in place?

To provide accurate, consistent, and citation-based answers while reducing the burden on the Operations team, you will create a **Microsoft Copilot Studio agent** that serves as a centralized FAQ assistant for the Fargo expansion project. The agent will:

- Answer natural language questions using approved documentation.
- Provide citations and references to source content.
- Avoid speculation and unsupported answers.
- Redirect users when information is unavailable.
- Support frontline workers, supervisors, coordinators, and leadership teams.

## Lab Overview

In this hands-on lab, you will use the **Copilot Studio Agent Builder** to create a Facility Expansion FAQ Assistant. You will:

- Create and configure a new Copilot Studio agent.
- Define agent purpose, audience, and detailed operating instructions.
- Upload approved knowledge source documents.
- Generate and customize suggested prompts.
- Test the agent's responses against uploaded documentation.
- Publish the completed agent for use.

> **`Note:`** This task uses the Copilot Studio Agent Builder experience designed for business users. No coding or development experience is required.

## Prerequisites — Download Required Knowledge Files

Before starting this task, download the following files and save them to your **OneDrive** account. Verify all seven files are available in OneDrive before continuing.

| File |
|------|
| Contoso_Expansion_Project_Overview.docx |
| Contoso_Expansion_FAQ_Reference.docx |
| Contoso_Expansion_Knowledge_Pack.docx |
| Contoso_Inventory_Move_Schedule.xlsx |
| Contoso_Safety_Protocol_Updates.docx |
| Contoso_Temporary_Evacuation_Routes.docx |
| Contoso_Vendor_Access_and_Hours.docx |

## Steps

### Open Copilot Studio Agent Builder

1. In your **Microsoft Edge** browser, navigate to the Microsoft 365 home page:

    ```
    https://www.microsoft365.com
    ```

1. Enter the following credentials to sign in to Microsoft 365:

    - **Email/Username**: **<inject key="AzureAdUserEmail"></inject>**

    - **Password**: **<inject key="AzureAdUserPassword"></inject>**

1. In the left navigation pane, select **New agent** to open the **Agent Builder** experience.

    ![](../media/task-2/new-agent.png)

### Create the Facility Expansion FAQ Assistant

1. In the agent creation prompt field, enter the following request and select **Send**:

    ```
    Create an agent titled Facility Expansion FAQ Assistant. The purpose of this agent is to answer employee questions about Contoso's Fargo distribution center expansion, such as construction timelines, safety protocols, temporary evacuation routes, inventory move waves, vendor access requirements, and operational impacts—using only approved documents that are assigned to this agent as knowledge sources.
    ```

    ![](../media/task-2/create-agent-prompt.png)

1. Wait up to two minutes for Copilot Studio to generate the agent. In the **Agent Preview** pane, review the generated **Agent Name**, **Description**, and **Purpose**.

    ![](../media/task-2/agent-preview.png)

### Review and Enhance the Agent Configuration

1. Select the **Configure** tab and review the **Name**, **Description**, and **Instructions** fields. Scroll through the Instructions section to observe how Copilot translated the business description into detailed operating instructions.

    ![](../media/task-2/configure-tab.png)

    > **`Note:`** Copilot automatically converts natural language requirements into structured instructions, reducing the need to manually author detailed system prompts.

1. Return to the **Describe** tab and enter the following prompt to add guardrails and scope restrictions to the agent instructions:

    ```
    Update the Instructions to include the following items:

    - Don't speculate. If information is missing or ambiguous, flag the gap and provide a polite fallback response, such as: "I don't have a verified answer for that yet. Please check the Expansion Overview or contact Operations Intake."

    - Politely decline sensitive topics (for example, budget breakdowns or contracts) with: "I'm unable to share that information. Please contact the Project Controller."

    - Keep answers specific to the Fargo expansion and the current 24-week timeline.

    - Provide links/citations and highlight critical dates or zones in the response.
    ```

    ![](../media/task-2/enhance-instructions.png)

1. Select the **Configure** tab and verify the new guardrails, fallback messaging, citation requirements, and scope restrictions were added to the Instructions section.

    ![](../media/task-2/updated-instructions.png)

1. Return to the **Describe** tab and ask Copilot the following to further improve the agent:

    ```
    What additional instructions would you recommend to improve this agent?
    ```

    Review the recommendations. If the suggestions appear useful, submit the following prompt:

    ```
    Add all recommended improvements to the instructions.
    ```

    Return to the **Configure** tab and verify the instruction set has been updated with the additional best practices.

    ![](../media/task-2/additional-instructions.png)

### Configure Knowledge Sources

1. In the **Configure** tab, scroll to the **Knowledge** section. Verify that **Search all websites** is **disabled**. If the toggle is enabled, disable it.

    > **`Note:`** The agent should only answer using approved project documentation — not public web content.

    ![](../media/task-2/knowledge-section.png)

1. Select **Upload from device**, browse to your **OneDrive** location, and select all seven knowledge files downloaded in the prerequisites. Upload the files and wait for indexing to complete.

    ![](../media/task-2/upload-files.png)

### Generate and Add Suggested Prompts

1. Return to the **Describe** tab and enter the following prompt to generate starter prompts for the agent:

    ```
    Generate three suggested prompts for this agent.
    ```

    Review the generated prompts and note the **Title** and **Message** fields for each one.

    ![](../media/task-2/generated-prompts.png)

1. Select the **Configure** tab, scroll to the **Suggested prompts** section, and verify the Copilot-generated prompts are present. Select **Add a suggested prompt** and add two or three additional prompts from the following options:

    **Construction Timeline Check**
    - Title: `Construction Timeline Check`
    - Message: `What construction phase are we currently in for the Fargo distribution center expansion, and which areas of the building are affected this week?`

    **PPE & Safety Requirements**
    - Title: `PPE & Safety Requirements`
    - Message: `What PPE is required in the construction-adjacent zones, and do these requirements change during the 24-week expansion?`

    **Temporary Evacuation Route Guidance**
    - Title: `Temporary Evacuation Route Guidance`
    - Message: `What is the temporary evacuation route for the Packing area during the expansion, and where is the nearest assembly point?`

    **Inventory Move Wave Details**
    - Title: `Inventory Move Wave Details`
    - Message: `Which SKUs are included in the next inventory move wave, and what are the start and end dates for that wave?`

    **Vendor Access & Parking Instructions**
    - Title: `Vendor Access & Parking Instructions`
    - Message: `Where should vendors park during the expansion, and what are the temporary access hours and check-in rules?`

    **Operational Impacts Summary**
    - Title: `Operational Impacts Summary`
    - Message: `What operational impacts should staff expect over the next few weeks due to the ongoing construction and dock upgrades?`

    ![](../media/task-2/add-prompts.png)

### Test the Agent

1. Select several of the suggested prompts and review the responses generated by the agent. Verify that each response:

    - References the uploaded project documents.
    - Provides citations where available.
    - Remains within the Fargo expansion scope.
    - Does not speculate or use unapproved information.

    ![](../media/task-2/test-prompts.png)

1. Optionally, test the following custom prompts to further validate the agent's behavior:

    ```
    Is Dock 3 currently operational?
    ```

    ```
    What safety updates affect warehouse staff this month?
    ```

    ```
    When is the next inventory move wave scheduled?
    ```

    ![](../media/task-2/custom-prompts.png)

### Create and Publish the Agent

1. When testing is complete and you are satisfied with the agent's responses, select **Create** and wait for agent creation to finish.

    ![](../media/task-2/create-agent.png)

1. When the confirmation dialog appears, select **Go to agent** and review the completed Facility Expansion FAQ Assistant.

    ![](../media/task-2/agent-complete.png)

1. You have now completed **Task 2**.

## Summary

In this task, you used **Microsoft Copilot Studio** to build a business-focused FAQ agent for Contoso's Fargo distribution center expansion. You:

- Created the **Facility Expansion FAQ Assistant** using the Agent Builder experience.
- Configured detailed operating **instructions** including guardrails, fallback messaging, citation requirements, and scope restrictions.
- Enhanced the instruction set further using Copilot's own improvement recommendations.
- Restricted the agent to **approved knowledge sources** by uploading seven project documents and disabling web search.
- Generated and customized **suggested prompts** to improve agent usability for frontline staff, supervisors, and vendors.
- Tested the agent against uploaded documentation to validate citation-based, in-scope responses.
- Published the completed agent for organizational use.

## Key Takeaways

By completing this task, you learned how to:

- Create a **business-focused agent** using Copilot Studio Agent Builder — no coding required.
- Define agent behavior through **natural language instructions** and iterative prompt refinement.
- Restrict agent answers to **approved knowledge sources** to ensure accuracy and compliance.
- Upload and manage **enterprise knowledge documents** as agent knowledge bases.
- Build and customize **suggested prompts** that improve agent discoverability and usability.
- Test and validate agent responses before deployment to ensure quality and scope adherence.

## Support Contact

The **CloudLabs support** team is available 24/7, 365 days a year, via email and live chat to ensure seamless assistance at any time. We offer dedicated support channels tailored specifically for both learners and instructors, ensuring that all your needs are promptly and efficiently addressed.

Learner Support Contacts:

- Email Support: [cloudlabs-support@spektrasystems.com](mailto:cloudlabs-support@spektrasystems.com)
- Live Chat Support: https://cloudlabs.ai/labs-support

Click **Next** from the bottom right corner to proceed to the next task!

![](../media/task-2/next-button.png)