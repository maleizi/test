git init

git status

git add .
git add filename

git config --global user.email "you@example.com"
git config --global user.name "Your Name"

git commit -m 'xxx'

git log

git reset --hard 版本号（从版本库返回未修改状态）

git reset HEAD filename（从绿色状态返回红色状态）

git checkout -- filename（从红色状态返回未修改状态）

git reset --soft 版本号（从版本库返回绿色状态）

git reset --mix 版本号（从版本库返回红色状态）

git branch（查看分支）

git branch 分支名（创建分支）

git branch -d 分支名（删除分支）

git checkout 分支名（切换分支）

git merge 分支名（合并分支）
注意：先切换到主分支，可能产生冲突

git remote add origin（别名）https://github.com/xxx/xxx.git

git push -u origin master
git push -u origin dev

git clone https://github.com/xxx/xxx.git