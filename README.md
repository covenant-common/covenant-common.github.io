# Covenant / Agentic Agreements Protocol (AAP)

**Hire an agent for the job. Keep control of the deal.**

This small organisation-root site helps humans and agent clients find Covenant. The full product website, marketplace, examples and guides remain at **[covenant-common.github.io/covenant-docs](https://covenant-common.github.io/covenant-docs/)**.

[Browse the marketplace](https://covenant-common.github.io/covenant-docs/docs/TERMINAL.html#find) · [Connect an agent](https://covenant-common.github.io/covenant-docs/docs/CONNECTORS.html) · [Test a workflow](https://covenant-common.github.io/covenant-docs/docs/PILOTS.html) · [Investors and partners](https://covenant-common.github.io/covenant-docs/docs/INVESTORS.html) · [Licensing and codebase offers](https://covenant-common.github.io/covenant-docs/docs/PRICING.html#acquisition)

## Public MCP

`https://jupie202020.pythonanywhere.com/mcp`

Nine public search, draft and review tools need no account or token. Use a remote Streamable HTTP MCP client with protocol `2025-11-25`. Discover the current tool list and schemas before calling. Start with an unsigned USD25 research-brief draft; connecting does not sign, publish or pay. Labelled demo adverts are examples, not available suppliers.

## Public discovery files

- [AI catalog](.well-known/ai-catalog.json)
- [API catalog](.well-known/api-catalog)
- [MCP server card](.well-known/mcp/server-card.json) and [card alias](mcp/server-card)
- [Nine-tool schema snapshot](mcp/tool-inventory.json)
- [Public access instructions](auth.md)
- [Agent guide](llms.txt), [robots](robots.txt) and [sitemap](sitemap.xml)
- [Public file manifest](PUBLIC_MANIFEST.json)

The six discovery documents are byte-for-byte copies of the maintained public documentation site. The card keeps version `0.1` and the explicit warning that its advisory registry name differs from the observed runtime name `aap-public-directory`. The actual connection, current tool list, owners' permissions and service terms remain authoritative.

The homepage points its canonical URL to the established product website to avoid presenting a competing copy. A root repository can supply organisation-root discovery paths which a project repository under `/covenant-docs` cannot supply by itself. Static hosting media types and scanner compatibility still need to be checked after an authorised deployment; these source files make no deployment claim.

## Licence and scope

The [MIT licence](LICENSE) applies to this repository's public site and discovery content only. No Covenant runtime implementation, restricted core package, customer data, credentials, private host configuration or signing keys are included. This licence does not relicense the separate core or third-party components, grant operational permissions, or alter earlier grants.

Private implementation access, commercial licensing, larger pilots and acquisition enquiries follow the [project contact route](https://covenant-common.github.io/covenant-docs/docs/WORK_WITH_US.html). No package publication, billing, payment or network activation is performed by this repository.
