# PPT Master Deck MCP

PPT Master Deck MCP is a hosted remote MCP for ppt-master.

This repository is a public documentation project for PPT Master Deck MCP. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://pptmasterdeck.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=pptmasterdeck_public_docs&utm_content=readme_home
- Pricing: https://pptmasterdeck.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=pptmasterdeck_public_docs&utm_content=readme_pricing
- Checkout: https://pptmasterdeck.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=pptmasterdeck_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://pptmasterdeck.clauxel.com/mcp
- Server card: https://pptmasterdeck.clauxel.com/server-card.json
- Registry name: `com.clauxel.pptmasterdeck/pptmasterdeck-mcp`
- Tools: `generate_editable_deck`, `revise_deck_outline`, `render_deck_preview`, `export_deck_receipt`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: generate_editable_deck
- MCP tool: revise_deck_outline
- MCP tool: render_deck_preview
- MCP tool: export_deck_receipt

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
