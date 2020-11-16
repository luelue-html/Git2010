  # git使用

  工作区 - 暂存区 - 本地仓库

  # readme   文档
  1. readme 文件可以以txt文档，也可以是md文档
  2. 一般和项目放在一起，作为项目的说明文档

  1. 
  2. 
  3. 工作区持有项目实际文件

  # 初始化
  1. git init 初始化的版本库
  2. 有  master   代表初始化成功
  3. 在当前目录下会生成一个隐藏文件，  .git代表这是一个版本库
  4. 不能操作 .git 不管他（继续隐藏）

  # 工作区内容提交到本地仓库
  1. 执行命令 git  add  文件名 将工作区的内容提交到暂存区
  2. "."   命令 git add .将所有变动   略略




  # 将本地仓库提交到远程仓库
  1. 在github创建一个远程仓库 git2009
  2. 本地工作区提交到本地仓库
  3. git remote add origin 远程仓库
  4. git remote-v 查看本地仓库所关联的远程仓库地址
  5. git push -u origin master   第一次执行
    git push 把本地仓库推送到远程仓库
    -u origin master 设置默认提交master分支到origin
    
    远程操作前
  