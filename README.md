# Practice repository to learn Git

#Commands used

- git init: creat a repository
- git status: compare working directory, staging area, and current branch
- git add: add changes from working directory
- git commit: commit changes from staging area to current branch
- git config: set or get configuration
- git log: show history of project commits
- git checkout: check out branch (update HEAD and apply changes to working directory)
- git branch: -c: create a branch 
- git checkout -b: create a branch then check it out 
- git merge: Merge changes from different branches 
- git remote add <remote> <url>: Add a new <remote> at <url>
- git remote -v: List remote repositories 
- git push -u <remote> <branch>: Push <branch> to <remote>, and set default upstream for <branch> 
- git fetch: Fetch changes from remote repository


## What's a branch?
A branch is a ref(erence) to a commit. When HEAD points to a branch, we say we're on that branch. When we make a commit while we're on a branch, the branch is updated to ref(er) to the new commit. 

##commit messages

Default editor is vim (this can be changed)
  - `i` ti enter *insert* mode
  - type commit messages
  - `Esc` -> `:wq` or `:wq!` -> `Enter` to write message and quit
Or use `git commit -m "<meessage>"`

- First line should be clear, accurate and concise
- Use proper grammar and punctuation
- Don't end wiht a `.`

for more advice, see: https://chris.beams.io/posts/git-commit/
