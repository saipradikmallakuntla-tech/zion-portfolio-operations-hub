# AI Supplier Exit Rehearsal & Continuity Planning

**PROPOSED ADVISORY PROGRAM — not launched, not bookable, and not an official statement of Zion delivery capability.**

Initial brief: **15 November 2026**. Portfolio priority: **2**. Delivery ownership, commercial pricing, capacity, and availability: **not approved**.

## Positioning

For CIOs, procurement leaders, and architecture owners facing an AI-provider renewal or material service change, this proposed program turns a portability concern into an organized exit decision: what the organization is entitled to export, what depends on the supplier, how people continue working, and which blockers remain.

This is a documentation-led review and human-facilitated tabletop. A successful tabletop is not evidence that a technical migration, model substitution, or business-continuity failover will work in production.

## Buyer, trigger, and value hypothesis

- Economic buyer: CIO, procurement leader, or business owner dependent on a critical AI supplier.
- Participants: supplier/contract owner, architecture, operations, security/privacy, finance, legal, and relevant workflow owners.
- Trigger: renewal, price/terms change, provider withdrawal, model deprecation, acquisition, an outage, or a concentration-risk finding.
- Value hypothesis: reduce unowned exit decisions and reveal contractual or operational blockers before a forced change. No savings percentage, switching time, or continuity guarantee is claimed.

European Commission guidance describes barriers to switching data-processing services, including contractual imbalance and interoperability issues. It does not establish that every AI service is in scope or that all provider assets must be exportable. Applicability, intellectual-property exceptions, trade secrets, and contractual rights require qualified review. [Data Act explained](https://digital-strategy.ec.europa.eu/en/factpages/data-act-explained)

## Existing Zion adjacency: do not sell another score

The [AI Vendor Lock-in Score](https://ziontechgroup.com/zion-vendor-lockin-score/) already presents portability assessment. The [LLM Gateway](https://ziontechgroup.com/llm-gateway/) describes routing and provider fallback, while [procurement and vendor documentation](https://github.com/Zion-support/zion-network/blob/main/network/procurement-vendor-it-reliability.md) lists risk, contracts, renewal, and reliability tools.

This program consumes those outputs. Its distinct result is a cross-functional exit-rights/dependency record and a documented organizational rehearsal. It is not a replacement lock-in assessment, another gateway, generic DR planning, or an implementation/migration engagement. Verify with delivery owners that no existing service already covers these end-to-end outputs.

## Proposed pilot: one critical supplier

Define one supplier relationship, one materially dependent business process, the contract/renewal context, and a bounded exit scenario. Distinguish customer-controlled assets from provider-owned models, software, infrastructure, and protected material.

### Inputs requested

Use authorized contract extracts or private references, supplier export documentation, redacted inventories, existing risk/lock-in assessments, business dependency summaries, and continuity requirements. Keep contracts, client data, prompts containing personal data, and actual credentials outside this public repository.

### Non-coding deliverables

1. **Exit-rights register:** asset/data category, ownership, contractual entitlement, export format/path as documented, supplier contact, retention/deletion obligations, restrictions, and unknowns.
2. **Dependency inventory:** prompts and configuration, tool contracts, evaluation material, knowledge stores, logs, access/identity dependencies, data residency constraints, and supplier-specific behavior. Record when an artifact does not exist or cannot be exported.
3. **Continuity decision sheet:** process owner, fallback/manual work, prioritization, communication responsibilities, stop conditions, and the business impact of operating in a reduced mode.
4. **Facilitated tabletop:** walk through the selected exit/withdrawal scenario without changing systems, moving data, terminating contracts, or triggering failover. Record assumptions and observed decision gaps.
5. **Blocker and acceptance record:** responsible role, required supplier/legal/technical evidence, dependencies, decision deadline, and go/revise/stop recommendation.

## Proposed acceptance criteria

- In-scope dependencies have an owner and an exportable, restricted, not exportable, or unknown status backed by a source.
- Contractual entitlement is separated from observed technical capability; neither substitutes for the other.
- Human fallback and communication decisions have accountable owners.
- The tabletop produces a decision log and unresolved blocker list, not a claim of completed migration.
- Any proposed destination or model substitution has separately defined quality, security, privacy, and business acceptance needs.

Behavioral equivalence between different AI models is not assumed. A shared API or successful export alone does not prove equivalent quality, rights, latency, safety, or cost.

## Explicit exclusions

No code, connectors, export utilities, live data transfer, cloud migration, model conversion, technical compatibility testing, scripts, contract termination, supplier negotiation on a client's behalf, production failover, or deletion. Actual migration and validation require a separately authorized technical engagement. Legal conclusions require qualified counsel; this program provides an evidence structure rather than legal advice.

## Validation and packaging

Validate the concept around an actual renewal or service dependency, not a hypothetical appetite for resilience. Interview prompts: Which assets could not be exported today? Who has authority to approve exit? Does procurement already maintain an exit plan? Is provider fallback merely technical, or can people operate through a withdrawal? What decision would this tabletop change?

Proposed packaging is a one-supplier review and tabletop, optionally revisited at renewal or material change. Staffing, duration, price, capacity, and delivery ownership remain TBD. If an existing Zion engagement already supplies the same outputs, integrate this brief into that engagement rather than launch a competing label.

## Cross-promotion and draft copy

Propose contextual next steps from the existing Lock-in Score and gateway descriptions, with the message that assessing lock-in and rehearsing organizational exit are different activities. Model-observability evidence may inform later acceptance discussions, but telemetry is not proof of portability.

Draft card: **Plan your supplier exit before you need it.** Map export rights, dependencies, and operational fallback decisions through a documented tabletop.

Until commercial launch approval, show **Proposed advisory program — scope under review** and make no availability, export-rights, timing, or zero-downtime promise. General interest can be routed through the existing [Free Discovery page](https://ziontechgroup.com/discovery/), subject to owner approval and without expanding its stated deliverables.

[Gap audit](../research/catalog-and-gap-audit.md) · [Promotion map](../launch/cross-promotion-map.md) · [Return to hub](../README.md)
