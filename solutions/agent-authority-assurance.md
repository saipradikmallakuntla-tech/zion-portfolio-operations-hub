# Agent Authority & Accountability Assurance

**PROPOSED ADVISORY PROGRAM — not launched, not bookable, and not an official statement of Zion delivery capability.**

Initial brief: **15 November 2026**. Portfolio priority: **1**. Commercial price, delivery owner, capacity, and service availability: **not approved**.

## Positioning

For enterprise teams introducing agents that can change records, send messages, spend money, or delegate work, this proposed documentation-led engagement defines business authority and accountable human ownership before autonomy expands.

It is an advisory review and facilitated tabletop, not a security certification, technical enforcement layer, or guarantee that an agent is safe. The word assurance refers to evidence-oriented decision support, not an independent assurance opinion.

## Buyer, trigger, and job to be done

- Economic buyer: CISO, COO, or enterprise automation leader.
- Participants: workflow owner, security/identity owner, operations, legal/risk where relevant, and the team administering the agent platform.
- Trigger: moving a read-only assistant into a write-capable workflow; expanding a spending limit; granting a new tool; changing ownership; or investigating unclear delegation after an incident.
- Job: know who authorized each consequential action, the limits of that authority, and who can stop or revoke it.

High-impact actions require more than a broad instruction to be careful. OWASP recommends explicit authorization, least privilege, human approval, autonomy boundaries, and auditable action controls. [OWASP AI Agent Security](https://cheatsheetseries.owasp.org/cheatsheets/AI%5FAgent%5FSecurity%5FCheat%5FSheet.html) · [Excessive Agency](https://genai.owasp.org/llmrisk/llm062025-excessive-agency/)

## Existing Zion adjacency and distinct scope

The ecosystem already lists agent builders, orchestration platforms, handoff designers, gateway budgets/logging, governance material, and an MCP security checklist. See the [agent toolkit](https://github.com/Zion-support/zion-network/blob/main/network/agent-builder-toolkit.md), [MCP checklist page](https://ziontechgroup.com/zion-mcp-security/), and [LLM Gateway](https://ziontechgroup.com/llm-gateway/).

This proposal does not duplicate those products. Its distinctive deliverable is a human-approved **business mandate and decision-rights record** for one workflow. A diagram of agent handoffs or a list of token scopes is an input, not the outcome. Owner confirmation that no existing engagement already covers this outcome remains required.

## Proposed pilot: one workflow

Include one named write-capable agent workflow, its human sponsor, the systems it can affect, the action classes it may perform, and any delegation chain. Record systems that cannot be inspected as unknown rather than assuming control coverage.

### Inputs requested

Obtain approved, appropriately redacted workflow descriptions; a tool/action inventory; named business and platform owners; known financial/reputational/data risks; existing approval rules; and policy or incident summaries. Do not request credentials or copy operational logs into this public repository.

### Non-coding deliverables

1. **Ownership and mandate register:** purpose, accountable sponsor, operator, beneficiaries, affected parties, approved environment, review date, and stop conditions.
2. **Action-authority matrix:** action, target/resource boundary, permitted scope, financial or volume ceiling, required human approver, approval expiry, delegation permission, and evidence reference.
3. **Approval and revocation procedures:** how a reviewer sees the exact proposed action; how responsibility transfers; who revokes access; and what happens when an approval, policy, or evidence record is missing.
4. **Facilitated tabletop record:** discussion of an excessive-spend request, wrong-recipient message, ownership departure, unexpected delegation, or equivalent workflow-specific scenario. Record decisions and unanswered questions; do not execute the action.
5. **Prioritized handoff:** documentary gaps, accountable owner, risk rationale, and any separately scoped technical remediation requiring authorization.

## Suggested acceptance criteria

These are proposed pilot gates, not achieved results:

- Every in-scope action class has an accountable business owner and an explicit allow, require approval, prohibit, or unresolved decision.
- Consequential actions record limits, approving role, expiry/reconfirmation expectation, and revocation responsibility.
- A tabletop produces a decision log with open items and named owners.
- Documentary intent and technical enforcement evidence are recorded separately. Missing enforcement evidence is not marked implemented.
- The sponsor accepts remaining uncertainties or pauses expansion; no unresolved risk is silently translated into approval.

## Explicit exclusions

No agent/application development, IAM changes, OAuth implementation, token rotation, policy deployment, integrations, security testing, scripts, production monitoring, or incident execution. The engagement does not make payments, send messages, delete records, or alter any permission. Technical checks and remediation would be separately scoped and authorized outside this non-coding project.

## Validation and packaging questions

Prepare interviews rather than sending outreach automatically. Ask: Who owns agent-caused loss? Which action approvals are ambiguous today? Is an existing IAM or governance engagement already producing this record? Would the team sponsor a one-workflow review? Who will implement and verify any required control changes?

Draft packaging is a fixed-scope review and tabletop with an optional periodic documentary review. Duration, staffing, pricing, and any ongoing service must be validated and approved before promotion. No numerical ROI or risk-reduction claim is currently substantiated.

## Cross-promotion and safe copy

Proposed entry points: agent ecosystem documentation and the MCP checklist. Companion context: gateway logging/budget descriptions and model-observability material. These are proposed placements only; no backlink or production page change is authorized.

Draft card: **Know what every agent is allowed to do.** Define accountable owners, action limits, and human approvals before expanding autonomous workflows.

Before service approval, pair any teaser with **Proposed advisory program — scope under review**. The existing [Free Discovery page](https://ziontechgroup.com/discovery/) can be proposed for general interest routing, without implying this pilot is included in Discovery.

## FAQ

**Is this another agent builder?** No. It produces owner-approved operating documentation, not an agent or integration.

**Does a signed matrix enforce permissions?** No. Platform enforcement must be independently implemented and evidenced by authorized technical owners.

**Can we claim compliance or certification afterward?** No blanket claim is supported. Any jurisdictional or assurance statement needs separate qualified review and substantiation.

[Gap audit](../research/catalog-and-gap-audit.md) · [Promotion map](../launch/cross-promotion-map.md) · [Return to hub](../README.md)
