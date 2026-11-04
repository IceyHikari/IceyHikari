# 创建任务分支

独立任务使用独立分支。确认当前工作区状态后，从期望的基线创建分支：

```sh
git status
git switch main
git pull --ff-only
git switch -c practice/short-description
```

示例假设默认分支名为 `main`、已设置上游且工作区适合切换。若出现本地修改阻止切换，先处理并保存自己的工作，不要强行覆盖。

## 练习

在自己的练习仓库创建一个尚不存在的分支，运行 `git branch --show-current` 确认名称。

## 完成时核对

基线正确；分支名能说明任务；默认分支没有直接混入练习改动。

参考：[Git switch](https://git-scm.com/docs/git-switch)。
