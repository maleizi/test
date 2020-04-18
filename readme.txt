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