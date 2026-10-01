# AI 痕迹检测与降 AI 味

> AI 率自检→不达标自动改写→敏感词扫描→过检出稿

工作流 `wf-creator-script-ai-gate`　·　归属 短视频脚本创作师　·　触发 事件（交付前强制闸门）　·　
复杂度 M　·　阶段 P0

## 调用链

- `平台合规词扫描`（compliance-word-scan）
- `口语化改写`（colloquial-rewrite）

## 文档

- [`WORKFLOW.md`](WORKFLOW.md) — 完整编排、闸门、降级与验收标准
- [`tests/cases.yaml`](tests/cases.yaml) — 端到端 / 闸门 / 降级用例

## 一句话试用

```text
帮我跑 短视频脚本创作师 的「AI 痕迹检测与降 AI 味」：<你的输入>
```
