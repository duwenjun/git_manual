# 用法: 
```    
    git [--version] [--exec-path[=GIT_EXEC_PATH]] [--html-path]
           [-p|--paginate|--no-pager] [--no-replace-objects]
           [--bare] [--git-dir=GIT_DIR] [--work-tree=GIT_WORK_TREE]
           [--help] 命令 [别名]
``` 

## 最常用的命令有：
    * add        加入文件到缓冲区
    * bisect     用过2分法查找特定的错误提交
    * branch     显示列表，创建，或删除 分支。
    * checkout   检出分支 或 根据git目录地址切换到相应的工作区
    * clone      克隆一个仓库到新的目录 （可以是本地仓库，也可以是远程仓库）
    * commit     记录提交到版本库的更改
    * diff       显示版本差异 （可以根据commit_id,tag,branch等等）
    * fetch      从其他仓库中获取 文件和引用
    * grep       从git仓库中搜索匹配到的文字或文件
    * init       创建一个空的Git仓库或重新初始化现有仓库
    * log        显示提交日志 Show commit logs
    * merge      合并分支 （可以是两个或多个）
    * mv         重命名文件，目录或符号链接
    * pull       从其他仓库获取更新并自动合并 =(git fetch + git merge)
    * push       把本地仓库修改推送到远程关联仓库
    * rebase     Forward-port local commits to the updated upstream head
    * reset      重置当前指针到特定的状态
    * rm         从当前工作区中删除文件
    * show       显示各种类型的对象信息 （一次提交，一个tag，一个分支等等）
    * status     显示当前工作区的状态
    * tag        创建，删除，显示或者验证 标签
