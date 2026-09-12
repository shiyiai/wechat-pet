# 微信会话情报

微信会话情报是一个本地优先的桌面应用，用于查看和分析本机微信会话。

本仓库只提供公开安装包和应用内更新所需的 Tauri manifest。项目源码和构建流程保存在私有仓库。

## 下载

请前往 [最新版本](https://github.com/shiyiai/wechat-pet/releases/latest) 下载：

- macOS Apple Silicon：`.dmg`
- Windows x64：`_x64-setup.exe`

应用安装后会从 GitHub Releases 自动检查更新。

## 隐私

聊天数据在本机读取和处理，不会随安装包上传。应用需要用户自行登录 AI 服务并授予操作系统所需的本地权限。

## 源码与发布

源码仓库为私有仓库。每个 GitHub Release 只包含最终安装包、Tauri updater 包、签名文件和 `latest.json`；不发布源码、调试符号或聊天数据。
