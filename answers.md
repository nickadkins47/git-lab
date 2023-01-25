------------------------------------------------------------
Answer 1:

git version 2.17.1

------------------------------------------------------------
Answer 2:

user.name=NickAdkins
user.email=na761422@ohio.edu

------------------------------------------------------------
Answer 3:

usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.

------------------------------------------------------------
Answer 4:

On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	README.md
	answers.md

nothing added to commit but untracked files present (use "git add" to track)

------------------------------------------------------------
Answer 5: 

On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	answers.md

------------------------------------------------------------
Answer 6:

On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md
	new file:   answers.md

------------------------------------------------------------
Answer 7:

On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")

------------------------------------------------------------
Answer 8:

commit e2933afbfc6db257f5667c0084535a174ab3e612 (HEAD -> master)
Author: NickAdkins <na761422@ohio.edu>
Date:   Wed Jan 25 16:49:22 2023 -0500

    Initial commit

------------------------------------------------------------
Answer 9:

On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   answers.md

------------------------------------------------------------
Answer 10:

I checked, and the local README.md file on the linux system has not updated after
changing the file online at github.com

------------------------------------------------------------
Answer 11:

Basically the way i view it is that the README.md file i have locally on this linux system is now
out of date after the changes made online previously, and now git refuses to push an outdated version of my file to the online repository.

Username for 'https://github.com': nickadkins47
Password for 'https://nickadkins47@github.com': 
To https://github.com/nickadkins47/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/nickadkins47/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

------------------------------------------------------------
Answer 12:

After using "git pull" the changes i made online were applied to the local file.

------------------------------------------------------------
Answer 13:

.  ..  .git  .gitignore  README.md



