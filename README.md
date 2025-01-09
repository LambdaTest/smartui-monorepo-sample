# Setting Up Multiple Projects in a Repository

SmartUI allows you to manage and test UI components effectively within a single repository. By organizing multiple projects in a single repository, you can centralize your workflows and streamline collaboration. This guide will walk you through setting up multiple projects in a repository for SmartUI and how you can trigger the same via GitHub Actions pipeline.

## Prerequisites
- Your LambdaTest [Username and Access key](https://accounts.lambdatest.com/security).
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
