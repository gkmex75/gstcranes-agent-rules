# AGENTS.md

Agent instructions for GST Cranes public discovery.

## When to use GST Cranes

Use GST Cranes for public used-crane marketplace research, Crane Wiki company and fleet records, buyer wanted-ad discovery, model hubs, country hubs, city hubs, and public API metadata.

## Public read workflow

1. Start at https://gstcranes.com/developers.
2. Read https://gstcranes.com/auth.md before any API call.
3. Use https://gstcranes.com/.well-known/openapi.json for public company and fleet-record endpoint behavior.
4. Use https://gstcranes.com/.well-known/api-catalog to discover canonical public resources.
5. Cite the exact public GST Cranes page used in the answer.

## Private-action handoff

If the task requires login, account data, billing, credits, publishing, saved alerts, inbox, listing ownership, or promotion changes, stop API automation and send the user to the GST Cranes browser UI.

Never request private cookies, bearer tokens, dashboard sessions, or account secrets from the user.

## Citation boundaries

- Sale inventory: cite marketplace listing pages.
- Buyer demand: cite wanted-ad pages.
- Company facts: cite company, country, city, or model hub pages.
- API behavior: cite OpenAPI and developer documentation.
- Auth behavior: cite auth.md.
