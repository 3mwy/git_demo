# git

## basic
1. `git add <filename/all>`
> 添加文件到暂存区
2. `git status `
> 查看文件夹状态
3. `git commit -m <massage>`
> 提交库
4. `git log`
> 查看日志
---
## 撤销
1. `git checkout <filename>`
> 将暂存区文件反向覆盖源文件夹
2. `git rm --cached <filename>`
> 删除暂存区文件，终止提交
3. `git reset --hard <commitID>`
> 恢复版本
---
## 分支
1. `git branch`
> 查看分支信息
2. `git branch <newBranchName>`
> 新建分支
3. `git checkout <branchName>`
> 切换分支
4. `git merge <branchName>`
> 合并分支，前提是已经切换至被合并分支
5. `git branch -d <branchName>` 
> 删除分支
## 分支暂存
1. `git stash`
> 存
2. `git stash pop`
> 取

## github 远程仓库
1. `git push <respositoryName> <branchName>`
> 推送到远程仓库
2. `git remote add <origin/diyName> <remoteURL> ` 
> 给远端url添加别名，简化步骤1
3. `git push -u <diyName/remoteURL> <branchName>`
> -u记住url及分支名称，下次简化步骤1至只需`git push`