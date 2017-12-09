先本地有一个test1库(里面有很多内容），后在远端建一个test1库（或其它名称），再把本地内容push到远端
2
本地空目录好像不能推送
```
git remote -v
git remote add upstream URL
git fetch upstream
git merge upstream/master
```
