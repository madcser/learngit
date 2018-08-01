Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes of files.
Creating a new branch “dev” is so quick.

安装

1、linux
用Debian或Ubuntu Linux，通过一条sudo apt-get install git就可以直接完成Git的安装,老一点的Debian或Ubuntu Linux，要把命令改为sudo apt-get install git-core,其他Linux版本，可以直接通过源码安装。先从Git官网下载源码，然后解压，依次输入：./config，make，sudo make install这几个命令安装就好了。
http://forum.ubuntu.org.cn/
https://www.iplaysoft.com/ubuntu.html
https://www.debian.org/

2、Mac OS
运行Xcode，选择菜单“Xcode”->“Preferences”，在弹出窗口中找到“Downloads”，选择“Command Line Tools”，点“Install”就可以完成安装了。

3、Windows
如果你使用Windows系统，为了避免遇到各种莫名其妙的问题，请确保目录名（包括父目录）不包含中文
https://git-scm.com/downloads

初始化
“Git”->“Git Bash”初始化
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"

通过git init命令把这个目录变成Git可以管理的仓库


Git鼓励大量使用分支：

查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>