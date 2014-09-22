Learning Git 
==========

this is an example!

==========

##1. Basic
###1.1. Init
Local init repo, Or clone a repo from remote<br>
* Local init, and add remote repo<br>
In any directory, init local run follow command:
```Bash
git init
```
>now ,git initialize this directory as a repo, you will see a .git direcrory<br>

add remote git repo with this repo
```bash
git remote add origin git@github.com:andy6355/git-study.git
```

* Clone a repo from remote<br>
In any directory, run follow command:
```Bash
git clone git@github.com:andy6355/git-study.git
```
>before run this command,you should have this repo permission.
>otherwise,you can fork this repo to your repo,and clone it from your git url.


###1.2. Add file
For a new file, add to git repository, run follow command:
```Bash
git add [newfile]
```

###1.3. Commit change
After add new files, no matter how many files, run commit to submit changes, run follow command:
```Bash
git commit -m "your commit messages"
```

###1.4. status,diff
check repository status, it will show which file is modified and not commit to repository. diff command can show the changes with UNIX style diff format.
```Bash
git status
git diff [file]
```   

 
==========

##Cheatsheet
---------
![](https://github.com/andy6355/git-study/blob/master/static/cheat-sheet-large01.png "come from : http://www.git-tower.com/blog/assets/2013-05-22-git-cheat-sheet/cheat-sheet-large01.png")


