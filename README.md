# GITHUB COMMANDS 


# Refer this handbook for GITHUB
==================================

* https://docs.github.com/en/get-started/using-git/about-git

* Colt -> https://www.youtube.com/watch?v=nhNq2kIvi9s&t=1s

* WebDev Simplified -> https://www.youtube.com/watch?v=IHaTbJPdB-s&t=1244s

* Love Babbar -> https://www.youtube.com/watch?v=uj4fy4kpaOA

* Anuj -> https://www.youtube.com/watch?v=uaeKhfhYE0U


GITHUB COMMANDS -> SMALL FILES - Work for all cases
---------------------------
* open folden location - where u have project

* open location of - folder & write - cmd

HOW TO ADD IMAGE IN GITHUB -> click on the New Issue button and drag and drop your image inside Leave a comment box.

![WhatsApp Image 2021-05-06 at 12 43 46 PM](https://user-images.githubusercontent.com/41515202/117257356-69842880-ae69-11eb-9961-bea900d6c010.jpeg)

![WhatsApp Image 2021-05-06 at 12 43 53 PM](https://user-images.githubusercontent.com/41515202/117257333-64bf7480-ae69-11eb-838b-e92620a7ba5e.jpeg)

Then perform -> these "OPERATIONS" -> in CMD::

1).  git init ----------------------------------------------------------------> (create .git folder)

2).  git clone https:// ------------------------------------------------------> (clone)

3).  git remote add origin https://  -----------------------------------------> (add/upload all files to -> existing/given repo created by you)

4.1).  git add . -------------------------------------------------------------> (add/upload all files)

4.2).  git add lol.txt -------------------------------------------------------> (only add/upload given file i.e., lol.txt)

5).  git commit -m "Initial working commit" ----------------------------------> (alwayas after adding files -> always save/commit)

6).  git push origin master --force ------------------------------------------> (push all the files from local folder -> to repo) 
(or) git push -u origin main


Extras
======
* mkdir (create new directory)

* cd (move into directory)

* ls (list the contents of a folder/directory)

* pwd (show your present/current directory)

* git pull 

* fork


* git diff (show what changes have u done)

* git log (show all summary/logs)

* git status (check branch status)

* git branch (show branch)

* git branch -b AkashBranch (or) git branch AkashBranch (create branch)

* git branch -d AkashBranch (delete branch)

* git checkout -b AkashBranch (or) git checkout -b AkashBranch  (create/switch to branche(s))

* git merge -b AkashBranch (or) git merge AkashBranch (merge into one branch)

====================================================================


# …or create a new repository on the command line
echo "# lol" >> README.md
* git init
* git add README.md
* git commit -m "first commit"
* git branch -M main
* git remote add origin https://github.com/akashkam559/lol.git
* git push -u origin main

# …or push an existing repository from the command line
* git remote add origin https://github.com/akashkam559/lol.git
* git branch -M main
* git push -u origin main


# …or import code from another repository
* You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

==============================================================================

problem - in pushing code => watch this ::
* go to control panel -> manage credendial -> find github -> delete all previous credentials -> GITHUB small Box will open -> enter ID & pass > again enter ID & Pass - in CMD (if asked)

* or watch this video -> to get fixed
https://www.youtube.com/watch?v=R8QmCCcm0GU ... 
.
https://www.youtube.com/watch?v=KnuaVfi5MFU
.
====================================================================.
.
LARGE FILES/LFS
----------------
git init

git remote add origin https://

git add . / git add .gitattributes / git add flight_rf.pkl

git pull 

#git commit -m "Add Comments Test"

git push --set-upstream origin Master -> git push
git lfs push --all origin master
git push -u origin master
git pull --rebase origin master
git push origin master

---------------------------------------
git lfs install

git lfs track "*.psd"

git add .gitattributes

git add file.psd

git commit -m "Add design file"

git push origin master

---------------------------------------
*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

==============================================================================

Deployement
-----------
1). make account 

2). create app => by giving to app

3). connect with -> GITHUB pipeline

4). choose pipeline -> master / Main  

5). deploy button

==============================================================================

* 1 cd barclaysBatch1/ 
* 2 dir 
* 3 git -version
* 4 git --version 
* 5 git branch 
* 6 git log
* 7 dir 
* 8 git checkout a7fe97585c7d32725723d3b9ac4547bbfe01242b
* 9 git log
* 10 cd ..
* 11 dir
* 12 cd barclaysBatch1/
* 13 cd ..
* 14 cd barclaysBatch1/ 
* 15 dir 
* 16 git checkout main 
* 17 git log
* 18 dir
* 19 pwd 
* 20 git log 
* 21 git log --oneline 
* 22 git checkout a7fe975 
* 23 git log
* 24 git log --all
* 25 git log --all --oneline
* 26 git log --all --oneline --graph
* 27 git checkout main 
* 28 git status 
* 29 git status 
* 30 git checkout a7fe975
* 31 git restore x.java
* 32 git status 
* 33 git log 
* 34 git status 
* 35 git status 
* 36 git add x.java
* 37 git status
* 38 git restore x.java
* 39 git status 
* 40 git restore --staged x.java
* 41 git status 
* 42 git add x.java
* 43 git status 
* 44 git status
* 45 git add a.txt
* 46 git status 
* 47 git status 
* 48 git add .
* 49 git status 
* 50 git commit -m "added a, b, c.txt and modified x.java"
* 51 git config --global user.email "developer@skillrary.com" 
* 52 git config --global user.name "Mithun Ashok"
* 53 git commit -m "added a, b, c.txt and modified x.java"
* 54 git status 
* 55 git log
* 56 dir
* 57 git checkout 0ca46b9a7c905ee9c614dfe2669eb2337663f12d 
* 58 ir 
* 59 dir
* 60 git log 
* 61 git checkout main 
* 62 git checkout 0ca46b9a7c905ee9c614dfe2669eb2337663f12d 
* 63 git tag V1.1 
* 64 git checkout main
* 65 git checkout V1.1
* 66 git checkout main 
* 67 git log
* 68 git tag V1.1
* 69 git status
* 70 git push 
* 71 git push 
* 72 git log 
* 73 git bracnch 
* 74 git branch 
* 75 git branch --all 
* 76 git log --oneline
* 77 git branch feature123 
* 78 git branch
* 79 git log
* 80 git checkout feature123 
* 81 git branch
* 82 git status
* 83 git add a.txt
* 84 git status 
* 85 git commit
* 86 git config --global core.editor notepad.exe
* 87 git log
* 88 git status
* 89 git add x.java
* 90 git status 
* 91 git commit
* 92 git log
* 93 git log --oneline
* 94 git log --oneline --graph
* 95 git checkout master 
* 96 git checkout main
* 97 git log --oneline
* 98 git log --oneline -all
* 99 git log --oneline --all
* 100 git merge feature123 
* 101 git log --oneline
* 102 git checkout feature123
* 103 git status
* 104 git add b.txt
* 105 git commit -m "Added oneline to b.txt"
* 106 git statu 
* 107 git add c.txt 
* 108 git commit -m "added oneline to c.txt"
* 109 git log --oneline
* 110 git checkout main 
* 111 git status
* 112 git add b.txt
* 113 git commit -m "added line to b.txt"
* 114 git log --oneline --all
* 115 git log --oneline --all --graph
* 116 git merge feature123 
* 117 git status 
* 118 git commit
* 119 git add b.txt
* 120 git commit -m "merging"
* 121 git status 
* 122 git log --oneline --graph --all
* 123 git push
* 124 git log --oneline --graph --all
* 125 git log --oneline --graph --all
* 126 dir 127 git fetch 
* 128 dir 
* 129 git log --oneline --graph --all 
* 130 git pull
* 131 dir 
* 132 git log --oneline --graph --all
* 133 history

