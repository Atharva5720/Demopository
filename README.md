# Demopository

Learning to use Git and GitHub

I will now pull this repository in VSC

Set path to required folder:
cd ../(folder name)

clone the online repository, use the command:
git clone (link)

## Creating updates

The hidden .git file visible upon using:
ls -la

In the terminal,the updates should be reflected upon using:
git status

Added identity:
git config --global user.email "atharva.parolekar@gmail.com"
git config --global user.name "Atharva Parolekar"

To add untracked files, use:
git add (filename) or . for all files

and then to commit, use:
git commit -m "message"

For some reason, I was able to skip SSH keys step to push changes onto GitHub. I suppose Git credentials handled the problem for me.

Pushed changes by using:
git push origin main


## Generated branch
By:
git checkout -b feature-README-edit

Current and all branches visible:
git branch

switching:
git checkout main / (branch name)

Make changes, add, commit as usual in new branch.

Visualise changes and hit 'q' to exit:
git diff (branchname)

Merge locally and then push as usual by:
git merge (branchname)

or first push it over to github:
git push (--set-upstream / -u) origin (branchname)

Pushed branches are automatically detected, compare and pull request can be submitted.
Additional comments can be added.
Upon resolution of conflicts, branches are merged.

To update the merged main branch locally:
git checkout main
'git pull origin main' or just 'git pull' if upstream set

delete feature branch:
git branch -d (branchname)