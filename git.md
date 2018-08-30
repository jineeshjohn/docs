# docs
A collection of awesome things related to development






#### git commands
- `git show-ref <branchname>`	~ shows the pointers between local and remote
- `git checkout -b cssfloat `	~ creates new branch cssfloat
- `git checkout <branchname>`	~ switch branch
- `git branch -a 			`	~ list all local and remote branches
- `git branch -d <branchname>`	~ deletes the branch
- `git branch -m <newbranchname>`	~ rename branch
- `git push origin :<branchname>`	~ deletes remote branch
- `git add filename and path  `	~ add new file
- `git commit -am "comment"`	~ commit locally
- `git push origin master	`	~ sync local changes with remote
- `git log --pretty=oneline`
- `git tag v1.4.0 || git tag -a v1.4 -m` ~'my version 1.4'
- `git log --since=2.weeks` ~ show log for 2 weeks
- `git config --get remote.origin.url` ~ show the remote url
- `git clean -f` ~ remove untracked files
- `git diff --name-only` ~ return all changes files in a branch
- `git checkout -- file` ~ undo/reset changes to a file
- `git checkout .` ~undo/reset all the changes for list of files
- `git merge origin/develop --ff-only` ~ git fast forward
- `git cherry-pick <branch name>|hash` ~ pick the hash
- `git fetch --prune`
- `git remote -v` ~ get you the remote url *.git
- `git config --global` user.name "jjohn"
- `git reset` ~ unstage added files
- `git reset HEAD~1` ~ undo last commit and keep the changed files
- `git log | clip` ~ copy log to clip-board
- `git diff --name-only develop` ~ get all files that have been modified in other branch
- `git reset --hard HEAD~1` reset to one back
- `git stash --keep-index` //stash files - selected
- `git rm --cached file name` //remove from staged status
- `git reset HEAD` // remove from staged to modified
- `git fetch --all` // fetch all will pick up all the changes
- `git branch -f <branchName> 9be83aaf` // move branch head to a specific commit
- `git reset HEAD~1 --soft  ` undo without loosing changes
- `git stash apply stash^{/is}`
- `git stash save 'stash name'
- `git diff-tree --name-only commit id -r` // Print list of files in a commit
- `git checkout <hash>` -- path-to-filename
- `git rebase -i <hash>`  -- to-where-v-need
- `git stash show -p stash@{1}` -- view stash contents
- `git log --pretty=format:"%h|%ad|%an"` prettify logs
- `git reflog show --all | grep e632921` search a commit or find branch from a commit
- `git log --grep="<search keyword>"`
- `git pull --rebase` to avoid reset after force push
- `git checkout "`git rev-list master  -n 1 --first-parent --before=2018-01-01`"`  go one month back to commit
- `git reset --soft HEAD@{1}` reset to amended changes and make new commit
- `git config --global push.default current` git push default behaviour
- `git revert <commitId>` removes a particular commit
- `git stash show -p` see what is a stash
- `git commit message` : **If applied, this commit will** => refactor subsystem X for readability
- `:) esc:wq` ~ save you from get out of edit mode



