# css-project
I had git hub issues..
➜  invisiblecard git:(main) ✗ cd invisibleCard
➜  invisibleCard git:(main) ✗ ls
images     index.html style.css
➜  invisibleCard git:(main) ✗ git add .
➜  invisibleCard git:(main) ✗ git commit -m "added initial files" 
[main 383e1c1] added initial files
 4 files changed, 143 insertions(+)
 create mode 100644 invisibleCard/images/bg.jpg
 create mode 100644 invisibleCard/images/john-doe.jpg
 create mode 100644 invisibleCard/index.html
 create mode 100644 invisibleCard/style.css
➜  invisibleCard git:(main) ✗ git status
On branch main
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    ../images/bg.jpg
        deleted:    ../images/john-doe.jpg
        deleted:    ../index.html
        deleted:    ../style.css

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../css-project/

no changes added to commit (use "git add" and/or "git commit -a")
➜  invisibleCard git:(main) ✗ git status
On branch main
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    ../images/bg.jpg
        deleted:    ../images/john-doe.jpg
        deleted:    ../index.html
        deleted:    ../style.css

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../css-project/

no changes added to commit (use "git add" and/or "git commit -a")
➜  invisibleCard git:(main) ✗ git push
To github.com:jahman07104/invisibleCard.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'github.com:jahman07104/invisibleCard.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
➜  invisibleCard git:(main) ✗ git pull
From github.com:jahman07104/invisibleCard
 * [new branch]      main       -> origin/main
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> main

➜  invisibleCard git:(main) ✗ echo "# css-project" >> README.md                  
➜  invisibleCard git:(main) ✗ git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint:   git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint:   git branch -m <name>
Initialized empty Git repository in /Users/patrickharrison/Desktop/invisiblecard/invisibleCard/.git/
➜  invisibleCard git:(master) ✗ git config --global init.defaultBranch <name>
zsh: parse error near `\n'
➜  invisibleCard git:(master) ✗ git config --global init.defaultBranch <main>
zsh: parse error near `\n'
➜  invisibleCard git:(master) ✗ git config --global init.defaultBranch main  
➜  invisibleCard git:(master) ✗ commit -m "first commit"
zsh: command not found: commit

fatal: couldn't find remote ref master
➜  invisibleCard git:(main) ✗ git pull origin master jahman07104/css-project.git 
hint: Pulling without specifying how to reconcile divergent branches is
hint: discouraged. You can squelch this message by running one of the following
hint: commands sometime before your next pull:
hint: 
hint:   git config pull.rebase false  # merge (the default strategy)
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint: 
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
fatal: couldn't find remote ref master
➜  invisibleCard git:(main) ✗ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'github.com:jahman07104/css-project.git'
➜  invisibleCard git:(main) ✗ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   images/bg.jpg
        new file:   images/john-doe.jpg
        new file:   index.html
        new file:   style.css

➜  invisibleCard git:(main) ✗ git add .
➜  invisibleCard git:(main) ✗ git push
error: src refspec refs/heads/main does not match any
error: failed to push some refs to 'github.com:jahman07104/css-project.git'
➜  invisibleCard git:(main) ✗ git push --force
error: src refspec refs/heads/main does not match any
error: failed to push some refs to 'github.com:jahman07104/css-project.git'
➜  invisibleCard git:(main) ✗ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'github.com:jahman07104/css-project.git'
➜  invisibleCard git:(main) ✗ git checkout -b master
Switched to a new branch 'master'
➜  invisibleCard git:(master) ✗ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   images/bg.jpg
        new file:   images/john-doe.jpg
        new file:   index.html
        new file:   style.css

➜  invisibleCard git:(master) ✗ git push
error: src refspec refs/heads/master does not match any
error: failed to push some refs to 'github.com:jahman07104/css-project.git'
➜  invisibleCard git:(master) ✗ git add .
➜  invisibleCard git:(master) ✗ gti commit -m "added files"
zsh: command not found: gti
➜  invisibleCard git:(master) ✗ git commit -m "added files"
[master (root-commit) 5dc4929] added files
 5 files changed, 144 insertions(+)
 create mode 100644 README.md
 create mode 100644 images/bg.jpg
 create mode 100644 images/john-doe.jpg
 create mode 100644 index.html
 create mode 100644 style.css
➜  invisibleCard git:(master) git push
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 12 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (8/8), 595.91 KiB | 19.22 MiB/s, done.
Total 8 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:jahman07104/css-project.git
 * [new branch]      master -> master
➜  invisibleCard git:(master) 
************************************
I manged to resolve by checking out a new brach I called master and commited the files again 
and it worked