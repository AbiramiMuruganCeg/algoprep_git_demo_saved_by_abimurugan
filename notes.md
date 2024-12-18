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

# git workflow

* 'git init' -->Wherever you initiate the git an empty
   git repository is created.(tracker without any history)
* 'git add' --> added to staging area (snapshot of the code is added).
* '.gitignore' : this is the file where you can put the files and folder name which you don't want to be tracked.
* 'git add .' :->to send all the files current snap shot to
staging area.


- hint
  git add script.js
  git status
  node script.js
