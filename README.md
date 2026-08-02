# Paradromics

Paradromics is a clinical-stage neurotechnology company (Austin, TX; founded 2019 by Matt Angle) developing
high-data-rate implantable brain-computer interfaces. Its Connexus BCI is an investigational device under an
FDA Investigational Device Exemption for the Connect-One Early Feasibility Study (ClinicalTrials.gov
NCT07357428); Tempo BCI is a pre-clinical-trial pipeline product.

- Website: https://paradromics.com/
- Company: https://paradromics.com/company/
- Blog: https://paradromics.com/blog/
- News: https://paradromics.com/news/
- GitHub: https://github.com/paradromics
- Secondary market listing: https://forgeglobal.com/paradromics_stock/

## API surface

Paradromics publishes **no public developer API**. Contract discovery (2026-08-02) probed the apex and `www`
hosts for `/openapi.json`, `/openapi.yaml`, `/swagger.json`, `/v1/openapi.json`, `/api-docs`, `/redoc`,
`/graphql`, `/mcp`, `/api`, `/developers`, `/developer` and the full `/.well-known/` discovery surface —
every path returned 404. There are no `api.`, `developer.`, `docs.`, `status.` or `trust.` subdomains, the
`paradromics` GitHub org publishes only a `.github` profile repo, and no first-party package exists on npm
or PyPI. There is no OpenAPI, GraphQL, AsyncAPI, MCP server or A2A agent card to capture.

The one machine-readable public surface is an **`llms.txt`** AI-context file, captured verbatim in `llms/`.

## Artifacts

| Path | Type | Method |
|---|---|---|
| `llms/paradromics-llms.txt` | LLMsTxt | searched (verbatim from https://www.paradromics.com/llms.txt) |
| `well-known/paradromics-well-known.yml` | — (record of misses) | probed |
| `security/paradromics-domain-security.yml` | DomainSecurity | probed |
