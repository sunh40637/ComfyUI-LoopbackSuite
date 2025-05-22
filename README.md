# ComfyUI Loopback Suite 🌀

一个适用于 ComfyUI 的图生图“多轮循环处理”插件，支持 denoising 曲线、轮次控制、输出所有结果图像。适合动画生成、潜空间增强等。

## ✨ 功能亮点

- 多轮 latent 图像采样
- denoising 强度支持三种动态曲线
- 每轮图像自动保存输出
- 支持 SDXL / LoRA / ControlNet

## 📦 安装方式（通过插件管理器）

1. 打开 ComfyUI 插件管理器
2. 点击 “Install from URL”
3. 粘贴仓库地址：

安装成功后重启 ComfyUI

## 🧩 节点一览

- 🟡 Loopback Init
- 📈 Loopback Denoise Curve
- 🔁 Loopback Iterate
- 🧩 Loopback Controller
- 📤 Loopback Output Collector
