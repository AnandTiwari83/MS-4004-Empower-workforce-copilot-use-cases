# Exercise 1, Task 2: Use Copilot in Word to compare operational reports

As the Operations Manager at Adatum Corporation, you discovered that the current boiler system that heats the company's 50-year-old office building needs significant repair and may need to be replaced altogether. To support a recommendation to leadership, you need to create a report comparing boiler and furnace systems using publicly available information.

Since you want to create a report based on public web data related to heating systems, Microsoft Word is a natural place to work. Copilot in Word can help generate the initial report, revise it for a specific audience, and summarize findings in chat mode. This task also demonstrates the difference between using **Edit with Copilot** and using Copilot as a chat-based research assistant.

## Using Copilot in Word

Copilot in Word can behave in two different ways, depending on whether **Edit with Copilot** is enabled.

- When **Edit with Copilot** is enabled, Copilot can act like an in-document author and editor. It can create a document from scratch, revise content directly in the document, and help refine tone, structure, and clarity.

- When **Edit with Copilot** is disabled, Copilot behaves more like Copilot Chat. It can still research, summarize, and draft content, but it doesn't automatically update the document.

In this task, you'll use both approaches so you can see how Copilot's behavior changes and when each experience is most useful.

## Steps

1. In your **Microsoft Edge** browser, navigate to the Microsoft 365 home page:

    ```
    https://www.microsoft365.com
    ```

1. Enter the following credentials to sign in to Microsoft 365:

    - **Email/Username**: **<inject key="AzureAdUserEmail"></inject>**

    - **Password**: **<inject key="AzureAdUserPassword"></inject>**

1. In the Microsoft 365 portal, click on the **App launcher** button and select **Word**.

1. In **Word for the web**, select **Blank document**.

1. On the **Home** tab, select **Copilot** to open the Copilot pane. Verify the **Edit with Copilot** icon appears in the prompt field next to the plus (+) icon.

1. In the Copilot prompt field, enter a prompt that tells Copilot you're the Operations Manager for Adatum Corporation and that you're evaluating whether to replace the building's existing boiler system with a furnace system. Ask Copilot to generate a report based on publicly available information that includes:

    - An overview of each system, including energy efficiency considerations, maintenance requirements, and a high-level cost comparison.
    - Considerations when changing from an existing boiler system to a furnace system.
    - The average cost of transitioning from a boiler system to a furnace system in a commercial two-story building built in the 1970s.
    - Whether changing from a boiler system to a furnace system could affect the current air conditioning system.
    - Average defect rates or reliability considerations for boiler systems versus furnace systems.

    ![](./media/generate-report.png)

1. Review the report that Copilot generates directly in the document. Note the level of detail provided in each of the requested areas.

1. In the Copilot prompt field, ask Copilot to revise the report so it's more suitable for a **C-suite executive audience**.

    ```
    Revise this report to make it suitable for a C-suite executive audience.
    ```

    ![](./media/revise-prompt.png)

1. Review the updated report. Notice how Copilot applies the revisions directly to the document without requiring you to copy and paste the content manually.

1. Now disable **Edit with Copilot** by selecting the edit icon in the prompt field. Verify that the icon disappears.

    ![](./media/disable-edit.png)

    > **`Note:`** When **Edit with Copilot** is disabled, Copilot works in chat mode. It can still respond to prompts, but it no longer updates the document automatically.

1. In the Copilot prompt field, enter the following prompt:

    ```
    Summarize the key differences between boiler systems and furnace systems for commercial buildings. Focus on efficiency, maintenance, lifespan, and typical use cases.
    ```

    ![](./media/chat-prompt.png)

1. Review the response in the Copilot pane. Notice that the document itself remains unchanged because Copilot responded in chat mode only.

1. Below the Copilot response, review the available options. Select the **More actions (...)** menu and choose **Export to Word**.

    ![](./media/export-to-word.png)

1. Observe that Word for the web opens the exported content in a **new browser tab**. Review the exported document.

    ![](./media/exported-document.png)

    > **`Note:`** The exported document may include extra Copilot conversation text before or after the generated summary. Remove any unnecessary text that isn't part of the summary itself.

1. Compare the exported summary with the original report generated using **Edit with Copilot**. Consider how the two Copilot experiences - in-document editing and chat-based research - support different working styles.

1. You have now completed **Task 2**. Click **Next** to proceed to the next task.

## Summary

In this task, you used **Microsoft 365 Copilot in Word** to evaluate heating system options for Adatum Corporation's office building. You:

- Generated a boiler versus furnace comparison report using **Edit with Copilot**.
- Revised the report for a **C-suite executive audience** with Copilot applying the changes directly in the document.
- Disabled **Edit with Copilot** and used Copilot in **chat mode** to generate a focused summary.
- Exported the chat response to a new Word document.
- Compared the two Copilot experiences to better understand when each is most useful.

You now have both a detailed report and a concise summary that can help support leadership discussions about the building heating system.

## Support Contact

The **CloudLabs support** team is available 24/7, 365 days a year, via email and live chat to ensure seamless assistance at any time. We offer dedicated support channels tailored specifically for both technical and training-related queries.

Learner Support Contacts:

- Email Support: [cloudlabs-support@spektrasystems.com](mailto:cloudlabs-support@spektrasystems.com)
- Live Chat Support: https://cloudlabs.ai/labs-support

Click **Next** from the bottom right corner to proceed to the next task!

![](./media/next-button.png)
