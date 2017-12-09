本地空目录好像不能推送
```
git config --global alias.lol 'log --oneline --all --decorate --graph'
 ~/.gitconfig
 [alias]
    st = status
    ci = commit
    co = checkout
    br = branch
    unstage = reset HEAD --
    last = log -1 HEAD
    

git remote -v
git remote add upstream URL
git fetch upstream
git merge upstream/master
```
