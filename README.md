Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT
HP@kolarbrone MINGW64 /c/GIT (master)
$ git clone https://github.com/stevinalembong/belajarGIT.git

HP@kolarbrone MINGW64 /c/GIT (master)
$ git init

HP@kolarbrone MINGW64 /c/GIT (master)
$ cd belajarGIT

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-git

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-Git.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Css.txt
        Tugas-Html.txt
        Tugas-Js.txt
        Tugas-Php.txt
        Tugas-finalProject.txt
        Tugas-midProject.txt


HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git config --global user.email "stevinalembong.09@gmail.com"

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git config --global user.name "stevinalembong"

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git commit -m "tugasgit"
[Tugas-git f8133a2] tugasgit
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Css.txt
        Tugas-Html.txt
        Tugas-Js.txt
        Tugas-Php.txt
        Tugas-finalProject.txt
        Tugas-midProject.txt

nothing added to commit but untracked files present (use "git add" to track)

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-git
Updating fe4495b..f8133a2
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 281 bytes | 281.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/stevinalembong/belajarGIT.git
   fe4495b..f8133a2  main -> main

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-html

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git config --global user.email "stevinalembong.09@gmail.com"

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git config --global user.name "stevinalembong"

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git commit -m "tugashtml"
[Tugas-html 80bda78] tugashtml
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Css.txt
        Tugas-Js.txt
        Tugas-Php.txt
        Tugas-finalProject.txt
        Tugas-midProject.txt

nothing added to commit but untracked files present (use "git add" to track)

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-html
Updating f8133a2..80bda78
Fast-forward
 Tugas-Html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 277 bytes | 277.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/stevinalembong/belajarGIT.git
   f8133a2..80bda78  main -> main

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-css

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git config --global user.email "stevinalembong.09@gmail.com"

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git config --global user.name "stevinalembong"

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git commit -m "tugascss"
[Tugas-css 2a56574] tugascss
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Js.txt
        Tugas-Php.txt
        Tugas-finalProject.txt
        Tugas-midProject.txt

nothing added to commit but untracked files present (use "git add" to track)

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-css
Updating 80bda78..2a56574
Fast-forward
 Tugas-Css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 232 bytes | 232.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/stevinalembong/belajarGIT.git
   80bda78..2a56574  main -> main

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-js

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git config --global user.email "stevinalembong.09@gmail.com"

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git config --global user.name "stevinalembong"

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git commit -m "tugasjs"
[Tugas-js a251166] tugasjs
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Php.txt
        Tugas-finalProject.txt
        Tugas-midProject.txt

nothing added to commit but untracked files present (use "git add" to track)

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-js
Updating 2a56574..a251166
Fast-forward
 Tugas-Js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 228 bytes | 228.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/stevinalembong/belajarGIT.git
   2a56574..a251166  main -> main

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-midProject

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git config --global user.email "stevinalembong.09@gmail.com"

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git config --global user.name "stevinalembong"

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git commit -m "tugasmidproject"
[Tugas-midProject c4374b1] tugasmidproject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Php.txt
        Tugas-finalProject.txt

nothing added to commit but untracked files present (use "git add" to track)

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git merge
Already up to date.

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-midProject
Updating a251166..c4374b1
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 242 bytes | 242.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/stevinalembong/belajarGIT.git
   a251166..c4374b1  main -> main

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-php

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git chekcout Tugas-php
git: 'chekcout' is not a git command. See 'git --help'.

The most similar command is
        checkout

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git checkcout Tugas-php
git: 'checkcout' is not a git command. See 'git --help'.

The most similar command is
        checkout

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git config --global user.email "stevinalembong.09@gmail.com"

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git config --global user.name "stevinalembong"

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git commit -m "tugasphp"
[Tugas-php 4cf6ee7] tugasphp
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-finalProject.txt

nothing added to commit but untracked files present (use "git add" to track)

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-php
Updating c4374b1..4cf6ee7
Fast-forward
 Tugas-Php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 226 bytes | 226.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/stevinalembong/belajarGIT.git
   c4374b1..4cf6ee7  main -> main

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-finalProject

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git config --global user.email "stevinalembong.09@gmail.com"

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git config --global user.name "stevinalembong"

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git commit -m "tugasfinalproject"
[Tugas-finalProject 724c2ee] tugasfinalproject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
nothing to commit, working tree clean

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 4cf6ee7..724c2ee
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

HP@kolarbrone MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 246 bytes | 246.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/stevinalembong/belajarGIT.git
   4cf6ee7..724c2ee  main -> main