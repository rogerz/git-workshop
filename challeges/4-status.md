## challenge

- create empty files named `commit`, `staged`, `not-staged`, `untracked`
- take any steps or tools to create the specified status
- do NOT publish your changes to remote
- save output of `ls && git status` of each status

### status 1

- `commit` is committed
- `stage` is staged
- `not-staged` is not staged
- `untracked` is untracked

expected output

```
➜  git-workshop git:(master) ✗ ls && git status
README.md       commit          registration.md staged
challeges       not-staged      solutions       untrack
On branch master
Your branch and 'origin/master' have diverged,
and have 3 and 1 different commit each, respectively.
  (use "git pull" to merge the remote branch into yours)
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	new file:   staged

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   not-staged

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	untrack
```

### status 2

- `commit`, `stage`, `not-staged` and `untracked` are all committed

### status 3

- create status 1 again

### status 4

- remove `commit`, `stage`, `not-staged` and `untracked`

### publish

publish outputs of each status

## command

```
touch
git status
git add
git commit
git reset
git push
git clean
```
