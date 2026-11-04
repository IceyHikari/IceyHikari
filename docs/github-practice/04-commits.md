# 暂存与提交

优先明确指定本次任务的文件：

```sh
git add notes/example.md
git diff --cached
git commit -m "docs: explain the example workflow"
git show --stat --oneline HEAD
```

将 `notes/example.md` 替换为实际文件。提交说明描述具体结果，例如“补充运行步骤”，避免只写“update”。

## 练习

在自己的仓库提交一处文档修改，并查看最新提交的文件清单。不要为了增加提交数量重复修改同一行。

## 完成时核对

提交包含完整且单一的主题。作者身份来自自己的真实 Git 配置；协作署名只用于实际参与者。

参考：[Git commit](https://git-scm.com/docs/git-commit)。
