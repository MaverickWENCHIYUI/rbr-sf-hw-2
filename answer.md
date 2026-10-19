1.Working directory is the actual file that I can open and edit on my local device(like on VS Code)
Stageing area is a temporary zone when a group of modified files need to change
commit is saving my staged files into the local git history
remote repo is more like a server that store our local commits with a team

2.
HEAD is a dynamic pointer that normally indicates the exact commit is currently checked out to
main is usually the primary branch in repo
origin is the primary remote repo that clone my local repo from

3.
ensure you are writing codes base on the latest version codebase

4.
fetching is download all commits and branches from remote repo to local, it does not alter the working directory
pulling downloads the new changes while attempts to integrate them into current active branch

5.
merging combines two branches by creating a new merge commit. it preserves the history when commits were made
rebasing moves entire branch to another commit node. it creates a clean history without merge commits

when other people's work depend on the nodes, and you use rebase then it will become dangerous

6.
because it allows team members to discuss the changes and request a change to that 

7.
main and can branches had diverged, meaning both branches contained different commits. Git created a merge commit to combine the changes from both branches while preserving their history

8.
The can_id change was made in only one branch, so Git could automatically merge it without conflicts. However, both branches modified the same lines involving @version and loop(). Git could not determine which changes to keep

9.
A .gitignore file tells Git which untracked files and folders to ignore. 
It does not remove files because Git continues tracking them unless they are removed from the index. The .pio folder is ignored because it contains PlatformIO-generated build files and dependencies that do not need to be stored in the repository.