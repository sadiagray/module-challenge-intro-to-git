## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? git is an open source distributed version control system. 
essencially git is a system that is used to store and track content and 
the historyy of the changes. it allows multiple developers to work on a 
single project or repository. 
2. What is the difference between Git and GitHub? Git is a local version 
control system that allows developers to manage and keep track of their 
source code history. Github is a cloud-based hosting service that lets you 
manage repositories and the contributions of the individual developers 
working on a project. 
3. Why do we create a branch? branches allow you to encapsulate your 
changes to a repository and helps to organize work flow, especially when 
multiple developers are working on the same project. 
4. What is the purpose of a Pull Request? pull requests allow you to tell 
others working on a project about the changes youve pushed to a branch in 
a repository
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main. switch <branchname>
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do? 'git fetch' downloads commits, files, and refs from a remote repository to your local repo 'git 
merge' allows you to combine independent branches in a repository to a single branch. 'git pull' downloads content from a remote repository and updates the local repository to match the content. 
'git fetch' and 'git pull' are different in that 'git fetch' does not change the local files. 
7. What is a merge conflict? when two devolpers have made changes competing changes to the same line of a file or when one person edits a file and another deletes the same file
8. How do you resolve a merge conflict? to resolve a merge conflict you would use the 'git status' command to locate the conflicting files. you decide which changes you want to keep, or if both 
changes are needed you create a new branch, combine the change, then delete the conflict markers and continue on to a regular push using 'git add .' 'git commit -m"your message"' then 'git push'
