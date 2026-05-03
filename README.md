# AI 第二大脑 — Claude 级全生命周期记忆管理

# AI Second Brain — Claude-Level Full Lifecycle Memory Management

> 「受 Claude Code 512,000 行源码泄露启发，为你的 AI 打造永不遗忘的记忆系统。」
>
> *"Inspired by the leaked 512,000-line Claude Code source, building an unforgettable memory system for your AI."*

**由易效能创始人叶武滨创立 | Created by Ye Wubin, Founder of YiXiaoNeng**

[![GitHub stars](https://img.shields.io/github/stars/yewubin-jpg/claude-code-memory-yewubin.svg?style=social&label=Star)](https://github.com/yewubin-jpg/claude-code-memory-yewubin/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/yewubin-jpg/claude-code-memory-yewubin.svg?style=social&label=Fork)](https://github.com/yewubin-jpg/claude-code-memory-yewubin/network/members)
[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/yewubin-jpg/claude-code-memory-yewubin)

---

## 为什么你需要这个？| Why Do You Need This?

你的 AI 助手聊了 100 轮就忘了你是谁？你在 ChatGPT、豆包、Kimi 积累的记忆被锁死在平台上？

**AI 第二大脑**解决这一切。它让你的 AI 拥有 Claude 级别的三层记忆架构，跨会话永不遗忘，还能从其他平台迁移记忆。

Does your AI forget who you are after 100 messages? Are your memories locked inside ChatGPT, Doubao, or Kimi?

**AI Second Brain** solves all of this. It gives your AI a Claude-level three-layer memory architecture that never forgets across sessions, and can even migrate memories from other platforms.

---

## 核心功能 | Core Features

### 三层记忆架构 | Three-Layer Memory Architecture

像人类大脑一样分层存储，从短期到长期，自动管理：

Layered storage like the human brain, from short-term to long-term, fully automated:

| 层级 Layer | 名称 Name | 功能 Function |
|:---:|:---|:---|
| 第一层 | **工作记忆** Working Memory | 当前对话的上下文 |
| 第二层 | **短期记忆** Short-term Memory | 近期主题文件，按项目分类 |
| 第三层 | **长期记忆** Long-term Memory | 全局索引 MEMORY.md + 归档系统 |

### 自动做梦 AutoDream | Automatic Memory Consolidation

受 Claude Code 源码中的三重门触发器启发，AI 会像人类做梦一样自动整理记忆：

Inspired by Claude Code's Three-Gate Trigger, the AI consolidates memories like human dreaming:

- **时间门**：距上次整理 ≥ 24 小时自动触发
- **会话门**：累计 ≥ 5 次会话自动触发
- **五阶段整理**：定向 → 收集 → 整合 → 老化检测 → 剪枝
- 也可随时输入 `/dream` 手动触发

### KAIROS 主动式思维 | Proactive Thinking

从"被动响应"升级为"主动预判"：

Upgraded from reactive to proactive:

- 检测到截止日期时主动提醒记录
- 发现新项目时主动建议创建专题文件
- 记忆接近上限时主动建议整理
- 所有主动行为以"建议 + 询问"形式呈现，决定权在你

### 跨平台记忆迁移 | Cross-Platform Memory Migration

你在其他 AI 平台积累的记忆不应被锁死。支持从以下平台迁移：

Your memories from other AI platforms shouldn't be locked in. Migration supported from:

- **ChatGPT** — 官方导出或快捷迁移法
- **豆包 / Kimi / DeepSeek** — AI 自述法或浏览器插件导出
- **Gemini** — Google Takeout 官方导出
- **Claude** — 官方导出

### 易效能文件系统 | YiXiaoNeng File System

融入易效能八大领域管理体系，自动用"大主题+日期+子主题"规范命名所有笔记和文件。

Integrated with YiXiaoNeng's 8 Life Areas management system, automatically naming all notes and files with standardized conventions.

### 开放兼容 | Open Compatibility

独立安装即可使用，同时智能兼容其他 Skill（如 productivity-skill）。自动识别梦想目标、项目数据、每日笔记，无需额外配置。

Works standalone out of the box, while intelligently compatible with other Skills (like productivity-skill). Auto-detects goals, project data, and daily notes — zero extra configuration.

---

## 安装 | Installation

**海外用户 Global Users：**
```bash
clawhub install claude-code-memory-yewubin
```

**中国用户 China Users（国内镜像加速）：**
```bash
clawhub install claude-code-memory-yewubin --registry https://cn.clawhub-mirror.com/api
```

**从 GitHub 克隆 Clone from GitHub：**
```bash
git clone https://github.com/yewubin-jpg/claude-code-memory-yewubin.git
```

### 常用命令 | Commands

| 命令 Command | 功能 Function |
|:---|:---|
| `/dream` | 手动触发记忆整理（做梦） |
| `/backup` | 手动触发工作空间备份 |
| `/memory` | 查看当前记忆索引状态 |

---

## 安全与隐私 | Security & Privacy

本 Skill 严格遵循安全合规标准，把控制权完全交还给用户：

This Skill strictly follows security compliance standards, giving full control back to users:

- **数据不出境**：所有记忆、笔记和文件均保存在本地 workspace，绝不上传第三方服务器
- **透明的自动化**：AutoDream 和自动备份在初始化时明确请求同意，可随时修改
- **备份前报告**：执行备份前发送报告，由你确认后执行，绝不静默操作
- **安全安装**：安装时先备份旧记忆，展示评估报告，只有你明确同意后才写入

---

## 创作者 | Creator

AI 第二大脑由易效能创始人 **叶武滨** 创立。

**AI Second Brain** was created by **Ye Wubin**, founder of YiXiaoNeng.

叶武滨是全球知名的时间管理专家、畅销书作家，拥有 1.5 亿播放量，全球 10 国 50 城 1000 场演讲经验，持有国家发明专利，获批美国杰出人才。

Ye Wubin is a globally renowned time management expert and bestselling author with 150M+ audio plays, 1000+ workshops across 10 countries and 50 cities, holder of a Chinese National Invention Patent, and recognized as a U.S. Outstanding Talent (EB-1A).

- **官方网站 Official Website**: [www.yixiaoneng.com](https://www.yixiaoneng.com)
- **课程报名 Course Registration**: [Official Course Portal](https://www.yixiaoneng.com/courses)

---

## 支持我们 | Support This Project

如果这个 Skill 对你有帮助，请支持我们：

If this skill has helped you, please support us:

1. 在 [GitHub](https://github.com/yewubin-jpg/claude-code-memory-yewubin) 上点一个 **Star**
2. 在 [ClawHub](https://clawhub.ai/yewubin-jpg/claude-code-memory-yewubin) 上点 **Like** 并留下 **评论**
3. **分享**给你身边需要 AI 记忆管理的朋友

> 「每一个 Star、Like 和分享，都能帮助更多人让 AI 真正记住自己。」
>
> *"Every Star, Like, and Share helps more people make their AI truly remember them."*

---

## 免责声明 | Disclaimer

1. **合法使用**：本 Skill 仅供合法、正当用途使用。用户应确保其使用行为符合所在地区的法律法规。
2. **用户责任**：用户对使用本 Skill 管理的所有数据和记忆承担全部责任。虽然本 Skill 内置自动备份机制，但用户仍需对重要数据和数字资产负最终责任，建议定期将 workspace 备份到外部安全存储。
3. **AI 辅助声明**：本 Skill 由叶武滨原创构想，通过 AI 辅助设计与编写。用户在安装和使用前，有义务自行审阅本 Skill 中的所有指令和机制。
4. **数据安全**：本 Skill 已通过安全合规扫描，所有数据存储在本地，不会上传至第三方服务器。但因不可抗力、大模型底层故障或用户误操作导致的数据丢失，开发者不承担责任。
5. **免责条款**：因不可抗力、大模型底层故障、AI 生成内容的不可预见性、系统崩溃或用户误操作导致的任何数据丢失、业务中断或间接损失，开发者（叶武滨及易效能团队）不承担法律责任。

1. **Lawful Use**: This Skill is intended for lawful and legitimate purposes only. Users must ensure their usage complies with applicable laws and regulations.
2. **User Responsibility**: Users bear full responsibility for all data and memories managed by this Skill. Although automatic backup is built in, users are ultimately responsible for their important data and digital assets. Regular external backups of the workspace are recommended.
3. **AI-Assisted Design**: This Skill was originally conceived by Ye Wubin and developed with AI assistance. Users are responsible for reviewing all instructions and mechanisms before installation and use.
4. **Data Security**: This Skill has passed security compliance scanning. All data is stored locally and never uploaded to third-party servers. However, the developer is not liable for data loss caused by force majeure, underlying model failures, or user misoperation.
5. **Limitation of Liability**: The developer (Ye Wubin and the YiXiaoNeng team) shall not be held liable for any data loss, business interruption, or indirect damages caused by force majeure, underlying model failures, unpredictability of AI-generated content, system crashes, or user misoperation.

---

## 许可证 | License

MIT License
