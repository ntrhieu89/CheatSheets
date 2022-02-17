#### Delete all local branches except branches master, foo and bar
```
git branch -D `git branch | grep -vE 'master|foo|bar'`
```
