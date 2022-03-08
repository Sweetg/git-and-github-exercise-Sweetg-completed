git init<br>
git commit -m "commit 0"
git branch bug-fix
git commit -am "commit 1"
git commit -am "commit 2"
git checkout bug-fix
git commit -am "commit 3"
git commit -am "commit 4"
git branch bug-fix-experimental
git merge master
git commit -am "commit 5"
git commit -am "commit 6"
git checkout bug-fix-experimental
git commit -am "commit 7"
