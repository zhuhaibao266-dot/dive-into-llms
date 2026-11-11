# 个人大模型学习扩展

本目录记录个人学习路线、笔记、练习与 unified-ops 项目映射。原教程内容及其权利归上游作者和相应权利人所有。个人新增内容集中于 `personal-study/`，沿用原教程目录与历史。

## 学习入口

- [学习路线与 Top 10](STUDY_ROADMAP.md)
- [个人学习进度](PROGRESS.md)
- [unified-ops 与 Linux 内存异常 PoC 映射](UNIFIED_OPS_MAPPING.md)
- [笔记规范](notes/README.md)
- [练习规范](exercises/README.md)

## 核验基线

| 项目 | 记录 |
| --- | --- |
| 核验日期 | 2026-11-11，北京时间 |
| 上游 | [Lordog/dive-into-llms](https://github.com/Lordog/dive-into-llms) |
| 个人 Fork | [zhuhaibao266-dot/dive-into-llms](https://github.com/zhuhaibao266-dot/dive-into-llms) |
| 上游默认分支 | `main` |
| 上游基线 | `f84c04268794ef94f8949808bbc14ab8636763a0` |
| 最近提交 | Update README.md，2025-10-10 |
| 个人学习分支 | `learning/personal-study` |
| 阅读范围 | 根 README、完整目录树、11 章 README、11 份 notebook 源文本、第 11 章 requirements.txt |
| 阅读限制 | PDF 课件未逐页阅读，外部项目和昇腾站外课程未进行内容级核验，示例代码未运行 |
| LICENSE | 完整目录树未发现许可证文件，GitHub 返回 `license=null`，许可证待作者明确 |

根 README 的“公益、免费”描述与许可证授权范围应分别记录。后续复用、分发或商用前核实作者及各模型、数据集、依赖项目的授权。此目录未给上游材料添加推定许可证。

初始化资料由仓库阅读形成，个人课程状态统一为 `NOT_STARTED`。资料整理完成不代表个人已经读完课程或运行实验。

## 上游同步与个人分支

上游更新优先通过 GitHub Fork 的 Sync fork 同步到个人 `main`。同步前查看差异，个人笔记继续提交到学习分支。之后在学习分支合入经过核验的 `origin/main`，处理冲突并复核笔记对应章节。保留正常合并历史。

未来本地克隆时可按下列方式保留上游 remote。此段为使用说明，本次通过 GitHub 远程接口提交，没有建立本地克隆。

```bash
git clone https://github.com/zhuhaibao266-dot/dive-into-llms.git
cd dive-into-llms
git remote add upstream https://github.com/Lordog/dive-into-llms.git
git fetch upstream
git switch learning/personal-study
```

执行 `remote add` 前用 `git remote -v` 检查，已有 upstream 时核对地址。同步前保存工作区，查看上游变更。更新后记录基线 SHA、课程路径和学习路线变化。

## 当前实践边界

本次交付是学习初始化。unified-ops 映射属于未来设计，Linux 内存异常 PoC 尚未实现。个人练习后续采用合成或脱敏数据。离线实践的引擎、模型、缓存、知识库和日志统一放在 `/data`，日常运行使用普通账户 `tailweb`。

建议协作节奏为 ChatGPT 讲概念与复核理解，Work 整理资料与证据，Codex 实现和验证明确的练习任务。实际仓库权限、模型接口和联网能力按每次会话核验。
