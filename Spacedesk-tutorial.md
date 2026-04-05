# 📱 Spacedesk 教程：将手机/旧电脑变成你的第二块屏幕

> **屏幕扩展与投屏工具 (Windows PC to Mobile / PC to PC)**
> 
> 本教程介绍如何使用 **spacedesk**，通过局域网 (Wi-Fi) 或 USB 线，将你的安卓/iOS 设备或另一台旧电脑变成 Windows 主机的扩展显示器。

---

## 🛠 准备工作

在开始之前，请确保你拥有以下设备：
* **主控端 (Primary PC):** 一台安装了 Windows 10/11 的电脑（作为信号源）。
* **接收端 (Viewer):** * 手机/平板 (Android / iOS)
    * **或者** 另一台旧电脑 (Windows / Mac / Linux)
* **网络环境:** 两台设备需处于同一局域网下（连接同一个 Wi-Fi 或路由器）。

---

## 📥 第一步：安装主电脑驱动 (Server)

主电脑需要安装底层驱动才能发送信号。

1.  访问 [spacedesk 官网](https://www.spacedesk.net/)。
2.  下载 **spacedesk Driver Software for Windows** (推荐 64-bit)。
3.  运行 `.msi` 安装包。**注意：** 必须安装在电脑本地硬盘（通常是 C 盘），**不支持**在 U 盘运行。
4.  安装过程中请务必勾选 **"Add an exception to the Windows Firewall"** (添加防火墙例外)。
5.  安装完成后，**必须重启电脑**。
6.  重启后，右下角系统托盘出现 spacedesk 图标且显示为 `ON` 即表示成功。

---

## 💻 第二步：设置接收端 (Viewer)

根据你作为副屏的设备类型，选择对应的安装方式：

### 1. 手机/平板 (Android / iOS)
* **Android:** 在 Google Play 搜索 `spacedesk` 或在官网下载 APK。
* **iOS:** 在 App Store 搜索 `spacedesk` 下载。

### 2. 电脑投屏到电脑 (PC to PC / Mac)
如果你的副屏是一台旧笔记本或 Mac，有两种方式：
* **方法一：使用网页版 (最快，无需安装)**
    1. 副电脑打开浏览器（Chrome/Edge），访问 [viewer.spacedesk.net](https://viewer.spacedesk.net/)。
    2. 输入主电脑的 IP 地址，点击连接即可。
* **方法二：使用 Viewer 客户端 (更稳定)**
    1. 在副电脑安装官方的 `spacedesk Windows Viewer` 软件。
    2. 运行后它会自动搜索局域网内的电脑，双击名称即可。

---

## 🔗 第三步：连接与投屏

1.  确保主电脑和接收端连接在**同一个 Wi-Fi**。
2.  打开接收端 App（或网页版）。
3.  点击显示出的 **"Connection: [你的电脑 IP]"**。
4.  **大功告成！** 你的手机/旧电脑现在已经成了第二块屏幕。

---

## ⚙️ 进阶设置 (优化体验)

连接成功后，请在**主电脑**上进行以下设置：

1.  **排列位置：** 桌面右键 -> **显示设置**，拖动代表副屏的小方块，对齐你桌面上手机/旧电脑的实际位置。
2.  **扩展模式：** 在“多显示器设置”中选择 **“扩展这些显示器”** (Extend)。
3.  **性能调节：** 如果画面卡顿，在接收端 App 的 `Settings` -> `Quality / Performance` 中：
    * 降低 **Image Quality** (画质)。
    * 将 **Frame Rate** 锁定在 30 FPS。

---

## ❓ 常见问题排查 (FAQ)

* **Q: 搜不到主电脑的 IP？**
    * 检查两台设备是否在同一 Wi-Fi。
    * 检查主电脑右下角图标是否为绿色 `ON` 状态。
    * 暂时关闭主电脑上的第三方杀毒软件或 VPN。
* **Q: 为什么不能安装到 U 盘？**
    * Spacedesk 需要向 Windows 系统内核安装虚拟显示驱动，U 盘无法提供这种运行环境。
* **Q: 画面延迟很高？**
    * 推荐使用 **5G 频段** 的 Wi-Fi 路由器。
    * 手机用户可以尝试通过 **USB 网络共享 (USB Tethering)** 模式连接。

---

## 📜 许可与免责声明
本教程仅供技术交流，软件版权归 [spacedesk](https://www.spacedesk.net/) 官方所有。建议优先从官网下载以获取最新安全更新。

---
感谢支持！如果这个教程帮到了你，欢迎点个 **Star** ⭐
