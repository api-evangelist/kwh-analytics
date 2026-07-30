# kWh Analytics

kWh Analytics is a Beaverton, Oregon based managing general agent and data-analytics firm that
underwrites property and performance insurance for renewable energy assets — solar, wind, and
battery storage. Founded in 2012 and acquired by specialist insurer Beazley in 2023, the company
operates what it describes as the industry's largest solar performance database, covering roughly
30% of U.S. solar assets across 300,000+ renewable energy assets and $100B+ in loss data.

Its HelioStats platform ingests unstructured asset production documents (via AWS S3, Box, Dropbox,
email attachment, or API) and applies OCR and machine learning to extract, validate, standardize,
benchmark, and enrich operating data. Commercial products include data-driven Property Insurance,
the Solar Revenue Put, the Wind Proxy Hedge, and the SolarScape market intelligence offering.

## API surface

**No public API.** As of 2026-07-19 there is no developer portal, API reference, sign-up flow,
sandbox, SDK, CLI, changelog, status page, or machine-readable specification (OpenAPI, AsyncAPI,
GraphQL). The HelioStats ingest API is referenced in marketing copy as one of several document
submission channels but is not publicly documented — access is arranged through enterprise
engagement. This repo therefore carries identity and probe artifacts only; no API artifacts have
been fabricated.

## Artifacts

- `llms/kwh-analytics-llms.txt` — generated llms.txt from the catalog and site research.
- `security/kwh-analytics-domain-security.yml` — probed TLS/HSTS/DNSSEC/CAA/SPF/DMARC.
- `well-known/kwh-analytics-well-known.yml` — negative result record for `/.well-known/` probes.

Backed by: anthemis. Owned by Beazley (2023).
