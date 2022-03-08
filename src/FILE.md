
#Commands
git init<br>
git commit -m "commit 0"<br>
git branch bug-fix<br>
git commit -am "commit 1"<br>
git commit -am "commit 2"<br>
git checkout bug-fix<br>
git commit -am "commit 3"<br>
git commit -am "commit 4"<br>
git branch bug-fix-experimental<br>
git merge master<br>
git commit -am "commit 5"<br>
git commit -am "commit 6"<br>
git checkout bug-fix-experimental<br>
git commit -am "commit 7"<br>
git commit -am "commit 8"<br>
git commit -am "commit 9"<br>
git checkout master<br>
git commit -am "commit 10"<br>
git checkout bug-fix<br>
git merge bug-fix-experimental<br>
git commit -am "commit 11"<br>
git commit -am "commit 12"<br>
git checkout master<br>
git merge bug-fix<br>
git commit -am "commit 13"<br>
git commit -am "commit 14"<br>
git add src/commits.png<br>


#Image
![run.config](commits.png)
