# u-openclaw


## 官网

官网  http://u.u-openclaw.com 

## 支持模型
打开 Config 选模型、填入自己的 API Key 即可使用，支持 DeepSeek / 通义 / Claude / GPT 等国内外大模型

## Token 
想用「云优龙虾 | AI Token」中转站（一个 Key 调用国内外全部模型、免翻墙）：先到 http://u-openclaw.com 注册并创建 Key
聊天渠道开箱即用：便携版已离线预装 微信 / QQ / 钉钉 / 飞书 / 企业微信 插件，无需自己 npm 安装
OpenClaw runtime: 2026.6.9


## 下载
Windows 桌面版：U-OpenClaw.Setup.*.exe（安装到电脑）或 U-OpenClaw.*.exe（免安装绿色版）

MacOS 桌面版：U-OpenClaw-*-arm64.dmg（Apple Silicon）或 U-OpenClaw-*.dmg（Intel）

Windows 便携完整版（U 盘版）：u-openclaw-portable-windows-*.zip（约 150-200 MB，已预装 Node.js + OpenClaw，解压即用，零网络依赖）

macOS 便携骨架（开发者）：源码在 portable/ 目录，bash setup.sh 自动下载 Node + OpenClaw（国内镜像约 1 分钟）

U 盘格式建议：请用 NTFS 格式化 U 盘（NOT exFAT/FAT32）。Node.js 在 exFAT 上 IO 极慢且不支持符号链接，可能导致启动失败。

Windows 下右键 U 盘 → 格式化 → 文件系统选择 NTFS。

## 注意：
Windows 安装包未做代码签名，首次运行 SmartScreen 选择「仍要运行」。
MacOS DMG 未做公证，首次启动 xattr -rd com.apple.quarantine /Applications/U-OpenClaw.app 或右键打开。


