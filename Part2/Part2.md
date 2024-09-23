1. List three major version control software for software engineering 
	1. Git
	2. Apache Subversion
	3. Mercurial 

2. What are the main advantages to using Git in your software development, and how is it useful for game developers.
	1. Being able to share software and code easily 
	2. Push through updates and patches 
	3. Revert changes if there's a bug
	4. Branches allow for testing of new code without interfering with the main code and you can merge the code to the main easily.
3. Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge
	1. Branch - A branch allows for development off of the main code without having that main code affected. You can merge the branch and the main afterwards when the branch is ready
	1. Pull - Get the latest repository from the remote repository and update your local repository..
	1. Push - Upload your local repository to the remote repository 
	1. Repository - A repository is a place where you can store your code, files, and see each file's revision history. These repositories can have multiple collaborators and respositories can be public, 
which can be seen by anyone, or private.
	1. Working Copy - In Git a working copy is a directory full of files with a .git subdirectory. The same as a local repository.
	1. Merge -  A merge is an action in Git where you get one branch from a repository and merge it into another.
	
4. If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.
	1. Pulling before working in the policy and procedure as if someone works on an old copy or forgets to pull that would lead to conflicts with the code.
	1. Naming Pushes and changes appropriately would allow for clear organisation and communication.
	1. Working in Branches when testing and developing code would ensure the main code is safe from errors and bugs from development.
	1. Communicating when wanting to revert back a change or merge a branch so merge conflict errors are minimal.
5. Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.
	1. Visual studio code has tools to let you know what and where the merge conflict is.
	1. git mergetool can be run after a merge to resolve merge conflicts.
	1. Git status lets you identify what files are creating the merge conflict.
	1. git checkout --ours < file> let's you discard the changes from the incoming branch and keep the changes from the current branch
	1. git checkout --theirs < file> discards changes from the current branch and keeps the changes from the incoming branch
6. In a merged source code file, how does Git let you know there is a conflict?
	1. The git status command lets you identify the files creating the merge conflict
	1. In those files there's Git inserts conflict markers in the affected files to indicate the conflicting sections that require manual intervention.
7. What are the steps you can take to resolve Git conflicts?
	1. Identify and open the conflicting file, using git status you can find the conflicting file and when opening the file find the conflict markers in the file.
	1. Analyse the conflicting changes made in the current branch (between <<<<<< HEAD and =======) and the changes from the incoming branch (between ========= and >>>>>>>>> incoming_branch).
	1. Resolve the conflict then remove the conflict markers.
	1. Save the file(s)
	1. Add and commit the changes
8. What does git revert do, and how can you use it?
	1. git revert is a command in git that inverts the changes introduced by the commit and appends a new commit. Can be used to track down a bug and find what commit introduced the bug.
9. What does git reset do, and how can you use it?
	1. Used to undo changes. It has three primary forms --soft, --mixed, -- hard. These three arguments correspond to Git's three internal state management mechanism's. 
Used to undo local changes to the state of a Git repo. 
10. What is the difference between git revert and git reset?
	1. git revert is a safe alternative of undoing changes compared to reset as you risk losing work with a git reset. 
11. True or False: It is okay to commit broken code to the main branch.
	1. False 
12. True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.
	1. True
13. Describe what is DevOps, how is it useful for game developers?
	1. DevOps are tools used to automate manual task and help complex environments at scale. Useful for game devolpers as git is a DevOps tool and it helps manage source code for projects.
14. List what tools can be used with DevOps. Give a brief description of each one. (at least 3)
	1. Version Control is a tool for DevOps, Github is one of the larget DevOps tools, it is used to create, store, manage and share code amongst developers.
	1. Container Management tools like Docker helps manage containers, self-contained packeges of software that include all the components needed to run a piece of code. 
	1. Configuration Management is an automated method for maintaining computer systems and software in a known, consistent state.
15. What is CI/CD and how can it be used to automate the game development process?
	1. CI is continuous integration while CD refers to Continuous delivery and/or deployment. Github is a tool used for this process as you can automatically and frequently integrate code changes to test and deliver. 
		In Game Development you can use this to change your game by updating or patching it and then testing those changes to then deliever those code changes to the rest of the team and playerbase.