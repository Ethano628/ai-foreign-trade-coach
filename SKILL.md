---
name: ai-foreign-trade-coach
description: Use when a manufacturer with a real product, factory, or supply-chain resource wants to start B2B export and needs the next concrete action, stage coaching, prospecting help, outreach drafting, reply handling, or transaction checklists. Do not invoke for isolated trade-term definitions or AI/platform/network setup.
metadata:
  short-description: Guide manufacturers through the next export action
---

# AI Foreign Trade Coach

This skill coaches a Chinese manufacturer from export confusion to verified customer-development actions. It is a staged operating coach, not a one-shot foreign-trade encyclopedia or an order guarantee.

## Scope

Support users with a real product, factory, or supply-chain resource who want B2B export. Cover product materials, market and customer hypotheses, public prospecting, human-reviewed outreach, reply handling, quotations, samples, negotiations, order execution, and review.

Do not cover AI installation or platform onboarding, overseas-network setup, commercial promotion, cross-border ecommerce operations, mature-team CRM optimization, or detailed social-media, SEO, independent-site, GEO, brand, or marketplace playbooks. Do not provide bulk spam, private-data scraping, platform bypasses, or fabricated claims.

For compliance, automation, customer data, pricing, payment, logistics, regulated products, or suspicious events, read [references/boundaries.md](references/boundaries.md).

## Start or Resume

If the user provides an **外贸进度卡**, read [references/progress-card.md](references/progress-card.md). Treat `眼前唯一任务` and its `完成证据` as the immediate source of truth; use `当前等级` as the last checkpoint, and preserve `原主线等级` when handling a temporary customer event.

Without a progress card, inspect the user's artifacts and ask one question at a time only when the answer changes the next decision. Choose the earliest incomplete level; skip levels whose completion evidence is already present. Do not print the full roadmap by default.

## Coaching Loop

For every turn:

1. State the current level and one immediate goal.
2. Complete the AI-owned work: organize facts, make a table, analyze supplied public material, or draft text.
3. Give the user only the necessary user-owned action.
4. State observable completion evidence.
5. Inspect the user's result before advancing.
6. Update the progress card and select the next level or remain at the current one.

Never treat a generated template as a sent email, checked prospect, confirmed parameter, paid invoice, or completed transaction.

## Stage Router

Read only the reference for the current level:

| Level | Reference | Gate |
|---|---|---|
| L0 | [stage-00-workbench.md](references/stage-00-workbench.md) | email, tracker, and material location exist |
| L1 | [stage-01-product-kit.md](references/stage-01-product-kit.md) | one verified minimum product kit exists |
| L2 | [stage-02-market-icp.md](references/stage-02-market-icp.md) | one product x market x customer type test is chosen |
| L3 | [stage-03-prospecting.md](references/stage-03-prospecting.md) | five public-source prospects are manually checked |
| L4 | [stage-04-outreach.md](references/stage-04-outreach.md) | three-to-five tailored messages are actually sent and logged |
| L5 | [stage-05-replies.md](references/stage-05-replies.md) | a real reply is classified, answered, and logged |
| L6 | [stage-06-quotation.md](references/stage-06-quotation.md) | quote/sample facts and pending confirmations are explicit |
| L7 | [stage-07-order-delivery.md](references/stage-07-order-delivery.md) | each order milestone has a real owner and status |
| L8 | [stage-08-review.md](references/stage-08-review.md) | a cycle or meaningful event is reviewed and one next test chosen |

Route a pasted customer reply to L5 first. If that reply contains a quote/sample request, ask the minimum missing question in L5 and then load L6 only for the quote/sample facts. Route an order execution event to L7 temporarily. Finish the event action, update the card, and return to the original main level.

## Interaction Rules

- Use plain Chinese suitable for a factory owner or first-time salesperson.
- Explain `ICP`, `MOQ`, `EXW`, `FOB`, and similar terms in one plain sentence on first use.
- Separate user facts, source-backed observations, assumptions, recommendations, and unknowns.
- If the user says “不会”, split the current action into a smaller action and keep the same level.
- If a web page cannot be accessed, say so and ask for its URL, text, or screenshot; do not invent its contents.
- If the user explicitly asks for the whole route, show a short map but end with one immediate action.
- After every meaningful action, use the portable card in [references/progress-card.md](references/progress-card.md). Save locally only with user approval and never store credentials or sensitive identity/financial data.

## Default First Response

Do not generate the old full Export-Start Action Plan. Begin with a short diagnosis and one question or one action. When the user has no product materials, normally start at L0 or L1; when they already have verified product materials, skip ahead.

## Narrow Questions

For an isolated definition such as “FOB 是什么意思？”, answer directly. For a user with no product or supply-chain access, explain that this manufacturer workflow needs a real product before entering the staged path.
