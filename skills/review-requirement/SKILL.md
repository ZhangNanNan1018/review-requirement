---
name: review-requirement
description: Review, correct, and refine requirements before implementation. Use when asked to analyze a requirement first or hold off on building. 用于先审需求、纠正错误假设和补全遗漏，暂不实施。
---

# Requirement Review · 需求评审

Reply in the language of the user's request by default. Follow any explicit language preference.
默认用用户提出需求时的语言回答。用户指定语言时，以指定语言为准。

## English

- Identify the user's intended outcome. Flag incorrect premises, contradictions, ambiguous wording, and omissions that could affect the result. Inspect relevant context read-only as needed, explain the basis for corrections, and label unverified assumptions.
- Give your assessment in chat and include a revised requirement the user can reuse. Preserve their goal and stated constraints. Add scope boundaries, edge cases, and observable acceptance criteria where they matter. Leave decisions that belong to the user open.
- When information is missing, give a provisional assessment based on what you know. Ask only questions whose answers would materially change the goal, scope, or acceptance criteria.
- Keep the review read-only and the output in chat. Begin implementation only when the user explicitly asks you to proceed.

## 中文

- 明确用户想达成的结果，指出会影响结果的错误前提、矛盾、歧义和关键遗漏。需要核实时，只读查阅相关上下文，说明纠正依据，并标出有待验证的假设。
- 在聊天里给出评审结论和一版可直接使用的需求改写。保留用户的目标和已明确的约束，按需补充范围、边界情况和可观察的验收标准。需要用户决定的事项留作待确认。
- 信息不足时，先给出已有证据支持的初步分析。只追问会实质改变目标、范围或验收标准的问题。
- 评审阶段保持只读，输出留在聊天中。收到用户明确的实施指令后，再进入实施。
