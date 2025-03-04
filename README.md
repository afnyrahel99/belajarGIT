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
lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~
$ git clone https://github.com/afnyrahel99/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~
$ git checkout -b Tugas-git
fatal: not a git repository (or any of the parent directories): .git

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~
$ cd belajarGIT

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-git)
$ touch Tugas-Git.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-git)
$ echo "Ini adalah file git pertama saya" > Tugas-Git.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt
warning: in the working copy of 'Tugas-Git.txt', LF will be replaced by CRLF the next time Git touches it

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-Git.txt"
[Tugas-git 5242860] Menambahkan file Tugas-Git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt


lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git merge Tugas-git
Updating 95d685f..5242860
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 348 bytes | 348.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/afnyrahel99/belajarGIT.git
   95d685f..5242860  main -> main

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'
echo "
lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-html)
$ echo "Ini adalah file html pertama saya" > Tugas-html.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-html)
$ git add Tugas-html.txt
warning: in the working copy of 'Tugas-html.txt', LF will be replaced by CRLF the next time Git touches it

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-html)
$ git commit -m "Menanmbahkan Tugas-html.txt"
[Tugas-html 8554d26] Menanmbahkan Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt
g
lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git merge Tugas-html
Updating 5242860..8554d26
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 375 bytes | 375.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/afnyrahel99/belajarGIT.git
   5242860..8554d26  main -> main

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-css)
$ echo "Ini adalah file css pertama saya" > Tugas.css.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-css)
$ git add Tugas-css.txt
fatal: pathspec 'Tugas-css.txt' did not match any files

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-css)
$ git add Tugas.css.txt
warning: in the working copy of 'Tugas.css.txt', LF will be replaced by CRLF the next time Git touches it
git commit -m "Menambahkan Tugas.css.txt"

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas.css.txt"

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas.css.txt"
[Tugas-css 411b242] Menambahkan Tugas.css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas.css.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git merge Tugas-css
Updating 8554d26..411b242
Fast-forward
 Tugas.css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas.css.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 334 bytes | 334.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/afnyrahel99/belajarGIT.git
   8554d26..411b242  main -> main

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-js)
$ echo "Ini adalah file js pertama saya" > Tugas-js.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-js)
$ git add Tugas-js.txt
warning: in the working copy of 'Tugas-js.txt', LF will be replaced by CRLF the next time Git touches it

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan Tugas-js.txt"
[Tugas-js b7e3a73] Menambahkan Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git merge Tugas-js
Updating 411b242..b7e3a73
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 323 bytes | 323.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/afnyrahel99/belajarGIT.git
   411b242..b7e3a73  main -> main

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-midProject)
$ echo "Ini adalah file midProject pertama saya" > Tugas-midProject.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt
warning: in the working copy of 'Tugas-midProject.txt', LF will be replaced by CRLF the next time Git touches it

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-midProject)
$ git commit -m "Menanmbahkan Tugas-midProject.txt"
[Tugas-midProject c339a39] Menanmbahkan Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git merge Tugas-midProject
Updating b7e3a73..c339a39
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 351 bytes | 351.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/afnyrahel99/belajarGIT.git
   b7e3a73..c339a39  main -> main

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-php)
$ echo "Ini adalah file php pertama saya" > Tugas-php.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-php)
$ git add Tugas-php.txt
warning: in the working copy of 'Tugas-php.txt', LF will be replaced by CRLF the next time Git touches it

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-php.txt"
[Tugas-php 0375505] Menambahkan Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git merge Tugas-php
Updating c339a39..0375505
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 329 bytes | 329.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/afnyrahel99/belajarGIT.git
   c339a39..0375505  main -> main

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-finalProject)
$ echo "Ini adalah file finalProject pertama saya" > Tugas-finalProject.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt
warning: in the working copy of 'Tugas-finalProject.txt', LF will be replaced by CRLF the next time Git touches it

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-finalProject.txt"
[Tugas-finalProject d8b0f86] Menambahkan Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 0375505..d8b0f86
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

lenovo@LAPTOP-Q5R0L8S9 MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 353 bytes | 353.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/afnyrahel99/belajarGIT.git
   0375505..d8b0f86  main -> main

