# 管理一个项目

- git init 生成.git文件夹 这就是我们的仓库
- git add .  把当前文件夹里面的所有非空文件设置成准备提交的状态
- git commit -m '功能1完成'  引号里面是注释
- git log 查看提交的记录
- git checkout HEAD main.py     main.py 被修改过了,使用这个指令可以把main.py恢复到上一次你提交的状态
- git add main.py  把main.py 设置成准备提交的状态
- git commit -m '功能2完成' 
- git add 3.py   设置成准备提交的状态才能commit
- git commit -m '功能3完成'