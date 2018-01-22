检查2
test status
git checkout -- file 工作区文件回退  看是否已经提交后修改
git reset HEAD file 将已经提交到暂存区的修改撤销掉
git reset -- hard Head^或者~100
git reset -- hard 版本编号
git log 
git reflog 
rm file 删除文件
git rm file 在版本库和工作区删除文件
git branch dev  创建dev分支
git checkout dev 将HEAD指针切换到dev
git checkout -b dev 创建并切换
先关联仓库  看官网
git remote add origin git@github.com:Flyingpigsw/test.git
git push -u origin master 将当前分支master推送到远程
后面的推送操作 可以简化为  git push origin master
克隆先创建远程库
git clone git@github.com:Flyingpigsw/test.git
ls 查看文件
git merge dev 切换分支到master然后合并dev 到master
git branch -d dev 删除分支
git log --graph --pretty=oneline --abbrev-commit 查看分支的合并情况
在遇到提交冲突时需手动调解冲突
禁用Fast forward 
git merge --no-ff -m "提交解除Fast forward" dev


