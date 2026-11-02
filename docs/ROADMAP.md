# Demble — Working Roadmap

**Status:** early product definition, subject to validation.

Our north star is to reduce the coordination cost of turning an idea into a shared, testable result for a 2–10-person human + AI coding team.

This roadmap is sliced by **end-to-end validation**, not by arbitrary feature count. It does not commit to release dates or a specific technology stack.

## S0 — A usable team space

**Question:** Can three people discuss and hold a meeting without depending on an external messaging account?

Planned scope: Room membership and basic permissions, real-time group discussion, stable references, basic voice and screen-sharing feasibility, and manually maintained meeting notes.

**Done when:** three members can complete a discussion and meeting; permission boundaries and stable references can be demonstrated.

## S1 — Trusted shared context

**Question:** Can a discussion become a traceable team decision without AI inventing agreement?

Planned scope: source events, decisions, context links, AI change proposals, deduplication, a review inbox, batch review, and context revisions.

**Done when:** humans can review proposals together; confirmed decisions are traceable; replaced decisions do not appear as current truth.

## S2 — Ideas to demos

**Question:** Can the team compare two real prototypes and change direction based on feedback?

Planned scope: experiments, a lightweight plan, versioned artifacts and demos, scoped links, feedback, and experiment comparison.

**Done when:** two developers publish two comparable experiences and feedback stays attached to the correct versions.

## S3 — Agent interoperability

**Question:** Can different coding agents recover the same valid team context without sharing private sessions?

Planned scope: scoped CLI and HTTP context access, context revision identifiers, context packets, minimal progress and artifact reporting, and stale-context indicators.

**Done when:** at least two different harnesses read the same effective decisions and report results back to the appropriate experiment.

## S4 — A sustainable everyday workflow

**Question:** Does the system reduce information overload over two weeks of real use?

Planned scope: incremental recovery summaries, deduplication, search improvements, invited AI discussion support, reduced review noise, and resiliency improvements.

**Done when:** a real team can measure context recovery cost, review cost, and idea-to-demo time, and decide what to improve next.

## Boundaries

- We do **not** plan to replace IDEs or coding agent runtimes.
- We do **not** require a vendor-specific agent harness.
- We do **not** allow AI to confirm team-wide decisions silently.
- We do **not** promise full video-conferencing, local dynamic preview tunneling, or autonomous worker orchestration in the first slice.

The original product requirements draft remains under team review; approved changes will be reflected in this public roadmap.
