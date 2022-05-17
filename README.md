1. diff btw git and github?

when first time install git any system we need to config email and username:
    git config --global user.email "you@example.com"
    git config --global user.name "Your Name"


basic commands:
    git status (for check git status)

steps:
1. Initialize repo
    git init

2. add files in stageing area
    git add file1, file2, file3 or git add . (for all files)

3. remove files from stageing area
    git reset file1, file2, file3 or git reset . (for all files)

3. commit all changes
    git commit -m "you can type any commit msg"