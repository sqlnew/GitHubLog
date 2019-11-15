拉取或者推送出现此问题时，先尝试操作步骤顺序是否有问题：

步骤：如果有改动的东西，先提交->然后拉取->最后推送

如果还不能解决，说明有冲突，在报有黄色感叹号的文件进行冲突修改，然后重复上面步骤

记Git报错-refusing to merge unrelated histories

用如下操作允许pull未关联的远程仓库旧代码：
在Git CMD 中
git pull origin master --allow-unrelated-histories
然后我们可以push代码了
