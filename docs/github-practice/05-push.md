# 推送练习分支

推送前先查看远端地址，确认目的地：

```sh
git remote -v
git branch --show-current
git status
git push -u origin practice/short-description
```

示例分支名必须替换为当前实际分支。`-u` 设置上游，后续可以使用 `git push`。远端要求认证时，只使用 GitHub 支持的认证方式。

## 练习

将自己拥有的练习分支推送到自己的仓库，在 GitHub 分支页面确认最新提交。

## 完成时核对

远端属于预期账户；分支正确；没有将凭证或不应公开的文件推送出去。推送失败先读原因，不要直接强推。

参考：[Git push](https://git-scm.com/docs/git-push)。
