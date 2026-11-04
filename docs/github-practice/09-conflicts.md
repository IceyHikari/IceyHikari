# 理解合并冲突

当两个分支改动同一段内容，Git 可能要求手动决定最终版本。

## 处理顺序

1. 运行 `git status` 确认冲突文件。
2. 打开文件，阅读 `<<<<<<<`、`=======`、`>>>>>>>` 附近内容。
3. 根据实际需求整理出完整结果，并移除冲突标记。
4. 检查文件、暂存解决后的文件，再按 Git 提示完成合并。
5. 运行与改动相关的验证。

“接受全部当前内容”不一定正确；两个分支可能各有需要保留的变化。

## 练习

在隔离的练习仓库，用两个分支修改同一行，体验一次冲突。不要在团队仓库人为制造冲突。

在合并过程尚未完成时，`git merge --abort` 可以尝试退出；开始前仍应保存自己的修改。

参考：[解决合并冲突](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/about-merge-conflicts)。
