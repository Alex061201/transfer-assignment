# How to use `git`
1. Initialize a repository with `git init`.
2. Stage your files with `git add <path to file or directory>`.
3. Whenever you made a substantial change, put it into the history with `git commit`.
4. See your history with `git log`.
5. Move around (history and branches!) with `git checkout <ID of the commit or name of the branch you want to jump to>`.
6. Create new branches with `git checkout -b <name of new branch>`. Alternatively one can also create a new branch with `git branch <name of new branch>`, but this command will not check the newly created branch out.
7. To collaborate, first `git pull` others changes, then `git push` yours.