Answer 1 
git version 2.31.1.windows.1

Answer 2
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
core.editor="C:\Users\alber\AppData\Local\Programs\Microsoft VS Code\Code.exe" --wait
user.name=Alberto Rosado
user.email=ar652820@ohio.edu
(END)

Answer 3
It sent me to the git-add(1) Manual Page. The URL file:///C:/Program%20Files/Git/mingw64/share/doc/git-doc/git-add.html

Answer 4
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)

Answer 5
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md

Answer 6
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

Answer 7
On branch master
nothing to commit, working tree clean

Answer 8
commit 413dbf1c25fd160804afce7b307e8ae5eb9440a5 (HEAD -> master)
Author: Alberto Rosado <ar652820@ohio.edu>
Date:   Tue May 11 11:14:08 2021 -0400

    Initial commit

Answer 9
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

Answer 10
 Were the changes you made online reflected in your local copy? No

Answer 11
Try the push command again git push. What happens? An error ocurred because the change I made online does not match what I have locally. 

Answer 12
Look at README.md in your local directory. Were the changes you made online reflected in your local copy? Yes they were. 

Answer 13
    Directory: C:\Users\alber\OneDrive\Desktop\cs2400\git-lab-2


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         5/11/2021  11:58 AM            302 .gitignore
-a----         5/11/2021  11:58 AM             11 README.md

