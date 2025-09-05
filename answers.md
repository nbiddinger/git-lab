Answer 1    
git version 2.43.0

Answer 2    
user.name=Nicolas Biddinger
user.email=nb755524@ohio.edu
            
Answer 3    
usage: git add [<options>] [--] <pathspec>...

-n, --[no-]dry-run    dry run  
-v, --[no-]verbose    be verbose

-i, --[no-]interactive
                          interactive picking
-p, --[no-]patch      select hunks interactively
-e, --[no-]edit       edit current diff and apply
-f, --[no-]force      allow adding otherwise ignored files
-u, --[no-]update     update tracked files
--no-]renormalize    renormalize EOL of tracked files (implies -u)
-N, --[no-]intent-to-add
	record only the fact that the path will be added later
-A, --[no-]all        add changes from all tracked and untracked files
--[no-]ignore-removal ignore paths removed in the working tree (same as --no-all)
--[no-]refresh        don't add, only refresh the index
--[no-]ignore-errors  just skip files which cannot be added because of errors
--[no-]ignore-missing check if - even missing - files are ignored in dry run
--[no-]sparse         allow updating entries outside of the sparse-checkout cone
--[no-]chmod (+|-)x   override the executable bit of the listed files
--[no-]pathspec-from-file <file>

--[no-]pathspec-file-nul
		with --pathspec-from-file, pathspec elements are separated with NUL charater
Answer 4:    
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)
            
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
commit f437d778da3fdf274929171e63a89d3d46a2b83e (HEAD -> master)
Author: Nicolas Biddinger <nb755524@ohio.edu>
Date:   Fri Sep 5 14:46:32 2025 -0400

    Initial Comit

Answer 9
On branch main
nothing to commit, working tree clean

Answer 10
Yes

Answer 11
To https://github.com/nbiddinger/git-lab
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/nbiddinger/git-lab'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

It failed because my local copy does not contain the changes that I mande on the website

Answer 12
Yes, git pull downloaded the changes I made online to the local copy

Answer 13
.  ..  .git  .gitignore  README.md
