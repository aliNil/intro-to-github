# intro-to-github
This is a demo repository to practice using GitHub.

It has two files in the **Code** tab:
- **README.md** is a file that describes this repo (you are currently reading it)
- **.gitignore** is a file that specifies which files and directories must be ignored by Git

You cannot directly modify files in this repo because you are not a *collaborator*.

The **Issues** tab is used to discuss ideas, enhancements, bugs, questions, and so on. They are grouped by *Open* and *Closed*.

The **Pull requests** tab contains proposals to make some changes in the files located in the repository. Repo's owners may review a request and put your changes if they look good.

You can create an *Issue* or make a *Pull request (PR)* to contribute to the project.

If you want to propose some changes to this repo, you may *fork* it, modify the content, and create *PR*. A *fork* is just a copy that allows you to change the content without affection the original project.


## Editing this file (myself)
I add the code below to show how git and gitub works to gather

$ git clone https://github.com/hyperskill/intro-to-github.git

$ git status

On branch master
Your branch is up-to-date with 'origin/master'.

$ git branch edit-readme

$ git checkout edit-readme

$ git status

On branch edit-readme
nothing to commit, working tree clean

$ git add README.md


$ git commit -m "Add information about local repository in readme file"


$ git push --set-upstream origin edit-readme
there is no branch with name edit-readme in origin(remote server) therefore
we should write push command this way

$ git push
for changes after the first one we can simply use push 

$ git pull
if someone else is working on the same brach we should first pull the 
repo and then push our changes to avoid coflict in our codebase




