# banxia1992-skill

一个用于学习半夏1992风格决策流程的 Codex skill：先诊断短线市场风格，再核验主线、低位接力、补涨或题材切换，最后形成带触发、失效和风险边界的观察预案。

它整理的是可复用的决策流程，不是模型微调、收益承诺、实时观点或自动交易策略。

## 文件

- `SKILL.md`：技能入口、任务路由和共同决策约束。
- `references/style-and-setups.md`：风格适配、补涨与切换的判断方法。
- `references/risk-and-execution.md`：行情证据、交易限制和仓位风险。
- `references/review-and-practice.md`：案例复盘与练习流程。
- `references/source-map.md`：证据分层和冲突处理。
- `references/casebook.md`：公开版案例材料说明。
- `agents/openai.yaml`：Codex skill 展示信息。

## 安装

将仓库克隆或下载到 Codex skills 目录，确保目录名为 `banxia1992-skill`：

```text
<CODEX_HOME>/skills/banxia1992-skill/
```

也可以把该目录放入当前 Codex 可发现的 skills 路径。重新加载或重新启动 Codex 后，使用 `$banxia1992-skill` 调用。具体目录取决于本机 Codex 配置。

## 公开内容边界

本仓库有意不包含原始实盘截图、OCR语料、账户流水和详细历史案例，因为这些材料可能显示个人财务与持仓信息。需要核验某个历史案例时，须在私有环境中另行提供原图或一手来源；不能用OCR或二手转述冒充原图核验。

技能要求遵守适用交易制度，明确区分事实、推断和预案参数，不编造胜率或成交情况。分析不授权下单。
