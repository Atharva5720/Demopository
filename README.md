# Demopository

Learning to use Git and GitHub

I will now pull this repository in VSS

## Creating updates

The hidden .git file visible upon the command:
ls -la

In the terminal,the updates should be reflected upon using the command:
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