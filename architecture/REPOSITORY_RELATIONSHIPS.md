# `sagitta-stack` repository relationships

Generated from reviewed policy and the current **public** repository inventory.

- Public repositories declared: **2**
- Private repository names withheld: **3**
- Relationship edges: **1**

## Repository roles

| Repository | Role | Lifecycle |
|---|---|---|
| [`.github`](https://github.com/sagitta-stack/.github) | `organization_governance` | `active` |
| [`sagitta-stack.github.io`](https://github.com/sagitta-stack/sagitta-stack.github.io) | `site` | `active` |

## Declared edges

| From | Relationship | To | Status/basis |
|---|---|---|---|
| `sagitta-stack/.github` | `governs` | `sagitta-stack/sagitta-stack.github.io` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |

## Composition, service, and observability contract

Git submodules compose editable source; Zed packages resolve packages/artifacts; dual-managed commits must match. Production deploys immutable image digests, not runtime source builds. Cross-service access uses APIs/SDKs/events rather than another service database. MCP uses the product API/SDK. Services emit OpenTelemetry traces, bounded metrics, and correlated structured logs.

## Privacy boundary

This public registry deliberately omits private repository names and edges; the count above makes the boundary explicit.
