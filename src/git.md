# git
* git仓库
git init:初始化仓库
git status 检查文件状态
git status -s 精简文件状态
？？（两个红色？表示未被跟踪的文件）
git add +文件名： 1.将未被跟踪的文件添加到暂存区 2.
git add . 把所有文件加到暂存区
git commit -s"提交了一个html"
git checkout --+文件名（撤销修改）
git reset HEAD+要移除的文件名
git commit -a -m"描述消息"跳过add,直接将文件保持到仓库
git commit -m "feat: 头部"
git commit -m "fix: 修复了购物车无法选择的问题"
git push origin master 把代码提交到远程
git pull origin master 把代码下载下来

分支  branch 
master 正式环境分支
dev: 开发环境分支
git status 当前仓库的状态
