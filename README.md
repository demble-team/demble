# Demble

**Build ideas with friends and agents.**

[简体中文](README.zh-CN.md) · [Roadmap](docs/ROADMAP.md) · [Contributing](CONTRIBUTING.md)

Demble is a source-available, self-hostable collaboration workspace for small startup teams and their AI coding agents.

Bring your friends. Bring your favorite coding agents. Explore ideas, make decisions, build competing demos, and learn from real feedback—without repeatedly copying context between people and tools.

> **Project status: early design / pre-alpha.** This repository currently describes the product vision and planned milestones. There is no installable release or public demo yet. The capabilities below are **planned**, not shipped.

## The problem

AI makes coding and prototyping faster, but working together can still be slow:

- Important decisions disappear in long chats, meeting notes, and agent sessions.
- Different people and coding agents work from different versions of the plan.
- Trying several ideas is easy; comparing real demos and deciding what to build next is not.
- Keeping everyone aligned requires too much manual summarization, copying, and status updating.

Demble aims to make coordination lightweight while keeping humans in charge.

## The idea

Each project lives in a **Room** where the team can:

1. **Talk** — use built-in discussions and meetings, with stable links to source material.
2. **Capture** — let AI suggest decisions, experiments, tasks, and relationships from the conversation.
3. **Review** — approve, edit, or dismiss those suggestions **in batches**. AI suggestions never silently become team decisions.
4. **Experiment** — test multiple directions in parallel and share versioned demos.
5. **Learn** — collect feedback, revisit decisions, and update a traceable plan.
6. **Continue building** — let developers use their own coding agents with a permission-scoped, versioned context interface.

The goal is **a shared understanding of what the team has actually agreed to**, not an AI that autonomously manages the team.

## Principles

- **Human-led.** People own priorities, permissions, decisions, and acceptance.
- **AI when useful.** AI organizes information quietly and joins discussions when invited.
- **Review before truth.** Raw evidence, AI proposals, and confirmed knowledge are separate states.
- **Harness-agnostic.** Codex, Claude Code, OpenCode, and other tools should be able to work with the same context; Demble does not require a specific agent runtime.
- **Experiment-first.** A demo and the evidence it produces matter more than a complicated task board.
- **Traceable.** Decisions and changes link back to their sources and revisions.
- **Self-hostable.** Core collaboration should not depend on a third-party messaging workspace.
- **Low noise.** Not every message should become a task or notification.

## What Demble is not

- Not another coding-agent harness or an autonomous agent swarm scheduler.
- Not a replacement for your IDE, Git host, or existing coding agents.
- Not a fully featured enterprise chat platform.
- Not a system where unreviewed AI output can silently rewrite official team plans.

## Roadmap

We are validating the product in small, end-to-end slices rather than committing to a large feature checklist.

| Slice | Goal | Status |
| --- | --- | --- |
| S0 · Team space | Rooms, discussion, references, basic meetings and permissions | Planned |
| S1 · Trusted context | Evidence, AI proposals, batch review, confirmed revisions | Planned |
| S2 · Ideas to demos | Experiments, versioned artifacts, feedback, comparisons | Planned |
| S3 · Agent interoperability | Scoped context packets and lightweight result reporting | Planned |
| S4 · Everyday flow | Better recovery, summaries, search, and reduced review noise | Planned |

See the [working roadmap](docs/ROADMAP.md) and the [product requirements draft (Chinese)](docs/PRD-v0.5.md). Scope and ordering may change after real team testing.

## Get involved

We are especially interested in how small teams build with different AI coding agents today.

- Share a specific collaboration problem or a possible experiment in an Issue.
- Challenge our assumptions about meeting notes, shared memory, and review workflows.
- Propose a small, testable change before starting a large implementation.

Please read [CONTRIBUTING.md](CONTRIBUTING.md) first. For security-sensitive reports, see [SECURITY.md](SECURITY.md).

## License

PolyForm Perimeter License 1.0.1. See [LICENSE](LICENSE).

Personal and internal business use are permitted under the license. Using Demble to provide a competing product or service to others, even free of charge, is not permitted under this license. Other non-competing uses may be permitted; the full license terms govern. This is source-available software, not OSI-approved open source.
