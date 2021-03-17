Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.

Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

When you are not ready to commit changes but do not want to lose them either, git stash is a great option. This command temporarily removes changes and hides them, giving you a clean working directory. When you are ready to continue working on the changes, simply use the git stash apply command to retrieve the hidden changes.

A collaborator can create a branch, work on it and save commit snapshots within it, switch between various branches, and merge changes. A Git branch is basically a movable pointer that always points to the most recent commit, or snapshot. Git uses the default local branch name “master,” which can be changed. Just because the default name is “master” does not imply that it is higher in importance or has more functionality than other branches. The head is a special pointer which indicates which branch you are currently working within.

A popular alternative to merging is rebasing.