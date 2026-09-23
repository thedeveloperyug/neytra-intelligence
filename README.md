# NEYTRA Intelligence Platform — Website

Official website: https://thedeveloperyug.github.io/neytra-os-website/

**Primary project:** NEYTRA Intelligence Platform (NIP)  
**Status:** Active development  
**Tagline:** Think. Adapt. Act.

## Purpose

This repository contains the public-facing website for **NIP — NEYTRA Intelligence Platform**.

NIP is an OS-agnostic intelligent execution platform designed for reasoning, planning, model orchestration, memory, environment awareness, capability discovery, tool intelligence, multi-task execution, verification, developer intelligence and controlled autonomy.

**NIP is the current engineering focus. NEYTRA OS remains a separate future operating-system project and is intentionally preserved as part of the NEYTRA vision.**

## What NIP is

NIP is designed as a control plane and execution platform rather than a chatbot or simple LLM wrapper.

Its target lifecycle is:

**Understand → Decompose → Plan → Discover → Select → Authorize → Execute → Observe → Critique → Reason → Verify → Recover / Replan → Learn**

The architecture supports:

- Job and multi-task orchestration
- Dependency-based task graphs and parallelism
- Deterministic Core execution
- Goal-driven agents
- Planner / Executor / Observer / Critic / Reasoner / Verifier pipeline
- Scheduler and bounded dispatch
- Agent placement
- Execution attempts, leases and fencing
- Agent runtime and worker lifecycle
- Model invocation and model execution attempts
- Model/provider abstraction and future intelligent routing
- Capability and tool discovery
- Capability-first tool selection
- Evidence-backed tool behavior knowledge
- Security, policy and authorization boundaries
- Checkpoints and recovery
- Verification and evidence traceability
- Developer intelligence
- Linux and future multi-OS adapters
- Future deep NEYTRA OS integration

## NIP ↔ NEYTRA OS

The projects have a deliberate boundary:

| Project | Responsibility |
|---|---|
| **NIP** | Intelligence, jobs, tasks, agents, models, capabilities, tools, reasoning, verification |
| **NEYTRA OS** | Operating system, services, desktop, hardware, isolation and system-level authority |
| **Integration Bridge** | Requests, events, capabilities, permissions, execution results and artifacts |

**NEYTRA OS provides the system. NIP provides the intelligence.**

The website therefore presents NIP as the active platform while retaining NEYTRA OS as the future operating-system direction.

## Website design

The site keeps the existing NEYTRA visual language and animations, including:

- Animated particle field
- Interactive cursor glow
- Animated intelligence core
- Rotating rings and orbital effects
- Scroll-reactive core motion
- Device-orientation interaction where supported
- Reveal-on-scroll sections
- Animated grid background
- Hover / tilt-style cards
- Responsive mobile navigation
- Reduced-motion accessibility support

The new NIP-first experience adds visual representations for:

- NIP execution lifecycle
- Platform architecture
- Core capabilities
- Controlled execution
- Model runtime
- NIP ↔ NEYTRA OS boundary
- Development roadmap

## Repository naming

The current GitHub repository is named `neytra-os-website`. The intended identity of this website is now **NEYTRA Intelligence Platform**.

GitHub repository renaming is an account-level repository setting; after renaming it, update the GitHub Pages URL and any external references if GitHub does not automatically preserve the expected redirect.

## Deployment

GitHub Actions deploys `main` to GitHub Pages via:

`.github/workflows/deploy.yml`

## Founder

**Yogesh Pandey** — Founder & creator of the NEYTRA platform vision.

LinkedIn: https://www.linkedin.com/in/thedeveloperyug  
Email: thedeveloperyug@gmail.com

---

**NIP — The intelligence layer for NEYTRA.**

**Think. Adapt. Act.**
