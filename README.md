# 共享下载文件

这个仓库用来放可以对外分享的文件。别人用「最新版下载链接」就能直接下载，你更新文件后链接不用换。

## 当前文件

| 文件 | 版本 | 最新版下载 |
| --- | --- | --- |
| 电机控制器客户需求确认表 | V2.2 | https://github.com/Hui-777/shared-docs/releases/latest/download/电机控制器客户需求确认表-V2.2.docx |

## 以后怎么更新

1. 把新的 `.docx` 放到本仓库 `files/` 目录（文件名建议仍用 `电机控制器客户需求确认表-V2.2.docx`，大改版可改成 V2.3）。
2. 提交并推送到 `main`。
3. 发一个新 Release（例如 `v2.3`），把同一个文件挂成 Release 资源。

若希望「别人手里的旧链接永远指向最新文件」，发布时保持 Release 资源文件名与上表一致，并始终用：

`https://github.com/Hui-777/shared-docs/releases/latest/download/<文件名>`

也可直接把新文件发给我，让我帮你替换并发布。
