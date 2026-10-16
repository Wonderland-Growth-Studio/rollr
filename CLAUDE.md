# Rollr

## Shopify

The `shopify-rollr` MCP server (in `.mcp.json`) is for the **Rollr** Shopify store only.
Use its tools (`mcp__shopify-rollr__*`) for Rollr store data. Before you write anything to
the store, call `get-shop-info` and check that it's connected to Rollr.

Ignore the account-level Shopify connector (`mcp__Shopify__*`) in this repo; it's
connected to a different store.

The server picks the store from whoever signs in. To connect it, run `/mcp`, choose
`shopify-rollr`, and sign in with the Rollr store.

## Meta Ads

The Rollr ad account is "bare bod 1's ad account" (`1360973291931355`, owned by the Rollr
business). Its creative source files are indexed in `michaelwonderland/brandassetsextractionsystem`
under `brands/rollr/`, with per-second timelines and transcripts for each video.

### Reading performance: spend is the signal (the breakdown effect)

Meta allocates budget by expected *marginal* cost, not by the average CPA you see in the
report. An ad with a low CPA on little spend has only bought the cheapest early impressions;
its CPA would rise if it got more budget. So:

- Treat spend at scale as the main proxy for creative quality. Low CPA on low spend means
  nothing on its own; only results at scale count.
- Don't compare average CPA across ads in the same ad set or campaign and call the cheaper
  one the winner.
- When variants share an ad set (e.g. hook tests), Meta's spend split *is* the test result.
  Don't call it "not a real test", and don't recommend forced budget splits or separate
  ad sets to "test it properly".
- Compare spend velocity (spend per day since launch), not just period totals, so ads that
  have been live longer aren't overrated.
- ROAS still decides whether scale is profitable: an ad can win Meta's allocation and still
  run below target.
