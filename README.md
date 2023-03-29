# devops

Admin@PU-IT-LT0-CPU-24 MINGW64 ~ (main)
$ echo "# devops" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/qwerty-2003/devops.git
git push -u origin main
Reinitialized existing Git repository in C:/Users/Admin/.git/
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Admin@PU-IT-LT0-CPU-24.(none)')
error: remote origin already exists.
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/qwerty-2003/devops.git'

Admin@PU-IT-LT0-CPU-24 MINGW64 ~ (main)
$ git config --global user.email"vitish_bhardwaj@protonmail.com"

Admin@PU-IT-LT0-CPU-24 MINGW64 ~ (main)
$ git config --global user.name "qwerty-2003"

Admin@PU-IT-LT0-CPU-24 MINGW64 ~ (main)
$ ;s
bash: syntax error near unexpected token `;'

Admin@PU-IT-LT0-CPU-24 MINGW64 ~ (main)
$ ls
'3D Objects'/
 AppData/
'Application Data'@
 Contacts/
 Cookies@
 Desktop/
 Documents/
 Downloads/
 Favorites/
 Links/
'Local Settings'@
 Music/
'My Documents'@
 NTUSER.DAT
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
 OneDrive/
 Pictures/
 PrintHood@
 README.md
 Recent@
'Saved Games'/
 Searches/
 SendTo@
'Start Menu'@
 Templates@
 Videos/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini

Admin@PU-IT-LT0-CPU-24 MINGW64 ~ (main)
$ echo "# devops" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/qwerty-2003/devops.git
git push -u origin main
Reinitialized existing Git repository in C:/Users/Admin/.git/
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next timtouches it
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Admin@PU-IT-LT0-CPU-24.(none)')
error: remote origin already exists.
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/qwerty-2003/devops.git'

Admin@PU-IT-LT0-CPU-24 MINGW64 ~ (main)
$ git remote add origin https://github.com/qwerty-2003/devops.git

Admin@PU-IT-LT0-CPU-24 MINGW64 ~ (main)
$ mkdir devops

Admin@PU-IT-LT0-CPU-24 MINGW64 ~ (main)
$ cd devops/

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (main)
$ git --version
git version 2.40.0.windows.1

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (main)
$ git --help
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (main)
$ git config --global user.name"qwerty-2003"

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (main)
$ git config --global user.email vitish_bhardwaj@protonmail.com

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (main)
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/etc/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=qwerty-2003
user.email=vitish_bhardwaj@protonmail.com
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
remote.origin.url=https://github.com/qwerty-2003/devops.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (main)
$ git init
Initialized empty Git repository in C:/Users/Admin/devops/.git/

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ touch master.txt

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ notepad master.txt

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        master.txt

nothing added to commit but untracked files present (use "git add" to track)

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ git add .

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   master.txt


Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ git commit -m "first commit"
[master (root-commit) 87bd42b] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 master.txt

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ git status
On branch master
nothing to commit, working tree clean

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ git log
commit 87bd42bf67e82f9a259646710da9246766b738c3 (HEAD -> master)
Author: qwerty-2003 <vitish_bhardwaj@protonmail.com>
Date:   Wed Mar 29 11:16:05 2023 +0530

    first commit

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ ls
master.txt

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ notepad master.txt

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ git commit -m "first commit"
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   master.txt

no changes added to commit (use "git add" and/or "git commit -a")

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   master.txt

no changes added to commit (use "git add" and/or "git commit -a")

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ git log
commit 87bd42bf67e82f9a259646710da9246766b738c3 (HEAD -> master)
Author: qwerty-2003 <vitish_bhardwaj@protonmail.com>
Date:   Wed Mar 29 11:16:05 2023 +0530

    first commit

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ remote add add origin https://github.com/qwerty-2003/devops.git
bash: remote: command not found

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ git remote add origin https://github.com/qwerty-2003/devops.git

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ touch master1.txt

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ notepad master1.txt

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   master.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        master1.txt

no changes added to commit (use "git add" and/or "git commit -a")

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ git add .

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   master.txt
        new file:   master1.txt


Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ git commit -m "second commit"
[master facf7c3] second commit
 2 files changed, 2 insertions(+)
 create mode 100644 master1.txt

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ git status
On branch master
nothing to commit, working tree clean

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ git log
commit facf7c3e443a0a2c81c107c8646d1474bf1ba8b5 (HEAD -> master)
Author: qwerty-2003 <vitish_bhardwaj@protonmail.com>
Date:   Wed Mar 29 11:28:56 2023 +0530

    second commit

commit 87bd42bf67e82f9a259646710da9246766b738c3
Author: qwerty-2003 <vitish_bhardwaj@protonmail.com>
Date:   Wed Mar 29 11:16:05 2023 +0530

    first commit

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ git remote -v
origin  https://github.com/qwerty-2003/devops.git (fetch)
origin  https://github.com/qwerty-2003/devops.git (push)

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$ git push -u origin master
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (7/7), 523 bytes | 261.00 KiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/qwerty-2003/devops.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

Admin@PU-IT-LT0-CPU-24 MINGW64 ~/devops (master)
$
