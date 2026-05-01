# Memory · 我的 AI 共享记忆

这个目录存放我希望所有 AI（Claude / ChatGPT / Gemini 等）都能读取的个人上下文，
用来解决"切换 AI 时记忆不通用"的问题。

## 文件结构

| 文件 | 内容 | 更新频率 |
|------|------|----------|
| `profile.md` | 我是谁、背景、长期目标 | 很少改 |
| `preferences.md` | 我希望 AI 如何与我交流（语气、详略、格式） | 偶尔改 |
| `context.md` | 当前在做什么、最近的进展 | 经常改 |

## 使用方法

### 方式 A：Claude Code（本仓库）
根目录的 `CLAUDE.md` 已自动引用本目录，无需手动操作。

### 方式 B：网页版 AI（ChatGPT / Claude.ai / Gemini）
新会话开始时，把这三个文件的内容粘贴到第一条消息里，并加上一句：
> 这是我的个人背景和偏好，请在本次对话中遵守。

### 方式 C：带 GitHub 集成的 AI
让它读取 `https://github.com/<你的用户名>/ai-learning/tree/main/memory`
（私有仓库需要先授权）。

## 隐私提醒

- 本仓库应设为 **Private**（GitHub 仓库 Settings → Danger Zone → Change visibility）
- 不要写入：密码、身份证号、银行卡、家庭住址等敏感信息
- Token 授权时只开 `repo:read` 权限，且只授权本仓库
