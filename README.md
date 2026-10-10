<img src="assets/app-icon.png" width="72" alt="Disk Care 应用图标">

# Disk Care · 磁盘检查与清理

看清文件用途、占用和清理影响，再决定如何整理磁盘。

本仓库是 **Disk Care 闭源应用的公开下载入口**，不包含应用源码。当前版本为免费公开测试版，尚未包含付费功能。

## 下载 Windows 安装包

**[下载 Disk Care 1.2.0 安装包](https://github.com/blaze-tc/Disk-Cleanup-Tool-Downloads/releases/download/v1.2.0/DiskCare-Setup-1.2.0-win-x64.exe)**

[查看版本说明](https://github.com/blaze-tc/Disk-Cleanup-Tool-Downloads/releases/tag/v1.2.0) · [所有版本](https://github.com/blaze-tc/Disk-Cleanup-Tool-Downloads/releases) · [SHA256 校验文件](https://github.com/blaze-tc/Disk-Cleanup-Tool-Downloads/releases/download/v1.2.0/DiskCare-Setup-1.2.0-win-x64.exe.sha256)

- 平台：Windows 64 位。
- 包含应用运行环境，无需单独安装 .NET。
- 为当前用户安装，无需管理员权限；可选桌面快捷方式。
- 可在 Windows 已安装应用或开始菜单入口卸载。
- 1.2.0 是公开测试版；应用与安装包尚未进行代码签名。

## 能做什么

- 展示磁盘剩余空间，检查常见软件占用。
- 解释资源用途、处理影响和建议步骤。
- 将文件标为可清理、需确认或受保护。
- 审核文件清单后移入 Windows 回收站；遇到变化、占用或权限问题时跳过。
- 在本机保留操作记录；卸载保留记录及额外用户文件。

## 使用方式

1. 安装并打开应用，点击「检查 / 重新检查常见占用」。
2. 选择项目，阅读右侧用途、影响和处理步骤。
3. 普通文件进入「文件检查与审核」，主动勾选后核对清单。
4. 工具将审核通过的文件移入回收站。确认不再需要后，由你自行清空回收站释放空间。

移入回收站通常不会立即释放空间。可清理标记仍需要结合文件用途审核；工具不会自动勾选未知资源或清空回收站。向导中的官方命令只支持复制，复制不会执行。

## 数据与反馈

当前版本在本机分析文件元数据，不上传个人文件内容。操作记录包含处理路径、大小和结果，仅保存在本机。

问题可通过 [Issues](https://github.com/blaze-tc/Disk-Cleanup-Tool-Downloads/issues) 反馈。公开问题中请避免粘贴私人文件路径、聊天记录、账号或未遮挡的个人资料。

## 源码与许可说明

应用源码在独立私有仓库中维护，未提供开源许可。本仓库的说明和品牌资产不构成应用源码开放授权。程序所包含的第三方组件保留各自的许可和声明；相关声明随程序文件提供。

Copyright © 2026 blaze-tc. All rights reserved.
