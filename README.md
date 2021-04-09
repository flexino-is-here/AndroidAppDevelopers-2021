# AndroidDevelopers-2021
GIT Commands to be used by all

A) Install GIT and GITFlow on your system

B) Follow instructions to push your work on the repository. 
https://blog.scottlowe.org/2015/01/27/using-fork-branch-git-workflow/
  
C)Create new branch in your git account forked repository according to your group and email id
 Like if you belong to Group A and your email is demo@gmail.com
 then your branch would be a-group-demo.
 
D) After finishing your task you have to push changes in this repository.

E) Do also add snapshot or video of your work in the current directory.

Command Used- 
mkdir DIGILOCKER_TASKS
cd DIGILOCKER_TASKS
git clone https://github.com/flexino-is-here/AndroidAppDevelopers-2021.git   //use forked repo url
cd AndroidAppDevelopers-2021
git remote add upstream https://github.com/wideclassrooms/AndroidAppDevelopers-2021.git
git checkout -b m-group-aavipul11               //change according to the format
notepad README.md
git add .
git commit -m "first commit" .