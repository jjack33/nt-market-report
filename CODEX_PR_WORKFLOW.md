# Codex PR Workflow

Changes to this public Morning Market Report repository must be submitted through pull requests.

The authoritative bridge instructions are maintained in:

https://github.com/jjack33/ninjatrader-replay-automation/blob/codex/replay-automation/docs/CODEX_CHATGPT_PR_REVIEW_BRIDGE.md

Required rules:

- Base branch: `main`
- Do not push generated report changes directly to `main`.
- Cross-link the source PR from `jjack33/ninjatrader-replay-automation`.
- Post one SHA-bound `[CODEX-HANDOFF]` comment after validation.
- Wait for `[CHATGPT-REVIEW]`.
- Merge automatically only after `PASS`, only when the reviewed SHA is still current, and only when no trade-semantic or indicator-behavior change exists.
- Never publish credentials, accounts, balances, positions, orders, local machine paths, or unrelated images.
- Never label script-generated scenarios as ChatGPT.
