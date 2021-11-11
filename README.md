# Git-CheatSheet

## Getting  Started

### Installation
Download `git` and install from [https://git-scm.com/downloads](https://git-scm.com/downloads)
### Configure tooling
```sh
git config --global user.name "[name]"
git config --global user.email "[email address]"
git config --global color.ui auto
```
### Basics

  ```sh
  git clone https_url

# Checking the list of remote and local branchs
  git branch -a
      
# Checking the list of Only remote branchs
  git branch -r
    
# Checking the list of Only local branchs
  git branch
  
# Creating and check out in a local branch
  git checkout -b local_branch_name_1
  
# After making changes and checking updates in my current branch
  git status
  
# commiting updates for the local branch
  git commit -m "updates"
  
# pushing local branch
  git push
  
# pushing local branch to upstream master branch
  git push origin main/master

  ```
