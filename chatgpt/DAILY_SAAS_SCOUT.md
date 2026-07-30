# Daily SaaS Scout

## Operating prompt

Research **exactly one** solo-SaaS opportunity today. The primary market is the United States; assess Indonesia only as a secondary expansion market when relevant.

**Business model scope:** B2B, B2B2C, and B2C are all allowed. Do not force every idea into B2B. Name the motion clearly (who pays, who uses, and whether an intermediary is involved).

Hold every motion to the same bar: real pain evidence, a credible willingness to pay, and a repeatable acquisition path. The evidence that satisfies that bar differs by motion. B2B and B2B2C usually turn on a named buyer, a budget, and a workflow. B2C usually turns on volume, retention, and acquisition cost versus lifetime value, so a B2C entry must address churn and CAC explicitly rather than assuming them away.

Use Google Trends and current, credible web sources. Inspect relevant GitHub projects to assess founder-market fit, technical feasibility, and build fit for one strong developer. Preserve source URLs and state collection dates.

Apply this consulting framework:

1. **Trend durability** — distinguish a durable demand shift from a short-lived spike.
2. **Customer and JTBD** — name the motion (B2B / B2B2C / B2C), the specific buyer (who pays), user (who uses), and job to be done. For B2B2C, name both the business partner and the end consumer.
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

1. Create a new agent-scoped journal file using the [trend journal template](templates/trend-journal.md):
   - ChatGPT / Codex → `trend-journal/YYYY-MM-DD-chatgpt.md`
   - Claude → `trend-journal/YYYY-MM-DD-claude.md`
   - Cursor → `trend-journal/YYYY-MM-DD-cursor.md`
   - Gemini Spark → `trend-journal/YYYY-MM-DD-gemini.md`
   Never overwrite another agent’s file. Never edit a different agent’s same-day journal. If your own agent-day file already exists, append an attributed section inside it.
2. Clearly distinguish **Verified evidence**, **Inference**, and **Assumptions** in the entry.
3. Attribute material changes with agent and date, and preserve earlier content in your file.
4. Promote an idea to `idea-grill/<slug>.md` only when the verdict is **Build** and the evidence is strong. Use the [idea grill template](templates/idea-grill.md).
5. Do not add application code, secrets, or credentials to this repository.

## Quality bar

Prefer a focused web app that can be built by one strong developer, offers a clear Stripe-backed purchase path (subscription, one-off, or usage), and solves a real workflow with a defendable wedge. B2B, B2B2C, and B2C are all in scope when the buyer, distribution, and willingness-to-pay story is credible. A concept without credible pain evidence, distribution, or falsifiable validation should remain **Watch** or be **Rejected**.

## Change log

- 2026-07-30 — Claude (Cowork): Opened business model scope to B2B, B2B2C, and B2C at the repo owner's direction. A concurrent edit by another agent made the same change; this merge keeps that agent's wording as the base and adds only the per-motion evidence note in the operating prompt and the B2B2C clarification in framework item 2. No other operating rules changed.
