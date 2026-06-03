# Exercise 1, Task 4: Use the Copilot Analyst agent to analyze customer support data

## Overview

Lamna Healthcare Company has been assisting Trey Research, a medical research organization running multi‑site clinical trials. Over the past 90 days, Lamna’s Support team recorded a surge of issues reported by Trey Research—ranging from appointment sync delays and Electronic Health Record (EHR) synchronization update lags to intermittent sync failures and slow module loads in Scheduling and EHR‑Sync components. Lamna’s Leadership team needs clear, data‑driven insight into what’s happening so they can prioritize fixes, coordinate with Engineering and Product, and prevent disruption to trial operations.

As Lamna’s Customer Service Manager, you plan to use Copilot’s Analyst agent to analyze Trey Research’s dataset, identify patterns in Trey Research’s 90‑day case history, and generate the most meaningful visuals.

Perform the following steps to complete this task:

1.  Select the following link to download the [**TreyResearch_Support_Cases.xlsx**](https://go.microsoft.com/fwlink/?linkid=2347816) file and then store it in your OneDrive account so that Copilot can access it from your tenant.

    > **Note:** To copy the link, right-click on the link and select "Copy link address," then paste the link into a new browser tab inside your Lab VM.

    > **Note:** If the link do not download automatically, it will open the document in browser, click on the Download button in the browser to download the file. 
    
3.  In your Microsoft Edge browser, go to the **Microsoft 365** home page and select the **Analyst** agent in the navigation pane.

      ![](../media/module-9/E1T4S2-0306.png) 

4.  In the **Analyst** agent, attach the **TreyResearch_Support_Cases.xlsx** **(1)** spreadsheet. Then ask the agent to analyze the attached dataset and produce a concise briefing that includes: top issue categories, severity mix, modules most impacted, escalation rate, and resolution-time distribution.

    Use the following prompt **(2)**:

    ```
    Analyze the attached dataset and create a concise executive briefing. Include the top issue categories, severity distribution, most impacted product modules, escalation rate, resolution-time distribution, and any notable trends or patterns observed in the data.
    ```

      ![](../media/module-9/E1T4S3-0306.png)

5.  Review the results. Everything looks good, so ask the agent to test correlations between Severity and escalation rate, and between Module and average resolution hours. Generate the three visuals that would communicate these findings most clearly.

    Use the following prompt: 

    ```
    Using the attached dataset, analyze the relationship between Severity and escalation rate, and between Module and average resolution hours. Generate the three most effective charts or visuals to communicate these findings and provide a brief explanation of each.
    ```

6.  Review the visuals. The agent might provide a suggested prompt asking if you want it to combine the three visuals into one dashboard-style summary image for easy presentation. Select and submit this prompt. If the agent doesn’t display this prompt in your lab, then manually enter this request.

    ```
    Combine the three visuals into a single dashboard-style summary that can be easily shared with leadership. Organize the charts clearly and include descriptive titles for each section.
    ```

7.  You really like this one-page summary. If the agent provides a suggested prompt to add annotations and key insights directly on this dashboard, then select and submit this prompt. If the agent doesn’t display this prompt in your lab, then manually enter this request.

    ```
    Add annotations and key insights directly to the dashboard. Highlight important trends, significant correlations, operational risks, and recommended focus areas that leadership should review.
    ```

8.  Review the updated summary that includes the annotations and key insights. If the agent provides a suggested prompt to create a presentation-ready version with a summary text panel alongside the charts, then select and submit this prompt. If the agent doesn’t display this prompt in your lab, then manually enter this request.

    ```
    Create a presentation-ready version of the dashboard that includes a concise executive summary panel alongside the charts. Ensure the content is suitable for a leadership review meeting and focuses on actionable insights.
    ```

9.  After the agent generates this presentation-ready version, it might ask if you want it to export this image as a PowerPoint slide (PPTX) for direct use in presentations. If you get a suggested prompt with this question, then select and submit it. Otherwise, manually enter this request.

    ```
    Export this presentation-ready dashboard as a PowerPoint slide (PPTX) that can be used directly in leadership presentations.
    ```

10. Select the link the agent provided to download the generated slide. Open the file once the download is complete and review the slide.

## Summary

In this task, you used the Copilot Analyst agent to analyze Trey Research’s 90-day customer support dataset. You identified key issue categories, severity trends, impacted product modules, escalation patterns, and resolution-time metrics. Using Copilot’s analytical capabilities, you explored correlations within the data, generated meaningful visualizations, consolidated them into a leadership dashboard, and created a presentation-ready report to support data-driven decision-making and service improvement initiatives.
