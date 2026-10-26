# Rollr

## Shopify

The `shopify-rollr` MCP server (in `.mcp.json`) is for the **Rollr** Shopify store only.
Use its tools (`mcp__shopify-rollr__*`) for Rollr store data. Before you write anything to
the store, call `get-shop-info` and check that it's connected to Rollr.

Ignore the account-level Shopify connector (`mcp__Shopify__*`) in this repo; it's
connected to a different store.

The server picks the store from whoever signs in. To connect it, run `/mcp`, choose
`shopify-rollr`, and sign in with the Rollr store.

## Trybe

The `trybe-rollr` MCP server (in `.mcp.json`) is for the **Rollr** Trybe brand only.
Use its tools (`mcp__trybe-rollr__*`) for Rollr creators, submissions and creator
performance. Start each session with `get_brand_context` and check that it reports
Rollr before you approve or reject submissions or message creators.

Ignore the account-level Trybe connector (`mcp__Trybe__*`) in this repo; it may be
pinned to a different brand.

Trybe pins each connection to the brand you sign in with. To connect it, run `/mcp`,
choose `trybe-rollr`, and sign in with your own Trybe login for Rollr.
