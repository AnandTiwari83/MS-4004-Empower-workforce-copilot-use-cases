# Exercise 2, Task 1: Use Copilot in Loop to Track Construction Milestones

## Scenario

As the Operations Lead for Contoso’s regional distribution center expansion project, you are responsible for coordinating multiple teams, managing project dependencies, and ensuring the project remains on schedule.

The expansion project includes several phases, including site preparation, construction, inspections, equipment installation, and final handover. Because numerous stakeholders are involved—including construction crews, logistics teams, safety personnel, IT staff, vendors, and leadership—you need a centralized location to organize project information and track progress.

Microsoft Loop provides a collaborative workspace where project plans, risks, responsibilities, decisions, and changes can be documented and maintained. Using Copilot in Loop, you will create and populate several project management pages to help coordinate the expansion effort.

For this exercise, you will create the following pages within a Loop workspace:

* 1-Milestones and Timeline
* 2-RAID Log (Risk/Assumption/Issue/Dependency)
* 3-RACI Matrix (Roles and Responsibilities)
* 4-Decision Log and Change Log

## Lab Overview

In this hands-on lab, you will use Microsoft 365 Copilot in Loop to generate project management artifacts for a distribution center expansion project. You will create milestone plans, risk tracking logs, responsibility matrices, and decision/change tracking documentation.

By the end of this exercise, you will have a structured Loop workspace containing key project governance artifacts that can be shared with stakeholders and updated throughout the project lifecycle.

## Prerequisites

Before starting this exercise, ensure that:

* You have access to Microsoft 365.
* A Microsoft 365 Copilot license is assigned to your account.
* Microsoft Loop is enabled for your organization.
* You are signed in using the provided Microsoft 365 lab credentials.
* Internet connectivity is available.
* Microsoft 365 Copilot is enabled in Loop.

## Task 1: Create and Populate a Project Management Workspace Using Copilot in Loop

In this task, you will create a Loop workspace and use Copilot to generate project planning content across four pages.

### Steps

#### Create the Loop Workspace

1. Open **Microsoft Edge** and navigate to:

   ```text
   https://www.microsoft365.com
   ```

2. Sign in using your Microsoft 365 credentials.

3. In the left navigation pane, select **Apps**.

4. Select **Loop** from the available applications.

5. In **Loop for the web**, create a new workspace.

6. Name the workspace:

   ```text
   Distribution Center Expansion – Project Plan
   ```

7. Verify that the new workspace opens successfully.

---

#### Create the Milestones and Timeline Page

8. Locate the default page that is created within the workspace.

9. Change the page title from **Untitled** to:

   ```text
   1-Milestones and Timeline
   ```

10. Open the **Copilot** pane.

11. Enter the following prompt:

```text
I’m the Operations Lead overseeing Contoso’s distribution center expansion project in Fargo, ND. This project involves multiple construction phases, safety updates, vendor coordination, and inventory transitions. Please build a detailed project plan that outlines all major milestones for this expansion. Organize the plan into a table with columns for: Task Name, Bucket/Phase, Start Date, Due Date, Dependencies, Owner (role), and Checklist Items. Use logical buckets such as Site Prep, Construction, Facility Systems, Inspections, and Go-Live Readiness. Assume the project begins next Monday and spans 24 weeks. Return the plan as a Loop table I can edit.
```

12. Submit the prompt.

13. Review the generated project plan table.

14. Verify that the table includes:

    * Task Name
    * Bucket/Phase
    * Start Date
    * Due Date
    * Dependencies
    * Owner (role)
    * Checklist Items

15. During testing, Copilot may not directly insert the table into the Loop page.

16. Select the **Copy** icon below the generated table.

17. Return to the page and paste the copied content into the **1-Milestones and Timeline** page.

18. Remove any extraneous text that may have been copied along with the table.

19. Scroll horizontally to review all columns.

20. Leave the generated content unchanged for this exercise.

---

#### Create the RAID Log Page

21. Create a new page within the workspace.

22. Rename the page:

```text
2-RAID Log (Risk/Assumption/Issue/Dependency)
```

23. Open the Copilot pane.

24. Enter a prompt similar to:

```text
Create a RAID log table for a 24-week distribution center expansion project. Include top risks, assumptions, issues, and dependencies related to construction, safety, inventory movement, vendor coordination, and facility readiness. Include columns for Type, Title, Description, Impact, Probability, Owner, Target Date, Mitigation/Action, and Status. Include a short paragraph identifying critical path risks below the table.
```

25. Submit the prompt.

26. Review the generated RAID log.

27. Verify that the table includes:

    * Type
    * Title
    * Description
    * Impact
    * Probability
    * Owner
    * Target Date
    * Mitigation/Action
    * Status

28. Verify that a summary of critical path risks is included below the table.

29. Select the **Copy** icon.

30. Paste the content into the **2-RAID Log (Risk/Assumption/Issue/Dependency)** page.

31. Remove any unnecessary copied conversation text.

---

#### Create the RACI Matrix Page

32. Create another page within the workspace.

33. Rename the page:

```text
3-RACI Matrix (Roles and Responsibilities)
```

34. Open the Copilot pane.

35. Enter a prompt similar to:

```text
Build a RACI matrix for the following milestones: site preparation, foundation, framing, electrical, sprinkler testing, dock upgrades, inspection, equipment installation, and go-live readiness. Create a table where rows represent milestones and columns represent the following roles: Operations Lead, Construction Lead, Safety Manager, Logistics Coordinator, Finance, IT, and Vendor PM. Populate the matrix using R, A, C, and I values.
```

36. Submit the prompt.

37. Review the generated matrix.

38. Verify that:

    * Rows represent milestones.
    * Columns represent project roles.
    * Each cell contains a RACI designation.

39. Select the **Copy** icon.

40. Paste the content into the **3-RACI Matrix (Roles and Responsibilities)** page.

41. Remove any unnecessary copied text.

---

#### Create the Decision Log and Change Log Page

42. Create a final page within the workspace.

43. Rename the page:

```text
4-Decision Log and Change Log
```

44. Open the Copilot pane.

45. Enter a prompt similar to:

```text
Create a Decision Log table for a distribution center expansion project. Include columns for Decision, Requested By, Due Date, Options Considered, Final Decision, Rationale, Owner, and Follow-up Tasks.
```

46. Submit the prompt.

47. Review the generated Decision Log table.

48. Verify that all requested columns are included.

49. Select the **Copy** icon.

50. Paste the table into the **4-Decision Log and Change Log** page.

51. Remove any unnecessary copied conversation text.

52. Place the cursor below the Decision Log table.

53. Open the Copilot pane again.

54. Enter the following prompt:

```text
Create a Change Log table for tracking schedule, scope, cost, and quality changes for a distribution center expansion project. Include columns for Change Request, Category, Description, Impact Summary, Approval Needed, Status, Owner, and Effective Date.
```

55. Submit the prompt.

56. Review the generated Change Log table.

57. Verify that the table includes:

    * Change Request
    * Category
    * Description
    * Impact Summary
    * Approval Needed
    * Status
    * Owner
    * Effective Date

58. Select the **Copy** icon.

59. Paste the Change Log below the Decision Log table.

60. Remove any unnecessary copied text.

---

#### Preserve the Workspace for Later Use

61. Review all four pages within the workspace.

62. Verify that each page contains the expected content.

63. Ensure that the workspace remains open.

64. In a later exercise, you will share this workspace with project stakeholders.

65. Keep the **Distribution Center Expansion – Project Plan** workspace available so that you can copy its link when required.

### Expected Outcome

You successfully used Microsoft 365 Copilot in Loop to:

* Create a project management workspace.
* Generate a project milestone and timeline plan.
* Create a RAID log for project governance.
* Build a RACI matrix to define responsibilities.
* Create a Decision Log and Change Log.
* Organize project information into a collaborative workspace that can be maintained throughout the project lifecycle.

## Key Takeaways

By completing this exercise, you learned how to:

* Create and organize collaborative workspaces in Microsoft Loop.
* Use Copilot to generate editable project management tables.
* Track project milestones, risks, and dependencies.
* Define roles and responsibilities using a RACI matrix.
* Document project decisions and changes.
* Improve project coordination using Microsoft 365 Copilot and Loop.
