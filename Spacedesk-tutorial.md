# 📱 Spacedesk 教程：将手机/平板变成电脑的第二块屏幕

> **手机投屏电脑 / 扩展副屏 (Windows PC to Mobile)**
> 
> 这是一个关于如何使用 **spacedesk** 软件，通过局域网或 USB 线将移动设备（安卓/iOS）变为 Windows 电脑副屏的详细教程。

---

## 🛠 准备工作

在开始之前，请确保你拥有以下设备：
* **主控端 (Server):** 一台安装了 Windows 10/11 的电脑。
* **接收端 (Viewer):** 安卓手机、平板、iPhone 或 iPad。
* **连接环境:** * **无线连接：** 两台设备需连接在同一个 Wi-Fi 网络下。
    * **有线连接：** 一条可靠的 USB 数据线。

---

## 📥 第一步：安装电脑端驱动 (Primary Machine)

电脑作为“发射源”，必须安装官方驱动程序。(不能安裝到USB drive)

1.  访问 [spacedesk 官方网站](https://www.spacedesk.net/)。
2.  在下载区域选择 **spacedesk Driver Software for Windows** (通常选择 Windows 10/11 64-bit)。
3.  下载并运行 `.msi` 安装程序，安装过程中请勾选“添加防火墙例外”。
4.  **重要：** 安装完成后请重启电脑。
5.  重启后，右下角系统托盘会出现 spacedesk 图标，确保状态显示为 **ON**。

---

## 📱 第二步：安装手机端应用 (Secondary Machine)

手机作为“显示器”，需要安装查看器软件。

* **Android:** 在 Google Play 商店搜索 `spacedesk`。
* **iOS (iPhone/iPad):** 在 App Store 搜索 `spacedesk`。
* **手动下载：** 若无法访问商店，可前往官网下载对应的 APK 安装包。

---

## 🔗 第三步：连接与投屏

### 1. Wi-Fi 连接（最推荐）
1.  确保手机和电脑连接的是**同一个 Wi-Fi**。
2.  打开手机上的 spacedesk App。
3.  App 会自动扫描局域网。当看到 `Connection: [你的电脑IP地址]` 时，点击它。
4.  投屏瞬间完成！

### 2. USB 连接（零延迟）
1.  使用数据线连接手机和电脑。
2.  在手机设置中开启 **USB 网络共享 (USB Tethering)**。
3.  打开手机 App，点击识别出的电脑 IP 即可连接。

---

## ⚙️ 进阶设置 (优化使用体验)

连接成功后，你可以像操作真实显示器一样设置它：

1.  **排列位置：** 在电脑桌面右键 -> **显示设置**，你可以拖动手机屏幕的位置（左边、右边或上方）。
2.  **扩展模式：** 在“多显示器设置”中选择 **“扩展这些显示器”**，这样手机就成了独立的第二屏幕。
3.  **性能优化：** 如果感觉卡顿，在手机 App 的 `Settings` -> `Quality / Performance` 中：
    * 降低 **Image Quality** (图像质量)。
    * 将 **Frame Rate** (帧率) 锁定在 30 FPS 或 60 FPS。

---

## ❓ 常见问题排查 (FAQ)

* **Q: 搜不到电脑 IP？**
    * 检查电脑和手机是否在同一 Wi-Fi（注意 2.4G 和 5G 频率有时会隔离）。
    * 检查电脑杀毒软件/防火墙是否拦截了 `spacedeskService.exe`。
* **Q: 画面延迟很高？**
    * 建议使用 5G 频段的 Wi-Fi。
    * 或者切换到 USB 连接模式。
* **Q: 手机显示“Disconnected”？**
    * 尝试重启电脑端的 spacedesk 服务（在图标上先选 OFF 再选 ON）。

---

## 📜 免责声明
本教程仅供技术分享，软件版权归 [spacedesk](https://www.spacedesk.net/) 官方所有。建议在官方渠道下载软件以确保安全。

---
感谢支持！如果这个教程帮到了你，欢迎点个 **Star** ⭐
