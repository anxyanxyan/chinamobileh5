Git常用操作参考链接：https://blog.csdn.net/pre_eminent/article/details/80488476

1.新建本地git仓库 
git init

2. git status
随便看一下 

3. 准备提交1.0版本的代码
本地操作：
git add --all

git status 

git commit -a -m 'china mobile h5 project init'

4. github仓库创建

5. 本地代码上传到远程git仓库
第一提交
git push https://github.com/anxyanxyan/chinamobileh5.git master

6. 以后,就是如下操作,提交之前先更新
git commit -a -m 'update readme.txt'

git pull https://github.com/anxyanxyan/chinamobileh5.git master
git pull orign master

git push https://github.com/anxyanxyan/chinamobileh5.git master

7. 其他每天上班下班的工作日常
如果有新增的文件:  git add --all

如果只是修改文件:  git commit -a -m '今天加一个logo'
