**GIT command for staging a change:**
The ${`git add`} command is used in Git to stage changes and prepare them for a commit. When we make changes to our files in a Git repository, those changes are initially considered as "unstaged" or "untracked."

By using ${`git add`,} we specify which changes or files we want to include in the next commit. It allows us to selectively stage specific files or changes instead of committing all the modifications at once.

1- To stage a specific file:
git add filename.txt

2- To stage all changes in the current directory and its subdirectories:
git add .

3- To stage all changes in a specific directory:
git add path/to/directory/

*GIT command for  Committing a change:*
The Git command for committing a change is ${bold}`git commit`. ${normal} After staging our changes using 'git add' to select the files or modifications we want to include in the commit, you use git commit to permanently save those changes to the Git repository's history.
***git commit -m "Your commit message"***
The -m flag stands for "message" and allows one to provide a concise description of the changes we're committing.

*GIT command for Pushing a committed change*
The Git command for pushing a committed change is ${bold}`git push`. ${normal} After we have committed our changes using git commit, the git push command is used to upload those commits to a remote repository, typically hosted on a platform like GitHub, GitLab, or Bitbucket.
***git push <remote> <branch>***
The  ${bold}`<remote>` ${normal} refers to the name of the remote repository where we want to push our commits. This is usually the name of the remote we cloned the repository from, such as origin.

The ${bold}`<branch>` ${normal} specifies the branch we want to push our commits to. For example, if we are working on the main branch, we would run:
***git push origin main***
This command pushes the commits from our local main branch to the main branch of the remote repository named origin.


