# 🚀 全平台代理客户端下载与使用指南 (V2Ray / Clash / Shadowrocket)

欢迎来到全平台网络工具下载与配置指南。本项目致力于整理最新、最安全的开源代理客户端，并提供简易上手教程。无论您使用的是 Windows、macOS、Android 还是 iOS，都能在这里找到合适的工具。

> ### 🌟 本项目特别推荐 / 赞助商
> **【Supaboard】 - 稳定 · 高速 · 流媒体解锁 · ChatGPT 无忧**
> 
> 找不到好用的节点？客户端下载好了不知道怎么配置？欢迎体验我们的优质网络服务：
> - 👉 **[点击访问官网，注册即送体验流量](https://supaboard.cc)**
> - 💡 提供 IPLC/IEPL 专线接入，晚高峰不卡顿。
> - 📺 全量解锁 Netflix / Disney+ / YouTube Premium / ChatGPT 等限制区域服务。

---

## 📥 客户端下载直通车

请根据您的设备系统，选择对应的客户端进行下载和安装。为保证设备安全，以下链接均指向**官方 GitHub Release** 或官方应用商店。

### 🍎 iOS (苹果手机 / iPad)
> ⚠️ **重要警告：** 租用或购买非国区 Apple ID 时，**千万不要在系统的“设置”中登录 iCloud！** 只能在 App Store 软件里面登录，否则有手机被锁死的风险！

由于不可抗力，iOS 科学上网工具无法在国区 App Store 下载，需要使用**非国区 (如美区、港区) Apple ID** 登录 App Store 获取。

*   **Shadowrocket (小火箭)**：最经典、最普及的代理软件，支持几乎所有协议。（需付费购买，约 $2.99）
    *   📖 **[图文导入使用教程](https://supaboard.cc/#/knowledge)**
*   **Quantumult X (圈X) / Loon / Surge**：进阶高阶玩家推荐，支持强大的重写、脚本和分流功能。

### 🪟 Windows (电脑端)
*   **Clash Verge Rev** (⭐ 强烈推荐)：目前 Windows 环境下最好用的客户端，界面现代，完美替代停更的 Clash for Windows。
    *   🔗 **[前往 GitHub 下载](https://github.com/clash-verge-rev/clash-verge-rev/releases)** (小白提示：在 Assets 列表中下载以 `Clash.Verge_xxx_x64_zh-CN_setup.exe` 结尾的安装包)
*   **v2rayN**：Windows 下最老牌经典的 V2Ray 客户端。
    *   🔗 **[前往 GitHub 下载](https://github.com/2dust/v2rayN/releases)** (小白提示：在 Assets 列表中下载 `zz-v2rayN-With-Core-Vxxx.zip`，解压后即可运行)

### 🍏 macOS (苹果电脑)
*   **Clash Verge Rev (Mac版)** (⭐ 强烈推荐)：跨平台神作，同样适用于 Mac。
    *   🔗 **[前往 GitHub 下载](https://github.com/clash-verge-rev/clash-verge-rev/releases)** (小白提示：M1/M2/M3 芯片选择 `aarch64.dmg`；Intel 老电脑选择 `x64.dmg`)
*   **V2rayU**：Mac 上老牌的 V2Ray 客户端，支持系统状态栏便捷操作。
    *   🔗 **[前往 GitHub 下载](https://github.com/yanue/V2rayU/releases)** 

### 🤖 Android (安卓手机 / 平板)
*   **Clash Meta for Android** (⭐ 强烈推荐)：原 Clash 生态的优秀延续，功能最强大。
    *   🔗 **[前往 GitHub 下载](https://github.com/MetaCubeX/ClashMetaForAndroid/releases)** (小白提示：下载 `app-universal-release.apk` 即可安装)
*   **v2rayNG**：轻量稳定，支持多种主流协议。
    *   🔗 **[前往 GitHub 下载](https://github.com/2dust/v2rayNG/releases)** (小白提示：下载 `v2rayNG_xxx_universal.apk`)
*   **Surfboard**：界面非常美观（冲浪板），兼容 Surge 配置格式。
    *   🔗 **[前往 GitHub 下载](https://github.com/getsurfboard/surfboard/releases)**

---

## 📖 快速上手教程 (三步连网)

如果您是第一次使用，请按照以下三个步骤进行操作：

1. **获取订阅链接**：
   * 前往 **[Supaboard 官网](https://supaboard.cc)** 注册账号并选购适合您的套餐。
   * 进入“仪表盘 (Dashboard)”，找到并点击**“一键订阅”**，复制您的 **订阅链接 (Subscribe URL)**。

2. **导入客户端**：
   * 打开您刚刚下载安装好的客户端（例如 Clash Verge 或 Shadowrocket）。
   * 在软件内找到 `配置 (Profiles)`、`订阅 (Subscription)` 或 `节点` 选项。
   * 将复制的订阅链接粘贴进去，并点击 `下载 (Download)` 或 `更新 (Update)`。

3. **开启系统代理**：
   * 节点列表刷新出来后，选择一个延迟较低（绿色）的节点。
   * 找到主界面的开关，打开 `系统代理 (System Proxy)` 或点击连接按钮，此时您就可以自由访问外部网络了！

---

## ❓ 常见问题 FAQ

**Q1：为什么我更新了订阅，但是依然无法上网？**
> A：请检查几个地方：1. 您的套餐是否已过期或流量耗尽（可前往 [官网](https://supaboard.cc) 查看）；2. 电脑系统时间是否准确（必须自动同步北京时间）；3. 是否正确开启了“系统代理 (System Proxy)”。

**Q2：什么是“系统代理”和“TUN 模式”？**
> A：“系统代理”一般只能代理浏览器流量；如果您的游戏、命令行、Telegram 等软件需要代理，建议在客户端设置中开启“TUN 模式 (虚拟网卡模式)”，可以实现全局强制代理。

---
*免责声明：本项目仅收集整理开源或正版网络工具，方便开发者学习和工作使用。请严格遵守您所在国家和地区的法律法规，切勿用于任何非法用途。*
