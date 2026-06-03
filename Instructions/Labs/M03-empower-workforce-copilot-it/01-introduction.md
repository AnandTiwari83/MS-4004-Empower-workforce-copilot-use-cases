# Module 03- Empower Workforce Copilot - IT

## Estimated duration: 44 minutes

### Lab Overview
---
Modern IT departments face increasing demands to deliver projects faster, support innovation, and ensure successful technology adoption across their organizations. Microsoft 365 Copilot is transforming the way IT professionals work by providing intelligent, AI-powered assistance that streamlines complex tasks, enhances collaboration, and drives measurable outcomes.

In this module, you learn how Microsoft 365 Copilot can serve as a valuable tool for IT professionals, allowing them to navigate the intricacies of technology management with ease. By utilizing Copilot, IT professionals can save time and focus on critical aspects of their role. For example, Copilot can assist IT departments in enhancing system reliability, implementing innovative solutions, and proactively addressing IT challenges.

Throughout this module, you experience how Copilot provides the following key benefits for IT personnel:

- **Accelerated project planning and execution**. Copilot enables IT teams to quickly synthesize information from emails, chat logs, and documents, creating unified project frameworks that clarify goals, deliverables, milestones, and risks. Copilot can automate routine documentation and reporting, freeing IT professionals to focus on strategic decision-making and innovation.

- **Enhanced collaboration and communication**. Copilot integrates seamlessly with tools like Whiteboard, PowerPoint, and Viva Engage, facilitating brainstorming sessions, executive presentations, and engaging communications. IT teams can use Copilot to draft announcements, best-practice guides, and training materials that help end users understand and embrace new technologies.  

- **Streamlined technology adoption**. Copilot assists IT professionals in planning and executing feature rollout campaigns. With Copilot, IT can create clear, user-friendly resources and measure the effect of adoption initiatives, ensuring employees are confident and productive with new tools.  

- **Data-driven insights and continuous improvement**. Copilot’s Analyst and Surveys agents empower IT teams to gather feedback, visualize adoption trends, and generate actionable insights for leadership. By identifying blockers and opportunities, IT can continuously refine strategies to maximize technology value and user satisfaction.

Microsoft 365 Copilot is more than just an automation tool—it’s a digital partner that helps IT professionals work smarter, not harder. By integrating Copilot into daily workflows, IT teams can:

- Reduce manual effort and administrative overhead.
- Improve project transparency and governance.
- Deliver faster, more effective technology rollouts.
- Foster a culture of collaboration, learning, and innovation.

As you progress through this training, you experience firsthand how Copilot can transform IT operations, making your team more agile, efficient, and impactful.

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
