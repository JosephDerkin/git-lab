Answer 1: git version 2.15.0

Answer 2: 
core.excludesfile=~/.gitignore
core.legacyheaders=false
core.quotepath=false
mergetool.keepbackup=true
push.default=simple
color.ui=auto
color.interactive=auto
repack.usedeltabaseoffset=true
alias.s=status
alias.a=!git add . && git status
alias.au=!git add -u . && git status
alias.aa=!git add . && git add -u . && git status
alias.c=commit
alias.cm=commit -m
alias.ca=commit --amend
alias.ac=!git add . && git commit
alias.acm=!git add . && git commit -m
alias.l=log --graph --all --pretty=format:'%C(yellow)%h%C(cyan)%d%Creset %s %C(white)- %an, %ar%Creset'
alias.ll=log --stat --abbrev-commit
alias.lg=log --color --graph --pretty=format:'%C(bold white)%h%Creset -%C(bold green)%d%Creset %s %C(bold green)(%cr)%Creset %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative
alias.llg=log --color --graph --pretty=format:'%C(bold white)%H %d%Creset%n%s%n%+b%C(bold blue)%an <%ae>%Creset %C(bold green)%cr (%ci)' --abbrev-commit
alias.d=diff
alias.master=checkout master
alias.spull=svn rebase
alias.spush=svn dcommit
alias.alias=!git config --list | grep 'alias\.' | sed 's/alias\.\([^=]*\)=\(.*\)/\1\     => \2/' | sort
include.path=~/.gitcinclude
include.path=.githubconfig
include.path=.gitcredential
diff.exif.textconv=exif
credential.helper=osxkeychain
user.name=Joseph Derkin
user.name=Joseph Derkin
git config --global user.email jd039218@ohio.edu
git config --global user.name Joseph


Answer 3: 
usage: git [--version] [--help] [-C <path>] [-c name=value]
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

Answer 4: 
On branch master

No commits yet

Untracked files:
(use "git add <file>..." to include in what will be committed)

README.md
answers.md

nothing added to commit but untracked files present (use "git add" to track)

Answer 5:
On branch master

No commits yet

Changes to be committed:
(use "git rm --cached <file>..." to unstage)

new file:   README.md

Untracked files:
(use "git add <file>..." to include in what will be committed)

answers.md

Answer 6:
On branch master

No commits yet

Changes to be committed:
(use "git rm --cached <file>..." to unstage)

new file:   README.md
new file:   answers.md

Answer 7:
On branch master
nothing to commit, working tree clean

Answer 8:
commit 29c76b19a45969214cd12c9401c2fc6c9c767885 (HEAD -> master)
Author: Joseph Derkingit config --global user.email jd039218@ohio.edugit config --global user.name Joseph <josephderkin@Josephs-MacBook-Pro.local>
Date:   Thu May 16 13:17:44 2019 -0400

Initial commit

commit b6bafd8cb51fe1be4cc7aaeb44494068b97c8080
Author: Joseph Derkingit config --global user.email jd039218@ohio.edugit config --global user.name Joseph <josephderkin@Josephs-MacBook-Pro.local>
Date:   Thu May 16 13:13:02 2019 -0400

Initial commit

Answer 9:
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git checkout -- <file>..." to discard changes in working directory)

modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")

Answer 10:
I ran the command "Head README.md" in terminal window, and no, the changes made online were not reflected in the local copy of README.md

Answer 11:
git-lab josephderkin$ git push

To https://github.com/JosephDerkin/git-lab.git
! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/JosephDerkin/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Answer 12:
I ran the command "Head README.md" in terminal window, after first running the git pull command. This time, the changes made online were reflected in the local copy of README.md

Answer 13:
.        ..        .git        .gitignore    README.md

Answer 14:
Done.
