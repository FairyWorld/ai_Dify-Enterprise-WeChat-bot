# Dify-企微机器人-
# Dify-Enterprise-WeChat-bot
## 📌 介绍

欢迎来到 **Dify-企业微信机器人** 仓库！这是一个专为企业微信设计的知识库聊天机器人，利用 Dify API 增强其功能。兼容企业微信最新版本 4.1.13.6009，特别是针对外部群组的新功能。
打开项目下载最新企业微信发布的的4.1.13.6009版本 下载：https://dldir1.qq.com/wework/work_weixin/WeCom_4.1.22.6009.exe
## ✨ 核心功能

- **上下文管理**：借助 Dify API，实现聊天上下文的维护，使机器人可以无缝处理复杂对话。
- **独立会话管理**：为企业微信群聊中的每个用户维护独立的会话，实现个性化互动。
- **智能回复**：通过改进的AI算法，提供更准确的响应，增强用户体验。
- **聊天记录功能**：自动记录聊天内容，方便回顾与进一步的AI训练。
- **配置灵活性**：用户可以通过配置文件自定义机器人的行为，如上下文管理和会话处理。
- **持续优化**：定期推出新功能和性能优化，不断提升机器人的表现。

## 🚀 最近更新
- **2024/05/20**：

2024/05/20 -废除原有的本版采用官网最新的版本，新版沿用win方式登录，大幅降低风险 目前测试有半年安全无风险
2024/05/20 -新增私有化部署本地dify对接企微 #USE_LOCAL_SERVER=false代码使用dify官网进行回复 可配置值
true：设置为 true 时，应用程序将连接到本地部署的dify服务。这通常用于本地开发和测试。
false：设置为 false 时，应用程序将连接到dify官网服务。这用于生产环境或当本地服务器不可用时写个超级简单是说明

- **2024/04/27**：
    ~~- **PAD协议登录**：新的登录协议，显著降低安全风险。~~
    - **完全兼容**：支持最新的Dify工作流程和API。
    - **聊天记录输出**：优化输出格式，支持数据的二次训练。
    - **上下文关联**：强化与Dify后台的数据关联，实现高效的会话管理。

## 🔜 即将推出的功能

- 语音转文本及语音识别功能
- Dify 图像识别和文件发送功能
- 自动基于用户对话进行知识库训练，实现机器人的自我学习和迭代
- 批量添加好友功能
# #dify部署教程


   ```bash
   # 配置 Dify Key
   echo "YOUR_DIFY_KEY_HERE" > .env
[.env](.env)
## 快速开始

**1.打开dify官网登录进去**

**2.创建自己的应用**
![image](https://github.com/luolin-ai/Dify-Enterprise-WeChat-bot/assets/135555634/79509f35-2c98-4742-8860-006d286cb694)

**3.选择对话型应用**
![image](https://github.com/luolin-ai/Dify-Enterprise-WeChat-bot/assets/135555634/f871a335-012b-4d43-af4f-1851c3ad2534)

**3.点击构建好应用页面的api访问**
![image](https://github.com/luolin-ai/Dify-Enterprise-WeChat-bot/assets/135555634/58b5010d-996d-430a-abe8-41066814c7b4)

**4.生成自己应用key**
![image](https://github.com/luolin-ai/Dify-Enterprise-WeChat-bot/assets/135555634/2961ed63-bc6c-4a71-ab8e-88be9d424c27)

**打开项目的配置文件填写自己的dify的key**
![img_1.png](img_1.png)
**运行项目的的app软件**


![image](https://github.com/luolin-ai/Dify-Enterprise-WeChat-bot/assets/135555634/fecd6610-3462-4137-b420-ba98cbb9058f)


## Dify企微机器人项目交流群**

添加小助手入群加微信备注dify
![微信图片_20240307051544](https://github.com/luolin-ai/Dify-Enterprise-WeChat-bot/assets/135555634/279afe8d-c602-4dcb-b16c-f0d7fdc4b23d)
