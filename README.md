# Setting up Cloud9 Development environments with Github

### Creating your account
In Chrome or Firefox navigate to https://c9.io/
In the top right corner, locate the "octokitty" icon to sign up for a Cloud9 account using your Github.com account.
When prompted, enter your Github.com username and password. (If you do not have a Github.com account sign up for one first)
When you get to the "Authorize application" screen, click the green "Authorize application" bottom towards the bottom of the screen. (note you must have a verified email address associated with your Github.com account)
This allows Cloud9 to access your email address, create a public key and to access your repositories. 

If prompted to "create an account before logging in with Github" please navigate to the Cloud9 homepage and click Sign Up button in top right corner. Create an account manually by entering your Name, Email and other preferences for Cloud9. When asked, "what type of developer are you" select student. When asked "how do you plan to use Cloud9" select coursework.

Follow the spam prevention steps and complete the account creation process.

Once logged in, click the "settings" icon to access your account settings. Click the "connected services" tab on the left side. Locate the "GitHub" service and click "connect."

When prompted log in to Github using your username and password, then click "authorize application"

Once you've authorized Github you should now be able to access your Github repositories.

### Creating your first workspace
From your "dashboard" click the "Create Workspace" button to begin the process of creating a workspace. 

In the "Workspace name" field enter a name for your workspace. This should be easy to identify later. A good example for this lesson would be *github-cloud9-example*. In the description field, write a few words to remind yourself (and possibly others) what is inside this workspace.

Select the privacy level for this workspace. For this workspace, select *public*.

In the "Clone from Git or Mercurial URL" field, enter the url to your fork of the project that you'll be contributing to. In this case: https://github.com/fsainnovationlab/cloud9-setup-instructions.git 

In the "Choose a template" section, select the *blank* option (with Ubuntu icon)

Then click "Create workspace"

Wait as Cloud9 creates your new workspace...

### What this is?

Cloud9 uses Docker to create an on demand cloud server for you to use with this project. When your workspace is open the virtual appliance is running. Cloud9 will shut down the machine when you're done.

### Navigating the Cloud9 IDE

When you first begin, Cloud9 will offer a "tour" of the important parts of the IDE layout. While you *can* customize this interface, it is recommended that you **do not** change the layout until you're familiar with all parts of the IDE.

It is suggested that you familiarize yourself with the parts of the IDE interface at this time.

The Cloud9 IDE screen is broken into three main sections:

*The left side of the navigator shows your Workspace (file browser), Navigator, and Commands tabs.
*The larger area on the upper right side of the screen is the "Immediate Window" and is the space where you edit your files, run tests and commands. 
*The smaller area in the lower right side is a command line interface to your virtual server.

#### Workspace tree
From the workspace tree you can browse all of the files inside of your project. Double click a file to open it in the editor space.

#### Editing space

