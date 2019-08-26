git status //本地修改存储起来
git stash list  //保存的信息
git pull // 继续
git stash pop stash@{0} //还原暂存的内容 不加stash{0} 默认是最新的
git add foo //解决完冲突继续提交
