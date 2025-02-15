如何推送文件至远程？
1、①建立本地仓库
②与远程建立连接，测试：ssh -T git@github.com
2、③init命令初始化仓库：git init
3、④手动拷贝文件，并执行add命令
git add 文件夹1/ 文件夹2/
4、⑤commit命令：git commit -m “注释”
5、⑥push命令：git push -u origin master
