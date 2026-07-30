# Daily SaaS Scout

## Operating prompt

Research **exactly one** solo-SaaS opportunity today. The primary market is the United States; assess Indonesia only as a secondary expansion market when relevant.

Use Google Trends and current, credible web sources. Inspect relevant GitHub projects to assess founder-market fit, technical feasibility, and build fit for one strong developer. Preserve source URLs and state collection dates.

Apply this consulting framework:

1. **Trend durability** — distinguish a durable demand shift from a short-lived spike.
2. **Customer and JTBD** — name the specific buyer, user, and job to be done.
3. **Pain evidence** — cite observable complaints, workarounds, spend, or urgency.
4. **Alternatives** — map incumbent tools, manual workarounds, and their gaps.
5. **Wedge** — define the narrow initial use case and why it can win.
6. **MVP** — specify the smallest Stripe-monetizable web app a strong solo developer can ship.
7. **AI role** — explain the workflow-specific advantage; reject generic AI-wrapper concepts.
8. **Pricing** — propose a credible willingness-to-pay hypothesis and packaging.
9. **Distribution** — identify the first repeatable acquisition path.
10. **Risks** — cover market, product, technical, legal, and go-to-market risks.
11. **Kill criteria** — define evidence that should stop the idea.
12. **Verdict** — choose **Build**, **Watch**, or **Reject**.

## Required output

1. Create a new `trend-journal/YYYY-MM-DD.md` entry using the [trend journal template](templates/trend-journal.md). Never overwrite an existing daily journal; if a same-day entry exists, create an additive, clearly attributed supplement.
2. Clearly distinguish **Verified evidence**, **Inference**, and **Assumptions** in the entry.
3. Attribute material changes with agent and date, and preserve earlier content.
4. Promote an idea to `idea-grill/<slug>.md` only when the verdict is **Build** and the evidence is strong. Use the [idea grill template](templates/idea-grill.md).
5. Do not add application code, secrets, or credentials to this repository.

## Quality bar

Prefer a focused web app that can be built by one strong developer, offers a clear Stripe-backed purchase path, and solves a real workflow with a defendable wedge. A concept without credible pain evidence, distribution, or falsifiable validation should remain **Watch** or be **Rejected**.
