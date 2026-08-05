# git教程
git add
git commit -m "decrispte"
git commit -am "decrispte"
git commit -amend "new decrispte" 修改上一条提交信息
git log -p 文件名（--pretty=short）
git log --graph 以图表形式查看分支
git reflog 查看当前仓库执行过的操作日志
git status
git diff (HEAD) 查看最新提交和工作树的差别
git branch 分支名
git checkout (-b) 分支名 远程仓库标识符/分支名 以远程仓库分支为来源在本地仓库创建分支
git merge --no-ff 分支名 合并分支
git reset --hard 目标时间点的哈希值 回溯历史版本
git rebase -i 压缩历史
git remote add 标签名 github上的仓库路径 添加远程仓库
git clone 仓库路径 获取远程仓库，标识符自动设置为origin
git push -u 远程仓库标签名 分支名 推送分支至远程仓库
git pull 远程仓库标签名 分支名 获取远程仓库分支最新状态
Git is a Version control system.
Git is free software.
