1. Write instructions on installing git on a windows system.
	1. Go to a search engine and type in "Git".
	2. the first link should be to the Git website, https://git-scm.com click on the link.
	1. Click on the text "Downloads" as it is a hyperlink.
	1. Click on the "Windows" text.
	1. Click the hyperlink text "Click here to download" as it will be the latest Git for Windows.
	1. Save the installation executable onto your computer and run it.
	1. Git will automatically have setting selected for you when you install it unless you want to change any you can keep clicking next until it installs.
	1. A html file will be downloaded as well, if you open it the file will take you to a website for the release notes for Git.
	1. If you had issues along any point you can go on google and look up your issue.

2. Do research on some principles/techniques of industry standard best practices creating and working with repositories and branches in Git. 
	1. Favour branching over forking when working with regular collaborators.
	1. Create a README file for every repository to help others understand and navigate your work.
	1. Have multiple branches like a branch for feature's your working on, bugfixes, testing, etc. These branches would later on be merged into main.
	1. Ensure naming of commits are accurate and detailed.
	1. Naming of branches needs to be accurate.
	1. Don't merge broken code into main.
	1. Ensure you pull before changing code.
	1. Commits should be small not large as a commit containing multiple bugfixes that needs to be reverted will cause more issues vs a small commit needing to be reverted and helps track bugs.
3. List the steps in a Git workflow that the team should follow when working on projects.
	1. Create a branch for Development, and staging.
	1. Work in Development for adding or fixing bugs.
	1. Commits should be small so 1 different bugfix is 1 different commit.
	1. Commits should be named the accurately and detailed about what was changed.
	1. Merge development into staging when testing the changes.
	1. Merge staging into main once changes are tested.