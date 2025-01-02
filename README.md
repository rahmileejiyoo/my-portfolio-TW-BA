# my-portfolio-TW-BA
My Portfolios which I get from my work in Technical Writer and Business Analyst scope area

**##Riwayat Kodingan**
Berikut riwayat kodingan repository ini:

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA
$ git init
Initialized empty Git repository in D:/Automate/my-portfolio-TW-BA/.git/

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (master)
$ ls -a
./  ../  .git/

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (master)
$ git remote add new-origin https://github.com/rahmileejiyoo/my-portfolio-TW-BA.git

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (master)
$ git branch -m master main

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ nano file-portfolio1.txt

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ add file-portfolio1.txt
bash: add: command not found

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ nano file-portfolio1.txt

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git add file-portfolio1.txt
warning: in the working copy of 'file-portfolio1.txt', LF will be replaced by CRLF the next time Git touches it

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git add --renormalize file-portfolio.txt
fatal: pathspec 'file-portfolio.txt' did not match any files

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git add --renormalize file-portfolio1.txt

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   file-portfolio1.txt


lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git commit -m "upload new file"
[main (root-commit) eabfabe] upload new file
 1 file changed, 2 insertions(+)
 create mode 100644 file-portfolio1.txt

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git status
On branch main
nothing to commit, working tree clean

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git remote -v
new-origin      https://github.com/rahmileejiyoo/my-portfolio-TW-BA.git (fetch)
new-origin      https://github.com/rahmileejiyoo/my-portfolio-TW-BA.git (push)

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git push --set-upstream new-origin main
To https://github.com/rahmileejiyoo/my-portfolio-TW-BA.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/rahmileejiyoo/my-portfolio-TW-BA.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git pull new-origin main --rebase remote
fatal: couldn't find remote ref remote

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ ^C

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git pull --rebase new-origin main
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 961 bytes | 192.00 KiB/s, done.
From https://github.com/rahmileejiyoo/my-portfolio-TW-BA
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> new-origin/main
Successfully rebased and updated refs/heads/main.

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git push new-origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 410 bytes | 410.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/rahmileejiyoo/my-portfolio-TW-BA.git
   c6d1d75..a7ad67f  main -> main

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git status
On branch main
nothing to commit, working tree clean

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git checkout -b my-task-including-TW
Switched to a new branch 'my-task-including-TW'

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ nano portfolio-TW_Scope.txt

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ git add portfolio-TW_Scope.txt
warning: in the working copy of 'portfolio-TW_Scope.txt', LF will be replaced by CRLF the next time Git touches it

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ git add --renormalize portfolio-TW_Scope.txt

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ git status
On branch my-task-including-TW
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   portfolio-TW_Scope.txt


lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ ls
README.md  file-portfolio1.txt  portfolio-TW_Scope.txt

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ git add .

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ git commmit -m "added new file"
git: 'commmit' is not a git command. See 'git --help'.

The most similar command is
        commit

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ git commit -m "added new file"
[my-task-including-TW 9fd2f54] added new file
 1 file changed, 1 insertion(+)
 create mode 100644 portfolio-TW_Scope.txt

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ git status
On branch my-task-including-TW
nothing to commit, working tree clean

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ nano portfolio-BA_Scope.txt

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ git add portfolio-BA_Scope.txt
warning: in the working copy of 'portfolio-BA_Scope.txt', LF will be replaced by CRLF the next time Git touches it

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ git --renormalize portfolio-BA_Scope.txt
unknown option: --renormalize
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ git add --renormalize portfolio-BA_Scope.txt

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ ls
README.md  file-portfolio1.txt  portfolio-BA_Scope.txt  portfolio-TW_Scope.txt

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ git add .

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ git commit -m "added new file"
[my-task-including-TW 60ad942] added new file
 1 file changed, 1 insertion(+)
 create mode 100644 portfolio-BA_Scope.txt

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ nano portfolio-QA_Scope.txt

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ git add portfolio-QA_Scope.txt
warning: in the working copy of 'portfolio-QA_Scope.txt', LF will be replaced by CRLF the next time Git touches it

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ git add --renormalize portfolio-QA_Scope.txt

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ ls
README.md            portfolio-BA_Scope.txt  portfolio-TW_Scope.txt
file-portfolio1.txt  portfolio-QA_Scope.txt

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ git add .

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ git commit -m "added new file"
[my-task-including-TW bdf89b7] added new file
 1 file changed, 1 insertion(+)
 create mode 100644 portfolio-QA_Scope.txt

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ git checkout main
Switched to branch 'main'

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git checkout my-task-including-TW
Switched to branch 'my-task-including-TW'

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ git checkout main
Switched to branch 'main'

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git remote -v
new-origin      https://github.com/rahmileejiyoo/my-portfolio-TW-BA.git (fetch)
new-origin      https://github.com/rahmileejiyoo/my-portfolio-TW-BA.git (push)

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git branch
* main
  my-task-including-TW

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git push --set-upstream new-origin my-task-including-TW
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 8 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (9/9), 879 bytes | 879.00 KiB/s, done.
Total 9 (delta 2), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'my-task-including-TW' on GitHub by visiting:
remote:      https://github.com/rahmileejiyoo/my-portfolio-TW-BA/pull/new/my-task-including-TW
remote:
To https://github.com/rahmileejiyoo/my-portfolio-TW-BA.git
 * [new branch]      my-task-including-TW -> my-task-including-TW
branch 'my-task-including-TW' set up to track 'new-origin/my-task-including-TW'.

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git merge my-task-including-TW
Updating a7ad67f..bdf89b7
Fast-forward
 portfolio-BA_Scope.txt | 1 +
 portfolio-QA_Scope.txt | 1 +
 portfolio-TW_Scope.txt | 1 +
 3 files changed, 3 insertions(+)
 create mode 100644 portfolio-BA_Scope.txt
 create mode 100644 portfolio-QA_Scope.txt
 create mode 100644 portfolio-TW_Scope.txt

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git pull new-origin main
From https://github.com/rahmileejiyoo/my-portfolio-TW-BA
 * branch            main       -> FETCH_HEAD
Already up to date.

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git push --set-upstream new-origin main
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/rahmileejiyoo/my-portfolio-TW-BA.git
   a7ad67f..bdf89b7  main -> main
branch 'main' set up to track 'new-origin/main'.

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git add .

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git commit -m "Save all changes"
On branch main
Your branch is up to date with 'new-origin/main'.

nothing to commit, working tree clean

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git push new-origin main
Everything up-to-date

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git checkout my-task-including-TW
Switched to branch 'my-task-including-TW'
Your branch is up to date with 'new-origin/my-task-including-TW'.

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (my-task-including-TW)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'new-origin/main'.

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git branch -d my-task-including-TW
Deleted branch my-task-including-TW (was bdf89b7).

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git push origin --delete my-task-including-TW
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git push new-origin --delete my-task-including-TW
To https://github.com/rahmileejiyoo/my-portfolio-TW-BA.git
 - [deleted]         my-task-including-TW

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git add .

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git commit -m "Save all changes"
On branch main
Your branch is up to date with 'new-origin/main'.

nothing to commit, working tree clean

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$ git push new-origin main\
>
Everything up-to-date

lia.rahmi@NBSS-D-0599 MINGW64 /d/Automate/my-portfolio-TW-BA (main)
$
