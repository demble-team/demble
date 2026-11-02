# Demble team working agreement

Status: initial operating workflow. Product and technical choices remain subject to review.

## Maintenance

The project is maintained in the [demble-team organization](https://github.com/demble-team).
The `@demble-team/maintainers` team shares implementation and review responsibility.
Organization owners manage membership and repository administration. Repository access
is granted through teams; ordinary contributors do not need organization Owner access.

The current organization owner is `@SH1ROd`. A second trusted owner and individual
product, technical, and release responsibilities remain to be agreed with the team.
Do not treat this document as assigning responsibilities to people who have not accepted them.

## Development workflow

1. For a non-trivial change, open or select an Issue with a concrete goal and acceptance criteria.
2. Work on a focused branch, such as `feat/room-membership`, `fix/message-reference`, or `docs/context-contract`.
3. Open a pull request describing the problem, behavior, verification, and remaining questions.
4. Obtain approval from at least one other reviewer and resolve review conversations.
5. Squash merge into `main`, then remove the completed branch.

Keep `main` protected from force pushes and deletion. Repository administrators may
use the pull-request bypass for necessary bootstrap or recovery work; explain the
reason in the PR. Routine changes should follow the normal review process.

CI requirements will be added after actual checks are available and passing.
There is no agreed application stack or release pipeline yet.

## Decisions and disagreements

Discuss consequential product, architecture, permission, and scope changes in an Issue
or PR. Record the outcome, rationale, participants, and unresolved objections.
Do not describe a disputed proposal or AI inference as confirmed team agreement.
Keep work blocked by an unresolved decision visible instead of silently changing scope.

The current license is [PolyForm Perimeter 1.0.1](LICENSE). Changes to licensing,
commercial authorization arrangements, and contribution rights require a separate
explicit agreement; GitHub administrative permissions are not that agreement.

## Security and growth

Use individual GitHub accounts and enable two-factor authentication before the
organization makes it mandatory. Report vulnerabilities using [SECURITY.md](SECURITY.md).

Start with one maintainers team. Split ownership by area when real review workloads
justify it, and update CODEOWNERS and this agreement together. Revisit owner continuity,
member access, and release responsibility when members join or leave.
