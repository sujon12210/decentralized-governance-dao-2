# Decentralized Governance DAO

A complete smart contract suite for launching a DAO. This repository implements a robust governance system where stakeholders can propose actions, vote on them, and execute successful proposals automatically.

## Governance Workflow


1. **Proposal:** A member with sufficient tokens creates a proposal (e.g., "Transfer 10 ETH to Project X").
2. **Voting:** Token holders vote "For", "Against", or "Abstain" during the voting period.
3. **Quorum & Success:** If the quorum is met and the majority votes "For", the proposal succeeds.
4. **Execution:** The DAO executes the proposal's encoded function call.

## Features
* **Token-Weighted Voting:** Influence is proportional to the number of governance tokens held.
* **Timelock Integration:** Delayed execution of passed proposals for added security.
* **OpenZeppelin Governance:** Built on top of industry-standard, audited patterns.

## Tech Stack
* **Solidity:** 0.8.20
* **Tokens:** ERC20Votes (Checkpoints-enabled for historical voting power)
