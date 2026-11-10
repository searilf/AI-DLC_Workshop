# AI-DLC Workshop Presentation — Expanded v2

**Duration:** 180 minutes | **Slides:** 33 | **Language:** Thai

Slides are maintained as a PowerPoint artifact separately; this outline is the source of truth for topic order, timings, and alignment with the hands-on guide.

## A. AI-DLC Concepts & Methodology — 60 minutes (Slides 01–20)

1. AI-Driven Development Lifecycle — introduction
2. 3-hour workshop journey
3. AI Coding in three visual modes — Autocomplete, Chat-assisted Coding, and Coding Agent (icon-based workflow)
4. AI-assisted Coding vs AI-DLC
5. AI-DLC Maturity — AI-Assisted → AI-Enabled → AI-Orchestrated → AI-Native (illustrative model)
6. Harness vs AI-DLC Orchestrator architecture (Kiro, Claude Code, Codex CLI)
7. Core delivery flow: Inception → Construction → Operation; roles, rituals, artifacts, units, bolts and deployment (editable infographic)
8. Initialization and Ideation: preparing context and framing intent
9. Inception: requirements, acceptance criteria, design and delivery plan
10. Construction: units, delivery slices, code and executed tests
11. Operation: deployment, monitoring and continual improvement
12. Five phases and 33 stages — visual lifecycle with stage counts and runtime caveat
13. Interactive Stage-by-Scope Matrix — click one of 11 standard scopes to view EXECUTE / SKIP stages in linked appendix
14. Depth and Test Strategy controls
15. Question modes: Guide Me, Edit File, Chat
16. AI Agents and Human Roles
17. Human Validation Gates and approval decisions
18. Artifacts, per-intent State and Audit Trail
19. Bolt, Mob and Gate terminology
20. Securing AI-DLC across Code → Cloud → Runtime (Wiz Academy/AppSec guidance)

## B. Live Demo — 20 minutes (Slides 21–23)

21. Infrastructure Health Monitoring demo scenario using local mock data
22. Demo walkthrough: intent, requirements, build one slice, validate
23. Three observable outcomes: Intent Clarity, Human Decisions, Executed Evidence

## C. Break and Lab Readiness — 10 minutes

Open this repository and ensure the selected harness and AI-DLC workflow work; installation should be completed before workshop day.

## D. Hands-on Team Challenge — 70 minutes (Slides 24–31)

24. Start team challenge
25. Mission: IT Incident Management Application
26. 4 team roles: Product Owner, Solution Architect, Developer, QA/DevOps
27. GitHub repository as step-by-step playbook
28. The six learning milestones over 70 minutes
29. Steps 01–03: Setup, Problem Understanding, Requirements & Design
30. Steps 04–06: Implementation, Testing & Validation, Review & Wrap-up
31. Testing: executed evidence, not AI's unsupported claims

Participants follow [mission.md](../mission.md), [success-criteria.md](../success-criteria.md), and [steps/](../steps/).

## E. Team Showcase — 15 minutes (Slide 32)

Share prototype/progress, key AI-DLC artifacts, two Human Decisions, test results, and next steps.

## F. Q&A and Wrap-up — 5 minutes (Slide 33)

**Principle:** AI drives the work. Humans own the decisions.

## Official AI-DLC Sources

- https://awslabs.github.io/aidlc-workflows/guide/00-introduction/
- https://awslabs.github.io/aidlc-workflows/guide/04-phases-and-stages/
- https://awslabs.github.io/aidlc-workflows/guide/workflow-profiles/
- https://awslabs.github.io/aidlc-workflows/guide/07-interaction-modes/
- https://awslabs.github.io/aidlc-workflows/guide/10-state-and-audit/
- https://awslabs.github.io/aidlc-workflows/guide/glossary/

> Stage counts and scope defaults refer to the AI-DLC Workflows docs as checked on 10 November 2026. Validate the installed harness/version before delivery. This deck is a workshop interpretation and not an AWS official presentation.

## Interactive Stage-by-Scope Matrix — Appendix (Slides 34–44)

11 clickable scopes on slide 13, each linking to a detailed EXECUTE/SKIP grid with back-navigation to slide 13. All content is editable PowerPoint shapes. PowerPoint Slide Show mode is required for the full link interaction.

| Scope | EXECUTE / 33 |
|---|---:|
| enterprise | 33 |
| feature | 33 |
| mvp | 23 |
| poc | 8 |
| bugfix | 9 |
| refactor | 10 |
| infra | 15 |
| security-patch | 10 |
| classic | 18 |
| workshop | 26 |
| express | 10 |

Reference: [AWS Labs Stage-by-Scope Matrix](https://github.com/awslabs/aidlc-workflows/blob/main/docs/guide/05-scopes-and-depth.md). EXECUTE means included in the standard scope plan; conditional stages may skip at runtime. Matrix reviewed 10 November 2026.

Visual reference: user-provided diagrams; security reading: [Wiz Academy AI-DLC](https://www.wiz.io/academy/ai-security/ai-driven-development-lifecycle-ai-dlc). All slides use Open Sans text.
