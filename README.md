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
....

jane@JANE MINGW64 ~ (master)
$ pwd
/c/Users/user

jane@JANE MINGW64 ~ (master)
$ git config --global user.email "janneferpandelaki@gmail.com"

jane@JANE MINGW64 ~ (master)
$ git init
Initialized empty Git repository in C:/Users/user/.git/

jane@JANE MINGW64 ~ (master)
$ ^C

jane@JANE MINGW64 ~ (master)
$ cd Desktop

jane@JANE MINGW64 ~/Desktop (master)
$ git clone https://github.com/janneffer/belajarGIT.git
fatal: destination path 'belajarGIT' already exists and is not an empty directory.

jane@JANE MINGW64 ~/Desktop (master)
$ ^C

jane@JANE MINGW64 ~/Desktop (master)
$ cd BelajarGIT

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ git branch
  Tugas-git
* main

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ git branch Tugas-html

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ cd belajarGIT
bash: cd: belajarGIT: No such file or directory

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ ls
README.md  Tugas-git.txt

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ ^C

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ git checkout -b Tugas-html
fatal: a branch named 'Tugas-html' already exists

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ touch Tugas-html

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ touch Tugas-html.txt

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ git add Tugas-html.txt

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ git commit -m "Menambahkan file Tugas-html.txt"
[main d4abaeb] Menambahkan file Tugas-html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ git add Tugas-html.txt

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-html.txt"
[main 985fa25] Menambahkan perubahan pada Tugas-html.txt
 1 file changed, 1 insertion(+)

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ git pull origin main
From https://github.com/janneffer/belajarGIT
 * branch            main       -> FETCH_HEAD
Already up to date.

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ git merge Tugas-html
Already up to date.

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ git log
commit 985fa25ecb6bd42d4c394c5923b401e3ddaabae9 (HEAD -> main)
Author: janneffer <janneferpandelaki@gmail.com>
Date:   Fri Mar 8 09:27:25 2024 +0800

    Menambahkan perubahan pada Tugas-html.txt

commit d4abaeb66acf16388fd60aa10abbcd261d6d84e5
Author: janneffer <janneferpandelaki@gmail.com>
Date:   Fri Mar 8 09:20:25 2024 +0800

    Menambahkan file Tugas-html.txt

commit 6fc9213ebc34410e6a9e877dd37ff047d3f86f0a (origin/main, origin/HEAD, Tugas-html)
Author: janneffer <janneferpandelaki@gmail.com>
Date:   Wed Mar 6 16:36:20 2024 +0800

    Menambahkan file Tugas-git

commit 3778e005a4029dc112022184914cc9c095177921 (Tugas-git)
Author: jane <135977387+janneffer@users.noreply.github.com>
Date:   Wed Mar 6 13:11:04 2024 +0800

    Update README.md

commit d5ad6606d276be39c703036d3e277d295a5e259e
Author: jane <135977387+janneffer@users.noreply.github.com>
Date:   Wed Mar 6 12:53:32 2024 +0800

    Initial commit

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ git commit -m "Merge branch 'Tugas-Git' into main"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 569 bytes | 284.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/janneffer/belajarGIT.git
   6fc9213..985fa25  main -> main

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ ^C

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

jane@JANE MINGW64 ~/Desktop/BelajarGIT (main)
$


