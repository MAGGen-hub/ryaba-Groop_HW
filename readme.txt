isaik@DESKTOP-D1BC83P MINGW64 ~
$ help
GNU bash, version 4.4.23(1)-release (x86_64-pc-msys)
These shell commands are defined internally.  Type `help' to see this list.
Type `help name' to find out more about the function `name'.
Use `info bash' to find out more about the shell in general.
Use `man -k' or `info' to find out more about commands not in this list.

A star (*) next to a name means that the command is disabled.

 job_spec [&]                            history [-c] [-d offset] [n] or hist>
 (( expression ))                        if COMMANDS; then COMMANDS; [ elif C>
 . filename [arguments]                  jobs [-lnprs] [jobspec ...] or jobs >
 :                                       kill [-s sigspec | -n signum | -sigs>
 [ arg... ]                              let arg [arg ...]
 [[ expression ]]                        local [option] name[=value] ...
 alias [-p] [name[=value] ... ]          logout [n]
 bg [job_spec ...]                       mapfile [-d delim] [-n count] [-O or>
 bind [-lpsvPSVX] [-m keymap] [-f file>  popd [-n] [+N | -N]
 break [n]                               printf [-v var] format [arguments]
 builtin [shell-builtin [arg ...]]       pushd [-n] [+N | -N | dir]
 caller [expr]                           pwd [-LPW]
 case WORD in [PATTERN [| PATTERN]...)>  read [-ers] [-a array] [-d delim] [->
 cd [-L|[-P [-e]] [-@]] [dir]            readarray [-n count] [-O origin] [-s>
 command [-pVv] command [arg ...]        readonly [-aAf] [name[=value] ...] o>
 compgen [-abcdefgjksuv] [-o option] [>  return [n]
 complete [-abcdefgjksuv] [-pr] [-DE] >  select NAME [in WORDS ... ;] do COMM>
 compopt [-o|+o option] [-DE] [name ..>  set [-abefhkmnptuvxBCHP] [-o option->
 continue [n]                            shift [n]
 coproc [NAME] command [redirections]    shopt [-pqsu] [-o] [optname ...]
 declare [-aAfFgilnrtux] [-p] [name[=v>  source filename [arguments]
 dirs [-clpv] [+N] [-N]                  suspend [-f]
 disown [-h] [-ar] [jobspec ... | pid >  test [expr]
 echo [-neE] [arg ...]                   time [-p] pipeline
 enable [-a] [-dnps] [-f filename] [na>  times
 eval [arg ...]                          trap [-lp] [[arg] signal_spec ...]
 exec [-cl] [-a name] [command [argume>  true
 exit [n]                                type [-afptP] name [name ...]
 export [-fn] [name[=value] ...] or ex>  typeset [-aAfFgilnrtux] [-p] name[=v>
 false                                   ulimit [-SHabcdefiklmnpqrstuvxPT] [l>
 fc [-e ename] [-lnr] [first] [last] o>  umask [-p] [-S] [mode]
 fg [job_spec]                           unalias [-a] name [name ...]
 for NAME [in WORDS ... ] ; do COMMAND>  unset [-f] [-v] [-n] [name ...]
 for (( exp1; exp2; exp3 )); do COMMAN>  until COMMANDS; do COMMANDS; done
 function name { COMMANDS ; } or name >  variables - Names and meanings of so>
 getopts optstring name [arg]            wait [-n] [id ...]
 hash [-lr] [-p pathname] [-dt] [name >  while COMMANDS; do COMMANDS; done
 help [-dms] [pattern ...]               { COMMANDS ; }

isaik@DESKTOP-D1BC83P MINGW64 ~
$ cd C:\Users\isaik\Documents\GitHub\ryaba
bash: cd: C:UsersisaikDocumentsGitHubryaba: No such file or directory

isaik@DESKTOP-D1BC83P MINGW64 ~
$ ls
'3D Objects'/         Desktop/                 Links/                  NTUSER.DAT{fd9a35db-49fe-11e9-aa2c-248a07783950}.TM.blf                                        Pictures/       SendTo@           ntuser.ini
 AppData/             Documents/              'Local Settings'@        NTUSER.DAT{fd9a35db-49fe-11e9-aa2c-248a07783950}.TMContainer00000000000000000001.regtrans-ms   PrintHood@      Videos/           source/
'Application Data'@   Downloads/               MicrosoftEdgeBackups/   NTUSER.DAT{fd9a35db-49fe-11e9-aa2c-248a07783950}.TMContainer00000000000000000002.regtrans-ms   Recent@         ansel/           'Мои документы'@
 Contacts/            Favorites/               Music/                  NetHood@                                                                                      'Saved Games'/   ntuser.dat.LOG1   Шаблоны@
 Cookies@             IntelGraphicsProfiles/   NTUSER.DAT              OneDrive/                                                                                      Searches/       ntuser.dat.LOG2  'главное меню'@

isaik@DESKTOP-D1BC83P MINGW64 ~
$ cd Documents

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents
$ Github

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents
$ cd GitHub

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub
$ ls
ExampleDllMod/  FASM-Projects-and-Tests/  Mindustry/  TEST.asm  TEST.exe*  cpp/  hlp/  ryaba/  tests/

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub
$ ryaba
bash: ryaba: command not found

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub
$ cd ryaba

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba
$ cd ..

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub
$ cd ryaba/ryaba1

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1
$ git clone https://github.com/MAGGen-hub/ryaba-Groop_HW.git
Cloning into 'ryaba-Groop_HW'...
warning: You appear to have cloned an empty repository.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1
$ cd ryaba-Groop_HW

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git commit -m "Added ryaba.txt"
[master (root-commit) ad25323] Added ryaba.txt
 1 file changed, 13 insertions(+)
 create mode 100644 ryaba.txt

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git status
On branch master
Your branch is based on 'origin/master', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 495 bytes | 495.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 * [new branch]      master -> master

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ cd ..

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1
$ cd ..

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba
$ cd ryaba2

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2
$ git clone https://github.com/MAGGen-hub/ryaba-Groop_HW.git
Cloning into 'ryaba-Groop_HW'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2
$ cd ../..

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub
$ cd ryaba/ryaba3

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3
$ git clone https://github.com/MAGGen-hub/ryaba-Groop_HW.git
Cloning into 'ryaba-Groop_HW'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3
$ cd ../ryaba1

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1
$ cd ryaba-Groop_HW

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git tag v1.0

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git push
Everything up-to-date

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    ryaba.txt

no changes added to commit (use "git add" and/or "git commit -a")

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git commit -m "restart"
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    ryaba.txt

no changes added to commit (use "git add" and/or "git commit -a")

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git commit -m "restart"
[master 0e0761a] restart
 1 file changed, 13 deletions(-)
 delete mode 100644 ryaba.txt

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (2/2), 203 bytes | 203.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
   ad25323..0e0761a  master -> master

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git tag v1

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git commit -m "restart"
[master 4fac421] restart
 1 file changed, 13 insertions(+)
 create mode 100644 ryaba.txt

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 517 bytes | 517.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
   0e0761a..4fac421  master -> master

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ cd ../../ryaba2

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2
$ git clone https://github.com/MAGGen-hub/ryaba-Groop_HW.git
fatal: destination path 'ryaba-Groop_HW' already exists and is not an empty directory.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2
$ git clone https://github.com/MAGGen-hub/ryaba-Groop_HW.git
Cloning into 'ryaba-Groop_HW'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 1), reused 5 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.
Resolving deltas: 100% (1/1), done.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2
$ cd ../../ryaba3
bash: cd: ../../ryaba3: No such file or directory

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2
$ cd ../ryaba3

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3
$ git clone https://github.com/MAGGen-hub/ryaba-Groop_HW.git
Cloning into 'ryaba-Groop_HW'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 1), reused 5 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.
Resolving deltas: 100% (1/1), done.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3
$ cd ../ryaba1

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1
$ cd ryaba-Groop_HW

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ cd ..

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1
$ git clone https://github.com/MAGGen-hub/ryaba-Groop_HW.git
Cloning into 'ryaba-Groop_HW'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 1), reused 5 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.
Resolving deltas: 100% (1/1), done.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1
$ cd ryaba-Groop_HW

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git tag -l
v1.0

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ cd ../../ryaba2

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2
$ git clone https://github.com/MAGGen-hub/ryaba-Groop_HW.git
Cloning into 'ryaba-Groop_HW'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 1), reused 5 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.
Resolving deltas: 100% (1/1), done.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2
$ cd ../ryaba3

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3
$ git clone https://github.com/MAGGen-hub/ryaba-Groop_HW.git
Cloning into 'ryaba-Groop_HW'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 1), reused 5 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.
Resolving deltas: 100% (1/1), done.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3
$ cd ../ryaba1

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1
$ cd ryaba-Groop_HW

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git remote
origin

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git checkout -b zoya
Switched to a new branch 'zoya'

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (zoya)
$ git status
On branch zoya
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ryaba.txt

no changes added to commit (use "git add" and/or "git commit -a")

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (zoya)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (zoya)
$ git branch -l
  master
* zoya

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (zoya)
$ git checkout master
Switched to branch 'master'
M       ryaba.txt
Your branch is up to date with 'origin/master'.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   ryaba.txt


isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   ryaba.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ryaba.txt


isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git checkout master
Already on 'master'
M       ryaba.txt
Your branch is up to date with 'origin/master'.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   ryaba.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ryaba.txt


isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git push origin
Everything up-to-date

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   ryaba.txt


isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git commit -m "User 1 add new branch and change master" -m "Poor chicken..."
[master 28cd9d2] User 1 add new branch and change master
 1 file changed, 13 insertions(+), 13 deletions(-)
 rewrite ryaba.txt (60%)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git push origin
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 369 bytes | 369.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
   4fac421..28cd9d2  master -> master

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git checkout zoya
Switched to branch 'zoya'

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (zoya)
$ git push origin
fatal: The current branch zoya has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin zoya


isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (zoya)
$ ^C

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (zoya)
$ git push --set-upstream origin zoya
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'zoya' on GitHub by visiting:
remote:      https://github.com/MAGGen-hub/ryaba-Groop_HW/pull/new/zoya
remote:
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 * [new branch]      zoya -> zoya
Branch 'zoya' set up to track remote branch 'zoya' from 'origin'.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (zoya)
$ git status\
> ^C

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (zoya)
$ git status
On branch zoya
Your branch is up to date with 'origin/zoya'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ryaba.txt

no changes added to commit (use "git add" and/or "git commit -a")

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (zoya)
$ git commit -m "User 1 remade new branch" -m "Poor chicken..."
On branch zoya
Your branch is up to date with 'origin/zoya'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ryaba.txt

no changes added to commit (use "git add" and/or "git commit -a")

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (zoya)
$ git push origin
Everything up-to-date

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (zoya)
$ git status
On branch zoya
Your branch is up to date with 'origin/zoya'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ryaba.txt

no changes added to commit (use "git add" and/or "git commit -a")

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (zoya)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (zoya)
$ git commit -m "User 1 remade new branch" -m "Poor chicken..."
[zoya 6fa8569] User 1 remade new branch
 1 file changed, 2 insertions(+), 2 deletions(-)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (zoya)
$ git push origin
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 369 bytes | 369.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
   4fac421..6fa8569  zoya -> zoya

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (zoya)
$ cd ../../ryaba2/ryaba-Groop_HW

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git checkout –b dusya
error: pathspec '–b' did not match any file(s) known to git
error: pathspec 'dusya' did not match any file(s) known to git

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git branch -l
* master

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git checkout -b dusya
Switched to a new branch 'dusya'

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (dusya)
$ git status
On branch dusya
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ryaba.txt

no changes added to commit (use "git add" and/or "git commit -a")

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (dusya)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (dusya)
$ git commit -m "User 2 add new branch and change story" -m "Petrol production..."
[dusya 46f8dc4] User 2 add new branch and change story
 1 file changed, 3 insertions(+), 13 deletions(-)
 rewrite ryaba.txt (99%)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (dusya)
$ git status
On branch dusya
nothing to commit, working tree clean

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (dusya)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (dusya)
$ git commit -m "User 2 change story" -m "Petrol production..."
[dusya c379c59] User 2 change story
 1 file changed, 3 insertions(+), 1 deletion(-)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (dusya)
$ git status
On branch dusya
nothing to commit, working tree clean

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (dusya)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (dusya)
$ git commit -m "User 2 change story" -m "Petrol production..."
[dusya da60889] User 2 change story
 1 file changed, 1 insertion(+), 1 deletion(-)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (dusya)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git branch -l
  dusya
* master

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ryaba.txt

no changes added to commit (use "git add" and/or "git commit -a")

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git commit -m "User 2 change story in master" -m "New year!"
[master 51fa967] User 2 change story in master
 1 file changed, 2 insertions(+), 2 deletions(-)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git branch -l
  dusya
* master

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push origin
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/MAGGen-hub/ryaba-Groop_HW.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/MAGGen-hub/ryaba-Groop_HW.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ ^C

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ ^Mgit push --force-with-lease origin <имя_ветки>
bash: syntax error near unexpected token `newline'
git push --force-with-lease origin
isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ 1
bash: 1: command not found

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push --force-with-lease origin
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 ! [rejected]        master -> master (stale info)
error: failed to push some refs to 'https://github.com/MAGGen-hub/ryaba-Groop_HW.git'

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push --force-with-lease origin
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 ! [rejected]        master -> master (stale info)
error: failed to push some refs to 'https://github.com/MAGGen-hub/ryaba-Groop_HW.git'

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push --force-with-lease origin
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 ! [rejected]        master -> master (stale info)
error: failed to push some refs to 'https://github.com/MAGGen-hub/ryaba-Groop_HW.git'

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push --force-with-lease origin master
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 ! [rejected]        master -> master (stale info)
error: failed to push some refs to 'https://github.com/MAGGen-hub/ryaba-Groop_HW.git'

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push --force-with-lease
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 ! [rejected]        master -> master (stale info)
error: failed to push some refs to 'https://github.com/MAGGen-hub/ryaba-Groop_HW.git'

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push --force origin
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 457 bytes | 457.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 + 28cd9d2...51fa967 master -> master (forced update)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git branch -l
  dusya
* master

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git checkout dusya
Switched to branch 'dusya'

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (dusya)
$ git branch -l
* dusya
  master

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (dusya)
$ git push origin
fatal: The current branch dusya has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dusya


isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (dusya)
$ git push --set-upstream origin dusya
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 12 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (9/9), 1.13 KiB | 1.13 MiB/s, done.
Total 9 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), done.
remote:
remote: Create a pull request for 'dusya' on GitHub by visiting:
remote:      https://github.com/MAGGen-hub/ryaba-Groop_HW/pull/new/dusya
remote:
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 * [new branch]      dusya -> dusya
Branch 'dusya' set up to track remote branch 'dusya' from 'origin'.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (dusya)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git branch -l
  dusya
* master

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ryaba.txt

no changes added to commit (use "git add" and/or "git commit -a")

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git commit -m "User 2 change story in master" -m "Anarchy!"
[master 67e4899] User 2 change story in master
 1 file changed, 3 insertions(+), 3 deletions(-)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git commit -m "User 2 change story in master" -m "Crazy grangpa!"
[master 7b3fe7a] User 2 change story in master
 1 file changed, 1 insertion(+), 1 deletion(-)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git commit -m "User 2 change story in master" -m "More anarchy!"
[master acb1e4b] User 2 change story in master
 1 file changed, 3 insertions(+), 3 deletions(-)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git rebase -i
[detached HEAD 99d1853] User 2 change story in master
 Date: Fri Nov 13 17:59:42 2020 +0300
 1 file changed, 13 insertions(+), 13 deletions(-)
 rewrite ryaba.txt (75%)
Successfully rebased and updated refs/heads/master.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push origin
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 732 bytes | 732.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
   51fa967..99d1853  master -> master

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git checkout -b belka
Switched to a new branch 'belka'

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (belka)
$ git status
On branch belka
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ryaba.txt

no changes added to commit (use "git add" and/or "git commit -a")

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (belka)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (belka)
$ git status
On branch belka
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   ryaba.txt


isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (belka)
$ git commit -m "User 2 add new branch belka"
[belka 36b21be] User 2 add new branch belka
 1 file changed, 1 insertion(+), 1 deletion(-)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (belka)
$ cd ../../ryaba3

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3
$ cd ryaba-Groop_HW

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master)
$ git checkout -b maga
Switched to a new branch 'maga'

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git status
On branch maga
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ryaba.txt

no changes added to commit (use "git add" and/or "git commit -a")

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git commit -m "User 2 add new branch maga"
[maga ca670a9] User 2 add new branch maga
 1 file changed, 1 insertion(+), 1 deletion(-)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git commit -m "User 3 add new branch maga"
On branch maga
nothing to commit, working tree clean

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git commit --amend -m "User 3 add new branch maga"
[maga faa2fa7] User 3 add new branch maga
 Date: Fri Nov 13 18:48:47 2020 +0300
 1 file changed, 1 insertion(+), 1 deletion(-)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git rebase -i
There is no tracking information for the current branch.
Please specify which branch you want to rebase against.
See git-rebase(1) for details.

    git rebase '<branch>'

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> maga


isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ryaba.txt

no changes added to commit (use "git add" and/or "git commit -a")

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master)
$ git commit --amend -m "User 3 change story in master"
[master f0755a0] User 3 change story in master
 Date: Fri Nov 13 14:45:49 2020 +0300
 1 file changed, 15 insertions(+)
 create mode 100644 ryaba.txt

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master)
$ git commit -m "User 3 change story in master"
On branch master
Your branch and 'origin/master' have diverged,
and have 1 and 1 different commits each, respectively.
  (use "git pull" to merge the remote branch into yours)

nothing to commit, working tree clean

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master)
$ git fetch
remote: Enumerating objects: 20, done.
remote: Counting objects: 100% (20/20), done.
remote: Compressing objects: 100% (8/8), done.
remote: Total 18 (delta 6), reused 16 (delta 4), pack-reused 0
Unpacking objects: 100% (18/18), 2.41 KiB | 47.00 KiB/s, done.
From https://github.com/MAGGen-hub/ryaba-Groop_HW
   4fac421..99d1853  master     -> origin/master
 * [new branch]      dusya      -> origin/dusya
 * [new branch]      zoya       -> origin/zoya

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master)
$ git merge
CONFLICT (add/add): Merge conflict in ryaba.txt
Auto-merging ryaba.txt
Automatic merge failed; fix conflicts and then commit the result.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master|MERGING)
$ git status
On branch master
Your branch and 'origin/master' have diverged,
and have 1 and 3 different commits each, respectively.
  (use "git pull" to merge the remote branch into yours)

You have unmerged paths.
  (fix conflicts and run "git commit")
  (use "git merge --abort" to abort the merge)

Unmerged paths:
  (use "git add <file>..." to mark resolution)
        both added:      ryaba.txt

no changes added to commit (use "git add" and/or "git commit -a")

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master|MERGING)
$ git push master
fatal: 'master' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master|MERGING)
$ git push origin
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/MAGGen-hub/ryaba-Groop_HW.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master|MERGING)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master|MERGING)
$ git push origin
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/MAGGen-hub/ryaba-Groop_HW.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master|MERGING)
$ git merge
fatal: You have not concluded your merge (MERGE_HEAD exists).
Please, commit your changes before you merge.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master|MERGING)
$ git commit -m "User 3 Merge conflict solution" -m "Safe both versions"
[master 792d4c5] User 3 Merge conflict solution

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master)
$ git push origin
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 908 bytes | 908.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
   99d1853..792d4c5  master -> master

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master)
$ git checkout maga
Switched to branch 'maga'

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git push origin
fatal: The current branch maga has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin maga


isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git push --set-upstream origin maga
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 364 bytes | 364.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'maga' on GitHub by visiting:
remote:      https://github.com/MAGGen-hub/ryaba-Groop_HW/pull/new/maga
remote:
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 * [new branch]      maga -> maga
Branch 'maga' set up to track remote branch 'maga' from 'origin'.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ cd ../../ryaba2/ryaba-Groop_HW

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (belka)
$ git fetch
remote: Enumerating objects: 17, done.
remote: Counting objects: 100% (17/17), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 12 (delta 5), reused 11 (delta 4), pack-reused 0
Unpacking objects: 100% (12/12), 1.45 KiB | 46.00 KiB/s, done.
From https://github.com/MAGGen-hub/ryaba-Groop_HW
 * [new branch]      maga       -> origin/maga
   99d1853..792d4c5  master     -> origin/master
 * [new branch]      zoya       -> origin/zoya

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (belka)
$ git rebase master
Current branch belka is up to date.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (belka)
$ git rebase master
Current branch belka is up to date.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (belka)
$ git checkout master
Switched to branch 'master'
Your branch is behind 'origin/master' by 2 commits, and can be fast-forwarded.
  (use "git pull" to update your local branch)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git fetch

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git rebase belka
Successfully rebased and updated refs/heads/master.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/MAGGen-hub/ryaba-Groop_HW.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git pull
Auto-merging ryaba.txt
Merge made by the 'recursive' strategy.
 ryaba.txt | 23 ++++++++++++++++++++++-
 1 file changed, 22 insertions(+), 1 deletion(-)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git rebase belka
error: could not apply f0755a0... User 3 change story in master
Resolve all conflicts manually, mark them as resolved with
"git add/rm <conflicted_files>", then run "git rebase --continue".
You can instead skip this commit: run "git rebase --skip".
To abort and get back to the state before "git rebase", run "git rebase --abort".
Could not apply f0755a0... User 3 change story in master
CONFLICT (add/add): Merge conflict in ryaba.txt
Auto-merging ryaba.txt

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master|REBASE 1/1)
$ git rebase --continue
ryaba.txt: needs merge
You must edit all merge conflicts and then
mark them as resolved using git add

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master|REBASE 1/1)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master|REBASE 1/1)
$ git rebase --continue
Successfully rebased and updated refs/heads/master.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/MAGGen-hub/ryaba-Groop_HW.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push master
fatal: 'master' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push origin/master
fatal: 'origin/master' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/MAGGen-hub/ryaba-Groop_HW.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push --help

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git pull origin
Auto-merging ryaba.txt
Merge made by the 'recursive' strategy.
 ryaba.txt | 23 ++++++++++++++++++++++-
 1 file changed, 22 insertions(+), 1 deletion(-)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git rebase belka
error: could not apply f0755a0... User 3 change story in master
Resolve all conflicts manually, mark them as resolved with
"git add/rm <conflicted_files>", then run "git rebase --continue".
You can instead skip this commit: run "git rebase --skip".
To abort and get back to the state before "git rebase", run "git rebase --abort".
Could not apply f0755a0... User 3 change story in master
CONFLICT (add/add): Merge conflict in ryaba.txt
Auto-merging ryaba.txt

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master|REBASE 1/1)
$ git rebase belka
fatal: It seems that there is already a rebase-merge directory, and
I wonder if you are in the middle of another rebase.  If that is the
case, please try
        git rebase (--continue | --abort | --skip)
If that is not the case, please
        rm -fr ".git/rebase-merge"
and run me again.  I am stopping in case you still have something
valuable there.


isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master|REBASE 1/1)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master|REBASE 1/1)
$ git commit -m "User 2 Merge conflict solution"
interactive rebase in progress; onto 36b21be
Last command done (1 command done):
   pick f0755a0 User 3 change story in master
No commands remaining.
You are currently rebasing branch 'master' on '36b21be'.
  (all conflicts fixed: run "git rebase --continue")

nothing to commit, working tree clean

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master|REBASE 1/1)
$ git rebase --continue
Successfully rebased and updated refs/heads/master.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/MAGGen-hub/ryaba-Groop_HW.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push fast-forward
fatal: 'fast-forward' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push ^C

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git remote
origin

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git remote push
error: Unknown subcommand: push
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --verbose         be verbose; must be placed before a subcommand


isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git config receive.denyNonFastForwards false

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/MAGGen-hub/ryaba-Groop_HW.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git config receive.denyNonFastForwards true

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git pull master
fatal: 'master' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git pull
Auto-merging ryaba.txt
Merge made by the 'recursive' strategy.
 ryaba.txt | 23 ++++++++++++++++++++++-
 1 file changed, 22 insertions(+), 1 deletion(-)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git rebase belka ~HEAD1
fatal: fatal: no such branch/commit '~HEAD1'

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git rebase belka HEAD~1
Current branch HEAD~1 is up to date.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git rebase belka
Current branch master is up to date.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/MAGGen-hub/ryaba-Groop_HW.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git pull
Auto-merging ryaba.txt
Merge made by the 'recursive' strategy.
 ryaba.txt | 23 ++++++++++++++++++++++-
 1 file changed, 22 insertions(+), 1 deletion(-)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git rebase belka
error: could not apply f0755a0... User 3 change story in master
Resolve all conflicts manually, mark them as resolved with
"git add/rm <conflicted_files>", then run "git rebase --continue".
You can instead skip this commit: run "git rebase --skip".
To abort and get back to the state before "git rebase", run "git rebase --abort".
Could not apply f0755a0... User 3 change story in master
CONFLICT (add/add): Merge conflict in ryaba.txt
Auto-merging ryaba.txt

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master|REBASE 1/1)
$ git rebase --abort

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git rebase belka HEAD~1
Current branch HEAD~1 is up to date.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git rebase belka
Current branch master is up to date.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git rebase belka
Current branch master is up to date.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/MAGGen-hub/ryaba-Groop_HW.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git pull
Auto-merging ryaba.txt
Merge made by the 'recursive' strategy.
 ryaba.txt | 23 ++++++++++++++++++++++-
 1 file changed, 22 insertions(+), 1 deletion(-)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 701 bytes | 701.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
   792d4c5..46e03d7  master -> master

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git rebase belka HEAD~1
Current branch HEAD~1 is up to date.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/MAGGen-hub/ryaba-Groop_HW.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git pull
Updating 36b21be..46e03d7
Fast-forward
 ryaba.txt | 23 ++++++++++++++++++++++-
 1 file changed, 22 insertions(+), 1 deletion(-)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git update
Warning! `git update` has been deprecated;
Please use `git update-git-for-windows` instead.
Git for Windows 2.29.2.windows.2 (64bit)
Up to date

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git merge belka
Already up to date.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git checkout belka
Switched to branch 'belka'

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (belka)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git rebase -h
usage: git rebase [-i] [options] [--exec <cmd>] [--onto <newbase> | --keep-base] [<upstream> [<branch>]]
   or: git rebase [-i] [options] [--exec <cmd>] [--onto <newbase>] --root [<branch>]
   or: git rebase --continue | --abort | --skip | --edit-todo

    --onto <revision>     rebase onto given branch instead of upstream
    --keep-base           use the merge-base of upstream and branch as the current base
    --no-verify           allow pre-rebase hook to run
    -q, --quiet           be quiet. implies --no-stat
    -v, --verbose         display a diffstat of what changed upstream
    -n, --no-stat         do not show diffstat of what changed upstream
    --signoff             add a Signed-off-by: line to each commit
    --committer-date-is-author-date
                          make committer date match author date
    --reset-author-date   ignore author date and use current date
    -C <n>                passed to 'git apply'
    --ignore-whitespace   ignore changes in whitespace
    --whitespace <action>
                          passed to 'git apply'
    -f, --force-rebase    cherry-pick all commits, even if unchanged
    --no-ff               cherry-pick all commits, even if unchanged
    --continue            continue
    --skip                skip current patch and continue
    --abort               abort and check out the original branch
    --quit                abort but keep HEAD where it is
    --edit-todo           edit the todo list during an interactive rebase
    --show-current-patch  show the patch file being applied or merged
    --apply               use apply strategies to rebase
    -m, --merge           use merging strategies to rebase
    -i, --interactive     let the user edit the list of commits to rebase
    --rerere-autoupdate   update the index with reused conflict resolution if possible
    --empty <{drop,keep,ask}>
                          how to handle commits that become empty
    --autosquash          move commits that begin with squash!/fixup! under -i
    -S, --gpg-sign[=<key-id>]
                          GPG-sign commits
    --autostash           automatically stash/stash pop before and after
    -x, --exec <exec>     add exec lines after each commit of the editable list
    -r, --rebase-merges[=<mode>]
                          try to rebase merges instead of skipping them
    --fork-point          use 'merge-base --fork-point' to refine upstream
    -s, --strategy <strategy>
                          use the given merge strategy
    -X, --strategy-option <option>
                          pass the argument through to the merge strategy
    --root                rebase all reachable commits up to the root(s)
    --reschedule-failed-exec
                          automatically re-schedule any `exec` that fails
    --reapply-cherry-picks
                          apply all changes, even those already present upstream


isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git checkout belka
Switched to branch 'belka'

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (belka)
$ git rebase -onto master
error: did you mean `--onto` (with two dashes)?

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (belka)
$ git rebase --onto master
There is no tracking information for the current branch.
Please specify which branch you want to rebase against.
See git-rebase(1) for details.

    git rebase '<branch>'

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> belka


isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (belka)
$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> belka


isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (belka)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git rebase belka
error: could not apply f0755a0... User 3 change story in master
Resolve all conflicts manually, mark them as resolved with
"git add/rm <conflicted_files>", then run "git rebase --continue".
You can instead skip this commit: run "git rebase --skip".
To abort and get back to the state before "git rebase", run "git rebase --abort".
Could not apply f0755a0... User 3 change story in master
CONFLICT (add/add): Merge conflict in ryaba.txt
Auto-merging ryaba.txt

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master|REBASE 1/1)
$ git rebase --skip
Successfully rebased and updated refs/heads/master.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/MAGGen-hub/ryaba-Groop_HW.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push --force-with-lease origin master
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 + 46e03d7...36b21be master -> master (forced update)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git tag -a v1.1 -m "version 1.1"

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git tag -l
v1.0
v1.1

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git push
Everything up-to-date

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ cd ../../ryaba3/ryaba-Groop_HW

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git checkout -l
Your branch is up to date with 'origin/maga'.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git branch -l
* maga
  master

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 1), reused 2 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 379 bytes | 42.00 KiB/s, done.
From https://github.com/MAGGen-hub/ryaba-Groop_HW
 + 792d4c5...36b21be master     -> origin/master  (forced update)
Already up to date.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git branch -l
* maga
  master

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git pull origin
Already up to date.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git branch -l
* maga
  master

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git fetch

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git branch -l
* maga
  master

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git pull origin/zoya
fatal: 'origin/zoya' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git pull -l
error: unknown switch `l'
usage: git pull [<options>] [<repository> [<refspec>...]]

    -v, --verbose         be more verbose
    -q, --quiet           be more quiet
    --progress            force progress reporting
    --recurse-submodules[=<on-demand>]
                          control for recursive fetching of submodules

Options related to merging
    -r, --rebase[=(false|true|merges|preserve|interactive)]
                          incorporate changes by rebasing rather than merging
    -n                    do not show a diffstat at the end of the merge
    --stat                show a diffstat at the end of the merge
    --log[=<n>]           add (at most <n>) entries from shortlog to merge commit message
    --signoff[=...]       add Signed-off-by:
    --squash              create a single commit instead of doing a merge
    --commit              perform a commit if the merge succeeds (default)
    --edit                edit message before committing
    --cleanup <mode>      how to strip spaces and #comments from message
    --ff                  allow fast-forward
    --ff-only             abort if fast-forward is not possible
    --verify-signatures   verify that the named commit has a valid GPG signature
    --autostash           automatically stash/stash pop before and after
    -s, --strategy <strategy>
                          merge strategy to use
    -X, --strategy-option <option=value>
                          option for selected merge strategy
    -S, --gpg-sign[=<key-id>]
                          GPG sign commit
    --allow-unrelated-histories
                          allow merging unrelated histories

Options related to fetching
    --all                 fetch from all remotes
    -a, --append          append to .git/FETCH_HEAD instead of overwriting
    --upload-pack <path>  path to upload pack on remote end
    -f, --force           force overwrite of local branch
    -t, --tags            fetch all tags and associated objects
    -p, --prune           prune remote-tracking branches no longer on remote
    -j, --jobs[=<n>]      number of submodules pulled in parallel
    --dry-run             dry run
    -k, --keep            keep downloaded pack
    --depth <depth>       deepen history of shallow clone
    --shallow-since <time>
                          deepen history of shallow repository based on time
    --shallow-exclude <revision>
                          deepen history of shallow clone, excluding rev
    --deepen <n>          deepen history of shallow clone
    --unshallow           convert to a complete repository
    --update-shallow      accept refs that update .git/shallow
    --refmap <refmap>     specify fetch refmap
    -o, --server-option <server-specific>
                          option to transmit
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only
    --negotiation-tip <revision>
                          report that we have only objects reachable from this object
    --show-forced-updates
                          check for forced-updates on all updated branches
    --set-upstream        set upstream for git pull/fetch


isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (maga)
$ git checkout zoya
Switched to a new branch 'zoya'
Branch 'zoya' set up to track remote branch 'zoya' from 'origin'.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (zoya)
$ git checkout -b alternativehistory origin/zoya
Switched to a new branch 'alternativehistory'
Branch 'alternativehistory' set up to track remote branch 'zoya' from 'origin'.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory)
$ git merge -h
usage: git merge [<options>] [<commit>...]
   or: git merge --abort
   or: git merge --continue

    -n                    do not show a diffstat at the end of the merge
    --stat                show a diffstat at the end of the merge
    --summary             (synonym to --stat)
    --log[=<n>]           add (at most <n>) entries from shortlog to merge commit message
    --squash              create a single commit instead of doing a merge
    --commit              perform a commit if the merge succeeds (default)
    -e, --edit            edit message before committing
    --cleanup <mode>      how to strip spaces and #comments from message
    --ff                  allow fast-forward (default)
    --ff-only             abort if fast-forward is not possible
    --rerere-autoupdate   update the index with reused conflict resolution if possible
    --verify-signatures   verify that the named commit has a valid GPG signature
    -s, --strategy <strategy>
                          merge strategy to use
    -X, --strategy-option <option=value>
                          option for selected merge strategy
    -m, --message <message>
                          merge commit message (for a non-fast-forward merge)
    -F, --file <path>     read message from file
    -v, --verbose         be more verbose
    -q, --quiet           be more quiet
    --abort               abort the current in-progress merge
    --quit                --abort but leave index and working tree alone
    --continue            continue the current in-progress merge
    --allow-unrelated-histories
                          allow merging unrelated histories
    --progress            force progress reporting
    -S, --gpg-sign[=<key-id>]
                          GPG sign commit
    --autostash           automatically stash/stash pop before and after
    --overwrite-ignore    update ignored files (default)
    --signoff             add Signed-off-by:
    --no-verify           bypass pre-merge-commit and commit-msg hooks


isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory)
$ git merge --no-commit origin/dusya
Auto-merging ryaba.txt
CONFLICT (content): Merge conflict in ryaba.txt
Automatic merge failed; fix conflicts and then commit the result.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory|MERGING)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory|MERGING)
$ git merge
fatal: You have not concluded your merge (MERGE_HEAD exists).
Please, commit your changes before you merge.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory|MERGING)
$ git commit -m "User 3 merge zoya and dusya to alterhistory branch" -m "No conflict solution"
[alternativehistory b74e2ba] User 3 merge zoya and dusya to alterhistory branch

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory)
$ git merge
Already up to date.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory)
$ git push origin
fatal: The upstream branch of your current branch does not match
the name of your current branch.  To push to the upstream branch
on the remote, use

    git push origin HEAD:zoya

To push to the branch of the same name on the remote, use

    git push origin HEAD

To choose either option permanently, see push.default in 'git help config'.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory)
$ git branch -l
* alternativehistory
  maga
  master
  zoya

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory)
$ git checkout dusya
Switched to a new branch 'dusya'
Branch 'dusya' set up to track remote branch 'dusya' from 'origin'.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (dusya)
$ git checkout master
Switched to branch 'master'
Your branch and 'origin/master' have diverged,
and have 2 and 1 different commits each, respectively.
  (use "git pull" to merge the remote branch into yours)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master)
$ git push origin
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/MAGGen-hub/ryaba-Groop_HW.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master)
$ git checkout alternativehistory
Switched to branch 'alternativehistory'
Your branch is ahead of 'origin/zoya' by 4 commits.
  (use "git push" to publish your local commits)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory)
$ git push origin
fatal: The upstream branch of your current branch does not match
the name of your current branch.  To push to the upstream branch
on the remote, use

    git push origin HEAD:zoya

To push to the branch of the same name on the remote, use

    git push origin HEAD

To choose either option permanently, see push.default in 'git help config'.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory)
$

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory)
$

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory)
$ git push --set-upstream origin alternativehistory
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 680 bytes | 680.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'alternativehistory' on GitHub by visiting:
remote:      https://github.com/MAGGen-hub/ryaba-Groop_HW/pull/new/alternativehistory
remote:
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
 * [new branch]      alternativehistory -> alternativehistory
Branch 'alternativehistory' set up to track remote branch 'alternativehistory' from 'origin'.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory)
$ git merge --no-commit origin/maga
Auto-merging ryaba.txt
Automatic merge went well; stopped before committing as requested

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory|MERGING)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory|MERGING)
$ git commit -m "User 3 merge maga to althistory"
[alternativehistory a4cf2d0] User 3 merge maga to althistory

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory)
$ git checkout master
Switched to branch 'master'
Your branch and 'origin/master' have diverged,
and have 2 and 1 different commits each, respectively.
  (use "git pull" to merge the remote branch into yours)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master)
$ git pull
Auto-merging ryaba.txt
Merge made by the 'recursive' strategy.
 ryaba.txt | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master)
$ git merge --no-commit origin/maga
Auto-merging ryaba.txt
Automatic merge went well; stopped before committing as requested

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master|MERGING)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master|MERGING)
$ git commit -m "User 3 merge maga to master"
[master fbe0a1f] User 3 merge maga to master

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (master)
$ git checkout alternativehistory
Switched to branch 'alternativehistory'
Your branch is ahead of 'origin/alternativehistory' by 2 commits.
  (use "git push" to publish your local commits)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory)
$ git commit -m "User 3 add test1.txt"
[alternativehistory ed4cb44] User 3 add test1.txt
 1 file changed, 63 insertions(+)
 create mode 100644 test1.txt

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory)
$ git push origin
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 12 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 1.73 KiB | 1.73 MiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
   b74e2ba..ed4cb44  alternativehistory -> alternativehistory

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba3/ryaba-Groop_HW (alternativehistory)
$ cd ../../ryaba2/ryaba-Groop_HW

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git pull
remote: Enumerating objects: 15, done.
remote: Counting objects: 100% (15/15), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 9 (delta 2), reused 9 (delta 2), pack-reused 0
Unpacking objects: 100% (9/9), 2.33 KiB | 99.00 KiB/s, done.
From https://github.com/MAGGen-hub/ryaba-Groop_HW
 * [new branch]      alternativehistory -> origin/alternativehistory
Already up to date.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (master)
$ git checkout origin/alternativehistory
Note: switching to 'origin/alternativehistory'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at ed4cb44 User 3 add test1.txt

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW ((ed4cb44...))
$ git checkout alternativehistory
Switched to a new branch 'alternativehistory'
Branch 'alternativehistory' set up to track remote branch 'alternativehistory' from 'origin'.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (alternativehistory)
$ git branch -l
* alternativehistory
  belka
  dusya
  master

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (alternativehistory)
$ git add .

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (alternativehistory)
$ git commit -m "User 2 change test1.txt name to kolobok.txt"
[alternativehistory dc7a94a] User 2 change test1.txt name to kolobok.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 rename test1.txt => kolobok.txt (100%)

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (alternativehistory)
$ git push origin
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 302 bytes | 302.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/MAGGen-hub/ryaba-Groop_HW.git
   ed4cb44..dc7a94a  alternativehistory -> alternativehistory

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba2/ryaba-Groop_HW (alternativehistory)
$ cd ../../ryaba1/ryaba-Groop_HW

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (zoya)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master)
$ git pull
remote: Enumerating objects: 36, done.
remote: Counting objects: 100% (36/36), done.
remote: Compressing objects: 100% (17/17), done.
remote: Total 32 (delta 9), reused 28 (delta 6), pack-reused 0
Unpacking objects: 100% (32/32), 5.31 KiB | 64.00 KiB/s, done.
From https://github.com/MAGGen-hub/ryaba-Groop_HW
 + 28cd9d2...36b21be master             -> origin/master  (forced update)
 * [new branch]      alternativehistory -> origin/alternativehistory
 * [new branch]      dusya              -> origin/dusya
 * [new branch]      maga               -> origin/maga
Auto-merging ryaba.txt
CONFLICT (content): Merge conflict in ryaba.txt
Automatic merge failed; fix conflicts and then commit the result.

isaik@DESKTOP-D1BC83P MINGW64 ~/Documents/GitHub/ryaba/ryaba1/ryaba-Groop_HW (master|MERGING)
$
