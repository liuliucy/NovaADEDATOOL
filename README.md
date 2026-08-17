# NovaADEDATOOL · 大壮的AD工具

> **Aurora + Kepler + Nova** —— EasyEDA/立创商城(LCSC) 元件库 → Altium Designer / KiCad 一键导出工具

![GitHub Release](https://img.shields.io/github/v/release/liuliuczy/NovaADEDATOOL)
![Platform](https://img.shields.io/badge/platform-Windows%20x64-blue)

---

## 📦 简介

**大壮的AD工具**（内核代号：**Aurora** / **Kepler** / **Nova**）是一款面向电子工程师的元件库转换工具：

- 🔍 **监听剪贴板**：自动识别立创商城 LCSC 编号（如 `C14663`）
- ⚡ **一键导出**：符号 + 封装 + 3D 模型，输出 Altium Designer 的 SchLib/PcbLib 或 KiCad 库
- 🧩 **批量合并**：多个器件合并为一个库文件，支持增量追加（append）
- 🖥️ **3D 模型**：OBJ/STEP 自动下载，XYZ 定位精确校准（直插连接器也准确）
- 🔒 **断点续传**：批量导出中断后自动跳过已完成项

支持平台：Windows 10/11 x64

---

## ⬇️ 下载安装

| 版本 | 文件 | 说明 |
|---|---|---|
| 最新版 | [大壮的AD工具_x64-setup.exe](https://github.com/liuliuczy/NovaADEDATOOL/releases/latest/download/大壮的AD工具_1.0.18_x64-setup.exe) | NSIS 安装版（推荐） |
| 便携版 | [大壮的AD工具_x64_portable.zip](https://github.com/liuliuczy/NovaADEDATOOL/releases/latest/download/大壮的AD工具_1.0.18_x64_portable.zip) | 解压即用，免安装 |

> 也可在右侧 **Releases** 页面选择任意历史版本下载。

**使用说明**：[查看完整使用文档](使用说明.md)

---

## 🚀 快速上手

1. 安装后启动「大壮的AD工具」
2. 复制任意 LCSC 编号（如 `C2040`）到剪贴板
3. 工具自动识别，选择导出目标（Altium / KiCad）
4. 点击导出，库文件直接生成到指定目录

---

## ☕ 打赏支持

如果这个工具帮到了你，欢迎打赏支持作者继续维护：

| 微信 | 支付宝 |
|---|---|
| ![微信收款码](assets/wechat-pay.jpg) | ![支付宝收款码](assets/alipay.jpg) |

每一份支持都是持续更新的动力 ❤️

---

## 🔄 自动更新

本工具内置自动更新功能，新版本发布后启动时会自动检测并提示升级。

---

## ⚖️ 授权说明

- 当前版本：**免费使用**
- 后续版本将逐步转为**付费授权**模式（一次性买断 / 按版本授权），敬请关注
- 任何商业用途请提前联系作者

---

## 🧩 技术架构

| 模块 | 代号 | 职责 |
|---|---|---|
| GUI 壳 | **Nova** | Tauri 桌面应用，前端原生 TS |
| Altium 导出核心 | **Aurora** | SchLib/PcbLib 生成，Rust |
| KiCad 导出核心 | **Kepler** | KiCad 库生成，Rust |

---

## 📬 联系作者

- GitHub：[@liuliuczy](https://github.com/liuliuczy)
- 邮箱：809466020@qq.com
