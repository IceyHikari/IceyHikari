# 核对后合并

合并之前再次检查 PR 的最终差异。创建 PR 后发生的追加提交，也需要重新确认。

## 核对步骤

1. 确认 base 是预期分支。
2. 阅读最终文件差异，查看是否混入无关文件。
3. 完成仓库要求的测试、审核和状态检查。
4. 使用仓库允许的合并方式。
5. 查看 PR 显示的 Merged 状态和目标分支文件。

Merge commit、squash、rebase 会产生不同历史。选择前先理解团队约定，不绕过保护规则。

## 练习

在自己拥有的练习仓库合并一次文档 PR，再在目标分支查看文件。文档笔记本身不证明手动步骤已执行。

## 完成时核对

PR 已合并，并且目标分支实际包含预期结果。

参考：[合并拉取请求](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/merging-a-pull-request)。
