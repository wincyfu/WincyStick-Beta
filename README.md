# WincyStick · Stick to it

把想做的事，留在眼前。

一款面向 macOS 的本地桌面便签，将每日事项、周月计划和周期回顾放在一起。适合希望随手记录、持续行动，也愿意回看自己做过什么的人。

**当前：免费公开 Beta · 1.5.4（构建 32）· Apple 芯片 Mac · macOS 14+**

[下载试用版](https://github.com/wincyfu/WincyStick-Beta/releases/tag/v1.5.4-beta.1) · [安装说明](INSTALL.md) · [反馈问题](https://github.com/wincyfu/WincyStick-Beta/issues/new/choose)

## 可以做什么

- 桌面便签：每日事项、周月计划、完成勾选、改期与补充备注。
- 快捷记录：Control + Option + J 呼出，每行一条，Command + Return 保存到今天。
- 随时唤回：Control + Option + Command + P 显示主便签。
- 周、月、年回顾与年度热力图，支持搜索和 Markdown 导出。
- 手动连接 Obsidian，将回顾整理到自己的库中。
- 八种纸色、自由移动与缩放、最近删除和本地备份。

回顾由本地规则整理，目前不提供 AI、手机同步或多人协作。

## 三分钟开始

1. 下载 ZIP，按[安装说明](INSTALL.md)将应用移入 Applications。
2. 启动 WincyStick Beta，在今天的输入位置写一件事，按 Enter 保存。
3. 完成后勾选；积累记录后打开“回顾与归档”。

使用 Beta 时请退出原 WincyStick，避免两者争用同一组快捷键。Beta 默认不启用开机启动。

## 数据与隐私

记录保存在本机 `~/Library/Application Support/WincyStick Beta/`，与原 WincyStick 的记录目录分离，不自动导入旧数据。应用不内置遥测、账号登录或云端 AI；使用 GitHub 下载和反馈时适用 GitHub 自身的隐私政策。

Obsidian 同步需主动选择库，同步内容位于所选库的 `02-行动与复盘/wincy 便签`。Markdown 导出用于阅读，不等于完整数据备份。卸载前请自行备份数据目录。

详见[隐私说明](PRIVACY.md)与[已知限制](KNOWN_ISSUES.md)。

## 免费试用与未来收费

当前 Beta 免费使用，无需购买许可证。未来可能推出付费版本，价格、功能划分与升级方案尚未确定；不会承诺所有未来功能永久免费。当前支持将记录导出为 Markdown，也可备份本地数据。

本仓库用于安装包发布、文档和反馈，**不包含应用源码，不是开源项目**。免费试用不代表授予源码或品牌的开源使用权，详见[试用条款](TERMS.md)。

## 帮助产品变好

欢迎提交可复现的问题，或告诉我：你在什么场景使用、哪里卡住、什么功能让你愿意继续用。请勿上传真实私人记录、完整数据文件或未经遮挡的截图。

如果 WincyStick 对你有帮助，欢迎点一个 Star，方便关注后续版本。Star 不是使用条件。

## English

WincyStick is a local-first macOS desktop sticky note app for daily tasks, weekly/monthly plans and periodic reviews. This free public beta requires Apple Silicon and macOS 14 or later. The app is not notarized by Apple. This repository distributes binaries and collects feedback; application source code is private. Future paid offerings are not yet defined.
