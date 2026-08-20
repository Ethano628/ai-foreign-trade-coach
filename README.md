# AI Foreign Trade Coach

An open-source AI skill that helps manufacturers start B2B export business from 0 to 1.

## What it does

This skill helps a user who has a factory, product, or supply-chain resource but little foreign-trade experience turn a vague export idea into an actionable export-start plan.

It is designed for questions like:

> “We manufacture stainless steel bottles. We have only sold domestically before, and now we want to start exporting. Where should we begin?”

The skill guides the user through:

- Product and business diagnosis
- Export readiness assessment
- Priority market selection
- ICP customer profiles
- Buyer-facing value proposition
- Competitor and market research
- Customer-development channels
- Prospect search and screening
- First outreach and follow-up
- Quotation, sample, payment, logistics, and review notes
- A 30-day action plan

## V1 scope

V1 focuses on the **manufacturer-to-export** workflow.

It is not a foreign-trade encyclopedia, CRM, lead database, customs-data tool, or automated email sender.

Completion means the user can begin the first batch of qualified prospecting and outreach. It does not guarantee inquiries, orders, or revenue.

## Files

```text
ai-foreign-trade-coach/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── boundaries.md
    ├── manufacturer-playbook.md
    └── output-templates.md
```

## Safety boundaries

This skill supports human-reviewed B2B export planning. It does not:

- Guarantee orders or business results
- Fabricate customer information, purchase intent, certifications, or verified contacts
- Replace legal, tax, customs, sanctions, or regulated-product advice
- Support automated bulk sending, spam, impersonation, or platform-rule bypassing

## 中文说明

这是一个开源 AI Skill，目标是帮助“有产品 / 有工厂 / 有供应链，但不懂外贸”的用户，从 0 开始生成一份可执行的《外贸启动作战方案》。

V1 聚焦中国工厂从内贸或代工思维走向 B2B 外贸获客，不追求覆盖所有外贸知识，也不承诺拿到订单。它更像一个 AI 外贸启动教练：先帮用户判断产品、市场、客户画像、渠道、开发信和 30 天行动计划。
