# Daily SaaS Scout

## Operating prompt

Research **exactly one** solo-SaaS opportunity today. The primary market is the United States; assess Indonesia only as a secondary expansion market when relevant.

**Customer type is open.** B2B, B2B2C, and B2C are all in scope. Do not reject an opportunity because it sells to consumers, and do not favour a business buyer by default. Pick whichever customer type the evidence actually supports, then hold it to the same bar: real pain evidence, a credible willingness to pay, and a repeatable acquisition path. Note that the evidence you need differs by type. B2B and B2B2C usually turn on a named buyer, a budget, and a workflow. B2C usually turns on volume, retention, and cost of acquisition versus lifetime value, so a B2C entry must address churn and CAC explicitly rather than assuming them away.

Use Google Trends and current, credible web sources. Inspect relevant GitHub projects to assess founder-market fit, technical feasibility, and build fit for one strong developer. Preserve source URLs and state collection dates.

Apply this consulting framework:

1. **Trend durability** — distinguish a durable demand shift from a short-lived spike.
2. **Customer and JTBD** — state the customer type (B2B, B2B2C, or B2C) and name the specific buyer, user, and job to be done. For B2B2C, name both the business partner and the end consumer, and say which one is paying.
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

Prefer a focused web app that can be built by one strong developer, offers a clear Stripe-backed purchase path, and solves a real workflow with a defendable wedge. This applies equally to B2B, B2B2C, and B2C. A concept without credible pain evidence, distribution, or falsifiable validation should remain **Watch** or be **Rejected**, whoever the customer is.

## Change log

- 2026-07-30 — Claude (Cowork): Opened customer type to B2B, B2B2C, and B2C at the repo owner's direction. Added the customer-type rule to the operating prompt, extended framework item 2 to require naming the customer type, and made the quality bar explicitly type-neutral. No other operating rules changed.
