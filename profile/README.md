<p align="center">
  <a href="https://subregator.com">
    <img src="https://raw.githubusercontent.com/subregator/brand-kit/main/subregator-mark.svg" width="96" height="96" alt="Subregator">
  </a>
</p>

<h1 align="center">A clearer view of the IP address market.</h1>

<p align="center">
  Compare offers. Follow prices. Explore network data.
</p>

<p align="center">
  <a href="https://subregator.com"><strong>Explore Subregator</strong></a> ·
  <a href="https://api.subregator.com/">REST API</a> ·
  <a href="https://api.subregator.com/openapi.json">OpenAPI</a> ·
  <a href="https://github.com/subregator/subregator-backend/issues">Suggest a provider</a>
</p>

---

Subregator brings IP address lease and purchase offers from multiple providers into one searchable catalogue. We build tools that make pricing, listing history and network observations easier to inspect and compare.

## What you can do

- **Find an offer.** Compare IPv4 lease and purchase listings by provider, prefix size, currency and price per IP. Review billing terms and follow the link to the original provider.
- **Look beyond the price.** Explore observed price changes, listing history and source-scoped BGP, RPKI and Spamhaus DROP data.
- **Build on the data.** Use the read-only REST API or connect an MCP client to `https://mcp.subregator.com/`. Explore the code, run your own instance and contribute improvements.

Prices and availability reflect source observations. Confirm current terms with the provider; network checks are not a safety or ownership guarantee.

## Find your way around

| Repository                                                                   | What lives there                                                                         |
| ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| [**subregator-backend**](https://github.com/subregator/subregator-backend)   | Go service, PostgreSQL storage, provider collectors, listing history, REST and MCP APIs. |
| [**subregator-frontend**](https://github.com/subregator/subregator-frontend) | The web interface for searching offers, comparing prices and exploring provider data.    |
| [**brand-kit**](https://github.com/subregator/brand-kit)                     | The Subregator logo and its SVG and PNG exports.                                         |

Each application repository includes instructions for running it locally and checking your changes.

## Help make it better

Found a missing provider, incorrect listing or API problem? [Open a backend issue](https://github.com/subregator/subregator-backend/issues) with the source link and what you expected to see. For a new provider, include its public API or feed details and display terms when available.

For interface bugs and usability ideas, [open a frontend issue](https://github.com/subregator/subregator-frontend/issues). Include steps to reproduce and a screenshot when useful.

Pull requests are welcome: provider integrations, data quality improvements, clearer documentation and a better browsing experience all help. Keep changes focused and run the relevant repository checks.

For support and general questions, email [contact@subregator.com](mailto:contact@subregator.com).
