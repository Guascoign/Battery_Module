# Battery_Module

单电池升降压模块

## [Git 快速上手:](https://www.runoob.com/git/git-tutorial.html)
```
定位到目录		cd existing_repo
初始化			git init
查看状态			git status
追踪所有文件		git add .
追踪指定文件		git add xxx
上传本地暂存		git commit -m "commit"
查看绑定			git remote -v
定位仓库			add origin http://iicmc.cn:1002/ZM/M.2.git
重置仓库定位		git remote rm origin
切换分支			git branch -M main
上传云端仓库		git push -uf origin main:dev
克隆			git clone <repo>
设置提交用户信息		git config --global user.name "username"
			git config --global user.email xx@xx.com
比较文件的不同		git diff
回退版本			git reset
删除暂存区和工作区中文件	git rm
移动或重命名工作区文件	git mv
分支切换			git checkout
更清晰地切换分支		git switch 
恢复或撤销文件的更改	git restore 
查看历史提交记录		git log
列表查看指定文件的历史修改	git blame <file>
远程仓库操作		git remote
从远程获取代码库		git fetch
下载远程代码并合并		git pull
上传远程代码并合并		git push
列出分支			git branch
删除分支			git branch -d (branchname)
分支合并			git merge
Git 标签			git tag -a v1.0 
``` 
``` 
Git 全局设置
git config --global user.name "赵淼"
git config --global user.email "1529156314@qq.com"
创建一个新仓库
git clone git@iicmc.cn:ZM/M.2.git
cd M.2
git switch --create main
touch README.md
git add README.md
git commit -m "add README"
git push --set-upstream origin main
推送现有文件夹
cd existing_folder
git init --initial-branch=main
git remote add origin git@iicmc.cn:ZM/M.2.git
git add .
git commit -m "Initial commit"
git push --set-upstream origin main
推送现有的 Git 仓库
cd existing_repo
git remote rename origin old-origin
git remote add origin git@iicmc.cn:ZM/M.2.git
git push --set-upstream origin --all
git push --set-upstream origin --tags
``` 