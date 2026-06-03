# Module 06: Empower workforce with Microsoft 365 Copilot for Human Resources

### Overall Estimated Duration: 4 Hours

## Lab Overview

Human Resources (HR) departments are at the heart of every organization, responsible for supporting employees, managing policies, and driving engagement. As the workplace evolves, HR teams face increasing demands for efficiency, responsiveness, and data-driven decision-making. Microsoft 365 Copilot offers a powerful solution—utilizing artificial intelligence to streamline HR tasks, enhance employee experiences, and unlock new strategic capabilities.

Copilot can help HR departments in numerous ways, including:

- **Automating routine tasks**. Copilot can handle repetitive HR inquiries, such as questions about benefits, leave policies, promotions, and relocation. By integrating Copilot with your organization’s HR documents and systems, employees receive instant, accurate answers—reducing the workload on HR staff and improving service quality.

- **Enhancing data-driven insights**. HR professionals can use Copilot to analyze workforce data, identify trends in engagement and attrition, and generate actionable reports. Copilot in Excel, for example, can summarize manager performance metrics, visualize team health, and uncover patterns that inform coaching and development strategies.

- **Supporting strategic communication**. Copilot assists HR teams in drafting clear, professional communications—whether it’s summarizing survey results, preparing feedback for managers, or composing policy updates. Copilot ensures consistency and saves valuable time by automating the creation of emails and reports. 

- **Empowering employee self-service**. Custom Copilot agents enable employees to access HR information on their own, from policy details to relocation support. This self-service approach fosters transparency, empowers employees, and allows HR teams to focus on higher-value work.

- **Connecting internal and external knowledge**. Copilot can synthesize information from both company data and web sources. For example, employees relocating to a new city can use Copilot to research local schools, housing, and amenities—combining internal policies with external insights for holistic support.

This training module guides you through the following practical exercises that demonstrate Copilot’s effect on HR operations:

- **Delivering manager insights**. Learn how Copilot in Excel helps HR analyze manager performance, identify strengths and opportunities, and communicate findings to leadership.

- **Building an HR self-service agent**. Discover how to create custom Copilot agents that answer employee questions, streamline policy access, and support real-world scenarios like relocation and promotions.

By the end of this module, you should clearly see how Copilot can transform HR workflows, improve employee experiences, and enable your team to operate more strategically.

### Copilot prompting

One of the primary keys to effectively using Copilot is the quality of your Copilot prompts. A good Copilot prompt is built around the following four key elements that make your request clear, actionable, and tailored for the best results:

- **Goal**. Clearly state what you want Copilot to do. For example: “Generate three to five bullet points summarizing the latest project updates.”

- **Context**. Provide background information so Copilot understands why you need this request and who or what is involved. For example: “Prepare these bullet points for a meeting with Client X about their ‘Phase 3+’ brand campaign.”

- **Sources**. Specify where Copilot should look for information (documents, emails, Teams chats, and so on). For example: “Focus on emails and Teams chats since June.”

- **Expectations**. Define how you want the response delivered—tone, style, or level of detail. For example: “Use simple language so I can get up to speed quickly” or “Explain it as if I were a pirate.”

Keep these four elements front and center as you practice creating prompts—they’re the foundation for getting clear, accurate, and useful results from Copilot. Implementing these elements as you write prompts in these exercises can build real-world skills, so writing effective prompts becomes second nature.

## Prerequisites

To get the most out of this module, you should have:

- A basic understanding of Microsoft 365 applications like Word, Excel, and Loop.

## Getting Started with the lab

We've prepared a seamless environment for you to explore and learn about **Module 06 - Empower workforce with Microsoft 365 Copilot for Human Resources**. Let's begin by making the most of this experience!

## Accessing Your Lab Environment
 
Once the lab environment is ready, the virtual machine displayed on the left will be your primary workspace for completing the exercises, while the **Guide** on the right side provides step-by-step instructions for each task.

## Exploring Your Lab Resources
 
To get a better understanding of your lab resources and credentials, navigate to the **Environment** tab.
 
![](../media/module-4/env-0206.png)

## Utilizing the Split Window Feature
 
For convenience, you can open the lab guide in a separate window by selecting the **Split Window** button from the Top right corner.

![](../media/module-4/split-0206.png)

## Managing Your Virtual Machine
 
Feel free to **Start, Stop, or Restart (2)** your virtual machine as needed from the **Resources (1)** tab. Your experience is in your hands!

![](../media/module-4/res-0206.png)

# Lab Setup:

In this module, we'll create prompts for Microsoft 365 Copilot that reference files. First, let’s upload all required files to OneDrive to ensure they're accessible throughout the lab.

### Uploading Files to OneDrive

Follow the steps below to upload all files needed to **OneDrive**:

1. In the LabVM, open the **Microsoft Edge** browser from the from Desktop.

    ![Open Edge](../media/module-4/prereq-1.png)

1. In the address bar, enter the following URL to navigate to Microsoft 365:

    ```
    https://www.microsoft365.com
    ```
1. Enter the following credentials to sign in to Microsoft 365:

    - **Email/Username**: **<inject key="AzureAdUserEmail"></inject>**

    - **Password**: **<inject key="AzureAdUserPassword"></inject>**

1. If prompted to **Stay signed in**, select **Don't show this again** and then **Yes**.

1. In the Microsoft 365 portal, click on the **App launcher  (1)** button and select **OneDrive (2)**.

    ![](../media/module-4/prereq-2.png)

1. In **OneDrive**, in the top-left corner, select **+ Create or upload (1)** > **Files upload (2)**.

    ![](../media/module-4/prereq-3.png)

1. In **File Explorer**, navigate to **`C:\LabFiles\MS-4004-Empower-workforce-copilot-use-cases\ResourceFiles`** location and select all the files from the ResourceFiles folder and click **Open**.

1. When the upload is complete, you should see **Uploaded 92 items to My files** in the bottom center of the screen.

1. Leave **Edge** open and move on to the next task.

### Referencing Files in Copilot

When using Copilot, you may find that some files aren’t immediately available in the suggestions. This occurs because certain Copilot experiences only reference files from the **Most Recently Used (MRU)** list, while others let you browse **OneDrive** directly. To ensure a file appears in the **MRU** list, simply open it in the relevant Microsoft 365 app, and it will be added automatically.

> **`Important:`** Microsoft 365 Copilot can only work with files saved to **OneDrive**. Files stored locally on your PC will need to be moved to **OneDrive** for Copilot to access them.

## Support Contact
 
The **CloudLabs support** team is available 24/7, 365 days a year, via email and live chat to ensure seamless assistance at any time. We offer dedicated support channels tailored specifically for both learners and instructors, ensuring that all your needs are promptly and efficiently addressed.
 
Learner Support Contacts:
 
- Email Support: [cloudlabs-support@spektrasystems.com](mailto:cloudlabs-support@spektrasystems.com)
- Live Chat Support: https://cloudlabs.ai/labs-support
 
Click **Next** from the bottom right corner to embark on your Lab journey!

  ![](../media/module-4/next-0206.png)
