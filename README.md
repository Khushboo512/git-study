1. diff btw git and github?

when first time install git any system we need to config email and username:
    git config --global user.email "you@example.com"
    git config --global user.name "Your Name"


basic commands:
    git status (for check git status)
    git diff filename (for check recent changes in file)
    git checkout filename (for remove all recent changes in file)
    git log -<number> (for checking git commit history)
    git show <commit id> (for checking git commit history)

steps for making changes:
1. Initialize repo
    git init

2. add files in stageing area
    git add file1, file2, file3 or git add . (for all files)

3. remove files from stageing area
    git reset file1, file2, file3 or git reset . (for all files)

3. commit all changes
    git commit -m "you can type any commit msg"

step for publish our code to github:
1. check remote repo is add or not:
    git remote -v

2. add remote repo:
    git remote add remote-alias remote-url (usually use origin as remote-alias)

3. push code local repo to remote repo
    git push remote-alias branch-name
