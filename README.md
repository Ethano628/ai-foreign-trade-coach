# AI Foreign Trade Coach

An open-source AI skill for manufacturers who have a real product or factory resource and need to start B2B export one concrete step at a time.

## What changed

This is a staged operating coach, not a one-shot 30-day plan. It first identifies the earliest incomplete level, completes AI-owned work, gives the user one action, checks observable evidence, and updates an **外贸进度卡** before advancing.

```text
L0 工作台
 -> L1 产品资料包
 -> L2 市场与客户画像
 -> L3 五家潜客试样
 -> L4 定制开发信
 -> L5 回复与跟进
 -> L6 报价/样品/谈判
 -> L7 订单/物流/单证
 -> L8 数据复盘
```

When a real customer reply, quote request, or order event appears, the coach temporarily handles that event and then returns to the original main level.

## Target user

Chinese factory owners or factory salespeople with a product, production capability, or supply-chain access, but little experience developing overseas B2B customers.

## Explicit non-goals

The skill does not teach AI installation, platform onboarding, overseas-network setup, or commercial services. It does not provide automated bulk outreach, private-data scraping, platform bypasses, fabricated customer information, or certainty about orders, taxes, customs, sanctions, or regulated products. It does not attempt to be a complete social-media, SEO, independent-site, GEO, brand, or marketplace operations manual.

## Files

```text
ai-foreign-trade-coach/
├── SKILL.md
├── agents/openai.yaml
├── tests/behavior-cases.md
└── references/
    ├── stage-00-workbench.md
    ├── stage-01-product-kit.md
    ├── stage-02-market-icp.md
    ├── stage-03-prospecting.md
    ├── stage-04-outreach.md
    ├── stage-05-replies.md
    ├── stage-06-quotation.md
    ├── stage-07-order-delivery.md
    ├── stage-08-review.md
    ├── progress-card.md
    └── boundaries.md
```

`manufacturer-playbook.md` and `output-templates.md` remain as compatibility routers for earlier callers. They no longer contain a full one-shot output template.

## Completion boundary

The first milestone is that the user has prepared real product material, checked a small batch of real prospects, and sent the first manually reviewed outreach messages. This does not guarantee replies, orders, or revenue.

## 中文说明

这是一个给中国工厂使用的阶梯式 AI 外贸教练。它不再一上来输出一份大而全的方案，而是从当前缺口开始，每次只带用户完成一个外贸动作，用真实完成证据决定下一步，并通过《外贸进度卡》跨对话继续。
