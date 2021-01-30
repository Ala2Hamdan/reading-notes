# Version Control
Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.
# GitHub is :
- Snapshots:
Git is a Distributed Version Control systems that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.
- Local Operations:
Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.
- Tracking Changes :
Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.
- Loss of Data:
Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.
- States:
Files in Git can reside in three main states: committed, modified and staged.
* Setting up a Git Repository: 
- Importing :To import an existing project or directory into Git using  the Terminal or Command Line:
1. Switch to the target project’s directory
Example:

`$ cd test (cd = change directory)`
2. Use the git init command
`$ git init`
3. To start tracking these repository files, perform an initial commit by typing the following
`$ git add *.c`
`$ git add LICENSE`
`$ git commit -m “any message here”`
- Cloning :You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:
`$ git clone URL `

* Check File Status  : To determine the state of files
`$ git status`
* Tracking and Staging a New File :
- Single File `git add filename`

- All Files `$ git add *`
* Committing a File :After staging one or multiple files, you should commit the changes and record what you did within the commit message:
`$ git commit -m “made change x,y,z”`
- Committing All Changes `$ git commit -a`
* Pushing Changes :you would push changes to a remote repository.
`$ git push origin master`
* Stashing Changes :
When you are not ready to commit changes but do not want to lose them either, `git stash` is a great option. This command temporarily removes changes and hides them, giving you a clean working directory. When you are ready to continue working on the changes, simply use the` git stash apply ` command to retrieve the hidden changes.
* Remote Repositories  :
In order to collaborate on Git projects, you must interact with remote repositories, versions of a project residing online or on a network. You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use remote repositories to push information to and pull data from.

some commands and what we are using :

* git remote -v : you can view all the remote URLs next to their corresponding short names
* git remote add shortname url  :   To create a new remote Git repository with a short name
* git fetch [remote-name]  :  Fetching entails pulling data that you don’t have from a remote project 
* git fetch  :  solely pulls new data to a local repository; it does not merge changes with or modify your local work
* git push origin master  :  This command pushes committed changes from your local “master” branch upstream to the “origin” server
* git commit --amend : when you need to alter a commit message or forgot to add some files.

Branching  :
A collaborator can create a branch, work on it and save commit snapshots within it, switch between various branches, and merge changes
commands for Branch  :
git branch test :  creates a new branch named “test” that points toward your most recent commit
git checkout test : This command moves the HEAD pointer to the test branch
git checkout -b test2  : To simultaneously create a new branch and switch to it
git branch : You can list available branches
