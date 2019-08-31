这是一个练习GIT链接的demo


dev分支：指最近一次分支，当插入dev分支时，head从指向master改为指向dev。当dev完成时，将master和dev合并。head从新指向master。

实验3：
输入git status查找工作区内容

创建新分支：git branch dev——创建一个名为dev的分支
查询当前所在分支：git branch——绿色亮起的为当前位置
切换到分支：git checkout dev——cmder的显示会变为dev->origin

联合指令（不好用，不写了）
在分支编写内容后，切回主分支，在分支状态写的内容不会显示。

将dev内容合并到master上：在主分支状态下输入git merge dev
此时完成版本同步。
当不再需要分支时：git branch -d dev
再次查询当前所在分支：git branch，发现只剩下master了。


【解决冲突】
git checkout -b feature1

