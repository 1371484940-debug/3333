---
name: write-requirement-doc
description: Write professional Chinese product requirement documents and requirement specifications according to the user's provided PRD template. Use when the user asks to write, polish, structure, supplement, or review a requirement document, feature requirement, business requirement, functional rule, product plan, or demand analysis in Chinese, especially for education/training/course/exam platform features.
---

# Requirement Document Writing

Use this skill to produce Chinese requirement documents that follow the user's template standard.

## Core Workflow

1. Identify the requirement type before writing:
   - 页面字段新增/字段调整
   - 流程型需求
   - 多状态/多场景规则型需求
   - 列表管理型需求
   - 数据统计型需求
   - 页面展示型需求
   - 权限/审核/申诉/配置类需求
2. Build the document around one clear main requirement. Split it into functional points by business sequence; if there is no sequence, order by priority.
3. For each main requirement, write:
   - 需求背景: current state, pain point, missing capability, affected role/scenario.
   - 需求目标: intended business result and user value.
   - 业务流程: include only when the process matters.
   - 详细需求说明: function path, rules, field/table/status/query/action constraints.
4. Before functional rules, always state the function path, for example: `功能路径：管理端-考试管理-成绩申诉`.
5. Write rules in the order users or systems encounter them: page display first, then operation entry, validation, state change, result feedback, notifications, records/statistics.
6. Prefer tables for structured constraints: fields, permissions, statuses, query conditions, list columns, editability, operation buttons, statistics formulas.
7. Use precise product language. Avoid vague words like "支持一下", "优化", "相关", "等等" unless followed by explicit scope and rules.
8. If source information is incomplete, fill reasonable product assumptions and mark them as `待业务确认` instead of blocking the draft.

## Template Reference

When writing a full requirement document or detailed functional rules, read `references/template-standard.md`.

## Output Style

- Write in Simplified Chinese.
- Keep numbering hierarchical and stable: `1`, `1.1`, `1.1.1`.
- Use "规则如下：" before numbered rule lists.
- Use full-width Chinese punctuation in prose.
- Use tables when the template standard calls for them.
- Include a final `待确认问题` section when business policy, thresholds, roles, deadlines, or exception handling are uncertain.
