# 🎬 Universal AI Film

**Open, portable, human-directed filmmaking — from creative ideas to production workflows.**

Universal AI Film is an open-source ecosystem built around two independent, complementary projects: an AI filmmaking direction library and an optional visual film-planning workspace. Our goal is to help creators plan, review, and eventually produce films with clear creative control, portable project data, and optional production tools.

## Our projects

| Project | What it does | Current status |
| --- | --- | --- |
| [🎬 Universal AI Film Director](https://github.com/universal-ai-film/universal-ai-film-director) | Seven portable agent skills: one Director and six specialists for story, visual direction, cinematography, video production planning, sound and continuity/QA. Project Bible, approval-safe revisions, portable contracts and budget-aware planning. | **V2.6.0 released.** V2.7 is the proposed comprehensive testing milestone. Independent end-to-end agent and real-media quality remain subject to evidence. |
| [🎞️ Universal AI Film Studio](https://github.com/universal-ai-film/universal-ai-film-studio) | Planned accessible, local-first Angular workspace for Project Bible inspection, storyboards, shot timing, references, approvals and future production handoffs. | **Planning / S0–S6 roadmap.** No runnable application or published Studio release yet. The repository may not be publicly accessible during early development. |

**Use Director without Studio.** Studio is optional and will consume versioned, validated Director contracts rather than copying the skills. Neither product requires a paid AI provider as part of its core vision.

## How the ecosystem fits together

```text
             Filmmaker / creator
                     |
        +------------+------------+
        |                         |
   Film Director             Film Studio
   Creative reasoning        Visual planning & review
   Seven agent skills        Local project workspace
   Portable contracts        Accessible Angular UI
        |                         |
        +---- Versioned contracts-+
                     |
       Optional future production adapters
       Manual/local tools or approved providers
```

### Shared integration milestones (proposed)

| Gate | Creator outcome |
| --- | --- |
| **E1 — Contract compatibility** | Studio safely reads versioned Director project snapshots. |
| **E2 — Portable project packages** | Projects, revisions and asset provenance can be transferred and recovered. |
| **E3 — Human-approved handoffs** | Creators review and authorize scoped Director proposals. |
| **E4 — Controlled production** | Optional adapters execute only explicitly authorized jobs and budgets. |
| **E5 — Assembly and QA** | Approved assets can be assembled and evaluated against production criteria. |
| **E6 — AI/live-action interoperability** | Future workflows can coordinate AI-generated, filmed and hybrid projects. |

These are **future coordination goals**, not claims of implemented Studio integration, autonomous media generation or released provider adapters. Each project maintains its own releases and acceptance evidence.

## Principles

- **Creator control:** consequential creative changes, provider operations, spending and publication require explicit approval.
- **Free/local-first:** support manual, offline or local workflows; paid services remain optional.
- **Portable and provider-neutral:** avoid mandatory dependence on one agent host or media provider.
- **Reliable and honest:** distinguish deterministic tests from independent users, real host execution and inspected media quality.
- **Accessible and private:** prioritize usable interfaces, recoverable local project data, consent and rights-aware media handling.
- **Independent products:** each repository owns one canonical roadmap; shared contracts connect them.

## Roadmaps and getting involved

- [Director roadmap](https://github.com/universal-ai-film/universal-ai-film-director/blob/main/docs/ROADMAP.md) — V2.7 validation, proposed V3 production/live-action direction and longer-term research.
- [Studio roadmap](https://github.com/universal-ai-film/universal-ai-film-studio/blob/main/docs/ROADMAP.md) — S0–S6 MVP and proposed post-MVP visual production capabilities.
- [Get started with Director](https://github.com/universal-ai-film/universal-ai-film-director#-get-started) — plan a film with compatible agent skills.

Feedback, reproducible test reports and contributions are welcome through the respective project repositories. Roadmap milestones and target dates are proposals until separately accepted and released.

**Plan thoughtfully. Create responsibly. Keep creative control.**
