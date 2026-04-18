# OpenClaw for Zotero

[English](#english) | [中文](#中文)

---

<a name="english"></a>
## English

🤖 AI-powered chat assistant for Zotero. Ask questions about your references, get summaries, and explore your library with natural language.

### ✨ Features

- **Chat with your references** - Ask questions about any paper in your Zotero library
- **Context-aware responses** - AI understands the current paper's title, authors, abstract, and more
- **Conversation history** - Each paper maintains its own conversation history
- **Multiple AI models** - Support for GLM-5, DeepSeek, MiniMax, Qwen, and more
- **Customizable settings** - Configure system prompt, abstract length, author count, and timeout

### 📋 Requirements

- **Zotero 7.0+** or **Zotero 8.x**
- **OpenClaw Gateway** running locally or remotely
- **API Key** from your OpenClaw configuration

### 🚀 Installation

1. Download the latest `.xpi` file from [Releases](https://github.com/openclaw/openclaw-for-zotero/releases)
2. Open Zotero → **Tools → Add-ons**
3. Click the gear icon → **Install Add-on From File**
4. Select the downloaded `.xpi` file
5. Restart Zotero

### ⚙️ Configuration

1. Go to **Edit → Preferences → OpenClaw**
2. Configure the following:

| Setting | Description | Default |
|---------|-------------|---------|
| Server URL | OpenClaw Gateway address | `http://localhost:18789` |
| API Key | Your OpenClaw API key | *Required* |
| Model | AI model to use | GLM-5 |
| System Prompt | Custom AI behavior | (editable) |
| Abstract Length | Max characters to send | 300 |
| Max Authors | Max authors to include | 5 |
| Request Timeout | API timeout in seconds | 120 |

### 🎯 Usage

1. **Select a reference** in your Zotero library
2. **Click the OpenClaw icon** in the right sidebar
3. **Ask questions** about the paper

### ❓ FAQ

**Q: The plugin doesn't appear after installation?**
A: Make sure you're using Zotero 7.0+ or 8.x, restart Zotero completely.

**Q: "API Key not configured" error?**
A: Go to Preferences → OpenClaw and enter your API key.

**Q: "Network error" or "Connection failed"?**
A: Ensure OpenClaw Gateway is running and the Server URL is correct.

---

<a name="中文"></a>
## 中文

🤖 Zotero AI 聊天助手。针对文献提问、获取摘要、用自然语言探索你的文献库。

### ✨ 功能特点

- **与文献对话** - 对 Zotero 库中的任何论文提问
- **上下文感知** - AI 理解当前论文的标题、作者、摘要等信息
- **对话历史** - 每篇论文独立保存对话历史
- **多种 AI 模型** - 支持 GLM-5、DeepSeek、MiniMax、Qwen 等
- **可自定义设置** - 配置系统提示词、摘要长度、作者数量、超时时间

### 📋 系统要求

- **Zotero 7.0+** 或 **Zotero 8.x**
- **OpenClaw Gateway** 本地或远程运行
- **API Key** 从 OpenClaw 配置获取

### 🚀 安装方法

1. 从 [Releases](https://github.com/openclaw/openclaw-for-zotero/releases) 下载最新的 `.xpi` 文件
2. 打开 Zotero → **工具 → 附加组件**
3. 点击齿轮图标 → **从文件安装附加组件**
4. 选择下载的 `.xpi` 文件
5. 重启 Zotero

### ⚙️ 配置说明

1. 进入 **编辑 → 首选项 → OpenClaw**
2. 配置以下选项：

| 设置项 | 说明 | 默认值 |
|--------|------|--------|
| 服务器地址 | OpenClaw Gateway 地址 | `http://localhost:18789` |
| API Key | 你的 OpenClaw API 密钥 | *必填* |
| 模型 | 使用的 AI 模型 | GLM-5 |
| 系统提示词 | 自定义 AI 行为 | (可编辑) |
| 摘要长度 | 发送的最大字符数 | 300 |
| 最大作者数 | 包含的最大作者数 | 5 |
| 请求超时 | API 超时时间（秒） | 120 |

### 🎯 使用方法

1. **选中一篇文献**
2. **点击右侧边栏的 OpenClaw 图标**
3. **输入问题**，例如：
   - "总结这篇论文"
   - "主要贡献是什么？"
   - "解释一下方法论"
   - "与相关工作对比"

### ❓ 常见问题

**问：安装后插件没有出现？**
答：确保使用 Zotero 7.0+ 或 8.x，完全重启 Zotero。

**问：提示 "API Key not configured" 错误？**
答：进入首选项 → OpenClaw，输入你的 API 密钥。

**问：提示 "Network error" 或连接失败？**
答：确保 OpenClaw Gateway 正在运行，服务器地址正确。

---

## 📄 License

MIT License - Free to use, modify, and distribute.

## 📮 Support

- **Issues**: [GitHub Issues](https://github.com/openclaw/openclaw-for-zotero/issues)
- **Docs**: [OpenClaw Docs](https://docs.openclaw.ai)

---

Made with ❤️ by OpenClaw Team