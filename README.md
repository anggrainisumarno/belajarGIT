# belajarGIT
Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT
Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev
$ git init
Initialized empty Git repository in C:/webdev/.git/

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev (master)
$ git clone https://github.com/anggrainisumarno/belajarGIT
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev (master)
$ cd belajar git
bash: cd: too many arguments

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev (master)
$ cd belajarGIT

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git branch Tugas-git

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-GIT.txt

nothing added to commit but untracked files present (use "git add" to track)

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (Tugas-git)
$ git add Tugas-GIT
fatal: pathspec 'Tugas-GIT' did not match any files


Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (Tugas-git)
$ git add Tugas-GIT.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (Tugas-git)
$ git commit -m "Tugas-Git"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Asus@LAPTOP-A3F30CDJ.(none)')

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (Tugas-git)
$  git config --global user.email "anggrainipsumarno18@gmail.com"

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (Tugas-git)
$ ^C

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (Tugas-git)
$  git config --global user.name "anggrainisumarno"

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (Tugas-git)
$ git commit -m "Tugas-Git"
[Tugas-git 492d815] Tugas-Git
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-GIT.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (Tugas-git)
$ git checkout Tugas-git
Already on 'Tugas-git'

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (Tugas-git)
$ ^C

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git merge Tugas-git
Updating f721b90..492d815
Fast-forward
 Tugas-GIT.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-GIT.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git push

Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 302 bytes | 43.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/anggrainisumarno/belajarGIT
   f721b90..492d815  main -> main

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git branch belajarHTML

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git checkout belajarHTML
Switched to branch 'belajarHTML'

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarHTML)
$ git status
On branch belajarHTML
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-GIT.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-HTML.txt
        log.txt

no changes added to commit (use "git add" and/or "git commit -a")

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarHTML)
$ git add .

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarHTML)
$ git commit -m "belajarHTML"
[belajarHTML 9ae0b14] belajarHTML
 3 files changed, 47 insertions(+), 1 deletion(-)
 create mode 100644 Tugas-HTML.txt
 create mode 100644 log.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarHTML)
$ git chekcout main
git: 'chekcout' is not a git command. See 'git --help'.

The most similar command is
        checkout

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarHTML)
$ git chekout main
git: 'chekout' is not a git command. See 'git --help'.

The most similar command is
        checkout

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarHTML)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git merge belajarHTML
Updating 492d815..9ae0b14
Fast-forward
 Tugas-GIT.txt  |  4 +++-
 Tugas-HTML.txt |  1 +
 log.txt        | 43 +++++++++++++++++++++++++++++++++++++++++++
 3 files changed, 47 insertions(+), 1 deletion(-)
 create mode 100644 Tugas-HTML.txt
 create mode 100644 log.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 889 bytes | 88.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/anggrainisumarno/belajarGIT
   492d815..9ae0b14  main -> main


Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git branch belajarCSS

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git checkout belajarCSS
Switched to branch 'belajarCSS'
M       log.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarCSS)
$ git status
On branch belajarCSS
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   log.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-CSS.txt

no changes added to commit (use "git add" and/or "git commit -a")

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarCSS)
$ git add belajarCSS.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarCSS)
$ git status
On branch belajarCSS
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   belajarCSS.txt

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    Tugas-HTML.txt
        modified:   log.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        belajarHTML.txt


Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarCSS)
$ git commit -m "belajarCSS
> ;
> ;
> -
> "
[belajarCSS 1b53519] belajarCSS ; ; -
 1 file changed, 1 insertion(+)
 create mode 100644 belajarCSS.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarCSS)
$ git commit -m "belajarCSS"
On branch belajarCSS
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    Tugas-HTML.txt
        modified:   log.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        belajarHTML.txt

no changes added to commit (use "git add" and/or "git commit -a")

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarCSS)
$ git checkout main
Switched to branch 'main'
D       Tugas-HTML.txt
M       log.txt
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git commit -m "tugasCSS"
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    Tugas-HTML.txt
        modified:   log.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        belajarHTML.txt

no changes added to commit (use "git add" and/or "git commit -a")

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git checkout belajarCSS
Switched to branch 'belajarCSS'
D       Tugas-HTML.txt
M       log.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarCSS)
$ git commit -m "tugasCSS"
On branch belajarCSS
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    Tugas-HTML.txt
        modified:   log.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        belajarHTML.txt

no changes added to commit (use "git add" and/or "git commit -a")

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarCSS)
$ git merge belajarCSS
Already up to date.

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarCSS)
$ git push
fatal: The current branch belajarCSS has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin belajarCSS

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarCSS)
$


Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarCSS)
$ git branch belajarJS

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarCSS)
$ git checkout belajarJS
Switched to branch 'belajarJS'
D       Tugas-HTML.txt
M       log.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarJS)
$ git status
On branch belajarJS
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    belajarCSS.txt
        modified:   log.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-CSS.txt
        Tugas-JS.txt

no changes added to commit (use "git add" and/or "git commit -a")

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarJS)
$ git add .

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarJS)
$ git commit -m "belajarJS"
[belajarJS 389c215] belajarJS
 3 files changed, 271 insertions(+), 1 deletion(-)
 rename belajarCSS.txt => Tugas-CSS.txt (100%)
 create mode 100644 Tugas-JS.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarJS)
$ git commit -m "Tugas-JS"
On branch belajarJS
nothing to commit, working tree clean

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarJS)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git merge belajarJS
Updating 9ae0b14..389c215
Fast-forward
 Tugas-CSS.txt |   1 +
 Tugas-JS.txt  |   0
 log.txt       | 272 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++-
 3 files changed, 272 insertions(+), 1 deletion(-)
 create mode 100644 Tugas-CSS.txt
 create mode 100644 Tugas-JS.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git push
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 8 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (7/7), 2.29 KiB | 213.00 KiB/s, done.
Total 7 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/anggrainisumarno/belajarGIT
   9ae0b14..389c215  main -> main

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git branch belajarMidProject

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git checkout belajarMidProject
Switched to branch 'belajarMidProject'

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarMidProject)
$ git status
On branch belajarMidProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-MidProject.txt

nothing added to commit but untracked files present (use "git add" to track)

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarMidProject)
$ git add Tugas-MidProject.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarMidProject)
$ git add belajarMidProject.txt
fatal: pathspec 'belajarMidProject.txt' did not match any files

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarMidProject)
$ git commit -m "Tugas-MidProject"
[belajarMidProject 544df72] Tugas-MidProject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarMidProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git merge belajarMidProject
Updating 389c215..544df72
Fast-forward
 Tugas-MidProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git branch belajarPHP

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git checkout belajarPHP
Switched to branch 'belajarPHP'

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarPHP)
$ git status
On branch belajarPHP
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-PHP.txt

nothing added to commit but untracked files present (use "git add" to track)

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarPHP)
$ git add belajarPHP.txt
fatal: pathspec 'belajarPHP.txt' did not match any files

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarPHP)
$ git add Tugas-PHP.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarPHP)
$ git status
On branch belajarPHP
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-PHP.txt


Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarPHP)
$ git commit -m "Tugas-PHP"
[belajarPHP de70518] Tugas-PHP
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-PHP.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarPHP)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git merge belajarPHP
Updating 544df72..de70518
Fast-forward
 Tugas-PHP.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-PHP.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git push
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 535 bytes | 89.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/anggrainisumarno/belajarGIT
   389c215..de70518  main -> main

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git branch belajarFinalProject

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git checkout belajarFinalProject
Switched to branch 'belajarFinalProject'

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarFinalProject)
$ git status
On branch belajarFinalProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-FinalProject.txt

nothing added to commit but untracked files present (use "git add" to track)

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarFinalProject)
$ git add Tugas-FinalProject.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarFinalProject)
$ git status
On branch belajarFinalProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-FinalProject.txt


Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarFinalProject)
$ git commit -m "Tugas-FinalProject"
[belajarFinalProject 3e5e7cd] Tugas-FinalProject
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-FinalProject.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (belajarFinalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git merge belajarFinalProject
Updating de70518..3e5e7cd
Fast-forward
 Tugas-FinalProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-FinalProject.txt

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 253 bytes | 84.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/anggrainisumarno/belajarGIT
   de70518..3e5e7cd  main -> main

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git push origin –all
error: src refspec –all does not match any
error: failed to push some refs to 'https://github.com/anggrainisumarno/belajarGIT'

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git merge belajarFinalProject
Already up to date.

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git push origin –all
error: src refspec –all does not match any
error: failed to push some refs to 'https://github.com/anggrainisumarno/belajarGIT'

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git push origin –-all
error: src refspec –-all does not match any
error: failed to push some refs to 'https://github.com/anggrainisumarno/belajarGIT'

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git push origin -all
error: did you mean `--all` (with two dashes)?

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$ git push origin --all
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/anggrainisumarno/belajarGIT
 * [new branch]      Tugas-git -> Tugas-git
 * [new branch]      belajarCSS -> belajarCSS
 * [new branch]      belajarFinalProject -> belajarFinalProject
 * [new branch]      belajarHTML -> belajarHTML
 * [new branch]      belajarJS -> belajarJS
 * [new branch]      belajarMidProject -> belajarMidProject
 * [new branch]      belajarPHP -> belajarPHP

Asus@LAPTOP-A3F30CDJ MINGW64 /c/webdev/belajarGIT (main)
$
