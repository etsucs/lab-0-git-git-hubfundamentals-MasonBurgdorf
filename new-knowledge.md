# GitHub: 

*	Version Control System (VCS)
*	Way to manage files and directories
*	A platform to host git code repos
*	Can recall previous versions
*	Most popular Git host
*	Allows users to collaborate on projects from anywhere
*	Free!
# Git: 
*	Created in 2005 and is cross-platform, open source, and free
*	Distributed Version Control (DVC)
*	No single point failure
*	No need to connect to central server or an internet connection
# Repository (Repos)
*	Used to organize a single project
*	Can contain folder, files, images, videos, spreadsheet, and any other data constructs
# Branching
*	Ways to add new features and fixes without messing up the original code
*	Exists to manage workflow
*	Idea doesn’t work? Delete the Branch
*	Have many different versions of the same problem? Branch
# Main (<del> Master)
*	The main starting branch. All repos have one
*	Has latest working commit
*	In most cases don’t make direct changes to this. Use branching and work in it as a test environment
*	Branching is a core concept in Git and the entire GitHub flow is based on it. Only rule is that anything in the main branch is deployable
*	Extremely important that new branch is created off main when adding a feature or fixing a bug
# Commits
*	When new branch off main has been made its time to start making changes
*	When you add, edit, or delete a file you make commits and add them to your branch
*	This process of adding commits keeps track of progress as you work on feature branch
*	Commits also create a transparent history of work that others can follow to understand what you’ve done and why
*	An associated commit message is description of why a specific change was made
*	Work in small segments 
*	Each commit is considered a separate unit of change
*	This allows you to roll back changes if a bug is found or if you decide to head in a different direction
*	Write clear and concise committee messages
# Pull Request
*	Pull Requests initiate discussion about your commits
    * Can be done when?
    * Share something.
    *	Stuck and need help
*	Review your work
*	Great for collaboration or help
*	Pull Requests help start code review and conversation about proposed changes before they're merged into the main branch.
# Merge and Deploy
*	Once your pull request has been reviewed and the branch passes your tests, you can deploy your changes to verify them in production
*	If branch causes issues, you can roll back by deploying the existing main branch into production
*	Pull Requests preserve a record of the historical changes to your code
*	This is searchable to find out why things have been done
*	Keywords help with making historical documents and the changes that occurred
# Questions
* Don't really have any at the moment, but I know I'll have some in the future:smiley:
# Note
*	*Sometimes devs choose to place repo on GitHub as a central place where everyone commits changes, but it doesn’t have to be on **GitHub** specifically*
