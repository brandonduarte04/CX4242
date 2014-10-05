CX4242
======

Central location for our project. 

How to commit:

1. git checkout master # be on master
2. git pull # update to most current master
3. git checkout -b export-pdf-fixes # start a new branch off master
# do work
4. git add js/my-changed-file.js # etc
5. git commit -m "Change the layout of test results" # commit changes
6. git push origin HEAD -u # push your new branch to github


Now on github, there'll probably be a little banner asking if you want to compare and pull request. Hit the green button if that's there, otherwise, go to the branches page, find your branch, and hit "new pull request". Give it a good title, explain the changes you made, and provide a detailed test outline for verifying its functionality.
