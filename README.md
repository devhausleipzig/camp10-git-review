# camp10-git-review

this is where we review some of the git commands

## How to GIT

1. Go to your GitHub account and make a new repo using the `+` sign.
2. Make sure to add a README file in it.
3. Go to the code and copy the SSH

4. Open your terminal, go to the folder where you want to clone the repo from GIT.

5. use `git clone` in the terminal followed by the SSH keys from above

6. `cd` into the git folder, and now you can see that you are on the main branch.

## some commands to try out

##### git status

This gives you the information regarding the current branch that you are currently checked in to, status of the files inside the current folder, and whether your local branch is ahead, behind or up to date with the remote branch.

##### git add

It adds the modified files and untracked files to the staging area (This is still in your local machine).

##### git commit

git commit takes the files from the staging area to local repo, and commit is like taking a snapshot

use `-m` followed by a `commit message` in "" to avoid entering a text editor

##### git push

git push will push my local commit to the remote repo

here: origin always refers to the branch on github(online)

local refers to your local machine or computer

> Note: When you push a new branch using git push it has no set upstream to track

so use `git push --set-upstream origin <name of the branch>`

##### git branch <branch name>

##### git branch

gives me the list of all the branches in my local

by using `-a` I can also look at all the branches that are currently remote

##### git checkout <name of the branch>

will take you to the branch

> Note: To make a new branch and immediately switch to it you could also use

`git checkout -b <name of the new branch>`

# Merging branch into another branch

1. git checkout main (or to branch that you want something to be merged in)

2. git pull (always update from your remote)

3. git checkout branch (the branch that you want to merge)

4. git merge main (merge the updated main or the updated branch into your branch: this process is called reverse merge)

5. resolve the conflicts, and when everything is good. add, commit, push the branch

6. switch back to the branch or main

7. git merge branch

8. see the merge is working in your code editor, and if satisfied git push
