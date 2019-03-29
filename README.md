
```
git config --local user.name "xxx"
git config --local user.email "xxx@sina.com"

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

git commit -m"【一级模块】a 【二级模块】b【内容】增加model"
git commit -m"【模块】a【内容】增加model"
```
