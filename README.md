# Agentic AI Implementation and Lifecycle Governance

**One lifecycle for AI agents and the assets they are built from, from idea to retirement.**

AI has moved from a few projects a year to agents built every week, by many people, on many platforms. Agents call
tools, read and write data and start processes; they are assembled from shared parts that change on their own. This
framework sets out how an organisation can govern them in proportion to risk, without slowing them down:

- **one register and one record** for every AI asset and its connections, shown as it stood on any date;
- **one lifecycle with two tracks**: the full track, with three gates, for the assets that produce outcomes (agents,
  AI-enabled systems, platforms), and a shorter component track for the building blocks they use (models, tools, MCP
  servers and APIs, skills, knowledge sources);
- **build, test and approve kept apart**, following the ADG framework (Adopt · Defend · Govern);
- **change materiality decides the path** (Light, Standard or Enhanced), when an asset is first assessed and whenever
  it changes substantially; the level of autonomy sets the minimum controls;
- **a testing standard** by harm class, built on the OWASP Top 10 for LLM and Agentic Applications and MITRE ATLAS,
  with red teaming;
- **a data protection route** wherever personal data is processed or generated;
- **automation where it saves the most**, so that people spend their time on decisions;
- **technology-neutral**: it sets what the supporting technology must do, without assuming a product.

It is mapped to the EU AI Act, GDPR, DORA, ISO/IEC 42001 and the NIST AI RMF.

![Figure 1. One lifecycle, two tracks](diagrams/lifecycle-overview.svg)

## Contents

| File | What it is |
|---|---|
| [Agentic_AI_Implementation_and_Lifecycle_Governance.md](Agentic_AI_Implementation_and_Lifecycle_Governance.md) | The framework: 14 sections and appendices A to G |
| [diagrams/lifecycle-overview.svg](diagrams/lifecycle-overview.svg) | Figure 1. One lifecycle, two tracks |
| [diagrams/agent-anatomy.svg](diagrams/agent-anatomy.svg) | Figure 2. An agent is assembled, and its parts keep changing |
| [diagrams/operating-model.svg](diagrams/operating-model.svg) | Figure 3. Who builds, who tests, who approves |
| [diagrams/responsibility-matrix.svg](diagrams/responsibility-matrix.svg) | Figure 4. Who does what: the responsibility matrix |
| [diagrams/governance-paths.svg](diagrams/governance-paths.svg) | Figure 5. How much governance an asset gets |
| [diagrams/materiality-matrix.svg](diagrams/materiality-matrix.svg) | Figure 6. Change materiality: from three answers to a path |
| [diagrams/lifecycle-roles.svg](diagrams/lifecycle-roles.svg) | Figure 7. The lifecycle in detail: who does what at each stage |
| [diagrams/initial-approval.svg](diagrams/initial-approval.svg) | Figure 8. Gate 1: the initial approval |
| [diagrams/testing.svg](diagrams/testing.svg) | Figure 9. Testing: what is tested, by whom, and how deep |
| [diagrams/change-after-go-live.svg](diagrams/change-after-go-live.svg) | Figure 10. After go-live: does it still deserve its approval? |
| [diagrams/automation.svg](diagrams/automation.svg) | Figure 11. Where automation saves the most |
| [diagrams/solution-landscape.svg](diagrams/solution-landscape.svg) | Figure 12. The governance solution in its landscape |
| [diagrams/roadmap.svg](diagrams/roadmap.svg) | Figure 13. Introducing it: six phases |
| [diagrams/eu-ai-act-risk-class.svg](diagrams/eu-ai-act-risk-class.svg) | Figure 14. EU AI Act risk class: four questions |

Each figure is also provided as a PNG, for slides and documents.

## How to use it

The framework is a template. Words in [square brackets] are placeholders for an organisation's own names of
committees, functions, policies and tools. The paths, thresholds, review frequencies and effort targets are starting
points to calibrate in a pilot. Section 14 describes a way to introduce it, from agreeing the framework to choosing the
technology and running the full lifecycle.

## Licence

© 2026 Andres Gavriljuk. Licensed under the
[Creative Commons Attribution-NonCommercial 4.0 International licence](https://creativecommons.org/licenses/by-nc/4.0/)
(CC BY-NC 4.0). You may share and adapt it for non-commercial purposes, with attribution. For commercial use, ask the
author.

Attribution: *Andres Gavriljuk, "Agentic AI Implementation and Lifecycle Governance", version 1.1, 2026,
https://github.com/pragmatiqai/governanceframework, CC BY-NC 4.0.*

ADG (Adopt · Defend · Govern) is a framework of EC-Council; OWASP, MITRE ATLAS and the other frameworks and products
named belong to their owners. They are referred to, not reproduced.
