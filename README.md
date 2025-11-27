## Working Locally
- I use `git status` to see which files are modified and which branch I am on.
- `git add <file>` moves changes from my workspace into the staging area.
- `git commit -m "message"` saves a snapshot of the staged changes into my **local** repository.
- I can create and switch branches locally with `git switch -c <new-branch>` and `git switch <branch>`.
- `git log --oneline --graph --all` lets me see the history of commits and how branches and merges are connected.
 
## Working with Remotes
- A remote repository (like GitHub) is a copy of my project stored on a server so I can share it with others.
- `git remote add origin <url>` connects my local repository to a remote one on GitHub.
- `git push -u origin master` (or `main`) sends my local commits to the remote and sets the upstream tracking branch.
- `git pull` is basically `git fetch` + `git merge`: it brings new commits from the remote and merges them into my local branch.
- I should `git pull` before I push so I’m working with the most recent version and can resolve any conflicts locally.
