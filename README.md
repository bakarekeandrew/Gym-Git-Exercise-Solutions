# Git Exercise
## Bundle 1
### Exercise 1

```

gymubutwari@Ubutwaris-iMac Git-Exercise % ls
gymubutwari@Ubutwaris-iMac Git-Exercise % git init
Initialized empty Git repository in /Users/gymubutwari/Documents/thegym/Git-Exercise/.git/
gymubutwari@Ubutwaris-iMac Git-Exercise % git add .
gymubutwari@Ubutwaris-iMac Git-Exercise % git add .
gymubutwari@Ubutwaris-iMac Git-Exercise % git status        
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   trial.html

gymubutwari@Ubutwaris-iMac Git-Exercise % git branch -m master main
gymubutwari@Ubutwaris-iMac Git-Exercise % git branch    
* main
gymubutwari@Ubutwaris-iMac Git-Exercise % git branch -m main master
gymubutwari@Ubutwaris-iMac Git-Exercise % git branch
* master
gymubutwari@Ubutwaris-iMac Git-Exercise % git commit -m "first exercise"
[master (root-commit) a324dcb] first exercise
 Committer: Gym Ubutwari <gymubutwari@Ubutwaris-iMac.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 11 insertions(+)
 create mode 100644 trial.html
gymubutwari@Ubutwaris-iMac Git-Exercise % git remote add origin https://github.com/bakarekeandrew/Gym-Git-Exercise-Solutions.git
gymubutwari@Ubutwaris-iMac Git-Exercise % git status
On branch master
nothing to commit, working tree clean
gymubutwari@Ubutwaris-iMac Git-Exercise % git remote -v
origin  https://github.com/bakarekeandrew/Gym-Git-Exercise-Solutions.git (fetch)
origin  https://github.com/bakarekeandrew/Gym-Git-Exercise-Solutions.git (push)
gymubutwari@Ubutwaris-iMac Git-Exercise % git push -u origin master
Username for 'https://github.com': bakarekeandrew
Password for 'https://bakarekeandrew@github.com': 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 407 bytes | 407.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/bakarekeandrew/Gym-Git-Exercise-Solutions.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.
gymubutwari@Ubutwaris-iMac Git-Exercise % git checkout master
Already on 'master'
Your branch is up to date with 'origin/master'.
gymubutwari@Ubutwaris-iMac Git-Exercise % git checkout -b dev
Switched to a new branch 'dev'
gymubutwari@Ubutwaris-iMac Git-Exercise % git checkout dev
Already on 'dev'
gymubutwari@Ubutwaris-iMac Git-Exercise % git checkout -b test
Switched to a new branch 'test'
gymubutwari@Ubutwaris-iMac Git-Exercise % git checkout dev
Switched to branch 'dev'
gymubutwari@Ubutwaris-iMac Git-Exercise % git branch -d test
Deleted branch test (was a324dcb).
gymubutwari@Ubutwaris-iMac Git-Exercise % git branch
* dev
  master
gymubutwari@Ubutwaris-iMac Git-Exercise % 

```
