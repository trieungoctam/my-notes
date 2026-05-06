---
type: concept
title: "valuation-metrics"
date: 2026-05-06
last_updated: 2026-05-06
sources: [summaries/Running Lean, 3rd Edition  Iterate from Plan A to a Plan That Works Ash Maurya z-library.sk, 1lib.sk, z-lib.sk-A-Bonus-Material.md]
brief: Numbers used to judge whether a business model can create value.
citations: [{"book": "Running Lean, 3rd Edition", "pages": "133-178", "chapter": "Chapter 3. Stress Test Your Idea for Viability", "perspective": "Valuation is grounded in Fermi estimates, ARPU, churn, and required customer counts"}, {"book": "Running Lean, 3rd Edition", "pages": "229-237", "chapter": "Part II. Validation", "perspective": "Metrics should be actionable, cohort-based, and tied to customer behavior rather than vanity counts"}, {"book": "Running Lean, 3rd Edition", "pages": "424-439", "chapter": "Chapter 12. Get Ready to Launch", "perspective": "Launch metrics should show repeatable traction, not just raw product activity"}]
tags: ["startups", "metrics", "valuation", "viability", "business-model"]
understanding_level: unreviewed
last_reviewed: null
review_count: 0
---

# Valuation Metrics

Valuation metrics are the numbers used to judge whether a business model can become economically meaningful. In *Running Lean*, they are not framed as abstract finance-only indicators, but as the practical signals that tell you whether your idea can support a real company before you invest too much time and money.

These metrics sit at the center of [[concepts/traction]], [[concepts/viability]], and the [[concepts/customer-factory]] model. They answer questions like:

- How many customers do we need?
- What is each customer worth over time?
- How fast are customers leaving?
- Can the model sustain growth and cash flow?

## What Valuation Metrics Do

Maurya uses valuation metrics to stress test whether a startup can plausibly reach its [[concepts/minimum-success-criteria]] within a chosen time horizon. The key point is that valuation is not just about an eventual exit number; it is about whether the business model can produce enough recurring value to justify continued effort.

The book emphasizes a small set of metrics that make the business model legible:

- **ARR / revenue target**: the minimum success threshold for the business
- **ARPU / pricing**: how much value is captured per customer
- **Customer lifetime / churn**: how long customers stay
- **Active customer count**: how many paying customers are needed
- **Conversion rates**: how many leads become trials and trials become customers
- **LTV / CAC**: whether customer value exceeds acquisition cost

These metrics are used together, not in isolation. A high revenue target with weak pricing or high churn can still make the model impossible.

## How the Book Uses Valuation Metrics

In the viability chapter, the book uses a Fermi estimate to test Steve's AR/VR business model. The logic is bottom-up:

1. Set a minimum success criteria such as $10M ARR in 3 years.
2. Estimate pricing and customer lifetime.
3. Calculate how many active customers are required.
4. Estimate churn and the number of new customers needed just to hold steady.
5. Estimate leads required based on conversion rates.
6. Check whether the model is realistic.

This makes valuation a practical design tool rather than a post-hoc finance exercise.

For example, Steve's model breaks down when he sees that:

- low pricing means too many customers are required,
- churn forces constant replacement of lost customers,
- weak conversion rates require massive lead volume.

That failure exposes valuation metrics as a way to identify the real bottleneck in the model.

## Actionable vs. Vanity Metrics

A major theme in the book is that not all metrics are equally useful. Maurya strongly favors **actionable metrics** over vanity metrics.

### Vanity metrics
These look good but do not help you make decisions. Examples include:

- total sign-ups ever
- total page views
- cumulative counts that can only go up

### Actionable metrics
These connect actions to results and help reveal causality. Examples include:

- trial-to-paid conversion rate
- customer retention rate
- monthly churn
- referral rate
- cohort-based activation

This is why valuation metrics must be tied to the [[concepts/customer-factory]] rather than just surface-level growth.

## The Customer Factory Lens

Maurya's customer factory model is a way to turn valuation into a system:

- **Acquisition** brings in leads
- **Activation** creates first value
- **Retention** keeps customers engaged
- **Revenue** captures monetizable value
- **Referral** feeds new acquisition

Valuation metrics help answer whether that factory can output enough economic value to support the business. In other words, valuation metrics tell you whether the factory is worth building and whether it can scale.

## Important Implications

### 1. Valuation is tied to pricing
Price is part of the product. It is also a signal about who the customer is and how much value they expect to receive. The book repeatedly argues that pricing should be anchored against existing alternatives and the value promised by the [[concepts/unique-value-proposition]].

### 2. Valuation is tied to retention
If customers leave too quickly, valuation collapses. Even a strong acquisition engine cannot rescue a model with poor retention.

### 3. Valuation is tied to unit economics
The model must eventually satisfy conditions like:

- **LTV > CAC**
- **CAC payback period is short enough**

These are not just investor metrics; they are indicators that the model can survive.

### 4. Valuation is stage-dependent
Early on, the goal is not to maximize valuation on paper. The goal is to prove that a viable business model exists. Later, once traction is repeatable, valuation metrics become more meaningful for scaling and fundraising.

## Why This Matters

Valuation metrics force a founder to face the hard question: **Can this business become large enough to matter, and can it do so in time?**

This is one of the main reasons *Running Lean* insists on quantitative stress testing before building. The numbers reveal whether the idea is merely interesting or economically workable.

## Related Concepts

- [[concepts/traction]]
- [[concepts/viability]]
- [[concepts/customer-factory]]
- [[concepts/minimum-success-criteria]]
- [[concepts/lean-canvas]]
- [[concepts/churn]]
- [[concepts/arpu]]
- [[concepts/ltv-cac]]
- [[summaries/Running Lean, 3rd Edition  Iterate from Plan A to a Plan That Works Ash Maurya z-library.sk, 1lib.sk, z-lib.sk-A-Bonus-Material]]

## Sources & Perspectives

- **Running Lean, 3rd Edition - Chapter 3, pages 133-178**
  - Presents valuation through the lens of viability testing. The book uses Fermi estimates, pricing, churn, and required customer counts to decide whether a model can realistically hit its minimum success criteria.

- **Running Lean, 3rd Edition - Part II / validation sections, pages 229-237**
  - Frames valuation-related metrics as actionable measures inside a customer factory, emphasizing cohort behavior and real customer actions over vanity numbers.

- **Running Lean, 3rd Edition - Chapter 12, pages 424-439**
  - Reuses valuation metrics during launch planning to make sure the MVP supports repeatable traction, not just initial excitement or activity.


<!-- openkb-deep-study-start -->
> [!tip]- ELI5
> Valuation metrics are the numbers that tell you if a business idea can become big enough to be worth the effort. They help you check if customers will pay enough, stay long enough, and come in fast enough for the business to work.

> [!tip]- Real-World Analogy
> It's like checking whether a restaurant can stay open: you need enough customers, enough spending per customer, and low enough waste to cover rent, staff, and ingredients. If the math doesn't work, the restaurant is a bad bet even if the food is great.

> [!warning]- Common Misconceptions
> Myth: Valuation metrics are only for investors. Reality: founders need them early to decide whether the business model is worth pursuing.
> Myth: More sign-ups always means a better business. Reality: sign-ups are meaningless if customers do not pay, stay, or refer others.
> Myth: Revenue forecasts are enough. Reality: valuation depends on pricing, churn, conversion, and unit economics working together.

> [!question]- Check Your Understanding
> {'Q': 'Why does the book treat pricing as part of valuation rather than a separate marketing decision?', 'A': 'Because price determines how much value you capture per customer and also shapes which customers you attract.'}
> {'Q': 'What is the difference between a vanity metric and an actionable valuation metric?', 'A': 'A vanity metric looks impressive but does not guide decisions; an actionable metric helps reveal what is really happening in the business model.'}
> {'Q': 'Why can high acquisition still fail to produce a viable business?', 'A': 'Because if churn is high or price is too low, the business may need an impossible number of new customers just to stay afloat.'}
> {'Q': 'How does the customer factory help evaluate valuation metrics?', 'A': 'It shows the full flow from acquisition to revenue and referral, making it easier to see whether the model can generate enough value sustainably.'}
> {'Q': 'What does a Fermi estimate contribute to valuation thinking?', 'A': 'It gives a rough but useful bottom-up check on whether the model can hit its success target with realistic assumptions.'}

> [!info]- Why It Matters
> Valuation metrics keep founders from mistaking enthusiasm for a viable business. They show whether the model can actually produce enough economic value to justify more time, hiring, and investment.
<!-- openkb-deep-study-end -->