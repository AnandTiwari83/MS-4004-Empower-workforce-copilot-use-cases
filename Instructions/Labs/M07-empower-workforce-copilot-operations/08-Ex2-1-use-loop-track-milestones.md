# Exercise 2, Task 1: Use Copilot in Loop to Track Construction Milestones

As the Operations Lead for Contoso's regional distribution center expansion project, you are responsible for coordinating multiple teams, managing project dependencies, and ensuring the project remains on schedule.

The expansion project includes several phases — site preparation, construction, inspections, equipment installation, and final handover. Because numerous stakeholders are involved — including construction crews, logistics teams, safety personnel, IT staff, vendors, and leadership — you need a centralized location to organize project information and track progress.

Microsoft Loop provides a collaborative workspace where project plans, risks, responsibilities, decisions, and changes can be documented and maintained. Using Copilot in Loop, you will create and populate four project management pages to help coordinate the expansion effort:

- **1-Milestones and Timeline**
- **2-RAID Log** (Risk/Assumption/Issue/Dependency)
- **3-RACI Matrix** (Roles and Responsibilities)
- **4-Decision Log and Change Log**

## Lab Overview

In this hands-on lab, you will use **Microsoft 365 Copilot in Loop** to generate project management artifacts for the distribution center expansion. You will create milestone plans, risk tracking logs, responsibility matrices, and decision/change tracking documentation.

By the end of this task, you will have a structured Loop workspace containing key project governance artifacts that can be shared with stakeholders and updated throughout the project lifecycle.

## Steps

### Sign in and Create the Loop Workspace

1. In your **Microsoft Edge** browser, navigate to the Microsoft 365 home page:

    ```
    https://www.microsoft365.com
    ```

1. Enter the following credentials to sign in to Microsoft 365:

    - **Email/Username**: **<inject key="AzureAdUserEmail"></inject>**

    - **Password**: **<inject key="AzureAdUserPassword"></inject>**

1. In the Microsoft 365 portal, click on the **App launcher (1)** button and select **Loop (2)**.

    ![](../media/task-1/app-launcher-loop.png)

1. In **Loop for the web**, create a new workspace and name it:

    ```
    Distribution Center Expansion – Project Plan
    ```

    ![](../media/task-1/create-workspace.png)

### Page 1: Milestones and Timeline

1. Locate the default page created within the workspace. Change the page title from **Untitled** to:

    ```
    1-Milestones and Timeline
    ```

    ![](../media/task-1/milestones-page.png)

1. Open the **Copilot** pane and enter the following prompt:

    ```
    I'm the Operations Lead overseeing Contoso's distribution center expansion project in Fargo, ND. This project involves multiple construction phases, safety updates, vendor coordination, and inventory transitions. Please build a detailed project plan that outlines all major milestones for this expansion. Organize the plan into a table with columns for: Task Name, Bucket/Phase, Start Date, Due Date, Dependencies, Owner (role), and Checklist Items. Use logical buckets such as Site Prep, Construction, Facility Systems, Inspections, and Go-Live Readiness. Assume the project begins next Monday and spans 24 weeks. Return the plan as a Loop table I can edit.
    ```

    > **`Note:`** This prompt demonstrates an effective structure that includes role, context, objective, and desired output format. Use it as a model when creating prompts for the remaining pages in this task.

    ![](../media/task-1/milestones-prompt.png)

1. Review the generated project plan table and verify that it includes the following columns: **Task Name**, **Bucket/Phase**, **Start Date**, **Due Date**, **Dependencies**, **Owner (role)**, and **Checklist Items**.

    > **`Note:`** Copilot may not insert the table directly into the Loop page. If that happens, select the **Copy** icon below the generated table, paste the content into the **1-Milestones and Timeline** page, and delete any extraneous conversation text that was copied along with the table.

    ![](../media/task-1/milestones-table.png)

1. Scroll horizontally to review all columns. Leave the generated content as-is and proceed to the next page.

### Page 2: RAID Log

1. Add a new page within the workspace and rename it:

    ```
    2-RAID Log (Risk/Assumption/Issue/Dependency)
    ```

    ![](../media/task-1/raid-page.png)

1. Open the **Copilot** pane and enter a prompt asking Copilot to create a RAID log table for a 24-week distribution center expansion project. Your prompt should ask for risks, assumptions, issues, and dependencies related to construction, safety, inventory movement, vendor coordination, and facility readiness. Ask for the following columns: **Type**, **Title**, **Description**, **Impact**, **Probability**, **Owner**, **Target Date**, **Mitigation/Action**, and **Status**. Also ask for a short paragraph identifying critical path risks below the table.

    ![](../media/task-1/raid-prompt.png)

1. Review the generated RAID log. Verify that all requested columns are present and that a critical path risk summary appears below the table. Select the **Copy** icon, paste the content into the **2-RAID Log** page, and delete any extraneous text.

    ![](../media/task-1/raid-table.png)

### Page 3: RACI Matrix

1. Add a new page within the workspace and rename it:

    ```
    3-RACI Matrix (Roles and Responsibilities)
    ```

    ![](../media/task-1/raci-page.png)

1. Open the **Copilot** pane and enter a prompt asking Copilot to build a RACI matrix for the following milestones: **site preparation**, **foundation**, **framing**, **electrical**, **sprinkler testing**, **dock upgrades**, **inspection**, **equipment installation**, and **go-live readiness**. Ask for a table where rows represent milestones and columns represent the following roles: **Operations Lead**, **Construction Lead**, **Safety Manager**, **Logistics Coordinator**, **Finance**, **IT**, and **Vendor PM**. Ask Copilot to populate each cell using **R**, **A**, **C**, and **I** values.

    ![](../media/task-1/raci-prompt.png)

1. Review the generated matrix. Verify that rows represent milestones, columns represent project roles, and each cell contains a valid RACI designation. Select the **Copy** icon, paste the content into the **3-RACI Matrix** page, and delete any extraneous text.

    ![](../media/task-1/raci-table.png)

### Page 4: Decision Log and Change Log

1. Add a final page within the workspace and rename it:

    ```
    4-Decision Log and Change Log
    ```

    ![](../media/task-1/decision-page.png)

1. Open the **Copilot** pane and enter a prompt asking Copilot to create a **Decision Log table** for a distribution center expansion project with the following columns: **Decision**, **Requested By**, **Due Date**, **Options Considered**, **Final Decision**, **Rationale**, **Owner**, and **Follow-up Tasks**.

    ![](../media/task-1/decision-prompt.png)

1. Review the generated Decision Log table and verify that all requested columns are included. Select the **Copy** icon, paste the table into the **4-Decision Log and Change Log** page, and delete any extraneous text.

    ![](../media/task-1/decision-table.png)

1. Place your cursor **below the Decision Log table**. Open the **Copilot** pane again and enter a prompt asking Copilot to create a **Change Log table** for tracking schedule, scope, cost, and quality changes for a distribution center expansion project. Ask for the following columns: **Change Request**, **Category**, **Description**, **Impact Summary**, **Approval Needed**, **Status**, **Owner**, and **Effective Date**.

    ![](../media/task-1/change-prompt.png)

1. Review the generated Change Log table and verify that all requested columns are present. Select the **Copy** icon, paste the Change Log **below the Decision Log table**, and delete any extraneous text.

    ![](../media/task-1/change-table.png)

### Preserve the Workspace for Later Use

1. Review all four pages within the workspace and verify that each contains the expected content:

    - **1-Milestones and Timeline** — project plan table with phases and checklist items
    - **2-RAID Log** — risk/assumption/issue/dependency table with critical path summary
    - **3-RACI Matrix** — roles and responsibilities matrix across all milestones
    - **4-Decision Log and Change Log** — two tracking tables on a single page

    ![](../media/task-1/workspace-complete.png)

    > **`Note:`** Keep the **Distribution Center Expansion – Project Plan** workspace open. In a later task, you will share this workspace with project stakeholders and will need to copy its link.

1. You have now completed **Task 1**.

## Summary

In this task, you used **Microsoft 365 Copilot in Loop** to build a structured project management workspace for Contoso's distribution center expansion. You:

- Created the **Distribution Center Expansion – Project Plan** Loop workspace with four project governance pages.
- Generated a **Milestones and Timeline** table covering all major phases across 24 weeks.
- Created a **RAID Log** tracking risks, assumptions, issues, and dependencies with a critical path summary.
- Built a **RACI Matrix** defining roles and responsibilities across all key project milestones.
- Produced a **Decision Log and Change Log** to document project decisions and track scope, schedule, cost, and quality changes.

This workspace now serves as the central hub for project coordination and will be shared with stakeholders as the expansion progresses.

## Key Takeaways

By completing this task, you learned how to:

- Create and organize **collaborative workspaces** in Microsoft Loop.
- Use **Copilot in Loop** to generate editable project management tables from structured prompts.
- Track project milestones, risks, and dependencies using a **RAID Log**.
- Define roles and responsibilities across project phases using a **RACI Matrix**.
- Document decisions and changes using a **Decision Log and Change Log**.
- Improve project coordination and governance using Microsoft 365 Copilot and Loop.

## Support Contact

The **CloudLabs support** team is available 24/7, 365 days a year, via email and live chat to ensure seamless assistance at any time. We offer dedicated support channels tailored specifically for both learners and instructors, ensuring that all your needs are promptly and efficiently addressed.

Learner Support Contacts:

- Email Support: [cloudlabs-support@spektrasystems.com](mailto:cloudlabs-support@spektrasystems.com)
- Live Chat Support: https://cloudlabs.ai/labs-support

Click **Next** from the bottom right corner to proceed to the next task!

![](../media/task-1/next-button.png)