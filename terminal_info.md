Last login: Mon Aug 26 15:08:22 on ttys000
Karinnes-Air:~ coel$ pwd
/Users/coel
Karinnes-Air:~ coel$ cd projects
-bash: cd: projects: No such file or directory
Karinnes-Air:~ coel$ mkdir projects
Karinnes-Air:~ coel$ git --version
git version 2.23.0
Karinnes-Air:~ coel$ pwd
/Users/coel
Karinnes-Air:~ coel$ cd projects
Karinnes-Air:projects coel$ git clone https://github.com/Coel316/hellow-world.git
Cloning into 'hellow-world'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
Karinnes-Air:projects coel$ cd .
Karinnes-Air:projects coel$ cd
Karinnes-Air:~ coel$ cd .
Karinnes-Air:~ coel$ cd..
-bash: cd..: command not found
Karinnes-Air:~ coel$ cd ..
Karinnes-Air:Users coel$ cd .
Karinnes-Air:Users coel$ cd ~
Karinnes-Air:~ coel$ cd codefellows
-bash: cd: codefellows: No such file or directory
Karinnes-Air:~ coel$ cd projects
Karinnes-Air:projects coel$ git clone https://github.com/Coel316/learning-journal.git
Cloning into 'learning-journal'...
remote: Enumerating objects: 85, done.
remote: Counting objects: 100% (85/85), done.
remote: Compressing objects: 100% (81/81), done.
remote: Total 85 (delta 26), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (85/85), done.
Karinnes-Air:projects coel$ get status
-bash: get: command not found
Karinnes-Air:projects coel$ get git status
-bash: get: command not found
Karinnes-Air:projects coel$ cd projects
-bash: cd: projects: No such file or directory
Karinnes-Air:projects coel$ ls
hellow-world		learning-journal
Karinnes-Air:projects coel$ cd
Karinnes-Air:~ coel$ ls
Applications	Documents	Library		Music		Public
Desktop		Downloads	Movies		Pictures	projects
Karinnes-Air:~ coel$ cd projects
Karinnes-Air:projects coel$ get git status
-bash: get: command not found
Karinnes-Air:projects coel$ get status
-bash: get: command not found
Karinnes-Air:projects coel$ git status
fatal: not a git repository (or any of the parent directories): .git
Karinnes-Air:projects coel$ ls
hellow-world		learning-journal
Karinnes-Air:projects coel$ cd
Karinnes-Air:~ coel$ git status
fatal: not a git repository (or any of the parent directories): .git
Karinnes-Air:~ coel$ cd projects
Karinnes-Air:projects coel$ ls
hellow-world		learning-journal
Karinnes-Air:projects coel$ cd hellow-world
Karinnes-Air:hellow-world coel$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
Karinnes-Air:hellow-world coel$ cd learning-journal
-bash: cd: learning-journal: No such file or directory
Karinnes-Air:hellow-world coel$ cd
Karinnes-Air:~ coel$ cd projects
Karinnes-Air:projects coel$ learning-journal
-bash: learning-journal: command not found
Karinnes-Air:projects coel$ learning-journal
-bash: learning-journal: command not found
Karinnes-Air:projects coel$ cd learning-journal
Karinnes-Air:learning-journal coel$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   learn-markup.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	HomePage
	Learning-with-git.md

no changes added to commit (use "git add" and/or "git commit -a")
Karinnes-Air:learning-journal coel$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   learn-markup.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	HomePage
	Learning-with-git.md

no changes added to commit (use "git add" and/or "git commit -a")
Karinnes-Air:learning-journal coel$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   learn-markup.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	Learning-with-git.md
	home-page.md

no changes added to commit (use "git add" and/or "git commit -a")
Karinnes-Air:learning-journal coel$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   learn-markup.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	home-page.md
	learning-with-git.md

no changes added to commit (use "git add" and/or "git commit -a")
Karinnes-Air:learning-journal coel$ git add home-page.md learning-with-git.md learn-markup.md 
Karinnes-Air:learning-journal coel$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   home-page.md
	modified:   learn-markup.md
	new file:   learning-with-git.md

Karinnes-Air:learning-journal coel$ git commit -m "initial practice with ACP"
[master 9d38444] initial practice with ACP
 3 files changed, 29 insertions(+), 3 deletions(-)
 create mode 100644 home-page.md
 create mode 100644 learning-with-git.md
Karinnes-Air:learning-journal coel$ git push 
Username for 'https://github.com': Coel316
Password for 'https://Coel316@github.com': 
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 1013 bytes | 1013.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Coel316/learning-journal.git
   afdf543..9d38444  master -> master
Karinnes-Air:learning-journal coel$ cd projects
-bash: cd: projects: No such file or directory
Karinnes-Air:learning-journal coel$ cd
Karinnes-Air:~ coel$ cd projects
Karinnes-Air:projects coel$ git status 
