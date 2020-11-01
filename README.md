# angryBirdsStage2.5
Angry Birds stage 2.5 with Class Inheritance and Images
logs for git commands
git init
$ git config --global user.name
SanidhyaMalviya

hp@LAPTOP-CF6BLI74 MINGW64 ~
$ cd c/Users/hp/OneDrive/Documents/WHITE_HAT_JR/CLASSES
bash: cd: c/Users/hp/OneDrive/Documents/WHITE_HAT_JR/CLASSES: No such file or directory

hp@LAPTOP-CF6BLI74 MINGW64 ~
$ cd OneDrive

hp@LAPTOP-CF6BLI74 MINGW64 ~/OneDrive
$ cd Documents

hp@LAPTOP-CF6BLI74 MINGW64 ~/OneDrive/Documents
$ cd WHITE_HAT_JR

hp@LAPTOP-CF6BLI74 MINGW64 ~/OneDrive/Documents/WHITE_HAT_JR
$ cd CLASSES

hp@LAPTOP-CF6BLI74 MINGW64 ~/OneDrive/Documents/WHITE_HAT_JR/CLASSES
$ mkdir Class26

hp@LAPTOP-CF6BLI74 MINGW64 ~/OneDrive/Documents/WHITE_HAT_JR/CLASSES
$ cd Class26

hp@LAPTOP-CF6BLI74 MINGW64 ~/OneDrive/Documents/WHITE_HAT_JR/CLASSES/Class26
$ git Clone https://github.com/whitehatjr/AngryBirdsStage2.5StudentActivity.git
fatal: cannot handle Clone as a builtin

hp@LAPTOP-CF6BLI74 MINGW64 ~/OneDrive/Documents/WHITE_HAT_JR/CLASSES/Class26
$ git clone https://github.com/whitehatjr/AngryBirdsStage2.5StudentActivity.git
Cloning into 'AngryBirdsStage2.5StudentActivity'...
remote: Enumerating objects: 44, done.
remote: Total 44 (delta 0), reused 0 (delta 0), pack-reused 44
Receiving objects: 100% (44/44), 2.54 MiB | 1.99 MiB/s, done.
Resolving deltas: 100% (13/13), done.

hp@LAPTOP-CF6BLI74 MINGW64 ~/OneDrive/Documents/WHITE_HAT_JR/CLASSES/Class26
$ cd Angry

hp@LAPTOP-CF6BLI74 MINGW64 ~/OneDrive/Documents/WHITE_HAT_JR/CLASSES/Class26/Angry (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

hp@LAPTOP-CF6BLI74 MINGW64 ~/OneDrive/Documents/WHITE_HAT_JR/CLASSES/Class26/Angry (master)
$
no changes added to commit (use "git add" and/or "git commit -a")

hp@LAPTOP-CF6BLI74 MINGW64 ~/OneDrive/Documents/WHITE_HAT_JR/CLASSES/Class26/Angry (master)
$ git add README.md

hp@LAPTOP-CF6BLI74 MINGW64 ~/OneDrive/Documents/WHITE_HAT_JR/CLASSES/Class26/Angry (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


hp@LAPTOP-CF6BLI74 MINGW64 ~/OneDrive/Documents/WHITE_HAT_JR/CLASSES/Class26/Angry (master)
$ git commit -m "Git Commands"
[master 3ab2ac3] Git Commands
 1 file changed, 51 insertions(+)

hp@LAPTOP-CF6BLI74 MINGW64 ~/OneDrive/Documents/WHITE_HAT_JR/CLASSES/Class26/Angry (master)
$ git remote add test https://github.com/SanidhyaMalviya/Class-26.git

hp@LAPTOP-CF6BLI74 MINGW64 ~/OneDrive/Documents/WHITE_HAT_JR/CLASSES/Class26/Angry (master)
$ git push -u test
Enumerating objects: 47, done.
Counting objects: 100% (47/47), done.
Delta compression using up to 8 threads
Compressing objects: 100% (30/30), done.
Writing objects: 100% (47/47), 2.54 MiB | 1.42 MiB/s, done.
Total 47 (delta 15), reused 42 (delta 13), pack-reused 0
remote: Resolving deltas: 100% (15/15), done.
To https://github.com/SanidhyaMalviya/Class-26.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'test'.

