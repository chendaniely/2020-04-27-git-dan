# 2020-04-27-git

- init: create a git repository in current directory
    - you should only do this once in a repository (i.e., no nested git repos)
- status: tells you what is going on
- add: put files into the staging area
- commit: commit the stageing area with a message
    - `commit -m`: commit with the message without opening up text editor
- `log`: look at all the commit history you've been doing
    - `log --oneline`: simple oneline log view
- `diff`: look at differences between current state and what git knows
- `checkout`: moving our head
- `HEAD`: place we're looking at right now on our computer

- remote: a place where the git repo is stored, e.g., GitHub
    - `git remote add origin <URL>` add a remote
- `git push origin master`: to push the master branch on our loacal computer to the remote name origin
