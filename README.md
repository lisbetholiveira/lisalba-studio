# Lisalba Studio

**Boutique Creative AI studio for distinctive, responsible visual communication.**

Lisalba Studio combines creative direction, generative AI and human editorial judgement to develop visual concepts, content systems and experimental AI products. The studio is designed for brands and independent professionals who need a clear visual point of view without the overhead of a large agency.

This repository is the public, portfolio-safe home of the studio's Creative AI practice. It documents methods, system architecture and selected case studies. It does not contain client-confidential material, credentials, private prompts or commercially sensitive assets.

## Core services

- AI-assisted photography and visual development
- Social media content systems
- Video concepts, short-form video and avatars
- Creative direction and visual identity systems
- Visual campaigns and launch concepts
- AI products, assistants and creative workflows

## Who we work with

- Beauty, skincare and wellness brands
- Fashion, jewellery and accessories brands
- Experts, founders and consultants
- E-commerce businesses

## Value proposition

Lisalba Studio turns a strategic brief into a coherent visual system: conceptually strong, adaptable across formats and transparent about the role of AI. The approach joins boutique-level attention with repeatable workflows, helping small teams move from an idea to a review-ready creative direction efficiently and consistently.

## Stack and process

The stack is selected per project and may combine:

- Research, briefing and structured knowledge tools
- Large language models for analysis, ideation and prompt development
- Generative image, video and avatar tools
- Photography, image editing and layout tools
- Human-led art direction, curation, quality review and final approval

Every project follows a controlled process with explicit checkpoints:

`Brief -> Creative Direction -> Prompt Builder -> Production -> Review`

See [Creative Workflow](docs/creative-workflow.md) for the full process.

The installable [JM Image & Video Prompt Assistant skill](skills/jm-image-video-prompt-assistant/SKILL.md) implements the Prompt Builder handoff. It includes routing, a versioned prompt card, explicit source limitations and a SOLAE structural smoke test. Copy the skill directory into a compatible Codex skills directory to install it; keep the folder structure intact. The seven original JM PDFs and the external GPT's internal instructions are not included or represented as verified.

## Agent system V1

The V1 architecture separates creative responsibilities into five specialised roles:

1. **Coordinator** — defines the route, dependencies and approval points.
2. **Brief Analyst** — translates the request into objectives, constraints and open questions.
3. **Creative Director** — establishes the concept and visual system.
4. **Prompt Builder** — converts the approved direction into production-ready prompt structures.
5. **Quality Reviewer** — checks consistency, craft, factual integrity and responsible-AI requirements.

The agents support the process; human judgement remains responsible for creative direction and final approval. See [Agent System V1](docs/agent-system.md).

## Quality and Responsible AI

Our working principles are:

- Human accountability and final review
- Clear distinction between real, conceptual and AI-generated work
- No invented clients, results, testimonials or performance claims
- Consent, privacy and rights-aware asset use
- Brand consistency, accessibility and context-appropriate craft
- Proportionate fact-checking and documented uncertainty
- No confidential or commercially sensitive material in public repositories

Read the complete [Quality Principles](docs/quality-principles.md).

## Case studies

Selected work will be added only when it can be presented accurately and without exposing confidential material. Each case study will distinguish verified facts from concepts, prototypes and hypotheses.

Browse the [case studies index](case-studies/README.md).

## Status

Foundation repository established. The agent architecture and creative workflow are documented; production integrations and functional tests will be added incrementally after validation.

## About

Lisalba Studio is led by Lisbeth Oliveira. Portfolio: [lisalbastudio.com](https://lisalbastudio.com/)
