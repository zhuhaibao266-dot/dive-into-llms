# 个人学习进度

初始化日期为 2026-11-11。所有单元初始状态均为 `NOT_STARTED`。本次仓库资料核验不计为个人课程学习完成，未运行教程代码或 PoC。

“是否可用于 unified-ops”是未来适用性评估。学习笔记路径先指向规范入口，具体课笔记在实际学习后创建。

| 编号 | 原教程章节 | 主题 | 优先级 | 状态 | 是否已阅读 | 是否已运行代码 | 是否完成练习 | 是否可用于 unified-ops | 学习笔记路径 | 备注 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| A00 | 根 README、11 章目录 | 总览与范围 | 第一 | NOT_STARTED | 否 | 否 | 否 | 是，学习规划 | [notes/README.md](notes/README.md) | 个人总览笔记待建立 |
| A01 | 第 1 章第 1、2、6 节 | LLM 基础 | 第一 | NOT_STARTED | 否 | 否 | 否 | 是，概念与模型选型 | [notes/README.md](notes/README.md) | 训练部分后置 |
| A02 | 第 2 章第 1—2 节，第 10 章第 2.3.1 节 | 模型调用 | 第一 | NOT_STARTED | 否 | 否 | 否 | 是，需适配本地服务 | [notes/README.md](notes/README.md) | DeepSeek endpoint、协议待核验 |
| A03 | 第 2 章第 3—5 节，第 10 章第 2.2 节 | Prompt 与推理 | 第一 | NOT_STARTED | 否 | 否 | 否 | 是，诊断报告输入输出 | [notes/README.md](notes/README.md) | JSON 校验与引用规则待补充 |
| A04 | 上游缺专章，第 8 章第 2.5.2 节仅作概念对照 | RAG、知识库、Embedding 与检索 | 第一，Embedding/向量技术为支撑补课 | NOT_STARTED | 否 | 否 | 否 | 是，需补独立教程 | [notes/README.md](notes/README.md) | 文档切分和检索来源待选 |
| A05 | 第 2 章第 6 节，第 10 章第 1—2.2 节，第 9 章概览 | Agent 与多轮诊断 | 第一，GUI 延伸为第二 | NOT_STARTED | 否 | 否 | 否 | 是，需设计状态与停止条件 | [notes/README.md](notes/README.md) | 外部 ReAct/CRITIC 内容待读 |
| A06 | 第 10 章第 2.2.2 节，第 2 章第 6 节 | Tool Calling | 第一 | NOT_STARTED | 否 | 否 | 否 | 是，需补标准协议和执行器 | [notes/README.md](notes/README.md) | 工具记录案例不代表可运行闭环 |
| A07 | 第 2 章、第 10 章，结合 A04/A06 补课 | Linux 内存异常 PoC 规划 | 第一 | NOT_STARTED | 否 | 否 | 否 | 是，项目映射 | [notes/README.md](notes/README.md) | 本次仅规划，后续单独立项实验 |
| A08 | 第 1 章微调，第 8—9 章，第 3—7、11 章 | 微调、多模态、GUI、安全及训练进阶 | 第二/第三 | NOT_STARTED | 否 | 否 | 否 | 按需，训练和隐写等相关性低 | [notes/README.md](notes/README.md) | 第 10 章关键运维风险案例提前读 |

## 更新规则

学习状态可依次记录为 `NOT_STARTED`、`READING`、`READ_DONE`、`LAB_DONE`、`REVIEWED`，受阻时用 `BLOCKED` 并说明原因。是否读过、运行代码和完成练习分别按事实更新，代码运行应留下环境、命令、退出码和输出摘要。

补充课程必须明确标为个人补课，记录来源和版本。每次完成学习后更新真实笔记路径、待验证问题与 unified-ops 适用性。学习分支上的文档更新通过正常提交保存。
