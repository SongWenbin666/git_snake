命令,作用,类比
git status,                                                  查看当前文件状态,查看“包裹”里装了什么
git add .,                                                   将所有改动放入暂存区,准备好要发货的商品
"git commit -m ""描述""",                                     正式提交存档,封箱并贴上标签
git log --oneline,                                           查看简洁的提交历史,翻看之前的存档记录
命令,作用,注意事项
git restore <文件>,                                        丢弃未提交的修改,代码写乱了，一键还原
git reset --soft HEAD~1,撤销上一次 commit,                  存档存错了，退回一步改描述
git checkout .,                                            撤销所有本地改动,彻底推倒重来
命令,作用
git checkout -b <分支名>,               创建并切换到新分支
git checkout main,                     切换回主分支
git merge <分支名>,                     将实验分支合并到当前分支
git branch -d <分支名>,                 删除已完成的分支
命令,作用
git push origin main,                    把本地存档推送到云端
git pull origin main,                    把云端最新的改动同步到本地
git remote -v,                            查看远程仓库的连接地址
