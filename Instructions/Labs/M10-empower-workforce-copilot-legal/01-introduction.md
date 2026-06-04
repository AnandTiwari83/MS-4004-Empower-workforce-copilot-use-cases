# Module 03- Empower Workforce Copilot - Legal

## Estimated duration: 4 hours

### Lab Overview

In this module, we'll create prompts for Microsoft 365 Copilot that reference files. First, let’s upload all required files to OneDrive to ensure they're accessible throughout the lab.


### Uploading Files to OneDrive

Follow the steps below to upload all files needed to **OneDrive**:

1. Log into the virtual machine provided by your tenant provider as the local **Administrator** account with the password `Pa55w.rd`.
2. In the Windows taskbar, select **Microsoft Edge**.
3. In the address bar, enter `https://www.office.com`.
4. Under **Welcome to Microsoft 365**, select **Sign in**.
5. At the **Sign-in prompt**, enter `userx@yourtenant.onmicrosoft.com` (username and tenant provided by your tenant provided) and select **Next**.
6. At the **Enter password** screen, enter the password (provided by tenant provider) for the User account, then select **Sign in**.
7. If prompted to **Stay signed in**, select **Don't show this again** and then **Yes**.
8. In **Microsoft 365**, select **Apps**.
9. Within **Apps**, select **OneDrive**.
10. In **OneDrive**, in the top-left corner, select **+** (add new) > **File upload**.
11. In **File Explorer**, select **This PC** > **Local Disk (C:)** and open the **ResourceFiles** folder.
12. Select all files within the **ResourceFiles** folder, then select **Open** to upload them to **OneDrive**.
13. When the upload is complete, you should see **Uploaded 29 items to My files** in the bottom center of the screen.
14. Leave **Edge** open and move on to the next task.

### Referencing Files in Copilot

When using Copilot, you may find that some files aren’t immediately available in the suggestions. This occurs because certain Copilot experiences only reference files from the **Most Recently Used (MRU)** list, while others let you browse **OneDrive** directly. To ensure a file appears in the **MRU** list, simply open it in the relevant Microsoft 365 app, and it will be added automatically.

> [!IMPORTANT]
> Microsoft 365 Copilot can only work with files saved to **OneDrive**. Files stored locally on your PC will need to be moved to **OneDrive** for Copilot to access them.

# Introduction 

For Legal professionals, precision, clarity, and compliance are non-negotiable. Whether drafting contracts, reviewing case materials, or advising on regulatory matters, the ability to work efficiently while maintaining legal accuracy is essential.

This module introduces Microsoft 365 Copilot as a transformative tool for Legal professionals. It can help streamline document creation, accelerate legal research, and manage large volumes of information across the Microsoft 365 suite.

In a field where time is critical and detail is everything, Copilot becomes an intelligent partner. It helps Legal teams reduce time spent on repetitive tasks, organize complex case data, and maintain a high standard of quality and compliance in every document. Whether you're reviewing contracts in Word, tracking case timelines in Excel, collaborating with internal teams in Teams, or preparing briefs in PowerPoint, Copilot can enhance your productivity and precision.

This module equips Legal professionals with the tools to use Copilot effectively in their day-to-day work. As a Legal expert, your ability to utilize Microsoft 365 Copilot is essential for:

- **Drafting legal documents**. Copilot can help you quickly generate or revise all sorts of legal documents, such as contracts, non-disclosure agreements (NDAs), and internal policies. For example, it can propose standard language, summarize long clauses, or adjust tone based on the audience.

- **Reviewing and analyzing content**. Copilot supports efficient legal review. For example, it can compare multiple versions of a contract, highlight key differences, and suggest areas that need further attention.

- **Managing legal workflows**. Copilot helps keep tasks and timelines organized. For example, it can track deadlines, generate action lists from meeting notes, and summarize case-related correspondence.

- **Enhancing research and compliance**. Copilot accelerates the process of finding relevant legal references or summarizing past decisions. For example, it can scan and extract key information from documents, emails, and internal files.

This training module is built around realistic, scenario‑driven exercises that reflect the responsibilities of modern Legal teams. These exercises mirror the daily work of Legal professionals—analyzing regulations, assessing risk, drafting guidance, and coordinating cross‑functional compliance efforts. Copilot strengthens these essential functions by accelerating research, improving clarity, and ensuring that legal information is consistent, defensible, and ready for action.

### Copilot prompting

One of the primary keys to effectively using Copilot is the quality of your Copilot prompts. A good Copilot prompt is built around the following four key elements that make your request clear, actionable, and tailored for the best results:

- **Goal**. Clearly state what you want Copilot to do. For example: “Generate three to five bullet points summarizing the latest project updates.”

- **Context**. Provide background information so Copilot understands why you need this request and who or what is involved. For example: “Prepare these bullet points for a meeting with Client X about their ‘Phase 3+’ brand campaign.”

- **Sources**. Specify where Copilot should look for information (documents, emails, Teams chats, and so on). For example: “Focus on emails and Teams chats since June.”

- **Expectations**. Define how you want the response delivered—tone, style, or level of detail. For example: “Use simple language so I can get up to speed quickly” or “Explain it as if I were a pirate.”


Keep these four elements front and center as you practice creating prompts—they’re the foundation for getting clear, accurate, and useful results from Copilot. Implementing these elements as you write prompts in these exercises can build real-world skills, so writing effective prompts becomes second nature.

## Lab Objectives

In this lab, you will explore how **Microsoft 365 Copilot** can help IT professionals streamline project planning, improve collaboration, support technology adoption initiatives, and generate actionable insights. You will use a variety of Copilot experiences and agents to create project deliverables, identify risks, develop user communications, collect feedback, and analyze adoption data, demonstrating how AI-assisted workflows can enhance productivity and decision-making across common IT scenarios.

## Prerequisites

Before starting this lab, here are the prerequisites you will have in the environment:

- A basic understanding of Microsoft 365 and prompt-writing concepts.
- A **Microsoft 365 Copilot** license assigned to your account.
- Access to** Microsoft 365 Copilot Chat** and the **Microsoft 365 applications** used in this lab.
- Permission to access and create content in Microsoft Whiteboard, PowerPoint, Viva Engage, and OneDrive.
- Access to **Microsoft 365 Copilot agents**, including Analyst and Surveys.
- A supported web browser and a stable internet connection.



## Getting Started with the lab
We've prepared a seamless environment for you to explore and learn about **Module 03 - Empower Workforce Copilot - IT**. Let's begin by making the most of this experience!

## Accessing Your Lab Environment

Once the lab environment is ready, the virtual machine displayed on the left will be your primary workspace for completing the exercises, while the **Guide** on the right side provides step-by-step instructions for each task.

![](../media/Module3/march-update-lab1-1.png)

##  Lab Guide Zoom In/Zoom Out

To adjust the zoom level for the environment page, click the **A↕ : 100%** icon located next to the timer in the lab environment.

![](../media/Module3/zoom.png)


## Exploring Your Lab Resources

To get a better understanding of your lab resources and credentials, navigate to the **Environment** tab.

![](../media/Module3/env.png)

## Utilizing the Split Window Feature

For convenience, you can open the lab guide in a separate window by selecting the **Split Window** button from the Top right corner.

![](../media/Module3/split.png)

## Managing Your Virtual Machine

Feel free to **Start, Stop, or Restart (2)** your virtual machine as needed from the **Resources (1)** tab. Your experience is in your hands!

![](../media/Module3/resources.png)


## Lab Setup

In this module, we'll create prompts for Microsoft 365 Copilot that reference files. First, let’s upload all required files to OneDrive to ensure they're accessible throughout the lab.


### Uploading Files to OneDrive

Follow the steps below to upload all files needed to **OneDrive**:

1. On your virtual machine, click on the **Microsoft Edge**.

    ![](../media/Module3/prereq-1.png)

1. In the address bar, enter the following 
   ```
    https://www.office.com
    ```

1. Under **Welcome to Microsoft 365**, select **Sign in**.

    ![](../media/Module3/signin.png)
1. You'll see the **Sign into Microsoft Azure** tab. Here, enter your credentials:

   - **Email/Username:** <inject key="AzureAdUserEmail"></inject>

     ![](../media/Module3/GSlogin.png)

1. Next, provide your **Temporary Access Pass**:

   - **Temporary Access Pass:** <inject key="AzureAdUserPassword"></inject>

     ![](../media/Module3/GSpwd.png)

1. If prompted to **Stay signed in**, select **Don't show this again** and then **No**.

    ![](../media/Module3/GSno.png)

1. In the Microsoft 365 portal, click on the **App launcher  (1)** button and select **OneDrive (2)**.

    ![](../media/Module3/prereq-2.png)

1. In **OneDrive**, in the top-left corner, select **+ Create or upload (1)** > **Files upload (2)**. 

    ![](../media/Module3/prereq-3.png)

1. In **File Explorer**, navigate to **`C:\LabFiles\MS-4004-Empower-workforce-copilot-use-cases\ResourceFiles`** location and select all the files from the ResourceFiles folder and click **Open**.

1. When the upload is complete, you should see **Uploaded 92 items to My files** in the bottom center of the screen.
 
1. Leave **Edge** open and move on to the next task.

## Support Contact

The CloudLabs support team is available 24/7, 365 days a year, via email and live chat to ensure seamless assistance at any time. We offer dedicated support channels tailored specifically for both learners and instructors, ensuring that all your needs are promptly and efficiently addressed.

Learner Support Contacts:

- Email Support: [cloudlabs-support@spektrasystems.com](mailto:cloudlabs-support@spektrasystems.com)
- Live Chat Support: https://cloudlabs.ai/labs-support

Click **Next** from the bottom right corner to embark on your Lab journey!

![](../media/Module3/Next.png)

Now you're all set to explore the powerful world of technology. Feel free to reach out if you have any questions along the way. Enjoy your workshop!
