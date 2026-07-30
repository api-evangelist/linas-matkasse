# Linas Matkasse

Linas Matkasse is a Swedish meal-kit subscription service that delivers pre-portioned ingredients and nutritionally calculated recipes to customers' homes each week. Customers pick from more than 150 weekly recipes across concepts such as Chef's Choice, Family Favorites, Quick & Easy, Calorie-Smart, Vegetarian, Gluten-Free and Lactose-Free, and can change their selection until Tuesday night before a Saturday-to-Monday delivery.

The brand is operated by [Cheffelo](https://cheffelo.com/), a Scandinavian meal-kit group listed on Nasdaq First North Growth Market that also runs Godtlevert in Norway and RetNemt in Denmark, delivering roughly 17 million meals a year.

Backed by: creandum

## API status

Linas Matkasse runs a consumer subscription storefront and a "Mina Sidor" customer account area. As of 2026-07-19 it publishes **no public API**: no developer portal, no OpenAPI/AsyncAPI/GraphQL specification, no SDKs or CLI, no MCP server, no `/.well-known/` discovery documents, and no published vulnerability-disclosure or trust-center program. `api.linasmatkasse.se`, `developer.linasmatkasse.se`, `api.cheffelo.com` and `developers.cheffelo.com` do not resolve.

The parent group's public GitHub org, [github.com/cheffelo](https://github.com/cheffelo), holds only internal tooling and engineering hiring exercises — no client libraries or API specifications.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| Domain security | `security/linas-matkasse-domain-security.yml` | probed |
| Well-known probe | `well-known/linas-matkasse-well-known.yml` | searched (all 404) |
| Packages / SDKs | `packages/linas-matkasse-packages.yml` | searched (none found) |
| llms.txt | `llms/linas-matkasse-llms.txt` | generated |
