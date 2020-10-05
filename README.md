# GITHUB COMMANDS 

SMALL FILES - Work for all cases
----------------------------------
git init 

git remote add origin https://

git add .

git commit -m "Initial working commit"

git push origin master --force


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
