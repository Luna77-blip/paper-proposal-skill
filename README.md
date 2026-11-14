# Paper Proposal Skill

一套用于研究生论文开题协作的 Codex Skill，覆盖候选题收敛、P0/P1证据门槛、文献真实性审查、研究问题设计、方法选择、开题报告修订与答辩压力测试。

该 Skill 源于一次完整的 MPAcc 开题协作复盘，已经将具体公司、导师和文件信息脱敏，并抽象为可迁移的方法论。

## 适合解决的问题

- 多个候选题如何统一评分和收敛；
- 一个热门案例是否真正能够支撑硕士论文；
- 导师说“太小”“太泛”“资料不够”时如何纠偏；
- 如何区分案例新、问题新和研究增量；
- 如何在完整写作前完成P0和P1核验；
- 如何核验参考文献真实性和全文状态；
- 如何建立一个主问题、三至四个子问题及章节对应关系；
- 如何避免方法堆砌、强因果和防御性写作；
- 如何在不覆盖旧版本和不破坏格式的情况下修订开题报告。

## 安装

### 方式一：克隆到 Codex Skills 目录

```bash
git clone https://github.com/Luna77-blip/paper-proposal-skill.git ~/.codex/skills/paper-proposal-skill
```

Windows PowerShell：

```powershell
git clone https://github.com/Luna77-blip/paper-proposal-skill.git "$env:USERPROFILE\.codex\skills\paper-proposal-skill"
```

重新打开相关会话后即可使用。

### 方式二：下载源码

下载仓库压缩包，将解压后的 `paper-proposal-skill` 文件夹放入 Codex Skills 目录。

## 使用

显式调用示例：

```text
使用 $paper-proposal-skill 对这三个候选题进行P0初筛，暂时不要写完整开题报告。
```

```text
使用 $paper-proposal-skill 验证这个案例能否通过P1，并建立研究命题—证据—缺口表。
```

```text
使用 $paper-proposal-skill 根据导师反馈纠偏，但不要覆盖原Word文件，也不要改变已有格式。
```

该 Skill 允许自动触发。当请求明显涉及论文开题、候选题筛选、P0/P1核验、开题报告修订或答辩准备时，也可以被自动选择。

## 核心工作流

```text
约束校准
  ↓
候选题生成与收敛
  ↓
P0：重要性、学科匹配、案例特征与初步资料
  ↓
P1：一手证据、连续数据、文献真实性与小规模试跑
  ↓
主问题与子问题
  ↓
文献综述、理论与方法
  ↓
开题报告与可编辑图表
  ↓
导师反馈纠偏
  ↓
提交审查与答辩准备
```

## 目录

```text
paper-proposal-skill/
├── SKILL.md
├── README.md
├── LICENSE
├── agents/
│   └── openai.yaml
├── examples/
│   └── anonymized-case.md
└── references/
    ├── checklists.md
    ├── document-revision.md
    ├── literature-audit.md
    ├── p0-p1-gates.md
    ├── prompt-templates.md
    ├── topic-selection-lessons.md
    └── workflow.md
```

## 文件说明

- `SKILL.md`：触发条件、模式选择、核心约束与资源路由。
- `references/workflow.md`：从需求校准到答辩准备的完整流程。
- `references/p0-p1-gates.md`：候选题P0和P1门槛。
- `references/topic-selection-lessons.md`：被否选题的原因、抢救方式和方向选择。
- `references/literature-audit.md`：文献真实性、全文状态和综述组织方法。
- `references/document-revision.md`：Word版本控制、局部修订和表述纠偏。
- `references/prompt-templates.md`：可复用提示词。
- `references/checklists.md`：提交前检查清单。
- `examples/anonymized-case.md`：由窄题调整为治理机制研究的脱敏案例。

## 设计原则

- 先核验证据，再写完整开题；
- 先修改研究问题，再修改标题；
- 区分研究方法与分析操作；
- 区分检索到、题录已核验、取得全文和核对原文；
- 单案例优先讨论机制、过程和边界，不轻易宣称因果；
- 外部发布、付费下载、覆盖文件和远程推送必须经过用户确认。

## 边界

该 Skill 不会：

- 编造参考文献或根据题名推断结论；
- 代替导师或学校的正式学术判断；
- 绕过数据库、版权或付费访问控制；
- 在没有证据识别的情况下宣称因果效果；
- 未经确认覆盖文件、发送材料或执行外部发布。

## 校验

可使用 Codex 的 Skill 校验脚本检查frontmatter和目录内容：

```bash
python /path/to/skill-creator/scripts/quick_validate.py ./paper-proposal-skill
```

## License

[MIT](LICENSE)
