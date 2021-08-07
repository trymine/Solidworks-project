# Solidworks-project
about solidworks

git使用记录
1、创建远程库仓库
如https://github.com/trymine/Solidworks-project.git
2、本地仓库初始化：
寻找合适本地路径，进行初始化
```C
git init
```
3、添加远程仓库名称和路径
```C
git remote add Solidworks https://github.com/trymine/Solidworks-project.git
```
4、先同步远程库内容到本地，避免冲突
```C
git pull Solidworks mian:master
git push Solidworks master:master
```
5、同步本地内容到本地仓库
```C
git add [file][.]
git commit -m "添加提交注释"
```
若想要取消本地已经add或commit操作
```C
git reset HEAD
git reset HEAD~1
```
6、本地仓库分支同步远程仓库分支

```C
git push Solidworks master:master
```