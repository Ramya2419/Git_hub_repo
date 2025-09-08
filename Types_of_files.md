Untracked: New file that git doesnt yet track
Modified: Changed
Staged: File is ready to be committed
Unmodified: unchanged

On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md (red color)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Types_of_files.md. (red color)

no changes added to commit (use "git add" and/or "git commit -a")

Add & Commit
add: add new or changed files in your working directory to the git staging area
 git add <filename>

On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Types_of_files.md. (green color)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md.  (red color)

git status .
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md   (green color)
        new file:   Types_of_files.md   (green color)

 Commmit: record of change
 git commit -m "msg"        (Commits in local machine)


 types_of_files
 2 files changed, 58 insertions(+)
 create mode 100644 Types_of_files.md

git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

push command
upload local repo content to remote repo
git push origin main 