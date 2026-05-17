# 等高线地形图3D交互式教学智能体

## 🏆 项目简介
本案例属于创AI案例·教育智能体类别。借助DeepSeek、Tripo3D等国产AI大模型，零编程基础自主开发了一款3D交互式等高线教学工具，内嵌“小峰老师”等高线教学智能体。

## 🌐 在线访问
- **应用地址**：[https://zzqrzm.top](https://zzqrzm.top)

## ✨ 核心功能
- 🏔️ 3D地形可视化：山峰、山谷、山脊、鞍部、陡崖等地貌特征
- 🎨 等高线实时渲染：GLSL着色器精准贴合地形表面
- 🤖 AI智能体助手：基于DeepSeek大模型，支持文字/语音问答
- 📱 跨平台触控操作：教室大屏、平板、手机均可使用
- 🔄 立体/平面模式一键切换
- 📊 等高线密度与垂直比例实时调节

## 🛠️ 技术栈
- **3D渲染**：Three.js + GLSL
- **AI建模**：Tripo3D
- **AI对话**：DeepSeek API
- **部署**：GitHub + Vercel

## 📁 文件说明
| 文件 | 说明 |
|------|------|
| index.html | 主页面（含3D模型、智能体对话窗口） |
| ContourLine.glb | 3D地形模型（Tripo3D生成，Draco压缩） |
| 0.jpg ~ 4.jpg | 教学对比图片 |
| api/chat.js | 智能体API代理（Vercel Serverless Function） |

## 🚀 本地运行
1. 下载本仓库所有文件到同一目录
2. 用浏览器打开 index.html
3. 支持鼠标拖拽旋转、滚轮缩放、触屏操作

## 📄 开源协议
MIT License
