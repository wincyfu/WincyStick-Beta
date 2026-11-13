# 安装与卸载

## 系统要求

- Apple 芯片（M 系列）Mac，macOS 14 或更新版本。
- 本次安装包不是 Intel / Universal 构建。
- 尚未使用 Developer ID 签名或通过 Apple 公证，属于测试版本。

## 安装

1. 从本仓库 Releases 下载 `WincyStick-Beta-0.1-arm64.zip`；可用同页 SHA256 文件校验完整性。
2. 解压，将 `WincyStick Beta.app` 拖到“应用程序”目录。
3. 打开 WincyStick Beta。若系统阻止打开，阅读系统提示，并在确认下载来源后前往“系统设置 → 隐私与安全性”，查看是否提供“仍要打开”。不同 macOS 版本提示可能不同。
4. 若设备管理策略不允许打开，请停止安装并提交反馈。不需要关闭 Gatekeeper 或 SIP。

打开失败时请提供 macOS 版本、芯片型号、完整提示文字和下载版本。不要上传私人数据。

## 使用

- 主便签：Control + Option + Command + P。
- 快捷记录：Control + Option + J；Command + Return 批量保存。
- 主便签 Enter 保存事项；Shift + Enter 添加补充。
- 关闭窗口仅隐藏；从应用菜单退出。
- Beta 默认不启用开机启动；需要时可在应用菜单设置。

## 更新与卸载

更新前退出应用并备份 `~/Library/Application Support/WincyStick Beta/`，再用新版本替换应用。新版本会在本仓库 Releases 发布。

卸载前如已启用开机启动，请在应用菜单关闭，再退出并删除应用。删除应用不会自动删除上述数据目录或已同步到 Obsidian 的文件。是否保留数据由你自行决定。
