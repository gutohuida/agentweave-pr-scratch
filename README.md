# agentweave-pr-scratch

Scratch repository for AgentWeave's pull-request landing drives
(slice 1 "a build lands as one pull request", slice 2 "the PR's CI is the full check").

Nothing here matters. `main` is protected with one required check, `ci-check`,
which **fails whenever a file named `FAIL` exists at the repository root** and passes otherwise.
Add `FAIL` to make CI red on demand; remove it to make it green.
