1 - Create an empty repository on GitHub

2 - Create a local repository with some files

3 - On the HyperTerminal, type:

- cd Git-Practice

- git init

- git status

- git add .

- git commit -m "Add two files"

- git branch

- git branch -M main

- git remote add origin https://github.com/TasneemZh/Git-Practice.git

- git push -u origin main
- git checkout -b temp
- touch README.md
- git status
- git add .
- git commit -m "Create README.md"
- git checkout main
- git rebase temp
- git push
- git checkout temp

4 - Change one of the files extensions [from txt to md]

5 - On the HyperTerminal, type:

- git status
- git add .
- git commit -m "Change the extension of git-command-local"

6 - Change the other file extension [from txt to md]

7 - On the HyperTerminal, type:

- git status
- git add .
- git commit -m "Change the extension of the second file"
- cat >>README.md
- *1 - Create an empty repository on GitHub*
- start README.md
- *[write more steps on README.md through the Atom application]*
- git rebase -i temp~3
- git status
- git branch -f main temp
- git push origin main
- git checkout main
- git branch -d temp
- git branch

8 - Format the two git-commands files on the remote repository

9 - On the HyperTerminal, type:

- git checkout -b new
- cat >>README.md
- *[write more steps on README.md through the HyperTerminal]*
- cat README.md
- git status
- git add .
- git commit -m "Write some content on README.md"
- git push origin new
- git checkout main
- git pull
- git merge new
- git push
- git push origin :new
- git branch -d new
- ls -a

### 10 - Format the README.md on the remote repository

### 11 - On the HyperTerminal, type:

> git fetch

> cat git-commands-local.md
*not updated yet*

> cat status
*the local main branch is behind the remote main branch by a number of commits*

> git merge origin/main

> cat git-commands-local.md
*now it is up-to-date*

#### 12 - Add the rest of steps on README.md on the remote repository








