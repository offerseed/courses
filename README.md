<div align="center">

# Offerseed 一周一课

**面向 AI Agent 与 AI Infra 的中文技术课件库**

从行业趋势、Agent 工程实践，到端侧智能与大模型推理，持续沉淀可直接阅读的课程讲义。

[![Courses](https://img.shields.io/badge/课程-8%20期-0969da)](#课程目录)
[![Topics](https://img.shields.io/badge/方向-Agent%20%7C%20AI%20Infra-1f883d)](#课程目录)
[![Language](https://img.shields.io/badge/语言-中文-ea4aaa)](#)

</div>

## 关于本仓库

这里收录 **Offerseed「一周一课」**系列课程的公开讲义，内容聚焦两个方向：

- **AI Agent**：理解 Agent 的行业影响、自进化机制、上下文管理与生产级工程实践。
- **AI Infra**：建立大模型基础设施认知，覆盖端侧 VLM、推理性能优化与完整推理链路。

所有资料均为 PDF，可直接在线预览或下载阅读。目前共收录 **8 期课程、184 页讲义**。

## 课程目录

### AI Agent

| 期数 | 主题 | 内容简介 | 课件 |
| :---: | --- | --- | :---: |
| 01 | Agent 到底是不是正在膨胀的泡沫？ | 从行业冲击、岗位演化、大模型关系与成熟度等角度，判断 Agent 的真实价值与发展阶段 | [在线阅读](./agent/01-行业趋势.pdf) |
| 02 | 从 DeepSeek Harness 看 Agent 自进化 | 介绍插件化、可回滚的 Agent 自进化架构，并延伸到 Self-Harness 与 ACE | [在线阅读](./agent/02-Agent自进化.pdf) |
| 03 | 上下文即操作系统 | 围绕 DeepSeek Harness、MemGPT、Context-Folding 与 ACON，拆解上下文管理系统 | [在线阅读](./agent/03-上下文管理.pdf) |
| 04 | 从 Demo 到 Production | 从真实项目出发，讨论 Agent 如何从可运行原型走向可持续演进的生产系统 | [在线阅读](./agent/04-生产实践.pdf) |

### AI Infra

| 期数 | 主题 | 内容简介 | 课件 |
| :---: | --- | --- | :---: |
| 01 | AI Infra 到底是干什么的？ | 从训练代码到大规模集群，建立 AI Infra 的基本概念、工作范围与职业认知 | [在线阅读](./ai-infra/01-基础认知.pdf) |
| 02 | VLM in Robotics | 聚焦机器人场景中的视觉语言模型，以及端侧 AI 的工程挑战与职业机会 | [在线阅读](./ai-infra/02-端侧VLM.pdf) |
| 03 | 从 2 帧到 15 帧 | 梳理端侧推理性能优化的完整链路与关键实践 | [在线阅读](./ai-infra/03-推理性能优化.pdf) |
| 04 | 大模型推理 | 用系统性思维理解大模型推理基础设施及其关键组成 | [在线阅读](./ai-infra/04-大模型推理.pdf) |

## 仓库结构

```text
courses/
├── agent/          # AI Agent 系列课件
├── ai-infra/       # AI Infra 系列课件
└── README.md       # 课程索引与学习路线
```

## 推荐学习路线

**想做 Agent 应用或工程化落地**

`Agent 01` 行业与技术判断 → `Agent 03` 上下文管理 → `Agent 04` 生产实践 → `Agent 02` 自进化探索

**想进入 AI Infra 或推理优化方向**

`AI Infra 01` 基础认知 → `AI Infra 04` 推理体系 → `AI Infra 03` 性能优化 → `AI Infra 02` 端侧与机器人场景

**只想快速了解全貌**

建议先阅读两个方向的第 01 期，再根据兴趣选择后续专题。

## 如何使用

你可以直接点击上方表格中的「在线阅读」，也可以克隆仓库后离线查看：

```bash
git clone https://github.com/offerseed/courses.git
cd courses
```

PDF 文件名包含空格和中文字符，在命令行中使用时请用引号包裹，例如：

```bash
open "agent/01-行业趋势.pdf"
```

## 参与贡献

欢迎通过 [Issue](https://github.com/offerseed/courses/issues) 反馈以下问题：

- 课件中的错别字、失效链接或事实错误
- 希望补充或深入讲解的主题
- 阅读体验与仓库组织方面的建议

如需提交新资料，请先确认你拥有相应内容的发布权，并在 Pull Request 中说明资料来源、主题与适合人群。

## 版权说明

本仓库课件仅供学习与交流使用。除非文件中另有说明，课件内容的版权归原作者或 Offerseed 所有；未经授权，请勿用于商业用途或二次分发。引用时请注明来源并保留原始署名。

---

<div align="center">

**Offerseed - 种下一颗种子，收获一份 Offer。**

</div>
