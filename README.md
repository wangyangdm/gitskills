# gitskills
gitskills
hello github
=================================================
你也许还注意到，GitHub给出的地址不止一个，
还可以用https://github.com/michaelliao/gitskills.git这样的地址。
实际上，Git支持多种协议，默认的git://使用ssh，但也可以使用https等其他协议。

使用https除了速度慢以外，还有个最大的麻烦是每次推送都必须输入口令，
但是在某些只开放http端口的公司内部就无法使用ssh协议而只能用https

要克隆一个仓库，首先必须知道仓库的地址，然后使用git clone命令克隆。
Git支持多种协议，包括https，但通过ssh支持的原生git协议速度最快。

Creating a new branch is quick.
Creating a new branch is quick.

Git鼓励大量使用分支：

查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>

Creating a new branch is quick and simple.

合并master and ferture
