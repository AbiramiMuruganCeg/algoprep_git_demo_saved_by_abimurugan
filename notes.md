## Installation

- windows :https://git-scm.com/download/win
- macos :https://sourceforge.net/projects/git-osx-installler/
- linux : https://www.git-scm.com/download/linux

## setup

- check whether you git is installed or not.
  '''bash
  git --version

## config addition -->name, email

- list of configs

'''bash
git config --list
'''

- add your username and email id
  '''bash
  git config --global user.name "Your name"
  git config --global user.email "youremail@example.com"
  '''

  - how git stores the changes
  - git has three areas ->working directory -> current changes
  - Intermediate layer ->staging

  ## terms

  **Repository (Repo):**

  A storage location for your project, including all the files and their entire history of their changes.

  **staging area**-->Tracked Changes

  **Working directory**-->UnTracked Changes

# git workflow

* 'git init' -->Wherever you initiate the git an empty
  git repository is created.(tracker without any history)
* 'git add' --> added to staging area (snapshot of the code is added).
* '.gitignore' : this is the file where you can put the files and folder name which you don't want to be tracked.
* 'git add .' :->to send all the files current snap shot to
  staging area.
* 'git status' ->difference between staging and working directory.
* g'commit '->git commit -m "commit message" ->a snap shot of the changes made to the repository. Each commit has a unique id and a message describing the changes.
* 'git log'->list of commits
* 'git checkout commit-hash'=> you can view how code looked like in a particular commit 
  * to go back to latest commit-> 'HEAD'
     *type git branch ->check your branch name
     *'git checkout branch-name' ->

### Comments to push your changes
**setup remote git hub**
Create a repo in git hub    
* git remote add origin 'remote-repo-name'
*
* git branch -M main
<!-- usuall drillg -->
  * git push -u origin main


* hint
  git add script.js
  git status
  node script.js
