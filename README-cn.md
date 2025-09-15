# 实时手势骨架跟踪 / Real-time Gesture Skeleton Tracking

基于 MediaPipe Hands、TensorFlow.js 和 Fingerpose 实现的实时手势识别网页示例，支持中英文多语言界面。
演示： https://nickdu088.github.io/gesture/
---

## 功能 Features

- 实时检测并跟踪手部骨架关键点
- 识别常见手势（点赞、胜利、拳头、张开掌）
- 支持中英文界面切换
- 兼容主流浏览器，无需安装额外软件
- 使用 TensorFlow.js 和 MediaPipe Hands 进行高效推断

---

## 预览 Preview

![截图示例](/screenshot.jpeg)  
*（可选：放置一个项目截图链接）*

---

## 使用说明 How to Use

1. 克隆或下载本项目代码：

   ```bash
   git clone https://github.com/nickdu088/gesture.git
   cd gesture

2. 直接用浏览器打开 index.html 文件（无需搭建服务器）。

3. 允许网页访问摄像头权限。

4. 点击页面右上角按钮切换语言（中文 / English）。

5. 对着摄像头做出手势，即可看到实时识别结果。

## 技术栈 Tech Stack

* MediaPipe Hands
 — 手部关键点检测

* TensorFlow.js
 — 浏览器端机器学习推断

* Fingerpose
 — 手势识别库

* Tailwind CSS
 — 页面样式

## 多语言支持 Multi-language Support

* 页面支持中文和英文，点击右上角按钮即可切换。

* 所有界面文字和状态日志均同步切换。

## 贡献 Contributing

欢迎提交 issue 和 PR 改进功能或修复问题！
请遵守项目的代码规范，保持良好提交信息。
