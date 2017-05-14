基本操作流程

从 https://github.com/Philosjay/YXH fork 到你自己的github中

创建本地仓库：

git clone https://github.com/**YourGithubAccount**/YXH
cd CCpp2017
ls

git config user.name=???
git config user.email=??? 

git remote -v
git remote add upstream https://github.com/luckymark/CCpp2017
修改、提交代码：

git status
git add .
git commit -m "完成了running letter"
git push

从 https://github.com/Philosjay/YHX 获取更新:

git fetch upstream
git merge upstream/master

Git 入门教程：
http://www.infoq.com/cn/news/2011/01/git-adventures-1
http://www.infoq.com/cn/news/2011/01/git-adventures-install-config
http://www.infoq.com/cn/news/2011/02/git-adventures-local-repository
http://www.infoq.com/cn/news/2011/03/git-adventures-index-commit
