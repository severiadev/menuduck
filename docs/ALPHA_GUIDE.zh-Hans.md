# 安装 MenuDuck

[MenuDuck](../README.zh-Hans.md) · [English](ALPHA_GUIDE.md) · [Русский](ALPHA_GUIDE.ru.md) · [Español](ALPHA_GUIDE.es.md) · 简体中文

需要 **macOS 26 或更高版本**。这是 Alpha 版，未使用 Developer ID 签名，也未经 Apple 公证。请先备份，并仅在信任来源时安装。

## 安装

1. 在 [Releases](https://github.com/severiadev/menuduck/releases) 的 **Assets** 中下载 `.dmg`，不要下载 **Source code** 源码压缩包。请阅读该版本的限制说明。
2. 核对 SHA-256：在终端输入 `shasum -a 256 `，将 DMG 拖入窗口后按回车。将完整结果与测试组织者通过私人渠道提供的校验值进行比较。
3. 打开 DMG，将 MenuDuck 拖入**应用程序**，然后推出磁盘映像。
4. 启动 MenuDuck。如果 macOS 无法验证开发者，请前往**系统设置 → 隐私与安全性 → 仍要打开**，再确认打开。

**如果校验值不一致、macOS 提示恶意软件或文件损坏，或没有“仍要打开”按钮，请停止操作。** 联系测试组织者，不要关闭 Gatekeeper 或绕过 Mac 的安全策略。[Apple 说明](https://support.apple.com/zh-cn/102445)。

## 首次使用

- 在设置中点击 **Enter License Key**，输入测试密钥。请勿公开密钥。
- 点击 **Update Catalog**，允许相应网络请求，然后安装 **Stay Awake** 或 **Network Speed**。
- 对标记为 **Planned** 的插件，点击 **I Need It** 表达兴趣；**Voted** 表示投票成功，**Remove Vote** 可撤销投票。

<details>
<summary>测试、更新与故障处理</summary>

试用图标隐藏、快捷键、屏幕设置和两个插件。每次只改一项设置；重启应用，确认设置已保存。在 **All (Experimental)** 壁纸模式下，遮盖刘海需要选择 **Dark** 壁纸外观。

更新需手动完成：先退出 MenuDuck，再按照新版本说明操作。未经指导，请勿降级。

出现问题时，撤销最后一次修改或退出应用。退出不一定能还原所有屏幕变化。**不要删除偏好设置、壁纸文件或恢复数据。** 报告中请提供应用与 macOS 版本、复现步骤，并先移除个人信息。

</details>

[报告问题](https://github.com/severiadev/menuduck/issues/new/choose) · [私人求助](../SUPPORT.md) · [隐私说明](../PRIVACY.md)
