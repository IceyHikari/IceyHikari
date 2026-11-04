# 编写清楚的 PR

创建 PR 时核对 base（目标分支）和 compare（提出修改的分支），再阅读 Files changed。

## 可复用描述

```md
这次解决了什么问题，以及修改后会发生什么。

验证：
- 实际执行的检查及结果。
- 尚未验证的部分（如适用）。
```

文档练习应明确写成文档练习。不要把阅读代码写成运行测试，也不要把草稿方案写成已完成的产品功能。

## 练习

为一项独立改动打开 PR，检查标题、目标分支和文件差异是否一致。

## 完成时核对

读者不需要聊天背景，也能理解改动目的和验证范围。

参考：[关于拉取请求](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)。
