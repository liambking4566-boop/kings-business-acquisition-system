# Kings Business Acquisition System

This system turns a rough business opportunity into a disciplined pilot. It is designed to avoid the common failure mode of buying stock, tools, or advertising before confirming demand, margin, and delivery capability.

## How to use it in GitHub

1. Create an issue using the **Business opportunity** form.
2. Ask the **Business Acquisition Orchestrator** to assess the issue and assemble the specialist roles needed.
3. Store each specialist brief as a comment, linked document, or pull request.
4. The orchestrator produces a single owner pack and requests approval at the relevant gate.
5. Keep pilot metrics and the final decision in the original issue. This becomes the reusable evidence base for future opportunities.

The agent definitions are in [`.github/agents`](../.github/agents). They are intentionally separate so a research task can be assigned to a focused role without losing the commercial decision framework.

GitHub is the coordination and audit trail: it holds the opportunity brief, team board, evidence, approvals, pilot results, and reusable SOPs. The files do not grant access to suppliers, payments, advertising accounts, warehouses, or delivery systems. Connect those tools only after the process and approval boundaries are working.

## Core decision formula

Only progress when all four conditions are credible:

```
Verified customer problem
× contribution margin after fulfilment and acquisition cost
× reliable supply and delivery
× manageable legal and operating risk
```

If any element is zero, the opportunity is a no-go until redesigned.

## Required owner approvals

The system can research and recommend. The owner must explicitly approve:

- sample orders, inventory, tools, advertising, contractors, or software spend;
- supplier contracts, customer terms, warranties, and delivery commitments;
- use of personal, company, customer, or payment data;
- any regulated construction, plumbing, electrical, import, or financial activity;
- launch and scale decisions.

## Pilot scorecard

Track these numbers weekly in the issue or connected dashboard:

| Area | Metric | Why it matters |
| --- | --- | --- |
| Demand | Qualified leads and paid validations | Signals real willingness to pay |
| Sales | Conversion rate and average order value | Tests the offer and sales process |
| Margin | Contribution dollars and margin percentage | Confirms the venture can fund itself |
| Delivery | On-time delivery and defect/return rate | Protects reputation and repeat purchase |
| Cash | Cash tied up and days to cash recovery | Prevents growth from creating a cash crunch |
| Repeatability | SOP completion and automation coverage | Shows whether the work can become an asset |

## Recommended first use case

Start with a productised service that fits the existing construction ecosystem, such as a landlord maintenance package, pre-sale property refresh, minor works subscription, or a practical construction template/product bundle. These can be sold and tested with lower stock risk than importing an unproven physical product.

## Performance improvement opportunities

The operating system can speed up commercial decisions without increasing risk. The ten strongest improvements are:

1. Add a fast-path triage step before forming the specialist team.
2. Require a one-page decision backlog instead of long open-ended research briefs.
3. Set a default research budget and hard stop-loss threshold for every role.
4. Force evidence-tier tagging for every claim to reduce wasted follow-up work.
5. Parallelise specialist research where dependencies allow instead of serialising low-value tasks.
6. Standardise the owner approval template to reduce back-and-forth clarification.
7. Run a margin gate before supplier and delivery analysis so weak economics are rejected early.
8. Split tasks into mandatory evidence vs optional stretch work to keep the work focused.
9. Add a "do not proceed" reason code for dead opportunities to shorten review cycles.
10. Track weekly operating metrics so the best-performing pilot patterns are reused instead of re-tested.

The highest-impact, lowest-effort improvement is the fast-path triage gate: it prevents needless specialist work on opportunities that fail basic customer, margin, and execution checks early.
