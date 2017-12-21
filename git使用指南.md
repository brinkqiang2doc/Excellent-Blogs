##Markdown基本语法
- [Markdown grammer](http://younghz.github.io/Markdown/)

##git使用问题记录
### 如果提交了某个版本，需要回滚怎么办？
> 分为两种情况，一种是只在本地commit，但还没有push到远程服务器上，此时可以使用*git reset [--soft | --mixed | --hard]*命令来进行还原，其中hard最为常用；若是已经push到服务器上，此时可以使用*git revert*来进行回滚，一般都是回滚到上一次提交之前的版本，也就是用一个新提交来消除一个历史提交所做的任何修改。

