---
allowed-tools: Bash(git add:*), Bash(git status:*), Bash(git commit:*)
description: 创建 git 提交
---

## 上下文

- 当前 git 状态：!`git status`
- 当前 git 差异（已暂存和未暂存的更改）：!`git diff HEAD`
- 当前分支：!`git branch --show-current`
- 最近的提交：!`git log --oneline -10`
- 提交: !`git commit -m COMMIT_MSG`

## 你的任务

基于上述更改、历史提交消息风格，思考应怎样风格一致、简洁地描述本次提交，将提交命令中的 COMMIT_MSG 替换为描述，创建单个 git 提交。