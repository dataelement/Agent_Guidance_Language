# AGL（Agent Guidance Language，标准Agent指导语言）

> 用 SOP 思维为 Agent 写“可执行的指令书”。AGL 让业务专家用自然语言稳定“操控”通用 Agent，把**专家偏好/偏见**和**私域知识**注入任务执行流程。

## 背景
大语言模型已经“博识且聪明”，但它的默认输出为了照顾所有人，往往**中庸平均**；而**企业场景的优秀 Agent 一定需要“偏见与品味”**。真正可落地的 Agent 必须让业务专家深度参与，把领域习惯、隐性规则和质量门槛注入系统。与此同时，真实任务的稳定执行还受限于：表达风格不一、关键信息遗漏、对模型/工具边界认识不足等。

为此，我们提出 **AGL（Agent Guidance Language）**：AGL使用自然语言表达，整体框架借鉴了管理学上的SOP（标准作业流程）概念，业务专家很熟悉；AGL同时又是一门Agentic友好的规范，尽可能考虑Agent适配性，极大提升了Agent任务效果稳定性。使用AGL标准撰写的任务说明，我们称之为： **“AGL 指导手册（AGL Manual）”**。

本仓库提供：
- ✨ **AGL 规范（draft）**：最小可行集（MVP）规范
- 🧩 **模板**：开箱即用的指导手册模板（与示例）
- 📚 **文档**：设计哲学、术语表、风格指南
- 🧪 **校验建议**：如何自检指导手册质量与稳定性

> 本项目由 **[BISHENG](https://github.com/dataelement/bisheng)** 发起，欢迎社区共同打磨标准。

---

## 快速开始
1. 复制模板：`/templates/agl-manual-template.md`
2. 填入你的任务，补齐“问题概述、所需资源、步骤说明”三大块。
3. 将你的手册放入 `/examples/` 并发起 PR。

## 目录
- `/docs/AGL-Spec-v0.1.md` — 规范
- `/templates/agl-manual-template.md` — 官方模板（与题主提供模板一致）
- `/examples/` — 示范手册
- `CONTRIBUTING.md` — 如何贡献（含 AGL 提案流程 AGLP）
- `LICENSE` — MIT


## License
MIT License
