Today we will learn about what git branch is and some git commands overall:
# Git Branch: A git Branch is a pointer to the latest commit in th repo.
# Commit: it is a literal snapshot of changes in the index area or staging area 
# Index: it is a staging area where we add changes we want to be captured.
# Working Directory: it is where we work 
# head or main : is the pointer pointing to the latest commit
# git add: it is a git command which makes changes being add to the staging area.
# git commit: it is a git command which makes a snapshot of changes in the staging area.
# git commit --amend: it amends the latest commit message or if we want changes we didn't include in the commit before we can stage it and include on the latest commit.
# git rebase -i: we can go back in the history of commits and pick the commit we want to edit and for a just moment git will ignore all the changes happened after this commit and then we can stage the file we want and add to this commit or edit the commit message as we like.
# git log --oneline: shows as the commit we did 
# git status: shows us the status of the index, working directory, and the head.
# git reset: this reset is a git command in which we forget the commit we did and have three kind of git reset, :
 # git reset commitpointer --soft: only moves the head to the specfic commit but doesnot remove the changes from the index.
 # git reset commitpointer --hard: moves the head to a specfic commit , removes it from the index, and removes it from working directory.
 # git reset commitpointer --mixed:
  moves the head to a specfic commit,
  removes it from the index, but doesnot remove it from the working directory.