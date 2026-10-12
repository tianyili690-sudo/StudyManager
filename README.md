# 学习管理者 · StudyManager

> 一个**完全公益、无广告、无内购**的自主学习平台 —— 把笔记、课程、刷题、计划与打卡收进同一个入口。
> 所有数据只存在你自己的设备里，不上传云端。

---

## ⬇️ 下载

| 平台 | 文件 | 大小 | 下载 |
| :--- | :--- | ---: | :--- |
| **Windows 电脑端**（安装版） | `StudyManager-Setup-1.0.0.exe` | 78.2 MB | [下载](https://github.com/tianyili690-sudo/StudyManager/releases/download/v1.0.0/StudyManager-Setup-1.0.0.exe) |
| **Windows 电脑端**（免安装版） | `StudyManager-Portable-1.0.0.exe` | 78.0 MB | [下载](https://github.com/tianyili690-sudo/StudyManager/releases/download/v1.0.0/StudyManager-Portable-1.0.0.exe) |
| **Android 安卓端** | `StudyManager-Android-1.0.0.apk` | 516 KB | [下载](https://github.com/tianyili690-sudo/StudyManager/releases/download/v1.0.0/StudyManager-Android-1.0.0.apk) |

全部版本：[**Releases 页面**](https://github.com/tianyili690-sudo/StudyManager/releases/latest)

> 安卓端安装包也在本仓库内：[`android/StudyManager-Android-1.0.0.apk`](android/StudyManager-Android-1.0.0.apk)

### 校验值（SHA-256）

下载后可以核对，确保文件没被篡改或传坏：

```
StudyManager-Setup-1.0.0.exe      5c927db56ff7c4b7c88fc823f279356b215ea515d4beefcbefb736266e214ed7
StudyManager-Portable-1.0.0.exe   a6bfc384e346f4e84dc8ab0e59d8dc91045da603b341ae034c632430e2f638fb
StudyManager-Android-1.0.0.apk    1aa72ed9d3ddb78cc831c7742175ecd1e48f74ea814cf3bce9f739df6211a68e
```

---

## 这是什么

「学习管理者」是一款陪伴式的自主学习工作台。它不卖课、不推广告，只想帮你把**想学的东西坚持下去**。

它不是又一个课程商城，而是一个**陪你坚持下去**的学习工作台。

---

## 功能

| 模块 | 说明 |
| :--- | :--- |
| 📊 **数据看板** | 学习时长、打卡天数、笔记数量、测验平均分一屏看完，配近 7 天时长趋势与笔记分类分布 |
| 📝 **学习笔记** | 富文本笔记，按分类归档，支持置顶与状态管理 |
| 🎬 **编程教学** | 21 门精选视频课程，覆盖 Python、Java、C / C++、前端、Go、Rust、数据库等 12 个技术方向，课程以**超链接**直达 |
| 🧮 **算法专题** | 17 个算法主题（复杂度、线性结构、排序查找、树与堆、贪心、动态规划、图论、字符串） |
| 📚 **基础课** | 大学英语、高等数学等基础学科课程 |
| ✍️ **在线刷题** | **247 道题 / 11 个类别**，答完立刻出分并逐题解析 |
| 🔁 **错题集** | 答错的题自动入集，**连续答对 2 次**才算真正掌握、自动移出；可一键重练组卷 |
| ✅ **学习打卡** | 打卡日历热力图，记录每天学了什么、学了多久，连续天数一目了然 |
| 🗓️ **学习计划** | 把想学的内容排成计划，设科目、优先级与预计时长 |
| 📈 **成绩分析** | 历次测验成绩走势、各题型正确率、薄弱环节定位 |
| ⚙️ **软件设置** | 账号、数据导出与清理等 |

---

## 安装

### Windows 电脑端

- **安装版** `StudyManager-Setup-1.0.0.exe`
  双击运行，按提示安装即可。会在开始菜单和桌面创建快捷方式。
- **免安装版** `StudyManager-Portable-1.0.0.exe`
  双击直接运行，不写注册表、不装到系统目录，可以放在 U 盘里带走。

> 首次运行 Windows 可能弹出「Windows 已保护你的电脑」（SmartScreen），
> 这是因为个人开发者没有购买代码签名证书。点「更多信息」→「仍要运行」即可。

### Android 安卓端

1. 把 `StudyManager-Android-1.0.0.apk` 传到手机（或手机浏览器直接下载）；
2. 点击安装，系统若提示「禁止安装未知应用」，在弹窗里选择**允许来自此来源的应用**；
3. 安装完成后即可离线使用。

> 安卓端是完全离线的 WebView 壳，**不需要联网也能用**。

### 网页端（免安装）

用手机或电脑浏览器打开即可使用，也可以在 Safari / Chrome 里「添加到主屏幕」，像 App 一样全屏使用、断网可用。

---

## 数据与隐私

- **数据只存在你的设备里。** 采用本地静态存储（`localStorage`），**没有任何云端服务器**，也不上传任何数据。
- 从设计上就不存在「信息泄露」的路径 —— 没有服务器，就没有可以被拖走的数据库。
- 电脑端与安卓端**各自独立运行**，互不干扰。
- 卸载软件即彻底清除数据；也可以在「软件设置」里手动导出或清理。

---

## 系统要求

| 平台 | 要求 |
| :--- | :--- |
| Windows | Windows 10 / 11（64 位） |
| Android | Android 7.0 及以上 |
| 网页端 | 任意现代浏览器（Chrome / Edge / Safari / Firefox） |

---

## 声明

- 本项目**完全公益**：没有会员、没有内购、没有付费墙，也不接受任何形式的赞助解锁。
- 界面里**没有任何推广位**，不会弹出第三方内容，也不会把学习数据拿去做别的事。
- 无隐藏消费、无插件广告、无恶意脚本。
- 后续的每一次优化都会在本仓库实时更新。

---

## 关于

- 作者：[@tianyili690-sudo](https://github.com/tianyili690-sudo)
- 版本：`v1.0.0`

如果这个软件帮到了你，欢迎点一个 ⭐ Star，让更多想学习的人看到它。
