First we start with downloading everything necessary before starting to link the accounts.
1-create a github account ----https://github.com/join
2- download git -- https://git-scm.com/downloads
3-download webstorm----https://www.jetbrains.com

now we will start linking/merger these accounts to improve performance

4-Display the Webstorm settings, press (Ctrl+Alt+S)
Choose Version Control -> Git. from the left side.

5-Click Test to make sure Webstorm is connected to Git. The path in the location box
it should be C:\Program Files\Git\bin\git.exe. (you will be notified when it is connected) then you can click ok and exit

Now that this is ready, it is time to create our project.

6-Click "Create new project" on the main page of Webstorm.
7- look in what format you are going to make the project in general it is html5 (when creating a new file you will be asked for a name to your project put it in lowercase)

8-start your project. already finished Click "VCS" look for "Import into Version Control" then you give "Create Git Repository" and push "ok"

9-Commit the changes to GIT: VCS->Git -> Commit File-->click Commit(Commit Your Changes)--> (Click Set and Commit)

10-Add the project to GITHUB
Click on VCS -> Import to version control -> Share project on Github (you will get a confirmation message) it is already on github

11-Add a new file to the GitHub repository.Create a new file.Name it README.MD--->Add some text and commit.

In the case that you want to make a change to your project and it comes out on github, what you have to do is the following/Push Change to Remote Repository:


12- start making your changes in the Webstorm.
13-VCS->Git->Commit
Add the Confirm comment and click Confirm
14-Push the change to Github VCS -> Git -> Push (Ctrl+Shift+K)

and up to here the tutorial, your project would be complete and uploaded to github
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Glossary
**Branch**:  at its most basic, is a copy of a Git project that you can change as you like and then combine with the original project. When you create a new repository in GitHub, there’s one branch by default—the “main” branch ( previously called “master” ). 

**Clone**:is nothing but a process of downloading an already presented git repository to your local system.  

**Commit**:creates a commit, which is like a snapshot of your repository. These commits are snapshots of your entire repository at specific times.

**Fetch**:is a feature available on GitHub that will retrieve new/changed branches into local repositories using the tracking branches and GitHub pull is a request that will let others know about the changes that you are pushing to a branch in a particular repository.

**GIT**: Git is a distributed version control system, which means that a local clone of the project is a complete version control repository.

**Github**: is a Git repository hosting service. GitHub also facilitates many of its features, such as access control and collaboration.

**Merge**:Merging in git is the process of connecting forked history. That facilitates the joining of two branch histories into one main.

**Merge Conflict**: happen when two people make changes to the same file on GitHub—a common occurrence when you’re working with other developers.

**Push**:The git push command is used to transfer or push the commit, which is made on a local branch in your computer to a remote repository like GitHub.

**Pull**:updates your current local working branch, and all of the remote tracking branches

**Remote**:is a common repository that all team members use to exchange their changes.

**Repository**:  is defined as a location in the GitHub platform where the files and codes corresponding to the projects and their respective versions as a part of revision history are stored, managed, and used. 
