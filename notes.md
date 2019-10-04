Very first time on a computer
-----------------------------

git config --global user.name "seanlegg9"
git config --global user.email "seanlegg9@gmail.com"

Once every new project, in the project folder
---------------------------------------------

git init

Every time I want to know what step I'm on
------------------------------------------

git status

Three step commiting process
----------------------------

* Make code changes, saved and run -> no errors
* Add code changes to the stage
    git add file_that_changed.rb
* Commit changes
    git commit -m "My commit message"

Show history
------------

git log

Make repository on GitHub
-------------------------

Drop down the + in the top right corner

Send to repository
------------------

git remote add origin https://"URL-Goes-Here"
git push -u origin master

To update on GitHub
-------------------

git push

To clone to work at home
------------------------

git clone https://"URL-Goes-Here"

To bring homework back on school computer
-----------------------------------------

git pull