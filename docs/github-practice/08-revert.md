# 用 revert 撤销提交

对于已分享的提交，通常通过新提交撤销变化，保留历史：

```sh
git status
git log --oneline -5
git show COMMIT_SHA
git revert COMMIT_SHA
```

将 `COMMIT_SHA` 替换为确认过的普通提交。以上示例不适用于直接撤销合并提交；合并提交需要理解主线父提交后单独处理。

## 练习

只在自己的练习仓库，对一条临时文本修改做 revert，查看原提交与撤销提交同时存在。

若产生冲突，先阅读提示；不准备继续时可用 `git revert --abort` 退出此次撤销过程。

## 完成时核对

文件内容恢复到期望状态，且撤销没有误伤之后需要保留的修改。

参考：[Git revert](https://git-scm.com/docs/git-revert)。
