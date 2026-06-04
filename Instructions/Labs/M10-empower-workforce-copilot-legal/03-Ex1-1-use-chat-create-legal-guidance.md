# Exercise 1 - Task 1: Use Copilot Chat to create regulatory legal guidance

## Estimated duration: 44 minutes

As an Associate Counsel at Boulder Innovations, you were assigned to support the Legal team in drafting an internal guidance brief on the CCPA and CPRA. Your role is to support the Legal department by producing two key deliverables that can inform Boulder Innovations’ preparation for CCPA/CPRA compliance. To streamline your research and drafting process, you want to use Microsoft 365 Copilot Chat to explore the regulations and generate clear, actionable content for both legal and nonlegal audiences.

Your two main objectives are:

- Summarize the key provisions of both the CCPA and CPRA, with a focus on how they apply specifically to Boulder Innovations’ business model and operations. This summary is intended for the Legal department and should include relevant regulatory definitions, thresholds, obligations, and enforcement risks.

- Draft a legal brief tailored to department heads across IT, Marketing, and Product Development. This document should outline the next steps each team must take to help the company achieve compliance. Avoid legal jargon—write in plain, accessible language that makes it easy for nonlegal stakeholders to understand their responsibilities and timelines.

#### Using Copilot Chat  

In Copilot Chat on the web, the response mode selector lets you control how much time and reasoning Copilot uses when answering your prompt. You can leave it set to **Auto** (the default option) so Copilot balances speed and depth for you, or choose a faster or more in‑depth response style depending on the task.

When Copilot Chat opens in **Work** mode, the response mode selector isn’t shown. In **Work** mode, Copilot is optimized for secure, work‑context queries, so it automatically manages response depth for you. When you switch to **Web** mode, the response mode selector appears, allowing you to choose between faster responses or deeper reasoning. Once the selector is enabled, it remains visible as you switch between **Work** and **Web** modes.  
<br/>If you’ve used Copilot in Excel, you know that it also includes a response control selector. However, its options are different from the Chat selector. In Copilot Chat, the selector controls how deeply Copilot reasons about your request. In Excel, the selector controls which AI model performs the work. Although these selectors might look similar, they control different aspects of Copilot and aren't the same setting.


1. On the **Microsoft 365** home page, over the Microsoft 365 Copilot Chat verify the **Work** tab is selected by default. 

   ![](../media/Module3/E1T1S1.png)

1. When Copilot Chat opens in **Work** mode, the response mode selector isn’t shown. In **Work** mode, Copilot is optimized for secure, work context queries, so it automatically manages response depth for you. When you switch to **Web** mode, the response mode selector appears, allowing you to choose between faster responses or deeper reasoning. Once the selector is enabled, it remains visible as you switch between **Work** and **Web** modes.

1. Since you want **Copilot Chat** to access web content for the CCPA and CPRA, select the **Web** toggle switch. Leave the response mode selector set to **Auto**.

    ![](../media/Module3/E2T1S1.png)

1.  Ask **Copilot** to outline the key provisions of the CCPA and CPRA acts.
   
    ```
    I'm an Associate Counsel at Boulder Innovations, a U.S.-based toy manufacturer and distributor. Please outline the key provisions of the California Consumer Privacy Act (CCPA) and the California Privacy Rights Act (CPRA). This material is intended for the Legal department and should include relevant regulatory definitions, applicability thresholds, business obligations, enforcement mechanisms, and potential risks. The summary should focus on how these laws impact Boulder Innovation’s ability to collect, store, and process personal information from U.S residents.
    ```
      > **NOTE:** For this first prompt, we’ve provided the text so you can see what an effective prompt looks like when it incorporates the four key elements discussed in the Introduction unit. You must write all remaining prompts in this exercise, but in doing so, you can use this prompt as a model to emulate.

1. Review the summary created by Copilot Chat. 

      ![](../media/Module10/E1T1S5.png)

1. While you feel it’s a good starting point, you’re concerned that it needs to do more to support IT and Legal in establishing retention schedules, deletion protocols, and user data access system. To address this shortcoming, give the following **Copilot Prompt** to add another section.
    ```
    Add another sectionthat summarizes how CCPA and CPRA affect data retention and deletion policies at Boulder Innovations and provide recommendations on how Boulder can ensure compliance, particularly regarding user rights like data deletion, correction, and access.
    ```
    ![](../media/Module10/E1T1S6.png)

1. You now want Copilot Chat to address privacy-by-design practices and build cross-functional awareness. To do so, give the following **Copilot Prompt** to add another section 
    ```
    Add another section that provides an action plan for the Product Development team at Boulder Innovations to help ensure new digital products are compliant with CCPA and CPRA from launch.
    ```
    ![](../media/Module10/E1T1S7.png)

1. At this point, you’re satisfied with the breadth of the document. However, you feel that it might be helpful to the Legal personnel if you create a crosswalk table, which should allow them to quickly see what changed and what needs updated attention. To do so, give the following **Copilot Prompt** to create a table. 
    ```
    Create a table in this document that compares CCPA and CPRA provisions side by side, highlighting any new or expanded obligations under CPRA.
    ```
    ![](../media/Module10/E1T1S8.png)

1.  In our testing, Copilot sometimes displayed the comparison table in the Chat page, and other times it created a separate document containing the table (for which it provided a link to the document). If it provides a link to a document, select the link and open the downloaded document to verify it looks OK.

1.  At this point, you feel the Summary is complete, so you want to save it for distribution to members of the Legal department’s project team assigned to this initiative. Since Copilot Chat responded to each of your prompts with separate responses that weren’t combined into one document, you want it to do so now. give the following **Copilot Prompt** to combine all the information that it generated in its previous responses into one document that you can download. Make sure you include the comparison table.

    ```
    Combine all the information that is generated in the previous responses into one document so that I can download. Make sure to include the comparison table.
    ```

    ![](../media/Module10/E1T1S10.png)


1.  Copilot Chat should generate a single document that combines all the information from its prior responses. You’re now ready to address the second requirement for this project.

1.  You now want Copilot to draft a legal brief tailored to department heads across IT, Marketing, and Product Development. This document should outline the next steps each team must take to help the company achieve compliance. To create this legal brief, give the following **Copilot Prompt** to create a legal brief. 

    ```
    Create a legal brief that outlines the next steps that the IT, Marketing, and Product Development teams at Boulder Innovations must take to help the company comply with the CCPA and CPRA. This legal brief should be tailored to the heads of each of these three departments. Ask Copilot to use plain, accessible language and avoid legal jargon so that nonlegal stakeholders can easily understand their responsibilities and focus on practical actions, recommended timelines, and how each department's work supports overall compliance.
    ```
    ![](../media/Module10/E1T1S12.png)

1.  Review the legal brief that Copilot generated. While this brief provides a summarization of the next steps, you feel it could be more effective with two updates. Submit a single prompt that includes the following requests.

      ```
      Apply both these requests to the legal brief and make it a downloadable document.

      1. First, you want to turn the legal brief into an actionable planning tool. To do so, ask Copilot to update the existing document by adding a simple compliance timeline or checklist that shows what actions should be completed in the next 30, 60, and 90 days.
    
      2. You also want stakeholders to understand the risks should the company not comply with these regulations. You want to reinforce urgency and help stakeholders understand why these steps matter. To do so, ask Copilot to enhance this legal brief by including a short section that explains the potential risks of noncompliance with CCPA and CPRA, using plain language.
      ```
    ![](../media/Module10/E1T1S13.png)

1. While your initial directive was to create a legal brief that covers IT, Marketing, and Product Development, you feel that it might be more effective to also create three separate documents one for each department that includes department-specific requirements. In doing so, the first legal brief that Copilot Chat created that combined all the departments into one document can be targeted towards senior management. Conversely, the individual legal brief for each department enables department heads to get only what they need, without extra context. Give the following **Copilot Prompt**, to create a downloadable legal brief strictly for Boulder’s Marketing department.

    ```
    Create a downloadable legal brief strictly for Boulder’s Marketing department. This legal brief should specify how the CCPA and CPRA regulations affect Marketing services such as digital advertising, customer data collection, and user consent practices.
    ```
    ![](../media/Module10/E1T1S15.png)

    >**NOTE:** If the downloadable link is not working as expected retry giving the prompt.

1. Download the Marketing legal brief and review it by clicking on the file it will navigate to new browser window. Verify that all the information you requested is in the document.

    ![](../media/Module10/E1T1S14.png)

    >**NOTE:** If the downloadable link is not getting verified due to an internal error and shows to **Continue anyway** click on it.

      ![](../media/Module10/E1T1S15N.png)


1. Now lets ask Copilot to create a legal brief strictly for Boulder’s IT department and provide actionable recommendations to ensure technical compliance with the regulations.

    ```
    Create a legal brief strictly for Boulder’s IT department. This legal brief should specify how the CCPA and CPRA regulations affect IT areas such as data security, user access requests, data deletion protocols, and system logging and provide actionable recommendations to ensure technical compliance with the regulations, with a downloadable link.
    ```
    ![](../media/Module10/E1T1S16.png)

1. Download the IT legal brief and review it. Verify that all the information you requested is in the document.

1. Finally, ask Copilot to create a legal brief strictly for Boulder’s Product Development and provide recommendations to help ensure products are compliant with privacy regulations from initial design through launch.

    ```
    Create a legal brief strictly for Boulder’s Product Development. This legal brief should specify how the CCPA and CPRA regulations affect product development areas such as privacy-by-design principles, default data collection settings, and consent mechanisms in new digital products. and  provide recommendations to help ensure products are compliant with privacy regulations from initial design through launch, with a downloadable link.
    ```
    ![](../media/Module10/E1T1S18.png)

1. Download the Product Development legal brief and review it. Verify that all the information you requested is in the document.

## You have successfully completed the task. Click on Next >> to proceed with the next exercise.

![](../media/Module3/Next.png)