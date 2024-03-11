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
ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev
$ git init
Initialized empty Git repository in C:/Users/ASUS/Documents/webdev/.git/

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev (master)
$ git clone https://github.com/indrikolang/belajarGIT
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev (master)
$ cd belajarGIT

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git branch belajarGIT

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git checkout belajarGIT
Switched to branch 'belajarGIT'

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarGIT)
$ git status
On branch belajarGIT
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        belajarGIT.txt

nothing added to commit but untracked files present (use "git add" to track)

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarGIT)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarGIT)
$ git add ^C

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarGIT)
$ git add belajarGIT.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarGIT)
$ git status
On branch belajarGIT
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   belajarGIT.txt


ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarGIT)
$ git commit-m "tugasGIT"
git: 'commit-m' is not a git command. See 'git --help'.

The most similar command is
        commit-tree

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarGIT)
$ git commit -m "tugasGIT"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'ASUS@DESKTOP-A3OLKAC.(none)')

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarGIT)
$  git config --global user.email "indriclaudia25@gmail.com"

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarGIT)
$  git config --global user.name "indrikolang"

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarGIT)
$ git commit -m "tugasGIT"
[belajarGIT 892160f] tugasGIT
 1 file changed, 1 insertion(+)
 create mode 100644 belajarGIT.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarGIT)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git marge belajarGIT
git: 'marge' is not a git command. See 'git --help'.

The most similar command is
        merge

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git merge belajarGIT
Updating 81ad6ec..892160f
Fast-forward
 belajarGIT.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 belajarGIT.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git branch belajarHTML

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git push

Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 305 bytes | 4.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/indrikolang/belajarGIT
   81ad6ec..892160f  main -> main

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git branch belajarHTML
fatal: a branch named 'belajarHTML' already exists

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git checkout belajarHTML
Switched to branch 'belajarHTML'

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarHTML)
$ git status
On branch belajarHTML
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        belajarHTML.txt

nothing added to commit but untracked files present (use "git add" to track)

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarHTML)
$ git add belajarHTML.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarHTML)
$ git status
On branch belajarHTML
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   belajarHTML.txt


ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarHTML)
$ git commit -m "tugasHTML"
[belajarHTML ef58517] tugasHTML
 1 file changed, 1 insertion(+)
 create mode 100644 belajarHTML.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarHTML)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git marge belajarHTML
git: 'marge' is not a git command. See 'git --help'.

The most similar command is
        merge

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$  git merge belajarHTML
Updating 892160f..ef58517
Fast-forward
 belajarHTML.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 belajarHTML.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 338 bytes | 84.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/indrikolang/belajarGIT
   892160f..ef58517  main -> main

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git branch belajarCSS

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git checkout belajarCSS
Switched to branch 'belajarCSS'

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarCSS)
$ git status
On branch belajarCSS
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        belajarCSS.txt

nothing added to commit but untracked files present (use "git add" to track)

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarCSS)
$ git add belajarCSS.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarCSS)
$ git status
On branch belajarCSS
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   belajarCSS.txt


ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarCSS)
$ git commit -m "tugasCSS"
[belajarCSS 3f3268b] tugasCSS
 1 file changed, 1 insertion(+)
 create mode 100644 belajarCSS.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarCSS)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git merge belajarCSS
Updating ef58517..3f3268b
Fast-forward
 belajarCSS.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 belajarCSS.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 289 bytes | 72.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/indrikolang/belajarGIT
   ef58517..3f3268b  main -> main

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git branch belajarJS

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git checkout belajarJS
Switched to branch 'belajarJS'

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarJS)
$ git status
On branch belajarJS
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        belajarJS.txt

nothing added to commit but untracked files present (use "git add" to track)

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarJS)
$ git add belajarJS.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarJS)
$ git status
On branch belajarJS
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   belajarJS.txt


ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarJS)
$ git commit -m "tugasJS"
[belajarJS d04f8e9] tugasJS
 1 file changed, 1 insertion(+)
 create mode 100644 belajarJS.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarJS)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git merge belajarJS
Updating 3f3268b..d04f8e9
Fast-forward
 belajarJS.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 belajarJS.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 298 bytes | 59.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/indrikolang/belajarGIT
   3f3268b..d04f8e9  main -> main

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git branch belajarmidProject

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git checkout belajarmidProject
Switched to branch 'belajarmidProject'

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarmidProject)
$ git status
On branch belajarmidProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        belajarmidProject.txt

nothing added to commit but untracked files present (use "git add" to track)

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarmidProject)
$ git add belajarmidProject.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarmidProject)
$ git status
On branch belajarmidProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   belajarmidProject.txt


ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarmidProject)
$ git commit -m "tugasmidProject"
[belajarmidProject 1045871] tugasmidProject
 1 file changed, 1 insertion(+)
 create mode 100644 belajarmidProject.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarmidProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git merge belajarmidProject
Updating d04f8e9..1045871
Fast-forward
 belajarmidProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 belajarmidProject.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 311 bytes | 103.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/indrikolang/belajarGIT
   d04f8e9..1045871  main -> main

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git branch belajarPHP

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git checkout belajarPHP
Switched to branch 'belajarPHP'

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarPHP)
$ git status
On branch belajarPHP
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        belajarPHP.txt

nothing added to commit but untracked files present (use "git add" to track)

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarPHP)
$ git add belajarPHP.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarPHP)
$ git status
On branch belajarPHP
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   belajarPHP.txt


ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarPHP)
$ git commit -m "tugasPHP"
[belajarPHP 2dd7bae] tugasPHP
 1 file changed, 1 insertion(+)
 create mode 100644 belajarPHP.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarPHP)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git merge belajarPHP
Updating 1045871..2dd7bae
Fast-forward
 belajarPHP.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 belajarPHP.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 290 bytes | 22.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/indrikolang/belajarGIT
   1045871..2dd7bae  main -> main

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git branch belajarfinalProject

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git checkout belajarfinalProject
Switched to branch 'belajarfinalProject'

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarfinalProject)
$ git status
On branch belajarfinalProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        belajarfinalProject.txt

nothing added to commit but untracked files present (use "git add" to track)

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarfinalProject)
$ git add belajarfinalProject.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarfinalProject)
$ git status
On branch belajarfinalProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   belajarfinalProject.txt


ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarfinalProject)
$ git commit -m "tugasfinalProject"
[belajarfinalProject 3ca30ff] tugasfinalProject
 1 file changed, 1 insertion(+)
 create mode 100644 belajarfinalProject.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (belajarfinalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git merge belajarfinalProject
Updating 2dd7bae..3ca30ff
Fast-forward
 belajarfinalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 belajarfinalProject.txt

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$ git push origin --all
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 303 bytes | 303.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/indrikolang/belajarGIT
   2dd7bae..3ca30ff  main -> main
 * [new branch]      belajarCSS -> belajarCSS
 * [new branch]      belajarGIT -> belajarGIT
 * [new branch]      belajarHTML -> belajarHTML
 * [new branch]      belajarJS -> belajarJS
 * [new branch]      belajarPHP -> belajarPHP
 * [new branch]      belajarfinalProject -> belajarfinalProject
 * [new branch]      belajarmidProject -> belajarmidProject

ASUS@DESKTOP-A3OLKAC MINGW64 ~/Documents/webdev/belajarGIT (main)
$
