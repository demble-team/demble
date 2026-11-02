# Contributing to Demble

Thanks for helping make small-team, human-led AI development better.

Demble is in **pre-alpha / product validation**. We welcome concrete problem reports, experiments, documentation fixes, design prototypes, and small code contributions as an implementation emerges.

## Before opening an Issue

1. Search existing Issues and Discussions to avoid duplicates.
2. Describe the real workflow and the coordination cost, not only a proposed feature.
3. If possible, describe the smallest experiment that would show whether an idea works.
4. Remove secrets, private agent transcripts, sensitive meeting content, and credentials from examples.

## Before opening a Pull Request

1. For non-trivial changes, discuss the scope in an Issue first.
2. Keep changes focused and reviewable. Include relevant documentation or tests when implementation exists.
3. Explain how the change affects people, coding agents, and shared context.
4. Do not introduce a required third-party messaging platform or a mandatory coding-agent harness without explicit project approval.
5. Do not silently turn AI-generated proposals into confirmed decisions or plans.
6. If behavior, data contracts, or permissions change, describe migration and compatibility implications.

We have not selected a permanent language, framework, database, or test runner yet. Please avoid treating a particular stack as an agreed requirement.

## Working philosophy

- Humans review consequential decisions.
- Source evidence and revisions stay traceable.
- Experiments should have a clear question and outcome.
- New abstractions should justify their cost to a 2–10-person team.
- Harness interoperability is a product boundary, not a reason to build another agent runtime.

Security issues should not be filed publicly. Please follow [SECURITY.md](SECURITY.md).
