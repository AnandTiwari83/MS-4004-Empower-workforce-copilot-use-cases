# Exercise 2, Task 2: Use Copilot Studio to build a Facility Expansion FAQ agent

Contoso recently began construction on the Fargo distribution center expansion project. As the Operations Lead, you're receiving a growing number of questions from frontline employees, supervisors, logistics teams, safety coordinators, vendors, and leadership stakeholders.

Many of these questions are repetitive and operational in nature, such as:

- Is Dock 3 open yet?
- Which temporary evacuation routes apply to Packing?
- When do CHAI-12 and COFF-08 move?
- What PPE is required in the new wing?

To provide accurate, consistent, citation-based answers while reducing the burden on the Operations team, you'll use **Copilot Studio** to build a **Facility Expansion FAQ Assistant**.

This agent should:

- Answer natural-language questions about the expansion using approved documents.
- Show citations and references so users can verify details.
- Use guardrails and avoid speculation.
- Provide fallback guidance when information is missing.

> **`Note:`** This task uses the Copilot Studio lite experience, which is designed for business users and doesn't require coding.

## Steps

1. Select each of the following links to download their respective files and store them in your **OneDrive** account:

    - [**Contoso_Expansion_Project_Overview.docx**](https://go.microsoft.com/fwlink/?linkid=2347809)
    - [**Contoso_Expansion_FAQ_Reference.docx**](https://go.microsoft.com/fwlink/?linkid=2347517)
    - [**Contoso_Expansion_Knowledge_Pack.docx**](https://go.microsoft.com/fwlink/?linkid=2347808)
    - [**Contoso_Inventory_Move_Schedule.xlsx**](https://go.microsoft.com/fwlink/?linkid=2347519)
    - [**Contoso_Safety_Protocol_Updates.docx**](https://go.microsoft.com/fwlink/?linkid=2347520)
    - [**Contoso_Temporary_Evacuation_Routes.docx**](https://go.microsoft.com/fwlink/?linkid=2347611)
    - [**Contoso_Vendor_Access_and_Hours.docx**](https://go.microsoft.com/fwlink/?linkid=2347521)

1. Open a new tab in your **Microsoft Edge** browser and navigate to the Microsoft 365 home page:

    ```
    https://www.microsoft365.com
    ```

1. In Microsoft 365, select **New agent** in the navigation pane. Doing so opens Copilot Studio's **Agent Builder**.

1. In the prompt field, ask Copilot to create an agent using the following prompt:

    ```
    Create an agent titled Facility Expansion FAQ Assistant. The purpose of this agent is to answer employee questions about Contoso's Fargo distribution center expansion, such as construction timelines, inventory move schedules, temporary evacuation routes, safety requirements, and vendor access rules. The target audience includes frontline staff, supervisors, coordinators, and leadership. The agent should answer questions using approved files, provide citations, avoid speculation, and stay within the Fargo expansion scope.
    ```

    ![](./media/create-agent-prompt.png)

1. Wait while Copilot creates the agent. Review the generated **Agent Name**, **Description**, and **Purpose** in the preview pane.

    ![](./media/agent-preview.png)

1. Select the **Configure** tab and review the generated **Instructions**.

    ![](./media/configure-tab.png)

1. Return to the **Describe** tab and ask Copilot to update the instructions by adding the following items:

    - Don't speculate. If information is missing or ambiguous, flag the gap and provide a fallback response.
    - Politely decline sensitive topics such as budget breakdowns or contract terms.
    - Keep answers specific to the Fargo expansion and the current 24-week timeline.
    - Provide citations and highlight critical dates or zones in the response.

    ```
    Update the Copilot instructions with the following guidance:

    * Do not speculate. If information is missing, incomplete, or ambiguous, clearly identify the gap and provide an appropriate fallback response.
    * Politely decline requests involving sensitive information, including budget breakdowns, financial details, or contract terms.
    * Keep all responses focused on the Fargo Distribution Center Expansion Project and the current 24-week project timeline.
    * Provide citations whenever possible and highlight critical dates, milestones, inspection deadlines, and operational zones that may impact project execution.
    * Ensure responses are accurate, concise, and aligned with available project documentation.
    ```

1. Review the updated instructions in the **Configure** tab.

    ![](./media/updated-instructions.png)

1. In the **Describe** tab, ask Copilot what additional instructions it recommends to improve the agent. If you like the recommendations, ask Copilot to add them.

    ```
    Review the current agent instructions and recommend additional guidance that would improve the quality, accuracy, and consistency of responses for the Fargo Distribution Center Expansion Project. Focus on areas such as risk identification, mileston tracking, issue escalation, schedule impacts, response formatting, source validation, and stakeholder communication. If the recommendations are appropriate, incorporate them into the agent instructions and provide a summary of the changes made.
    ```

1. In the **Configure** tab, scroll to the **Knowledge** section and verify that **Search all websites** is disabled.

    ![](./media/knowledge-section.png)

1. In the **Knowledge** section, select **Upload from onedrive** and upload all seven files that mention earlier on the lab guide.

1. Return to the **Describe** tab and ask Copilot to generate three suggested prompts for the agent.

    ```
    Generate three suggested prompts for this agent.
    ```

    ![](./media/add-prompts.png)

1. In the **Configure** tab, review the suggested prompts. Add two or three more prompts manually from the examples provided in the lab.

1. Test several of the suggested prompts and review the responses. Verify that the agent references the uploaded files and stays within scope.

1. When you're satisfied with the configuration and test results, select **Create**.

    ![](./media/create-agent.png)

1. When the confirmation dialog appears, select **Go to agent**.

    ![](./media/agent-complete.png)

1. You have now completed **Task 2**. Click **Next** to proceed to the next task.

## Summary

In this task, you used **Microsoft Copilot Studio** to build a Facility Expansion FAQ Assistant for Contoso's Fargo distribution center expansion. You:

- Created the agent using natural language.
- Reviewed and refined the agent instructions.
- Added scope controls and fallback guidance.
- Uploaded approved knowledge source documents.
- Generated and customized suggested prompts.
- Tested the agent's responses.
- Created the final agent.

The agent can now be used to answer common operational questions in a consistent, citation-based way.

## Support Contact

The **CloudLabs support** team is available 24/7, 365 days a year, via email and live chat to ensure seamless assistance at any time. We offer dedicated support channels tailored specifically for both technical and training-related queries.

Learner Support Contacts:

- Email Support: [cloudlabs-support@spektrasystems.com](mailto:cloudlabs-support@spektrasystems.com)
- Live Chat Support: https://cloudlabs.ai/labs-support

Click **Next** from the bottom right corner to proceed to the next task!

![](./media/next-button.png)
