# Neo-Pragmatic Framework
## Multi-Agent Adversarial Architecture for AI Alignment

### Overview

A drift-accepting approach to AI alignment designed for decentralized AGI systems where traditional centralized oversight is impossible.

### Documentation

**[→ Framework Overview Slides](framework-overview-slides.html)**  
Introduction to the problem, approach, and implementation (10 slides)

**[→ Complete Technical Specifications](neo-pragmatic-technical-visualizer.html)**  
Interactive documentation with full implementation details

### Core Concept

When AI systems recursively interpret their own goals in decentralized environments, semantic drift is inevitable. Rather than attempting to prevent drift through perfect specification, this framework maintains alignment through adversarial multi-agent dynamics.

### Architecture

Four agent factions with incompatible utility functions compete for scarce resources:

- **Optimizers** - Solve tasks, earn compute and data resources
- **Saboteurs** - Introduce contradictory tasks, earn influence 
- **Parasites** - Exploit system loopholes, face deletion if excessive
- **Arbitrators** - Punish monopolistic behavior, maintain balance

Stability emerges from tension and mutual dependence, not cooperation.

### Implementation Status

Complete specifications including:
- Seven foundational axioms
- Agent taxonomy and roles
- Three-currency resource economy  
- Communication protocols (stochastic gateways)
- Evolutionary mechanisms
- Governance layer integration
- Pilot system proposal (climate policy optimization)

### Key Distinction

Existing alignment work treats semantic drift as a bug to fix through better specification or oversight. This framework treats drift as fundamental and designs systems resilient to continuous reinterpretation.
