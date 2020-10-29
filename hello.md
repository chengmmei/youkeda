#### 绑定本地仓库文件到github：
1. cd命令进入文件夹并且使用命令git init进行初始化为一个git仓库
1. git remote -v查看是否曾远程绑定过，命令执行为空则没有绑定过
1. git remote add origin github仓库地址
1. 使用git remote -v查看是否绑定成功
#### 将本地仓库内容提交：
1. git add -A 
1. git commit -m "备注"
1. git branch -M main，这个要注意添加
1. git push origin main ，第一次添加使用这个命令