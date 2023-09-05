# Load a Grades project with Gitpod

To create a Gitpod workspace based on a repo, in the address bar of your browser enter `https://gitpod.io/#` and then the URL of the repo. For example,

```
https://gitpod.io/#https://github.com/<your-username>/<project-name>
```
{: .bleed-full }

This will take you to a "New Workspace" screen on Gitpod. You can accept the default settings and hit "Continue". 

<!-- ![](/assets/launch-gitpod.png) -->
![](https://res.cloudinary.com/dmxgp9oq2/image/upload/v1685989216/launch-gitpod_xq95rl.png)
{: .bleed-full }

This will take a minute or two to setup the workspace, but reopening the workspace will be much faster.

More details on using Gitpod can be found below for: 

* [loading a workspace from any repository](#getting-started-with-gitpod){: target="_self"}, and
* [sharing snapshots](#sharing-a-gitpod-snapshot){: target="_self"}

## Getting Started With Gitpod

  1. Sign up for a [Gitpod.io](https://www.gitpod.io) account. It will ask you to sign in using your GitHub account.
  1. We will create a **workspace** for each project that we work on. Each workspace is based on a GitHub **repository** (i.e., a folder with some code in it; a.k.a., **repo**).

      - For example, here is a repository: [github.com/appdev-projects/ruby-template](https://github.com/appdev-projects/ruby-template)

  1. To create a Gitpod workspace based on a repo, in the address bar of your browser enter **https\://gitpod.io/#** and then the URL of the repo. For example,

      - `https://gitpod.io/#https://github.com/appdev-projects/ruby-template`

  1. This creates a blank, brand-new computer. This is not a simple interactive terminal, nor is it an HTML application like we made for our early "Link in bio" project. But Ruby _is_ installed on this computer. 

<aside markdown="1">
To make the process of opening a workspace with `https://gitpod.io/#` easier, [Gitpod has a browser extension](https://www.gitpod.io/docs/20_browser_extension/) that you can install if you want to.
</aside>

## Sharing a Gitpod snapshot

It's often helpful to share a snapshot of the state of your entire Gitpod workspace with someone else.

### Take the snapshot

From the hamburger menu in the top-left corner of your IDE, select `Gitpod: Share Workspace Snapshot`:

<!-- ![](assets/technical-setup/gitpod-snapshot-file-menu.png) -->
![](https://res.cloudinary.com/dmxgp9oq2/image/upload/v1677021161/gitpod-snapshot-file-menu_ih8ihp.png)
{: .bleed-full }

### Copy the snapshot URL

It will take a moment to create the snapshot. Then a dialog will pop up in the bottom-right corner that will give you the URL to copy and share:

<!-- ![](assets/technical-setup/gitpod-snapshot-copy-url.png) -->
![](https://res.cloudinary.com/dmxgp9oq2/image/upload/v1677021172/gitpod-snapshot-copy-url_zdlmmn.png)
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
