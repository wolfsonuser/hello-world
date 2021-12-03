# hello-world
This is lemmi edit
=============
This is the description of the repository "hello-world".
=====================
Following the tips at guides dot github dot com activities hello-world
===========================
This is a branch ready to commit and this is the message.
==================================

# 12.02.2021
## This is a fork from nelsondio/hello-world made on the web
### This is a new entry to commit and to make a pull request
### patch-1 to fix an error 1001
### =========================
### NELSONDIO: steps to get here:
1) Pull request
2) create a pull request
3) nelsondio:master vs wolfsonuser:master there isn't anything to compare since the pull request was automatically merged by nelsondio a few minutes back.
4) Try switching the base for your comparison: 
5) base repository nelsondio/hello-world base: master <==== head repository wolfsonuser/hello-world compare: master
6) with an option: compare across forks. This is the option I selected previously. When I made a pull request, automatically generated a branch patch-1.
7) After base allowed to merge with head of wolfsonuser, it showed option to delete wolfsonuser/hello-world but a BIGGGG warning in setting, dangerous, risky, be carefull!!!. I authorized since I can write in nelsondio. 
8) Pending what to do with wolfsonuser/hello-world since master and patch-1 are not merged yet.
### ==============================
## Wolfsonuser patch-2 pull request started.
### follow the steps and see after commiting changes.
## ====================================
### it merged automatically with wolsonuser master, but I did not see the fork comparison option
### start patch-3 pull request to merge wolfsonuser as head and nelsondio master as base
## ===========================
### patch-4
#### nelsondio forgot to merge request
#### nelsondio quit  and  nothing was merged. 
#### wolfsonuser could not reopen the pull request.
#### wolfsonuser began new pull request after committing this
## =====================================
## patch-5 from VS Code laptop
### Clone repository, it asked to login with wolfsonuser and password, even though I created ed25519 keys and added to the account.
### TODO Edit README from VS code, commit, push to remote rep, make pull request to nelsondio
## ===========================

## 12.03.2021
### git clone https://github.com/somebody/something.git // rep you are interested in
### cd into something
### git checkout -b something-patch-1
### make some changes or patch
### git status
### git add . 
### git commit -m "Message patch-1 for instance"
### git remote -v
### git push origin something-patch-1
### create pull request
#### base rep: somebody/something.git master
#### head rep: yourfork/something.git master
### if your pull request is accepted you'll receive an email
### git branch
### git checkout master
### git remote add upstream https://somebody/something.git
### git fetch upstream
### git merge upstream/master
### git push origin master // this is your own fork synced
### git remote rm [remote name] // you may want to keep the local
### git branch -d something-patch-1
### git push origin --delete something-patch-1 //delete the branch on github too

## ====================================
### 12.03.2021 10+00 AM
### Merge pull request command line instructions
### Automatic merge cannot be performed or you want to test the changes first:
1) Step 1: git checkout -b wolfsonuser-master master
2)         git pull https://github.com/wolfsonuser/hello-world.git master
3) Merge the changes and update to github
3) Step 2: git checkout master 
           git merge --no-ff wolfsonuser-master
           git push origin master

