# Louplus
All thinng i get from 

创建本地文件
mkdir Demo
cd Demo
gedit README.md

将一个已存在文件夹，置于 Git 的控制管理之下。
git init

使用 git add + 文件名/目录名 命令，可以将你需要同步的文件，添加到本地的暂存区。我们先进入 DEMO 目录，然后把 README.md 文件添加一下

cd /home/XXX/Demo
git add README.md


输入 git status ，可以检测当前目录和暂存区的状态，查看哪些修改被暂存了
git status

git commit 提交是你工作的一个里程碑 —— 每当你完成一些工作，都可以创建一次提交，保存当前的版本。
$ git config --global user.name "YourName"
$ git config --global user.email "YourEmail@xxx.com"

完成配置后，我们可以创建提交了，请输入：
git commit -m "备注"

使用如下命令，将本地仓库连接到 GitHub 仓库中：
git remote add origin 仓库链接
add 很容易明白 —— 添加。git remote add 表示通知 Git 去添加一个远程仓库，
后面接上的 origin 是这个仓库的小名，方便以后沟通，通常默认用 origin 来表示；最后再接上远程仓库的地址，即你刚刚创建的 Github 仓库链接。

push 顾名思义，就是推送， 使用 push 可以把本地仓库推送到远端仓库中
git push origin master

如果你想要复制一个项目，看看代码，或者把自己的远程仓库复制到本地，可以执行命令
git clone [url]


NEXT TO do
在 Github 的个人主页中新建一个仓库，命名为 Louplus
复制仓库链接，在实验环境中，将该仓库克隆到本地
在 Github 的个人主页中新建一个仓库，命名为 Louplus
复制仓库链接，将该仓库克隆到本地
wget http：/dhhfhhh

使用 git add --all 命令，添加仓库内的所有文件
使用 git commit、git remote、git push 命令，将本地仓库同步到 Github 中
