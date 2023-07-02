# GIT command for staging a change:
* git add 

  The git add command is used in Git to stage changes and prepare them for a commit. When we make changes to our files in a Git repository, those changes are initially considered as "unstaged" or "untracked."

By using git add, we specify which changes or files we want to include in the next commit. It allows you to selectively stage specific files or changes instead of committing all the modifications at once.

*To stage a specific file:
git add filename.txt
*To stage all changes in the current directory and its subdirectories:
git add .
*To stage all changes in a specific directory:
To stage all changes in a specific directory:

#  GIT command for committing a change:
* git commit -m "Your commit message"

  The -m flag stands for "message" and allows one to provide a concise description of the changes we're committing.
  
# GIT command for pushing committed change
* git push
  
    After we have committed our changes using git commit, the git push command is used to upload those commits to a remote repository, typically hosted on a platform like GitHub, GitLab, or Bitbucket.
  
   Here's the basic syntax for the git push command:
  
* git push <remote> <branch>

The <remote> refers to the name of the remote repository where we want to push our commits. This is usually the name of the remote we cloned the repository from, such as origin.

The <branch> specifies the branch we want to push our commits to. 


