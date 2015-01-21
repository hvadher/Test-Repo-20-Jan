# Test-Repo-20-Jan
This is test repository Jan - 2015

https://github.com/github/gitpad

git config --list
git config --global --list

git status
git commit -m "Add file2.txt"
git add file2.txt
git commit -m "Add .txt to file1.txt"

git add file*
git status
git commit -m "Multiple staging"

git diff
git diff --staged
git diff HEAD

git log --patch
git log
git log --oneline
git log -S text_to_be_search
git log --grep file2

git branch
git branch -m rename_master_branch
git branch branch1_60
git checkout branch1_60
git log --oneline --graph --decorate --all
