# FAULTLINE

FAULTLINE builds open-source tools for AI agent reliability: measure repeated runs, check recorded traces before a release, and monitor MCP tool calls at runtime. [Explore the platform](https://www.faultline-labs.com/platform/).

## Installable tools

| Product | Use it for | Install | Details |
| --- | --- | --- | --- |
| **[faultgate](https://www.faultline-labs.com/products/faultgate/)** | Check recorded AI agent traces for failure modes and business-rule violations; compare candidate runs with measured baseline variation and return PASS, FAIL, or INCONCLUSIVE in CI. | `pip install faultgate` | [Source](https://github.com/Faultline-lab/faultgate) · [PyPI](https://pypi.org/project/faultgate/) · [Docs](https://www.faultline-labs.com/docs/) |
| **[MCP Guard](https://www.faultline-labs.com/products/mcp-guard/)** | Monitor local stdio MCP servers for changed tool definitions and tool-description poisoning; audit calls by default and block supported rule violations in enforce mode. | `pip install mcp-integrity` | [Source](https://github.com/Faultline-lab/mcp-guard) · [PyPI](https://pypi.org/project/mcp-integrity/) |

**Naming:** FAULTLINE MCP Guard is the product. Its Python package and command are named `mcp-integrity`. `pip install mcp-guard` is not the install command for this product.

## Research

The [FAULTLINE research workbench](https://github.com/Faultline-lab/faultline) contains reproducible studies of agent failures and reliability. Read the [research pages](https://www.faultline-labs.com/research/) for methods and results.

## Team and links

Built and maintained by [Samir Sawarkar (@samirsawarkar)](https://github.com/samirsawarkar). [Website](https://www.faultline-labs.com/) · [Contact](https://www.faultline-labs.com/contact/)
