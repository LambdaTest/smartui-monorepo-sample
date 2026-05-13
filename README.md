# Setting Up Multiple Projects in a Repository — TestMu AI (Formerly LambdaTest)

SmartUI allows you to manage and test UI components effectively within a single repository. By organizing multiple projects in a single repository, you can centralize your workflows and streamline collaboration. This guide will walk you through setting up multiple projects in a repository for SmartUI and how you can trigger the same via GitHub Actions pipeline.

## Prerequisites
- Your TestMu AI [Username and Access key](https://accounts.lambdatest.com/security).
- Your SmartUI Project Token

## Step 1: Organize Your Repository
Create a repository where you can organize your projects into various directories. You can use your own project to configure and test it. For demo purposes, we are using the sample repository.

## Step 2: Create your Secrets
- Click on the **Settings** of your repository.
- Go to the **Security** option > **Secrets and Variables** > **Actions**.
- Create your secrets with variable name **LT_USERNAME** and **LT_ACCESS_KEY**. You can fetch your credentials from the [Accounts and Settings](https://accounts.lambdatest.com/security) dashboard.

## Step 3: Create your GitHub Actions Workflow
- Navigate to the main page of the repository.
- Under your repository name, click **Actions**.
- In the left sidebar, click the **New workflow** button.

## 🚀 [LambdaTest is Now TestMu AI](https://www.testmuai.com/lambdatest-is-now-testmuai/)

👋 Welcome to TestMu AI, the next evolution of LambdaTest. As of January 2026, LambdaTest has officially rebranded to TestMu AI. We have evolved from a cross-browser testing cloud into a unified, AI-native quality engineering platform designed for the modern DevOps era.

Whether you have been part of the LambdaTest community for years or are just discovering TestMu AI, our mission remains the same: to help you ship faster with high-scale test execution, autonomous testing, and deep quality analytics.

**🔄 Our Rebrand Journey**

We chose the name TestMu AI to reflect our shift towards intelligent, autonomous testing. While our identity has changed, our core technology and commitment to the testing community stay the same.

**✨ Specialties**

- 🤖 AI-Native Test Execution (Formerly LambdaTest)
- ⚡ Autonomous Test Automation
- 🌐 Cross-Browser & Mobile Testing
- 📊 Unified Quality Intelligence

👉 Find [LambdaTest's New Home](https://www.testmuai.com/).