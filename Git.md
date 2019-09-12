# Git

## 基本使用

- 工作区 →暂存区 → 本地仓库 → 远程仓库
  - 工作区 →暂存区
  - 暂存区 →本地仓库
  - 本地仓库 →远程仓库
- 回退
  - 暂存区 →工作区
    - git checkout .
    - git checkout 文件名...
  - 本地仓库 →暂存区
    - git reset 文件名
  - 本地仓库→（暂存区和工作区）
    - git reset   --hard
- 分支
  - 查看分支
    - git branch
  - 创建分支
    - git branch 分支名
  - 切换分支
    - git checkout 分支名
  - 创建并切换分支
    - git checkout -b 分支名
  - 删除分支
    - git branch -d 分支名 （必须先切换到另外一个分支上，然后在删除当前分支）
  - 合并分支
    - git merge 分支名
- 其他命令
  - 查看文件的状态
    - git status
  - 查看历史纪录（会得到版本号）
    - git log
    - git log --oneline
  - 

## 可能的错误

![1566783613412](C:\Users\Junjie\AppData\Roaming\Typora\typora-user-images\1566783613412.png)