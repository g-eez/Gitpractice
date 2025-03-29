# git bash
(base)
HP@George MINGW64 ~ (master)
$ ls -al ~/.ssh
total 39
drwxr-xr-x 1 HP 197610    0 Mar 28 21:56 ./
drwxr-xr-x 1 HP 197610    0 Mar 29 09:43 ../
-rw-r--r-- 1 HP 197610  399 Dec 17 05:10 id_ed25519
-rw-r--r-- 1 HP 197610   91 Dec 17 05:10 id_ed25519.pub
-rw-r--r-- 1 HP 197610 3434 Mar 28 21:43 id_rsa_coursework
-rw-r--r-- 1 HP 197610  748 Mar 28 21:43 id_rsa_coursework.pub
-rw-r--r-- 1 HP 197610  828 Mar 28 21:56 known_hosts
-rw-r--r-- 1 HP 197610   92 Mar 28 21:56 known_hosts.old
(base)
HP@George MINGW64 ~ (master)
$ pwd
/c/Users/HP
(base)
HP@George MINGW64 ~ (master)
$ cd moringa
bash: cd: moringa: No such file or directory
(base)
HP@George MINGW64 ~ (master)
$ cd Documents
(base)
HP@George MINGW64 ~/Documents (master)
$ cd moringa
(base)
HP@George MINGW64 ~/Documents/moringa (master)
$ ls
(base)
HP@George MINGW64 ~/Documents/moringa (master)
$ mkdir phase1
(base)
HP@George MINGW64 ~/Documents/moringa (master)
$ cd phase1
(base)
HP@George MINGW64 ~/Documents/moringa/phase1 (master)
$ mkdir gitpractice
(base)
HP@George MINGW64 ~/Documents/moringa/phase1 (master)
$ ls
gitpractice/
(base)
HP@George MINGW64 ~/Documents/moringa/phase1 (master)
$ cd gitpractice
(base)
HP@George MINGW64 ~/Documents/moringa/phase1/gitpractice (master)
$ cd /c/Users/HP
(base)
HP@George MINGW64 ~ (master)
$ cd Documents
(base)
HP@George MINGW64 ~/Documents (master)
$ rmdir moringa
rmdir: failed to remove 'moringa': Directory not empty
(base)
HP@George MINGW64 ~/Documents (master)
$ rm -r moringa
(base)
HP@George MINGW64 ~/Documents (master)
$ mkdir Moringa
(base)
HP@George MINGW64 ~/Documents (master)
$ mkdir Phase1
(base)
HP@George MINGW64 ~/Documents (master)
$ mkdir Gitpractice
(base)
HP@George MINGW64 ~/Documents (master)
$ cd /c/Users/HP/Documents/Moringa/Phase1/Gitpractice
bash: cd: /c/Users/HP/Documents/Moringa/Phase1/Gitpractice: No such file or directory
(base)
HP@George MINGW64 ~/Documents (master)
$ cd Moringa
(base)
HP@George MINGW64 ~/Documents/Moringa (master)
$ cd Phase1
bash: cd: Phase1: No such file or directory
(base)
HP@George MINGW64 ~/Documents/Moringa (master)
$ cd Documents
bash: cd: Documents: No such file or directory
(base)
HP@George MINGW64 ~/Documents/Moringa (master)
$ cd /c/Users/HP
(base)
HP@George MINGW64 ~ (master)
$ cd Documents
(base)
HP@George MINGW64 ~/Documents (master)
$ rm -r Phase1 Gitpractice
(base)
HP@George MINGW64 ~/Documents (master)
$ ls
'AI DATA STRUCTURES.docx'          'Sct221-0209[2022].docx'
 BST.c                              SideSync/
'CONCEPTS OF GESTALT THEORY.docx'  'Visual Studio 2022'/
'Custom Office Templates'/          WindowsPowerShell/
 Downloads/                         compress.c
 Flatiron/                          compress.exe*
'George Kariuki'/                   compress.o
'George Kariuki.zip'                desktop.ini
'Gestalt theory.docx'               order.c
 GitHub/                            order.exe*
'Group 11.docx'                     order.o
'Inventor Server for AutoCAD'/      order2.c
'Liza Gota.docx'                    order2.exe*
 Microsys/                          order2.o
 Moringa/                           order3.c
'My Music'@                         order3.exe*
'My Pictures'@                      order3.o
'My Videos'@                        order4.c
 PowerShell/                        order4.exe*
'Pupils practical assistant'/       order4.o
'Python Scripts'/                  'prac 1.dwg'
 RPN.c                             'sct221-0209(2022).docx'
 RPN.exe*                          'sct221-0209(2022.docx'
 RPN.o                              solutionexample.java
'SCT221-0209[2022.docx'             songs.docx
(base)
HP@George MINGW64 ~/Documents (master)
$ cd Moringa
(base)
HP@George MINGW64 ~/Documents/Moringa (master)
$ mkdir Phase1
(base)
HP@George MINGW64 ~/Documents/Moringa (master)
$ cd Phase1
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1 (master)
$ mkdir Gitpractice
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1 (master)
$ cd Gitpractice
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git init
Initialized empty Git repository in C:/Users/HP/Documents/Moringa/Phase1/Gitpractice/.git/
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ ls
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ ls -a
./  ../  .git/
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ touch practice.py
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ code .
node:internal/modules/cjs/loader:1235
  throw err;
  ^

Error: Cannot find module 'C:\Users\HP\Anaconda3\Library\c\Users\HP\AppData\Local\Programs\cursor\resources\app\out\cli.js'
    at Module._resolveFilename (node:internal/modules/cjs/loader:1232:15)
    at Module._load (node:internal/modules/cjs/loader:1058:27)
    at c._load (node:electron/js2c/node_init:2:16955)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:188:12)
    at node:internal/main/run_main_module:28:49 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}

Node.js v20.18.1
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ ^[[200~code.cmd .
bash: $'\E[200~code.cmd': command not found
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ code.cmd .
Run with 'cursor -' to read output from another program (e.g. 'echo Hello World | cursor -').
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ cursor .
node:internal/modules/cjs/loader:1235
  throw err;
  ^

Error: Cannot find module 'C:\Users\HP\Anaconda3\Library\c\Users\HP\AppData\Local\Programs\cursor\resources\app\out\cli.js'
    at Module._resolveFilename (node:internal/modules/cjs/loader:1232:15)
    at Module._load (node:internal/modules/cjs/loader:1058:27)
    at c._load (node:electron/js2c/node_init:2:16955)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:188:12)
    at node:internal/main/run_main_module:28:49 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}

Node.js v20.18.1
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ cursor
node:internal/modules/cjs/loader:1235
  throw err;
  ^

Error: Cannot find module 'C:\Users\HP\Anaconda3\Library\c\Users\HP\AppData\Local\Programs\cursor\resources\app\out\cli.js'
    at Module._resolveFilename (node:internal/modules/cjs/loader:1232:15)
    at Module._load (node:internal/modules/cjs/loader:1058:27)
    at c._load (node:electron/js2c/node_init:2:16955)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:188:12)
    at node:internal/main/run_main_module:28:49 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}

Node.js v20.18.1
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ where cursor
C:\Users\HP\AppData\Local\Programs\cursor\resources\app\bin\cursor
C:\Users\HP\AppData\Local\Programs\cursor\resources\app\bin\cursor.cmd
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ ^C
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ C:\Users\HP\AppData\Local\Programs\cursor\resources\app\bin\cursor.cmd
bash: C:UsersHPAppDataLocalProgramscursorresourcesappbincursor.cmd: command not found
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ "/c/Users/HP/AppData/Local/Programs/cursor/resources/app/bin/cursor.cmd"
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ ^[[200~echo 'alias cursor="/c/Users/HP/AppData/Local/Programs/cursor/resources/app/bin/cursor.cmd"' >> ~/.bashrc
bash: $'\E[200~echo': command not found
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ echo 'alias cursor="/c/Users/HP/AppData/Local/Programs/cursor/resources/app/bin/cursor.cmd"' >> ~/.bashrc
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ source ~/.bashrc
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ cursor .
Run with 'cursor -' to read output from another program (e.g. 'echo Hello World | cursor -').
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ cursor .
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ source /c/Users/HP/Anaconda3/etc/profile.d/conda.sh
conda activate base
bash: /cygdrive/c/Users/HP/Anaconda3/Scripts/conda.exe: No such file or directory
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ python practice.py
Hello World!
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        practice.py

nothing added to commit but untracked files present (use "git add" to track)
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git add .
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   practice.py

(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   practice.py

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   practice.py

(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git add practice.py
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   practice.py

(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git commit -m"initialize git and create practice file"
[master (root-commit) 6e5de3e] initialize git and create practice file
 1 file changed, 2 insertions(+)
 create mode 100644 practice.py
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git status
On branch master
nothing to commit, working tree clean
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git remote add origin https://github.com/g-eez/Gitpractice.git
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git remote -v
origin  https://github.com/g-eez/Gitpractice.git (fetch)
origin  https://github.com/g-eez/Gitpractice.git (push)
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git push orgin master
fatal: 'orgin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git push origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 257 bytes | 64.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/g-eez/Gitpractice.git
 * [new branch]      master -> master
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git pull origin master
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 937 bytes | 33.00 KiB/s, done.
From https://github.com/g-eez/Gitpractice
 * branch            master     -> FETCH_HEAD
   6e5de3e..d5f8d4b  master     -> origin/master
Updating 6e5de3e..d5f8d4b
Fast-forward
 practice.py | 3 ++-
 1 file changed, 2 insertions(+), 1 deletion(-)
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git add .
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git commit -m"hello world 5"
[master ebf8f83] hello world 5
 1 file changed, 1 insertion(+)
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git push origin master
To https://github.com/g-eez/Gitpractice.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/g-eez/Gitpractice.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git pull origin master
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 939 bytes | 28.00 KiB/s, done.
From https://github.com/g-eez/Gitpractice
 * branch            master     -> FETCH_HEAD
   d5f8d4b..67d94c7  master     -> origin/master
Auto-merging practice.py
CONFLICT (content): Merge conflict in practice.py
Automatic merge failed; fix conflicts and then commit the result.
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master|MERGING)
$ git status
On branch master
You have unmerged paths.
  (fix conflicts and run "git commit")
  (use "git merge --abort" to abort the merge)

Unmerged paths:
  (use "git add <file>..." to mark resolution)
        both modified:   practice.py

no changes added to commit (use "git add" and/or "git commit -a")
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master|MERGING)
$ git add .
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master|MERGING)
$ git commit -m"hello world 4 or 5"
[master a5e0f0c] hello world 4 or 5
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git push origin master
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 614 bytes | 307.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/g-eez/Gitpractice.git
   67d94c7..a5e0f0c  master -> master
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git add .
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git commit -m "Resolved merge conflict by accepting incoming changes"
[master 5f3f5bb] Resolved merge conflict by accepting incoming changes
 1 file changed, 4 deletions(-)
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git push origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 305 bytes | 305.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/g-eez/Gitpractice.git
   a5e0f0c..5f3f5bb  master -> master
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git add .
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git commit -m"committing local edit"
[master 470ebfc] committing local edit
 1 file changed, 1 insertion(+)
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git push origin master
To https://github.com/g-eez/Gitpractice.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/g-eez/Gitpractice.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git pull origin master
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 936 bytes | 26.00 KiB/s, done.
From https://github.com/g-eez/Gitpractice
 * branch            master     -> FETCH_HEAD
   5f3f5bb..b297a7a  master     -> origin/master
Auto-merging practice.py
CONFLICT (content): Merge conflict in practice.py
Automatic merge failed; fix conflicts and then commit the result.
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master|MERGING)
$ git status
On branch master
You have unmerged paths.
  (fix conflicts and run "git commit")
  (use "git merge --abort" to abort the merge)

Unmerged paths:
  (use "git add <file>..." to mark resolution)
        both modified:   practice.py

no changes added to commit (use "git add" and/or "git commit -a")
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master|MERGING)
$ git add .
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master|MERGING)
$ git commit -m"merge local and remote"
[master 91ffc86] merge local and remote
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
$ git push origin master
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 538 bytes | 269.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/g-eez/Gitpractice.git
   b297a7a..91ffc86  master -> master
(base)
HP@George MINGW64 ~/Documents/Moringa/Phase1/Gitpractice (master)
