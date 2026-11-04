# 阅读改动差异

提交之前，分别查看工作区和暂存区：

```sh
git diff --stat
git diff
git diff --cached
git diff --check
```

普通 `git diff` 查看尚未暂存的修改；`--cached` 查看下一次提交会包含的修改。未跟踪文件通常不会出现在这些 diff 中，还需要结合 `git status` 检查。

## 练习

修改一行文字，先查看 diff，再暂存该文件，比较两个 diff 命令的输出变化。

## 完成时核对

没有无关文件、意外删除、私人信息或多余的空白问题。

参考：[Git diff](https://git-scm.com/docs/git-diff)。
