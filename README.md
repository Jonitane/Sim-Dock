# Sim Dock

Sim Dock 是面向飞行模拟玩家的 Windows 桌面管理工具，将游戏、外部软件、模组、超级手册、内置膝板和桌面/OpenXR VR 浮窗集中到一个入口。

当前稳定安装版：**V1.0**（安装包版本 `1.0.0`）

- [下载最新版](https://github.com/Jonitane/Sim-Dock/releases/latest)
- [提交问题或建议](https://github.com/Jonitane/Sim-Dock/issues)

## 主要能力

- 统一管理 DCS World、Falcon BMS、DCS Launcher、头显平台、外设驱动、语音通信和自定义工具。
- 按游戏隔离本地模组仓库、部署目录、预设、备份与应用状态。
- 导入本地手册，并提供带原文引用的超级手册问答。
- 在桌面与 OpenXR VR 中使用超级手册、内置膝板、离线中文拼音、本地语音输入和窗口捕获。
- 将设置、凭据、索引与缓存保存在用户选择的安装目录中。

## 支持范围

- Windows 10/11 x64
- DCS World、DCS Launcher 与 Falcon BMS
- OpenXR VR 环境
- VoxBind、DCS-SRS、DCS EyeMouse、MOZA Cockpit、Pimax Play、AimxyZ 和自定义 Windows 软件

Sim Dock 是玩家社区独立产品，与 Eagle Dynamics 及所接入软件的厂商、作者或项目没有隶属、授权或背书关系。

## 下载与安装

1. 从 [GitHub Releases](https://github.com/Jonitane/Sim-Dock/releases/latest) 下载 `Sim Dock Setup 1.0.0.exe` 和 SHA-256 校验文件。
2. 安装前在当前程序中停用全部已启用 Mod，并完全退出 DCS 与当前程序。
3. 在 Windows“已安装的应用”中手动卸载当前 DCSHUB 或旧版 Sim Dock。
4. 再运行 Sim Dock V1.0 安装程序。

安装器保留旧版精确检测与外部目录保护，作为遗漏旧版残留时的安全后备；这不能代替手动卸载。DCS、Saved Games、外部模组库和自定义内容源不会被删除。

当前安装程序未使用商业代码签名。Windows 可能显示 SmartScreen 提示；请只从本仓库 Releases 页面下载，并核对版本提供的 SHA-256。

## 更新方式

旧 DCSHUB 的更新入口会提供 Sim Dock V1.0，用户可以选择安装或稍后处理。Sim Dock V1 只读取本仓库 `1.x` 稳定版本；它不会自动下载或安装，只有用户确认后才会打开下载入口。

## 使用支持

请通过 [GitHub Issues](https://github.com/Jonitane/Sim-Dock/issues) 提交问题或建议，并附上 Windows 版本、Sim Dock 版本、相关软件版本、复现步骤和已脱敏日志。

本公开仓库仅提供正式安装包、版本说明和校验文件，不包含产品源码。
