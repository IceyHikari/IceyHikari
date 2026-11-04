# 查看工作区状态

开始任务前，先确认自己在正确仓库，并查看已有修改：

```sh
git rev-parse --show-toplevel
git status --short --branch
git branch --show-current
```

`??` 表示未跟踪文件；状态第一列对应暂存区，第二列对应工作区。不要覆盖自己不清楚来源的修改。

## 练习

在自己的练习仓库中新建一个文本文件，再运行 `git status --short`，观察它是否标记为 `??`。本笔记的加入不代表这个手动练习已经执行。

## 完成时核对

确认仓库根目录、当前分支、已有修改三项信息，再开始编辑。

参考：[Git status](https://git-scm.com/docs/git-status)。
