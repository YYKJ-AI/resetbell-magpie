<p align="center"><img src="page/icon.svg" width="64" height="64" alt="Reset"></p>

# Reset 雷达 · Reset Radar

在 Magpie 里，关注你正在使用的 AI 厂商。

GPT、Claude、Kimi、Grok，四选一关注公开额度重置、发卡与规则变化。
无需注册，不读取个人账户，也不需要提供 API Key。

## 界面预览

![Reset 雷达桌面版](https://raw.githubusercontent.com/YYKJ-AI/resetbell-magpie/main/docs/screenshots/dashboard-zh-1200.png)

![服务管理页](https://raw.githubusercontent.com/YYKJ-AI/resetbell-magpie/main/docs/screenshots/manage-zh-1200.png)

## 安装

适用于 macOS 和 Magpie 0.1.2181 及以上版本。

打开 **Magpie → 插件 → 发现**，在 GitHub 社区插件列表搜索 **Reset**、
**Reset 雷达** 或 **Reset Radar**，选择 **Reset 雷达** 安装。
社区索引可能延迟；搜索不到时，在插件安装入口粘贴：

```text
github:YYKJ-AI/resetbell-magpie
```

也可使用一条安装命令：

```sh
magpie plugin add github:YYKJ-AI/resetbell-magpie
```

安装后，从侧栏打开 **Reset 雷达**，选择一家厂商即可。
不需要下载网站项目，也不需要自行配置服务。

## 使用

- **只关注一家**：随时切换 GPT、Claude、Kimi 或 Grok；GPT 统一使用与网站相同的 ChatGPT 图标。
- **服务管理**：主页点击「管理」进入二级页面，可查看四家厂商并随时切换当前关注。
- **重置卡片**：显示距上次公开重置的实时相对时间、精确日期、近 30 天重置次数与逐日刻度。
- **一眼看完**：宽屏左侧监控、右侧动态，桌面尽量在一页内完成查看；手机自动改为单列与 2×2 厂商选择。
- **快速查找**：默认显示最新 4 条；按重置、发卡、规则变化筛选，再搜索动态、适用范围和官方原文，展示最新 4 条匹配结果；支持一键清除和 `/` 快捷搜索。
- **可选提醒**：默认关闭；开启后，只提醒此后发现的近期变化，不补发历史。
- **统一品牌**：交互使用 Reset 官网青绿主题色，背景与文字适配 Magpie 明暗模式，保留彩色厂商图标。
- **离线可看**：连接中断时保留上次内容，并明确提示未更新。

Magpie 运行时持续关注，关闭插件页面不影响监控；退出 Magpie 或电脑休眠时，
首次安装的插件不能继续检查。重新打开后恢复。
macOS 是否显示提醒取决于系统通知权限和专注模式；
可用「发送一条测试通知」检查。系统接受不等于已送达。

公开公告不证明个人额度到账。预告、第三方观察与官方完成状态会分别展示。

## 隐私

此客户端只读取 Reset 已公开的信息，不读取 Magpie 的账号、供应商密钥、
聊天记录或个人额度。选择和缓存保存在你自己的电脑上。
通知默认关闭，不自动更改系统权限。

## 网站与支持

- [Reset 网站](https://resetbell.dev)
- [报告问题](https://github.com/YYKJ-AI/resetbell-magpie/issues)

---

Follow public AI quota resets and official updates inside Magpie.
Install `github:YYKJ-AI/resetbell-magpie`, open **Reset Radar**, and choose
GPT, Claude, Kimi or Grok. No login or personal API key required.
Manage four providers, view the latest four updates, filter and search original posts,
and optionally enable notifications. macOS / Magpie 0.1.2181+.
