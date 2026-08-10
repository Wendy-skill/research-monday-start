# Research Monday Start｜科研周一启动

一个温暖、可靠的科研周一启动 Skill。它会恢复上周上下文，自动识别当前科研场景，生成本周唯一目标、周一最多三项任务、25 分钟开工路径和今日科研能量卡。

A warm, evidence-aware Skill that restores last week's research context, identifies the current research mode, and creates a focused Monday plan with a 25-minute starter.

## ✨ 主要功能｜Highlights

- 中英双语触发与输出，会跟随用户的主要语言。
- 自动识别论文写作、实验、模拟、文献阅读四类场景，也能处理混合场景。
- 默认输出一屏左右的温暖精简看板；回复“查看详情”或 “View details” 可展开完整方案。
- 严格区分“已确认 / 合理推断 / 待核实”，避免虚构科研进度、结果、文献或截止日期。
- 支持后续陪跑：`完成 / Done`、`卡住 / Stuck`、`改变 / Changed`、`今天收工 / Finish for today`。

## 📦 安装｜Install

1. 打开仓库的 **Releases** 页面并下载最新版 `research-monday-start.zip`。
2. 在支持 Skill 导入的界面上传 ZIP；使用本地 Skills 目录的 Agent 也可以解压后安装完整文件夹。
3. 安装后可以直接用下面的示例开始。

Open **Releases**, download the latest `research-monday-start.zip`, and import the ZIP into a Skill-compatible interface. For agents that use a local Skills directory, extract and install the complete top-level folder.

## 🚀 使用示例｜Example prompts

中文：

```text
开启科研周一。上周我完成了论文结果部分初稿，周四要给导师发修订稿，今天有半天时间。
```

English:

```text
Start my research week. I read six papers last week, my notes are scattered, and my literature review section is due on Friday.
```

## 🧭 四类科研场景｜Four research modes

| 场景 / Mode | Skill 会优先关注 / Priority |
| --- | --- |
| 论文写作 / Writing | 章节、图表、意见回复、论点与证据、可提交文本 |
| 实验 / Experiment | 设备、样品、方案、安全、数据记录、失败原因与重做成本 |
| 模拟 / Simulation | 算例、参数、日志、队列、收敛、重跑与后处理 |
| 文献阅读 / Literature | 研究问题、检索范围、阅读队列、证据表与引用落点 |

## 🤖 兼容性｜Compatibility

该 Skill 可用于 ChatGPT 和 Codex。其他能够读取标准 Skill 文件夹（包含 `SKILL.md`）的 Agent 也可以尝试使用；实际触发和工具能力取决于具体平台。

This Skill is designed for ChatGPT and Codex. Other agents that can load a standard Skill folder containing `SKILL.md` may also use it, subject to each platform's triggering and tool support.

## 作者｜Author

wendy.z

## 许可证｜Licence

MIT
