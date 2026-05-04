# 心桥 MindBridge 💛

> 让每一份工作，都被温暖支持

心智障碍群体就业支持平台 — 包含工作流程引导Agent、情绪安抚Agent、日常沟通辅助、视频通话等核心功能。

## 🌟 项目简介

心桥 MindBridge 是一款专为心智障碍群体（孤独症谱系障碍、智力发育迟缓、唐氏综合征、脑瘫伴随智力障碍等）设计的就业支持工具。

### 核心功能

- 🏠 **首页** — 今日概览、快捷入口、Agent对话
- 💼 **工作台** — 可勾选任务清单 + 工作Agent智能对话
- 💛 **情绪空间** — 8种情绪选择 + 情绪Agent + 呼吸练习动画
- 💬 **沟通助手** — 常用表达、视频通话、紧急联系人
- 👤 **个人中心** — 档案管理、AI设置、辅导员/主管关联
- 🆘 **SOS紧急** — 一键视频通话、紧急电话、求助消息

### AI 智能对话

- 集成智谱AI（GLM-4-Flash），**永久免费**
- 情绪Agent：温暖共情、情绪识别、安抚建议
- 工作Agent：步骤拆解、问题解答、安全提醒
- 无API Key时自动降级为本地智能回复

## 🚀 在线体验

👉 [点击这里体验](mindbridge-prototype.html)

## 📋 技术实现

- 纯 HTML + CSS + JavaScript，单文件应用
- 响应式设计，适配手机和桌面
- CSS变量管理主题色
- Emoji图标系统
- 智谱AI API集成（OpenAI兼容格式）

## 📂 项目结构

```
MindBridge/
├── index.html                          ← 主页面（重命名自 mindbridge-prototype.html）
├── README.md                           ← 项目说明
├── docs/
│   ├── 心桥MindBridge-设计规格文档.docx
│   └── 心桥MindBridge-部署与商业化指南.docx
└── screenshots/
    ├── 01-welcome.png
    ├── 02-register-step1.png
    ├── 03-register-step2.png
    ├── 04-home.png
    ├── 05-workplace.png
    ├── 06-emotion.png
    ├── 07-communication.png
    ├── 08-profile.png
    ├── 09-sos.png
    └── 10-home-with-ai-tip.png
```

## 🤖 AI 配置

1. 访问 [open.bigmodel.cn](https://open.bigmodel.cn/) 免费注册
2. 获取 API Key（GLM-4-Flash 永久免费，注册送2000万Token）
3. 在应用中点击 "我的" → "AI助手设置" → 粘贴API Key → 保存

## 📄 许可证

本项目为心桥 MindBridge 就业支持平台设计原型，旨在帮助心智障碍群体更好地融入职场。
