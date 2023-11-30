# Gitpod Guide

This guide will walk you through the following topics: 
1. [Loading a grades project with Gitpod](#loading-a-grades-project-with-gitpod){: target="_self"}
1. [Getting started with Gitpod (One time setup)](#getting-started-with-gitpod){: target="_self"}
1. [Sharing a Gitpod snapshot](#sharing-a-gitpod-snapshot){: target="_self"}

## Loading a Grades project with Gitpod

<div class="bg-blue-100 py-1 px-5">
The following is a quick-start for opening a project on Gitpod. **Before you do this,** follow the steps in the [Getting Started With Gitpod](#getting-started-with-gitpod){: target="_self" } section below. Those steps need to be done the very first time you setup Gitpod.
</div>

We will create a **workspace** for each project that we work on. Each workspace is based on a GitHub **repository** (i.e., a folder with some code in it; a.k.a., **repo**).

To create a Gitpod workspace based on a repo, in the address bar of your browser enter `https://gitpod.io/#` and then the URL of the repo. For example,

```
https://gitpod.io/#https://github.com/<your-username>/<project-name>
```
{: .bleed-full }

<aside markdown="1">
To make the process of opening a workspace with `https://gitpod.io/#` easier, [Gitpod has a browser extension](https://www.gitpod.io/docs/20_browser_extension/) that you can install if you want to.
</aside>

This will take you to a "New Workspace" screen on Gitpod. You can accept the default settings and hit "Continue". 

<!-- ![](/assets/launch-gitpod.png) -->
![](/assets/launch-gitpod.png)
{: .bleed-full }

This will take a minute or two to setup the workspace, but reopening the workspace will be much faster.

<div class="bg-blue-100 py-1 px-5">

You can manage your workspaces on the Gitpod dashboard: 

[gitpod.io/workspaces](https://gitpod.io/workspaces)

There, you can find options to stop and re-open workspaces and more, using the `...` menu next to each workspace, just like you did with your Codespaces at [github.com/codespaces](https://github.com/codespaces)
</div>

## Getting Started With Gitpod

**Follow these one-time setup instructions. Complete _every_ step in this section!**

Visit [gitpod.io/login](https://gitpod.io/login) and select "Continue with GitHub" to login with your GitHub credentials to create a new Gitpod account.

![](/assets/gitpod-first-login.png)
{: .bleed-full }

After you login, click the "Authorize gitpod-io" button:

![](/assets/gitpod-first-login-authorize.png)

You will be asked to connect your Linkedin account to receive 50 free hours of usage per month. If you do not connect your Linkedin account, you will only receive 10 hours of free usage per month. Likely 10 hours per month is insufficient for this course, so we strongly recommend connecting your Linkedin account. (If you have one; if not, now is a great time to quickly make one, you can always add to it later.)

![](/assets/gitpod-first-login-linkedin.png)
{: .bleed-full }

Finish setting up your account by answering a few analytics questions from Gitpod, after that you should land on your account's [gitpod.io/workspaces](https://gitpod.io/workspaces) page, where you can manage your active workspaces!

**Before we can push our code from our Gitpod workspace to our GitHub account (for eternal safekeeping), we need to give Gitpod permission to manage our repositories and to interact with our profile.**

Visit your Gitpod workspaces dashboard, click your icon in the top-right corner, and select "User Settings":

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
		
Now, you should get into the habit of pushing your code to GitHub very often. If you do, then you're certain never to lose your work, among many other benefits of using GitHub to store your code. **Gitpod will delete your workspace after a period of inactivity (14 days). You will lose all of your work if you do not make git commits and push the code to GitHub!!!**

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
