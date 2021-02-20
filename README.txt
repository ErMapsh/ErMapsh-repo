this file i was do for understanding  how normal directory begin git repository/

open file location where u want to make git repository - click right click then there two git option are available after 
installing git in our PC.

1.  open dirctory as git bash  after first check that u choosen directory is already git repository or not,
thats check using first command (git status) that will show git directory exist or not.  

2. check git version using next command git --version

3. if git repository do not exist then do this directory as git repository and make .git hidden repository .

directory, staging area, commit:

in directory data are change or u wanna commit data then  untracted file are found then use this command -- 
( git add .) 

then in staging area all files are tracked using above git add . command

then tracking file are commiting the file such as ex.text we are use this command= 
(git commit -m "commiting anything that related to changes")
then file is commited 

after  all file commiting use ( git push -u origin master) cmd for pushing data in github.
==============================================================================================
cmd for changes in file-
git diff for 
git diff --staged filename  for  staging area  after use git add . cmd

after changing the file and pushing  a data in github, but u want to back before changing file then use this command
git reset "that filename"
git checkout .  = for all file 
git checkout  file.extension
============================================================================================
staging 3 stage:
git pull is use for see any changes in repository by another user.
=======================================================================================

then u want any repository as projet as your repo then use this command
git clone "(ssh link of that repository)" 
using this download that repository in your pc

===================================================
 

then u want ingore some file that file u not want at that time then make a 
gitignore file using command - (touch .gitignore)

and then enter the command (notepad .gitignore)
and enter that command or file name or file extension 