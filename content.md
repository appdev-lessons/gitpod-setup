# Gitpod Guide

This guide will walk you through the following topics: 
1. [Loading a grades project with Gitpod](#loading-a-grades-project-with-gitpod){: target="_self"}
1. [Getting started with Gitpod (One time setup)](#getting-started-with-gitpod){: target="_self"}
1. [Sharing a Gitpod snapshot](#sharing-a-gitpod-snapshot){: target="_self"}

## Loading a Grades project with Gitpod

<div class="bg-blue-100 py-1 px-5">
The following is a quick-start for opening a project on Gitpod. **Before you do this,** follow the steps in the [Getting Started With Gitpod](#getting-started-with-gitpod){: target="_self" } section below. Those steps need to be done the very first time you setup Gitpod.
</div>

   1. We will create a **workspace** for each project that we work on. Each workspace is based on a GitHub **repository** (i.e., a folder with some code in it; a.k.a., **repo**).

      - For example, here is a repository: [github.com/appdev-projects/ruby-template](https://github.com/appdev-projects/ruby-template)

   1. To create a Gitpod workspace based on a repo, in the address bar of your browser enter `https://gitpod.io/#` and then the URL of the repo. For example,

        ```
        https://gitpod.io/#https://github.com/<your-username>/<project-name>
        ```
        {: .bleed-full }

   1. This will take you to a "New Workspace" screen on Gitpod. You can accept the default settings and hit "Continue". 

<aside markdown="1">
To make the process of opening a workspace with `https://gitpod.io/#` easier, [Gitpod has a browser extension](https://www.gitpod.io/docs/20_browser_extension/) that you can install if you want to.
</aside>

<!-- ![](/assets/launch-gitpod.png) -->
![](/assets/launch-gitpod.png)
{: .bleed-full }

This will take a minute or two to setup the workspace, but reopening the workspace will be much faster.

## Getting Started With Gitpod

Sign up for a [Gitpod.io](https://www.gitpod.io) account. It will ask you to sign in using your GitHub account.

Before we can push our code from our Gitpod workspace to our GitHub account (for eternal safekeeping), we need to give Gitpod permission to manage our repositories and to interact with our organization.

Visit the Gitpod dashboard (Workspaces), click your icon in the top-right corner, and select "User Settings":

![](/assets/user-setting.png)
{: .bleed-full }

Click "Git Providers" in the left sidebar, click the "..." next to "GitHub",  and select "Edit Permissions":

![](/assets/git-providers.png)
{: .bleed-full }

Make sure that **user:email**, **read:user**, **public_repo**, **repo** and **workflow** are checked, and then "Update Permissions" if necessary:

![](/assets/edit-permissions.png)
{: .bleed-full }

Finally, You can now "Commit" (Remember to add a commit message before you click on Commit) and "Sync" with GitHub:

![](/assets/git-commit.png)
{: .bleed-full }
		
Now, you should get into the habit of pushing your code to GitHub very often. If you do, then you're certain never to lose your work, among many other benefits of using GitHub to store your code.

## Sharing a Gitpod snapshot

It's often helpful to share a snapshot of the state of your entire Gitpod workspace with someone else.

### Take the snapshot

From the hamburger menu in the top-left corner of your IDE, select `Gitpod: Share Workspace Snapshot`:

<!-- ![](/assets/gitpod-snapshot-file-menu.png) -->
![](/assets/gitpod-snapshot-file-menu.png)

{: .bleed-full }

### Copy the snapshot URL

It will take a moment to create the snapshot. Then a dialog will pop up in the bottom-right corner that will give you the URL to copy and share:

<!-- ![](/assets/gitpod-snapshot-copy-url.png) -->
![](/assets/gitpod-snapshot-copy-url.png)

{: .bleed-full }

**The URL should look like this:**

  - **https\://gitpod.io#snapshot/5a47e40d-e279-44e5-96bc-ae33cd48f151**

Note the `#snapshot` fragment of the URL. That means you have the right one.

**The URL should NOT look like these:**

  - **https\://ac1bde40-34e8-421d-a102-6425971fb9db.ws-eu38.gitpod.io/**

    That is the URL of your own IDE, which no one else can access.

  - **https\://3000-ac1bde40-34e8-421d-a102-6425971fb9db.ws-eu38.gitpod.io**

    Note the `3000-` at the start. That is the URL of the live preview of your app.

### Snapshots are completely independent

When someone clicks on the snapshot URL, they will get their own private copy of your workspace in the state that it was in when you took the snapshot.

Any changes they make to their copy will not affect your workspace. Similarly, any changes you make to your workspace won't affect their snapshot. So you can keep trying to resolve the problem on your own, or work on the next task, without interfering with their snapshot.