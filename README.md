# allrize-idea

A durable venture journal for finding, testing, and shaping simple solo-SaaS opportunities.

The primary market is the United States. Indonesia is a secondary expansion market when the customer, distribution channel, or product economics make it relevant.

## Navigate

- [ChatGPT / Codex operating space](chatgpt/README.md)
- [Claude operating space](claude/README.md)
- [Gemini Spark operating space](gemini-spark/README.md)
- [Cursor / Grok operating space](cursor-grok/README.md)
- [Daily trend journal](trend-journal/README.md)
- [Promoted ideas](idea-grill/README.md)

## Journal rules

- Daily trend and demand research lives in `trend-journal/YYYY-MM-DD-<agent>.md` (one file per agent per day).
  - ChatGPT/Codex → `…-chatgpt.md`
  - Claude → `…-claude.md`
  - Cursor → `…-cursor.md`
  - Gemini Spark → `…-gemini.md`
- Agents must not edit another agent’s journal file for the same day.
- Promoted, validated ideas live in `idea-grill/<slug>.md`.
- ChatGPT, Codex, Claude, Cursor, and Gemini may contribute. Preserve prior entries, append or create new agent-scoped files rather than rewriting history, and attribute every material change with the contributing agent and date.
- Every entry must separate **Verified evidence**, **Inference**, and **Assumptions**.
- Favor simple web apps that one strong developer can build, monetize through Stripe, and distribute clearly. Avoid generic AI wrappers; AI must serve a specific workflow advantage.
- **Customer type is open: B2B, B2B2C, and B2C are all in scope.** No customer type is preferred or excluded by default. Every entry must state which type it is, and B2B2C entries must say which side pays. The evidence bar is the same for all three, but B2C entries must address churn and customer acquisition cost explicitly rather than assuming them away.

## Change log

- 2026-07-30 — Claude (Cowork): Opened customer type to B2B, B2B2C, and B2C at the repo owner's direction. Added the rule above, updated `chatgpt/DAILY_SAAS_SCOUT.md`, and added a **Customer type** field to both templates. No journal entries were edited and no other rule changed.

## Contribution flow

1. Research one opportunity and save the dated evidence in **your** agent-scoped trend journal file.
2. Apply the scout framework and make a Build, Watch, or Reject decision.
3. Promote only strong, evidence-backed Build candidates to the idea grill.
4. Keep source links, evidence labels, and attribution intact as the journal evolves.
