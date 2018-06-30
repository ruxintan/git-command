git log（--pretty=oneline）：查看提交历史记录（commit后）
git reset:版本回退（commit过）；暂存区的修改撤销（暂未commit到版本库）
git reflog：记录命令
git diff HEAD -- readme.txt：查看工作区和版本库文件的区别
git checkout -- file：版本库里的版本替换工作区的版本（暂未add到暂存区）
git rm：暂存区删除文件+git commit
git remote add origin git@github.com:michaelliao/learngit.git：关联远程仓库
git push origin master：本地库的内容推送到远程
git checkout -b dev：创建dev分支（git branch dev+git checkout dev）
git branch：查看当前分支
git merge dev：合并指定分支到当前分支
git branch -d <name>：删除分支
git log --graph：查看分支合并图
git stash：暂存状态
git remote：查看远程库信息
git tag <name>：打标签
.gitignore：忽略某些文件时
git config --global alias.st status：配置别名

git add -A 提交全部文件
git commit -m"message" 

git diff:查看修改内容