- Adding multiple files of a certain type

- Adding all files in directory (including hidden)

- Removing files

- Ignoring files

git init
git add *.html
git status
git commit -m "Add all html files"
git log

# add all files
git add -A

# remove files from the stage
git reset HEAD <file>

# ignoring files
touch .gitignore

# herein name the files to be ignored
# add and commit

git add -A
git status
git commit -m "Hide files"
