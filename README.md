# 乱花 / SUCHA-main

正在通过小型项目学习 AI 应用、全栈开发与工程化实践，并把过程整理成可以运行、可以展示、可以复盘的作品。

[个人网站](https://luanhua-site.vercel.app) · [技术笔记](https://luanhua-site.vercel.app/notes) · [GitHub 项目](https://github.com/SUCHA-main?tab=repositories)

## Current Focus

- **AI 应用**：RSS 摘要、Mock-first 工作流、本地模型和 Provider 接入。
- **全栈开发**：用 React、Astro、Node.js、Go 和 SQLite 完成小型 MVP。
- **DevOps**：通过 Docker、CI/CD 与本地监控实验理解交付流程。
- **AIoT**：准备从 ESP32、MQTT、传感器和 Web Dashboard 开始实践。

我的学习方式是先做出最小可运行版本，再补充安全边界、README、构建检查和项目复盘。

## Selected Projects

| 项目 | 简介 |
| --- | --- |
| [AI WeChat Digest MVP](https://github.com/SUCHA-main/ai-wechat-digest-mvp) | RSS + AI 摘要个人晚报 MVP。Mock 默认安全演示，可选 OpenAI-compatible / Ollama；不直接抓取微信，也不实现公众号发布。 |
| [Mini Provider Gateway Portal](https://github.com/SUCHA-main/mini-provider-gateway-portal) | 管理 Provider、Consumer Key 和调用元数据的个人网关 MVP。Provider Key 当前保存在本地 SQLite，不是生产级网关。 |
| [Go WebSocket Chatroom](https://github.com/SUCHA-main/go-websocket-chatroom) | Go WebSocket 实时聊天室学习项目，包含登录会话、消息广播、历史消息和可选本地 Ollama 助手。 |
| [LabelHub AI MVP](https://github.com/SUCHA-main/labelhub-ai-mvp) | React + Express 数据标注工作流 MVP，使用规则驱动 Mock AI Review；Demo 角色登录不是真实认证。 |
| [Sign Language Demo](https://github.com/SUCHA-main/sign-language-demo) | MediaPipe + OpenCV 五类自定义手势识别 MVP，不是通用手语翻译系统；模型和个人采集数据保持本地。 |
| [luanhua-site](https://github.com/SUCHA-main/luanhua-site) | 使用 Astro 构建的个人作品集与技术笔记站点，用于连接项目、真实边界和阶段性复盘。 |

第一篇项目复盘：[AI WeChat Digest MVP：从 RSS 到每日晚报](https://luanhua-site.vercel.app/notes/ai-wechat-digest-rss-to-daily-digest)

## Now / Next

当前阶段主要在整理已有公开仓库，让项目说明、数据边界、检查结果和个人网站保持一致。

下一步会继续补充自动化测试与 CI 经验，并尝试低成本、可复刻的 ESP32 / MQTT 小项目。

## Contact

项目相关问题可以通过对应仓库的 [GitHub Issues](https://github.com/SUCHA-main?tab=repositories) 联系。
