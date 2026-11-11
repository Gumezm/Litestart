# 项目长期记忆

## Git 操作约定（用户明确要求，必须遵守）

- 改动文件后**只执行 `git add`**，不要自动 commit
- 用户说「commit」后才执行 `git commit`
- 用户说「推送 / push」后才执行 `git push`
- 用户可能用缩写：`ga` = git add，`gc` = git commit，`gp` = git push
- 适用范围：`D:/Code/Website` 下全部仓库（nav、blog、kijin、about）

## 记忆文件入库

各仓库 `.workbuddy/*` 忽略，但 `!.workbuddy/memory` 与 `!.workbuddy/memory/**` 例外，记忆随仓库同步到 CNB。
