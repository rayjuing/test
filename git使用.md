# 管理一个项目

- git init <!--通过命令git init把这个文件夹变成Git可管理的仓库-->
- git add .  把当前文件夹里面的所有非空文件设置成准备提交的状态
- git commit -m '功能1完成'  引号里面是注释
- git log 查看提交的记录
- git checkout HEAD main.py     main.py 被修改过了,使用这个指令可以把main.py恢复到上一次你提交的状态

## 提交到仓库

- git add main.py   <!--把main.py 设置成准备提交的状态-->
- git commit -m '功能2完成'   <!--把项目提交的仓库-->
- git add 3.py   设置成准备提交的状态才能commit
- git commit -m '功能3完成'

## 配置你的username 和email

​	git config --global user.name YuHaoWu

 	git config --global user.email 2496120334@qq.com

## 上传本地仓库到github

1. 在github上新建一个repo(资源库)![image-20230409191919061](C:\Users\LEGION\AppData\Roaming\Typora\typora-user-images\image-20230409191919061.png)

1. git remote add origin git@github.com:rayjuing/test.git

​	这样就实现了本地仓库和刚刚新创建的仓库关联起来	

​	网址是上图中网址或者ssh 直接copy就行

	2. 关联后 要把内容推送的github上

​	$ git push -u origin master

