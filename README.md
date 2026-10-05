# windows-zone

Codingzhou.Top 「Windows 专区」的发布仓库，存放面向 Windows 的教学项目 EXE/ZIP 安装包。

- 线上入口：https://codingzhou.top → 左侧导航「Windows 专区」
- `manifest.json` 为本仓库的文件清单，站点服务端（Cloudflare Worker）读取它来生成下载列表
- ZIP 包按发布时间的先后顺序提交，便于查看版本历史

## 文件说明

| 文件 | 说明 |
|---|---|
| `日程表_Win7_20261004_1443.zip` | 日程表 Win7 版（2026-10-04 14:43） |
| `日程表_Win7_20261004_2159.zip` | 日程表 Win7 版（2026-10-04 21:59） |
| `日程表_Win7_20261005_0919.zip` | 日程表 Win7 版（2026-10-05 09:19，最新） |

每个 ZIP 内含：`日程表_Win7.exe`、`日程表_诊断工具.exe`、`使用说明.txt`。解压后直接运行 EXE，无需安装 Python。