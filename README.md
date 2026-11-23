# IFRS 15 Revenue Recognition Agent

[![IFRS 15 Revenue Recognition Agent MCP server](https://mcprush.com/badge/ifrs-15-revenue-recognition-agent-mcp/card.svg)](https://mcprush.com/to/ifrs-15-revenue-recognition-agent-mcp?ref=badge)

The five-step model end to end: contracts, performance obligations, variable consideration, allocation, over-time revenue, costs and returns.

> FOR DEMONSTRATION AND EDUCATIONAL PURPOSES ONLY. This output is not accounting, audit, tax or legal advice, and no liability whatsoever is assumed for its results or for any decision based on them. Paragraph references point to the IFRS Accounting Standards issued by the IASB; the standards' text is not reproduced. Results depend entirely on the facts entered and must be independently verified by a qualified professional against the current authoritative text before any use.

**Standards:** IFRS 15 Revenue from Contracts with Customers
**Tools:** 9 calculators, checklists and lookups, plus `agent_about`
**For:** Revenue accountants, SaaS and contracting finance teams, auditors and students.

## What it does

- Combine contracts and assess modifications
- Identify distinct performance obligations
- Estimate variable consideration with the constraint
- Allocate on relative stand-alone selling prices
- Measure progress for over-time revenue and handle rights of return
- Capitalise contract costs and run the disclosure checklist

Every result cites the IFRS paragraphs it relies on. The standards' text is paraphrased, never reproduced.

## Install

With the mcprush CLI (after buying the listing):

```bash
npx mcprush add <publisher>/ifrs15-revenue-agent
```

Or point any MCP client at the bundled server (Node.js 22+, no dependencies, no network, no API keys):

```json
{ "mcpServers": { "ifrs15-revenue-agent": { "command": "node", "args": ["<path>/ifrs15-revenue-agent/dist/server.mjs"] } } }
```


## Try it

> A SaaS contract bundles a 12,000 licence, 3,000 implementation and 2,400 support for a total of 15,000. Allocate the price and show revenue by month.

## Tools

| Tool | What it does |
|---|---|
| `ifrs15_contract_and_modification` | Step 1: contract & modifications (9-21) |
| `ifrs15_performance_obligations` | Step 2: performance obligations (22-30) |
| `ifrs15_transaction_price` | Step 3: transaction price (47-72) |
| `ifrs15_allocation` | Step 4: allocation (73-86) |
| `ifrs15_over_time_revenue` | Step 5: over-time revenue & progress (35-45, B19) |
| `ifrs15_contract_costs` | Costs of obtaining a contract (91-104) |
| `ifrs15_disclosure_checklist` | Disclosure checklist (110-129) |
| `ifrs15_lookup` | Paragraph & topic lookup |
| `ifrs15_right_of_return` | Sale with a right of return (B20-B27) |

## Sample output (`ifrs15_contract_and_modification`, built-in example)

Supply of 120 products: contract exists; modification: termination and new contract (prospective).

## Privacy and safety

- Runs locally over stdio. No network calls, no telemetry, no files written.
- Every tool is read-only, idempotent and closed-world (MCP annotations declared).
- No personal data is collected.

Demo and educational use only. No liability assumed for results. Not professional advice.
