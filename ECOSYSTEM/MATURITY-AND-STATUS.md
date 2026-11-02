# Maturity and Status

Before using any project, check its current README, commits, issues, CI, license, and releases.

Suggested status labels:
- **Draft:** under active design; breaking changes expected.
- **Experimental:** usable for exploration, not production reliance.
- **Test fixtures:** synthetic tests/examples; not runtime enforcement.
- **Stable:** only if maintainers explicitly declare stability and provide evidence.

Do not infer production readiness from passing CI, repository age, or a project name. Add per-project status and last-reviewed date after a maintainer audit.


## Portfolio snapshot — reviewed 2026-11-02

This snapshot is based on each public repository's README, repository tree, and latest observed CI state. It is an orientation aid, not an independent semantic or security audit.

| Public project | Current maturity | What the current evidence supports |
|---|---|---|
| [Open Source AI Independence](https://github.com/HuffmanRepositories/Open-Source-AI-Independence) | Mission / coordination hub | Public mission, roadmap, portfolio map, and community documentation; not a production runtime |
| [Open Agent Compatibility](https://github.com/HuffmanRepositories/Open-Agent-Compatibility) | Research / early foundation | Version-scoped mapping methodology, mapping-profile schema, structural validator, tests, and CI; no runtime conformance claim |
| [OAC Fixtures](https://github.com/HuffmanRepositories/Open-Agent-Compatibility-Fixtures) | Draft fixture corpus | Synthetic compatibility fixtures and structural validation; not proof of implementation interoperability |
| [OARMI](https://github.com/HuffmanRepositories/Open-Agent-Run-Metrics-Interop) | Early research / draft fixtures | Synthetic accounting cases and structural checks; not billing or financial correctness |
| [P10 Memory Portability](https://github.com/HuffmanRepositories/Agent-Memory-Portability-Tests) | Draft fixture corpus | Synthetic migration/loss cases and structural validation; not a memory protocol |
| [P11 Oracle Integrity](https://github.com/HuffmanRepositories/Agent-Evaluation-Oracle-Integrity-Fixtures) | Experimental draft fixtures | Offline evaluator-integrity scenarios and structural checks; not a benchmark or certification |
| [P12 Retry and Idempotency](https://github.com/HuffmanRepositories/Agent-Tool-Retry-Idempotency-Fixtures) | Draft fixture corpus | Synthetic retry/unknown-outcome scenarios and structural checks; not an exactly-once runtime |
| [P13 Delegation Scope](https://github.com/HuffmanRepositories/Agent-Delegation-Scope-Boundary-Fixtures) | Draft fixture corpus | Synthetic scope-boundary cases and structural/semantic checks; not a policy engine |
| [P14 Delegated Budgets](https://github.com/HuffmanRepositories/Agent-Delegated-Budget-Enforcement-Fixtures) | Draft fixture corpus | Synthetic allocation/reservation cases and structural/semantic checks; not a budget manager |
| [HuffmanRepositories profile](https://github.com/HuffmanRepositories/HuffmanRepositories) | Portfolio / discovery | Account-level public project navigation; not a technical implementation |
| [Huffman Ecosystem Guide](https://github.com/HuffmanRepositories/Huffman-Ecosystem-Guide) | Documentation / onboarding | Public orientation, safe-use guidance, and links to canonical project docs |

## Promotion criteria

Do not promote a fixture repository to stable or conformance status solely because CI passes. Promotion requires documented source/version baselines, reviewed semantics, reproducible evidence, an explicit maintainer decision, and clear release/version policy. Runtime claims require named implementations and repeatable tests. Security claims require separate security review.

The private planning and testing workspaces are intentionally outside this public maturity table.
