1. List three major version control software for software engineering 
	a. Git
	b. Apache Subversion
	c. Mercurial 

2. What are the main advantages to using Git in your software development, and how is it useful for game developers.
	a. Being able to share software and code easily 
	b. Push through updates and patches 
	c. Revert changes if there's a bug
	d. Branches allow for testing of new code without interfering with the main code and you can merge the code to the main easily.
3. Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge
	a. Branch - A branch allows for development off of the main code without having that main code affected. You can merge the branch and the main afterwards when the branch is ready
	b. Pull - Get the latest repository from the remote repository and update your local repository..
	c. Push - Upload your local repository to the remote repository 
	d. Repository - A repository is a place where you can store your code, files, and see each file's revision history. These repositories can have multiple collaborators and respositories can be public, 
which can be seen by anyone, or private.
	e. Working Copy - In Git a working copy is a directory full of files with a .git subdirectory. The same as a local repository.
	t. Merge -  A merge is an action in Git where you get one branch from a repository and merge it into another.
	
4. If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.
	a. Pulling before working in the policy and procedure as if someone works on an old copy or forgets to pull that would lead to conflicts with the code.
	b. Naming Pushes and changes appropriately would allow for clear organisation and communication.
	c. Working in Branches when testing and developing code would ensure the main code is safe from errors and bugs from development.
	d. Communicating when wanting to revert back a change or merge a branch so merge conflict errors are minimal.
5. Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.
	a. Visual studio code has tools to let you know what and where the merge conflict is.
	b. git mergetool can be run after a merge to resolve merge conflicts.
	c. Git status lets you identify what files are creating the merge conflict.
	d. git checkout --ours < file> let's you discard the changes from the incoming branch and keep the changes from the current branch
	e. git checkout --theirs < file> discards changes from the current branch and keeps the changes from the incoming branch
6. In a merged source code file, how does Git let you know there is a conflict?
	a. The git status command lets you identify the files creating the merge conflict
	b. In those files there's Git inserts conflict markers in the affected files to indicate the conflicting sections that require manual intervention.
7. What are the steps you can take to resolve Git conflicts?
	a. Identify and open the conflicting file, using git status you can find the conflicting file and when opening the file find the conflict markers in the file.
	b. Analyse the conflicting changes made in the current branch (between <<<<<< HEAD and =======) and the changes from the incoming branch (between ========= and >>>>>>>>> incoming_branch).
	c. Resolve the conflict then remove the conflict markers.
	d. Save the file(s)
	e. Add and commit the changes
8. What does git revert do, and how can you use it?
	a. git revert is a command in git that inverts the changes introduced by the commit and appends a new commit. Can be used to track down a bug and find what commit introduced the bug.
9. What does git reset do, and how can you use it?
	a. Used to undo changes. It has three primary forms --soft, --mixed, -- hard. These three arguments correspond to Git's three internal state management mechanism's. 
Used to undo local changes to the state of a Git repo. 
10. What is the difference between git revert and git reset?
	a. git revert is a safe alternative of undoing changes compared to reset as you risk losing work with a git reset. 
11. True or False: It is okay to commit broken code to the main branch.
	a. False 
12. True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.
	a. True
13. Describe what is DevOps, how is it useful for game developers?
	a. DevOps are tools used to automate manual task and help complex environments at scale. Useful for game devolpers as git is a DevOps tool and it helps manage source code for projects.
14. List what tools can be used with DevOps. Give a brief description of each one. (at least 3)
	a. Version Control is a tool for DevOps, Github is one of the larget DevOps tools, it is used to create, store, manage and share code amongst developers.
	b. Container Management tools like Docker helps manage containers, self-contained packeges of software that include all the components needed to run a piece of code. 
	c. Configuration Management is an automated method for maintaining computer systems and software in a known, consistent state.
15. What is CI/CD and how can it be used to automate the game development process?
	a. CI is continuous integration while CD refers to Continuous delivery and/or deployment. Github is a tool used for this process as you can automatically and frequently integrate code changes to test and deliver. 
		In Game Development you can use this to change your game by updating or patching it and then testing those changes to then deliever those code changes to the rest of the team and playerbase.