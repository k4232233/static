# Git常用命令

- 创建本地仓库

  ```java
  // 初始化当前目录为仓库，初始化后会自动将当前仓库设置为master
  git init
  ```

- 添加文件到本地仓库

  ```java
  // 将文件添加到缓存区
  git add
  // 将所有文件添加到缓冲区
  git add.
  // 提交到本地仓库
  git commit -m "简述"
  // 重写上一次提交信息（简述）
  git commit --amend
  ```

- 查看历史提交日志

  ```java
  // 查看日志
  git log
  ```

- 删除文件

  ```java
  git rm
  ```

- 查看提交记录

  ```
  git reflog
  ```

- 将本地仓库关联到远程仓库

  ```
  git remote add origin 仓库地址
  ```

- 推送到远程

  ```java
  // 第一次加上u，把所有分支提交上去
  git push -u origin master
  // 以后可以不加u，推最新代码
  git push origin master
  ```

- 拉取远程仓库

  ```java
  // 默认main分支
  git clone 仓库地址
  // 切换分支
  git clone -b分支名 仓库地址
  // 拉取所有分支
  git fetch
  ```

- 修改分支名称

  ```
  git branch
  ```

  