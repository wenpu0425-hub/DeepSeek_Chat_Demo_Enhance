# DeepSeek Chat Demo 增强版

基于 [DeepSeek Chat Demo](https://github.com/deepseek-ai/chat-demo)，增加全局记忆、对话压缩和四档思考强度。

[打开在线版](https://wenpu0425-hub.github.io/DeepSeek_Chat_Demo_Enhance/)

## 快速开始

打开在线版，在 **设置 → 数据管理** 填入自己的 DeepSeek API Key，即可开始对话。

- **全局记忆**：在 **设置 → 通用** 编辑，或发送 `/remember 默认用中文回答` 添加。普通对话会带上全局记忆。
- **对话压缩**：长对话中发送 `/compress`，调用 API 生成旧对话摘要。后续请求使用摘要和近期原文，聊天原文仍可查看，全局记忆按原文注入。
- **思考强度**：用输入框下方的滑杆选择 **Off / Low / High / Max**。

API Key、对话和全局记忆保存在当前浏览器，跨设备需分别配置。对话可通过历史 ZIP 迁移，记忆可从设置中复制。

## 许可证

[MIT](LICENSE)。保留上游 DeepSeek 版权声明。
