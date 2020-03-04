# git

## basic
1. `git add <!--filename/all-->`
> 添加文件到暂存区
2. `git status `
> 查看文件夹状态
3. `git commit -m ''`
> 提交库
4. `git log`
> 查看日志
---
## 撤销
1. `git checkout <!-- filename -->`
> 将暂存区文件反向覆盖源文件夹
2. `git rm --cached <!-- filename -->`
> 删除暂存区文件，终止提交
3. `git reset --hard commitID`
> 恢复版本