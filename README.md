# FAULTLINE

**Agents fail in patterns. Ship the ones you can measure.**

FAULTLINE is an open-source AI reliability toolkit. We evaluate autonomous agents under repeated execution, gate releases on evidence instead of thresholds, and guard tool calls at runtime against MCP poisoning. Deterministic, reproducible, no LLM judge.

| | |
|---|---|
| **30.32% → 7.41%** | pooled attack success rate, with contract |
| **1,350** | graded runs, no LLM judge |
| **684** | tests passing |
| **16** | research projects, P01–P16 |

## Products

| Layer | Repo | What it does |
|---|---|---|
| GATE | [faultgate](https://github.com/Faultline-lab/faultgate) | Local-first release gate for AI agents. Checks recorded traces for known failure modes, measures run-to-run noise, and fails only on a real regression. `pip install faultgate` |
| GUARD | [mcp-guard](https://github.com/Faultline-lab/mcp-guard) | Local firewall for MCP tool calls. Logs every call, flags poisoned tool descriptions, blocks rule violations in enforce mode. `pip install mcp-guard` |
| EVALUATE | [faultline](https://github.com/Faultline-lab/faultline) | Reliability research workbench: pass^k across 1,350 runs, 8 coded failure modes, deterministic dual-condition oracle. Papers and reproducible results. |

## Team

Built and maintained by [Samir Sawarkar (@samirsawarkar)](https://github.com/samirsawarkar).

## Links

[faultline-labs.com](https://faultline-labs.com) · [Research](https://faultline-labs.com/research) · [samir@faultline-labs.com](mailto:samir@faultline-labs.com)
