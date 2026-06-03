# Exercise 1, Task 2: Use Copilot in Teams to prepare for a client support meeting

## Overview

As part of Lamna Healthcare Company’s initiative to improve support efficiency, you must prepare for a strategic sync with your Support Leadership team. The topic of discussion is the recent uptick in issues coming from Trey Research, one of Lamna’s oldest and most valuable customers.

Trey Research is a medical research organization that conducts multi‑site clinical studies and patient trials. Their coordinators rely heavily on Lamna Healthcare Company’s scheduling and participant‑tracking platform to manage study visits, monitor participant registrations, and ensure accurate data capture across research sites.

Trey Research's Customer Service department reported a pattern of appointment‑sync failures, intermittent patient‑record delays, and inconsistencies in how its support teams communicate next steps. Before you meet with leadership, you want to assemble a clear understanding of the situation:

- What issues has Trey Research reported?
- What themes or patterns are emerging?
- What actions were taken, and which ones are still unresolved?
- What recommendations should be discussed in the meeting?

In a real-world setting, you would rely on historical emails, chats, support tickets, or meeting notes. However, since the training environment uses your own Microsoft 365 tenant rather than a lab tenant with demo data, there’s no lab data for Copilot to analyze involving Lamna and Trey Research. Therefore, to support this exercise, four realistic scenario files containing sample communications, summaries, and data related to Lamna and Trey Research are provided:

- **TreyResearch_EmailThread.docx**. A short email chain between clinic staff and Lamna support.

- **TreyResearch_MeetingNotes.docx**. Notes from an internal support-team discussion on recent Trey Research escalations.

- **TreyResearch_TicketSummary.xlsx**. A small dataset of support tickets with issue types and resolution times.

- **TreyResearch_ChatLog.txt**. A faux chat-log summary of internal troubleshooting discussion.

When you upload these files into your OneDrive, Copilot can analyze them as if they were part of your organization’s data. This alternative lets you learn how a Customer Service Manager can prepare for a meeting using Copilot, without requiring any real tenant messages or personal inbox data.

Perform the following steps to complete this task:

1.  Select the following links to download all the documents that contain sample communications, summaries, and data related to Lamna and Trey Research:

    - [**TreyResearch_EmailThread.docx**](https://go.microsoft.com/fwlink/?linkid=2347621)
    - [**TreyResearch_MeetingNotes.docx**](https://go.microsoft.com/fwlink/?linkid=2347815)
    - [**TreyResearch_TicketSummary.xlsx**](https://go.microsoft.com/fwlink/?linkid=2347525)

    - [**TreyResearch_ChatLog.txt**](https://go.microsoft.com/fwlink/?linkid=2347814) - Copy the contents of this file and save it in the OneDrive in your Lab VM, so that later we can attach the file in Copilot.

    > **Note:** To copy the links, right-click on each link and select "Copy link address," then paste the link into a new browser tab inside your Lab VM.

    > **Note:** If the links do not download automatically, it will open the document in browser, click on the Download button in the browser to download the file.

    Store these files in your OneDrive folder.

2.  In your Microsoft Edge browser, go to the **Microsoft 365** home page, selecy the **App launcher (1)** and select **Teams (2)**.

    ![](../media/module-9/E1T2S2-0306.png) 

3.  In **Teams for the web**, select **Copilot** in the left navigation pane. Doing so opens the Microsoft 365 Copilot Chat experience inside Teams.

4.  In a real-world scenario, you would now ask Copilot in Teams to analyze email and chat messages regarding a specific topic. Since we don’t have a lab tenant with demo data, we’re going to simulate the email and chat messages through the four files that you downloaded earlier. So in the Copilot prompt field, attach the four files **(1)** that you downloaded at the start of this task. Then ask Copilot **(2)** to analyze the attached files and summarize the key issues, themes, trends, and concerns raised by Trey Research.

    Use the following prompt:

    ```
    Analyze the attached files and provide a summary of the key issues, recurring themes, trends, customer concerns, and unresolved items reported by Trey Research. Highlight any patterns that appear across multiple files.
    ```

      ![](../media/module-9/E1T2S4-0306.png) 

5.  Review Copilot’s generated summary. Note any performance trends, repeated issues across files, and operational gaps or delays. If Copilot recommends any next steps that it can provide through suggested prompts, feel free to engage with it through those prompts.

6.  Next, ask Copilot to list the top three recurring issues affecting Trey Research, based on the files.

    ```
    Based on the attached files, what are the top three recurring issues affecting Trey Research? Explain why each issue is significant and how frequently it appears across the available information.
    ```

7.  Once Copilot responds with these issues, then ask it what it feels should be the highest‑priority items for Lamna’s upcoming leadership sync given these top three recurring issues.

    ```
    Given these top three recurring issues, what should be the highest-priority discussion items for Lamna Healthcare Company's upcoming support leadership sync? Explain the business impact of each priority.
    ```

8.  You want to further refine your preparation for the leadership sync. Ask Copilot to provide recommended next steps for each priority item and identify which internal teams should be involved in each action.

    ```
    For each priority item, recommend next steps to address the issue and identify the internal teams or stakeholders that should be involved in implementing the solution.
    ```

9.  You now want to transform Copilot’s insights into meeting‑ready content. To do so, ask Copilot to draft a meeting agenda for a support‑leadership sync focused on resolving these Trey Research issues. Ask it to write the agenda in a concise, executive‑friendly format.

    ```
    Create a concise executive-level meeting agenda for a support leadership sync focused on addressing Trey Research's recurring issues, reviewing current actions, discussing unresolved concerns, and planning next steps.
    ```

10.  Copy the final summary, action items, and agenda into a Word planning document and save it to your OneDrive and give it a name as `TreyResearch_LeadershipSync_Preparation.docx`.

      > **Note:** You can open Word for Web from the Microsoft 365 portal Apps section and save it in your OneDrive. 

      > **Note:** To save the word file, in the Word for Web after pasting the content, clikc on **File > Create a Copy > Create a copy online**, and save it to your OneDrive. 

## Summary

In this task, you used Microsoft 365 Copilot in Teams to analyze customer communications, support tickets, meeting notes, and troubleshooting discussions related to Trey Research. You identified recurring issues, evaluated business priorities, generated recommended actions and stakeholders, and created an executive-ready meeting agenda to support leadership decision-making and improve customer support outcomes.