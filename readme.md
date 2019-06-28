# 这首我的一份Markdown文件

将使用git管理
我添加了一行改动

## git 命令总结

- git init 创建版本库
- git config user.name 查看用户名
- git config user.email 查看邮箱
- git config --global user.name "<用户名>" 修改用户名
- git config --gloabl user.email "<邮箱>" 修改邮箱
- git add <文件名> 把修改提交到暂存区
- git commit -m "<描述>"
- git status 查看工作区状态
- git diff 查看修改内容
- git reset --hard <HEAD^> 回退到上一版本 <HEAD> 指当前版本 <HEAD^> 指上一版本 <HEAD^^>上上个版本 <HEAD~100> 上100个版本
- git reset --hard <commit_id> 根据id在版本间穿梭
- git log 查看提交历史 --pretty=oneline 显示简洁信息
- git reflog 查看命令历史
- git checkout -b <分支名> 创建新的分支并切换 等效下面两条命令
- git branch <分支名> 创建分支
- git checkout <分支名> 切换分支
- git branch 查看分支 当前分支前有*
- git branch -d <分支名> 删除分支
- git merge <分支名> 合并某分支到当前分支
