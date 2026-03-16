# 02. 从零配置 AI 开发环境

手把手教你配置 AI 编程开发环境。

## 环境要求

| 要求 | 最低版本 |
|------|---------|
| Node.js | 18.x |
| 内存 | 8GB |
| 磁盘 | 10GB |

## 步骤 1：安装基础工具

### 安装 Node.js

**Windows:**
```powershell
winget install OpenJS.NodeJS.LTS
```

**macOS:**
```bash
brew install node
```

### 安装 Git
```bash
# Windows: winget install Git.Git
# macOS: brew install git
```

## 步骤 2：安装 AI 工具

### OpenClaw（本地 AI 助手）

```bash
npm install -g openclaw
openclaw init
openclaw start
```

### Cursor（AI IDE）

下载: https://cursor.sh

### Copilot（代码补全）

VS Code 插件市场搜索 "GitHub Copilot"

## 步骤 3：配置 API

### OpenAI
1. https://platform.openai.com/api-keys
2. 创建 API Key
3. 配置到工具中

### Anthropic (Claude)
1. https://console.anthropic.com/
2. 创建 API Key

### 本地模型 (Ollama)
```bash
ollama pull llama2
ollama run llama2
```

## 步骤 4：验证环境

```bash
# 验证 OpenClaw
openclaw --version

# 验证 Cursor
cursor --version

# 验证 Copilot
# 在 VS Code 中登录 GitHub 即可
```

## 快速开始

配置完成后，运行第一个任务：

```
"帮我创建一个 hello.py 文件"
```

## 下一步

- [03. 用自然语言写第一个程序](./03-first-program.md)
