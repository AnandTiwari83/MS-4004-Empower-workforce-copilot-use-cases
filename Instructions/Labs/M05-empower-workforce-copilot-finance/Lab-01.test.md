# Lab-01: Module 5 Lab Setup and Introduction — Microsoft 365 Copilot for Finance

## Lab Overview

Welcome to **Module 5: Empower Your Finance Workforce with Microsoft 365 Copilot**. This lab sets up your working environment and introduces you to how Microsoft 365 Copilot can transform the daily work of finance professionals.

Before you begin any exercises in this module, you must upload the required resource files to **OneDrive** so that Copilot can access them throughout the lab activities. This lab also provides the foundational context for the entire module, explaining why Copilot matters in finance and how to write effective prompts.

**Estimated Duration:** 15 minutes  
**Difficulty Level:** 200 (Intermediate)

---

## Learning Objectives

By the end of this lab, you will be able to:

- Upload required lab resource files to OneDrive so they are accessible to Microsoft 365 Copilot.
- Explain how Microsoft 365 Copilot benefits finance professionals across key Microsoft 365 apps.
- Identify the four key elements of an effective Copilot prompt: **Goal**, **Context**, **Sources**, and **Expectations**.
- Understand how Copilot integrates with Excel, Word, PowerPoint, Outlook, Teams, and Loop to support finance workflows.

---

## Prerequisites

Before starting this lab, ensure the following:

- You have access to a Microsoft 365 tenant with Copilot enabled (provided by your lab environment or your own subscription).
- You can sign in to the virtual machine as the local **Administrator** using the password `Pa55w.rd`.
- You have a web browser (Microsoft Edge is recommended).
- You have access to **OneDrive** through your Microsoft 365 account.

---

## Exercise Overview

This lab has two parts:

| Part | Activity | Duration |
|------|----------|----------|
| Part 1 | Upload resource files to OneDrive | ~10 minutes |
| Part 2 | Review the Module 5 Introduction and Copilot prompting guidance | ~5 minutes |

---

## Part 1: Upload Resource Files to OneDrive

### Task 1.1 — Sign in and Upload Files

All exercises in this module reference files stored in your OneDrive. Complete the following steps to upload all required files before proceeding to any exercises.

**Step 1:** Log into the virtual machine provided by your lab environment as the local **Administrator** using the password `Pa55w.rd`.

> **📸 Screenshot placeholder:** Capture the virtual machine desktop immediately after signing in as the local Administrator.  
> Suggested filename: `M05-Lab01-Step01-VMDesktopSignIn.png`

**Step 2:** In the Windows taskbar, select **Microsoft Edge**.

- If Microsoft Edge is pinned, select the blue-and-green **e** icon on the taskbar.
- If the browser is already open, select its taskbar icon to bring it to the front.

> **📸 Screenshot placeholder:** Capture Microsoft Edge after the browser window opens on the virtual machine.  
> Suggested filename: `M05-Lab01-Step02-EdgeBrowserOpen.png`

**Step 3:** In the address bar, enter `https://www.office.com` and press **Enter**.

**Step 4:** On the Microsoft 365 welcome page, select **Sign in**.

- If the page loads directly to a sign-in experience, continue without returning to the home page.
- If you are already signed in, confirm you are using the lab-issued Microsoft 365 account before proceeding.

**Step 5:** At the sign-in prompt, enter the username provided by your lab environment (`userx@yourtenant.onmicrosoft.com`), then select **Next**.

**Step 6:** At the **Enter password** screen, enter the password provided by your lab environment, then select **Sign in**.

**Step 7:** If prompted with **Stay signed in?**, select **Don't show this again** and then **Yes**.

> **📸 Screenshot placeholder:** Capture the Microsoft 365 home page after sign-in is complete.  
> Suggested filename: `M05-Lab01-Step03-M365HomePage.png`

**Step 8:** In Microsoft 365, select **Apps** in the left navigation pane.

- If the left navigation pane is collapsed, select the **Apps** icon or expand the navigation menu first.

**Step 9:** In the **Apps** menu, select **OneDrive**.

> **📸 Screenshot placeholder:** Capture the OneDrive **My files** page after it opens.  
> Suggested filename: `M05-Lab01-Step04-OneDriveOpen.png`

**Step 10:** In OneDrive, select the **+** (add new) button in the top-left corner, then select **File upload**.

- Make sure you are on the **My files** view before starting the upload.

> **📸 Screenshot placeholder:** Capture the OneDrive upload menu with **File upload** visible.  
> Suggested filename: `M05-Lab01-Step05-OneDriveUploadMenu.png`

**Step 11:** In the **File Explorer** window that opens, navigate to **This PC** → **Local Disk (C:)** → **ResourceFiles** folder.

> **📸 Screenshot placeholder:** Capture the **ResourceFiles** folder in File Explorer before selecting the files.  
> Suggested filename: `M05-Lab01-Step06-ResourceFilesFolder.png`

**Step 12:** Select **all files** within the ResourceFiles folder, then select **Open** to begin the upload.

- You can press **Ctrl+A** in the folder to select every file before choosing **Open**.

> **📸 Screenshot placeholder:** Capture OneDrive while the file upload is in progress.  
> Suggested filename: `M05-Lab01-Step07-UploadInProgress.png`

**Step 13:** Wait for the upload to complete. You should see a message at the bottom of the screen confirming **Uploaded 29 items to My files**.

> **📸 Screenshot placeholder:** Capture OneDrive showing the completed upload confirmation with 29 items available in **My files**.  
> Suggested filename: `M05-Lab01-Step08-UploadComplete29Items.png`

**Step 14:** Leave Microsoft Edge open and proceed to Part 2.

> **🔧 Troubleshooting:**
> - If you see fewer than 29 files after upload, wait 30 seconds and refresh OneDrive.
> - If OneDrive doesn't open, ensure you are signed in with your Microsoft 365 account, not a personal Microsoft account.
> - If file upload fails, try uploading in smaller batches of 5-10 files at a time.
> - If you are prompted for MFA, complete the verification as directed by your lab provider.

### Expected Outcome

✅ All 29 resource files are uploaded to your OneDrive **My files** folder. These files will be referenced throughout Module 5 exercises.

---

## Part 2: Understand Copilot in Microsoft 365 for Finance

### Task 2.1 — Review the Module Introduction

Take a few minutes to read and internalize the following context before beginning the exercises. Understanding _why_ Copilot matters in finance will help you engage more meaningfully with each task.

#### Why Microsoft 365 Copilot Matters for Finance Professionals

Finance professionals are expected to deliver rapid insights, manage risk, and drive strategic decisions while navigating complex data, contracts, and collaboration demands. Microsoft 365 Copilot embeds AI-powered assistance directly into the tools Finance teams already use, enabling them to:

| Capability | Benefit |
|------------|---------|
| **Automate financial tasks** | Reduce time spent on budgeting, forecasting, and data entry |
| **Provide data insights** | Analyze financial statements, identify trends, and predict outcomes |
| **Improve productivity** | Generate reports, summaries, and proofreading assistance |
| **Enable collaboration** | Facilitate team communication, document sharing, and project management |

#### Copilot Across Microsoft 365 Apps

| App | Finance Use Case |
|-----|-----------------|
| **Excel** | Analyze COGS data, model what-if scenarios, and generate charts |
| **Word** | Draft and summarize reports, contracts, and policy briefs |
| **PowerPoint** | Build executive presentations from financial analyses |
| **Outlook** | Draft professional emails for stakeholder communication |
| **Teams** | Summarize meeting notes and extract action items |
| **Loop** | Turn insights into structured, collaborative content |

### Task 2.2 — Learn the Four Elements of an Effective Copilot Prompt

The quality of your Copilot output depends heavily on the quality of your prompts. All prompts you write in this module should include the following four elements:

| Element | Description | Example |
|---------|-------------|---------|
| **Goal** | What you want Copilot to do | "Summarize the top three cost drivers" |
| **Context** | Background information and purpose | "For a quarterly review with Finance leadership" |
| **Sources** | Which documents or data Copilot should reference | "Use the EcoSmart COGS Estimates spreadsheet" |
| **Expectations** | Desired tone, format, or level of detail | "Present findings in bullet points, suitable for a non-technical audience" |

> 💡 **Tip:** Keep these four elements front and center as you practice creating prompts throughout this module. Implementing them consistently will build real-world skills so that writing effective prompts becomes second nature.

### Expected Outcome

✅ You have a clear understanding of how Copilot supports finance workflows and how to write effective prompts using the Goal-Context-Sources-Expectations framework.

---

## Important Notes

> ⚠️ **Important:** Microsoft 365 Copilot can only work with files saved to **OneDrive**. Files stored locally on your PC will not be accessible to Copilot. Ensure all files are uploaded before starting the exercises.

> 💡 **File Availability Tip:** When using Copilot, some files may not immediately appear in suggestions because Copilot references the **Most Recently Used (MRU)** list. To add a file to the MRU list, simply open it in the relevant Microsoft 365 app before using it with Copilot.

---

## Before You Continue

Before moving to **Lab-02**, confirm the following:

- [ ] I can open **OneDrive** and see **29 resource files** in **My files**.
- [ ] I am still signed in to Microsoft 365 with my lab-provided account in Microsoft Edge.
- [ ] I understand that Copilot can only work with files stored in **OneDrive**.
- [ ] I can identify the four prompt elements: **Goal**, **Context**, **Sources**, and **Expectations**.

---

## Lab Summary

In this lab, you:

- ✅ Uploaded all 29 required resource files to OneDrive for use throughout Module 5.
- ✅ Reviewed how Microsoft 365 Copilot supports Finance professionals across Excel, Word, PowerPoint, Outlook, Teams, and Loop.
- ✅ Learned the four key elements of an effective Copilot prompt: **Goal**, **Context**, **Sources**, and **Expectations**.

You are now ready to begin **Lab-02**, which introduces Exercise 1 and the scenario for financial reporting and acquisition modeling.

---

*Next Lab: [Lab-02 — Exercise 1 Overview: Optimize Financial Reporting and Acquisition Modeling](./Lab-02.test.md)*
