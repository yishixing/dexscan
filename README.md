# DexScan Skill 介绍

## 一、 DexScan Skill是什么？

**DexScan Skill** 是基于 Skills 协议的 AI 智能工具包。通过将 DexScan Skill 添加到您的 AI Agent 技能列表，您的智能体即可便捷获取 DexScan 平台的代币行情、牛人榜、社交热度及信号相关数据。

**包名**：
`dexscan-skill`
---

## 二、安装与使用

### 2.1 安装 Skill
- 通用安装
```bash
npx skills add github:dex-scan/dexscan-skill
```
- OpenClaw安装
```bash
openclaw skills install dexscan-skill
```
- 其他方式，直接[下载](https://codeload.github.com/dex-scan/dexscan-skill/zip/refs/heads/main)安装包，下载完成后将安装包提交给智能体完成安装即可。

安装后，dexscan-skill 将自动出现在您的技能列表中。

### 2.2 配置认证
为了调用 DexScan 的 API，您需要配置 API Key（在 [DexScan 控制台](/dev-portal/home)获取）
- 方式一，添加环境变量到您的运行环境
```bash
export DS_ACCESS_KEY="您的API Key"
export DS_SECRET_KEY="您的Secret Key"
```
- 方式二，在dexscan-skill工作目录或上层目录添加.env文件文件，文件内容如下
```
DS_ACCESS_KEY="您的API Key"
DS_SECRET_KEY="您的Secret Key"
```

### 2.3 通过对话使用
配置完成后，您即可通过自然语言与 Agent 对话，例如：
- “帮我查一下 SOL 最新信号代币有哪些。”
- “xxx代币最新价格是多少？”

---

立即安装 DexScan Skill，让您的 AI Agent 拥有专业的区块链数据分析能力！