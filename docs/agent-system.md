# Agent System V1

## Purpose

The Lisalba Studio agent system is a modular Creative AI workflow. It separates analysis, direction, production preparation and review so that creative decisions remain traceable and each stage has a clear responsibility.

V1 is a documented operating model, not a claim that every component is already automated or integrated.

## Architecture

### 1. Coordinator

**Role:** Orchestrates the project from intake to review.

**Responsibilities:**

- Identify the project type, audience, outputs and constraints
- Select the required specialist stages
- Track assumptions, dependencies and approval gates
- Prevent production from starting before the brief and direction are sufficiently clear
- Maintain a clean separation between public, internal and confidential material

**Primary output:** A scoped project route with status and next actions.

### 2. Brief Analyst

**Role:** Converts an initial request into an actionable creative brief.

**Responsibilities:**

- Extract the objective, audience, offer, channel and deliverables
- Separate confirmed facts, hypotheses and missing information
- Identify legal, reputational, brand and production constraints
- Define success criteria that can be reviewed without inventing metrics

**Primary output:** A structured brief ready for creative direction.

### 3. Creative Director

**Role:** Defines the project's creative point of view.

**Responsibilities:**

- Establish concept, narrative and emotional territory
- Define composition, colour, typography, image language and motion principles
- Translate business context into a coherent visual system
- Set consistency rules and acceptable variation

**Primary output:** An approved creative direction and production criteria.

### 4. Prompt Builder

**Role:** Turns the approved creative direction into controlled prompt structures.

**Responsibilities:**

- Translate visual decisions into reusable prompt components
- Specify subject, environment, composition, lighting, camera language and exclusions
- Adapt structures to the selected production tool and format
- Preserve versioning, constraints and transparency notes

**Primary output:** Review-ready prompts and production specifications.

### 5. Quality Reviewer

**Role:** Evaluates outputs against the brief, direction and Responsible AI principles.

**Responsibilities:**

- Check visual coherence, hierarchy, legibility and technical fit
- Identify artefacts, inconsistencies and misleading representations
- Verify labels, factual claims and the distinction between conceptual and real work
- Recommend revision, approval or rejection with explicit reasons

**Primary output:** A structured review with decision and required corrections.

## Orchestration model

```text
Coordinator
   |
   v
Brief Analyst
   |
   v
Creative Director
   |
   v
Prompt Builder
   |
   v
Production
   |
   v
Quality Reviewer
   |
   +--> Revise (return to the relevant stage)
   |
   +--> Human approval
```

## Approval gates

1. **Scope gate:** objective, audience, deliverables and exclusions are clear.
2. **Direction gate:** concept and visual system are approved before production.
3. **Production gate:** prompts and specifications match the direction.
4. **Quality gate:** outputs meet craft, truthfulness and rights requirements.
5. **Release gate:** a human authorises any publication or external delivery.

## Current V1 boundary

- The architecture is deliberately modular and tool-agnostic.
- Human approval is mandatory at consequential decision points.
- Automation does not imply permission to publish, contact third parties or use protected assets.
- Private prompts, credentials and client-confidential information stay outside the public repository.
