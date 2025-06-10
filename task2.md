| **Blockchain Name**    | **Type**   | **Consensus Mechanism Used**        | **Permission Model** | **Speed / Throughput (TPS)**   | **Smart Contract Support** | **Token Support** | **Typical Use Case**                                | **Notable Technical Feature**              |
| ---------------------- | ---------- | ----------------------------------- | -------------------- | ------------------------------ | -------------------------- | ----------------- | --------------------------------------------------- | ------------------------------------------ |
| **Ethereum**           | Public     | Proof of Stake (PoS)                | Open                 | \~30 TPS (Base Layer)          | Yes (Solidity, Vyper)      | Native (ETH)      | Decentralized Apps (dApps), DeFi                    | EVM Compatibility, Global Decentralization |
| **Hyperledger Fabric** | Private    | Pluggable (default: RAFT / PBFT)    | Permissioned         | \~3,000 TPS                    | Yes (Go, Java, Node.js)    | No Native Token   | Enterprise Supply Chains, Private Business Networks | Modular Architecture, Private Channels     |
| **R3 Corda**           | Consortium | Notarization (by Designated Notary) | Permissioned         | \~170 TPS (with single notary) | Yes (JVM Languages)        | No Native Token   | Inter-bank Settlements, Trade Finance               | Point-to-Point Transactions, Privacy Focus |


📝 Short Report: Technical Comparison of Blockchain Platforms

The three platforms—Ethereum, Hyperledger Fabric, and R3 Corda—offer distinct capabilities tailored for different operational scenarios.

Ethereum, as a public blockchain, emphasizes openness and decentralization. It supports Turing-complete smart contracts via Solidity and Vyper and has a large global node base. Its major limitation lies in lower throughput (~30 TPS) and relatively high latency, though rollups and Layer 2 solutions address scalability challenges.

Hyperledger Fabric excels in private enterprise scenarios. Its permissioned model offers high throughput (~3,000 TPS) and fine-grained control over access through private channels. Smart contracts (called Chaincode) are supported in mainstream languages like Go and Java, but Fabric lacks a native token, limiting decentralized economic incentives.

R3 Corda is consortium-focused, designed for financial institutions needing privacy. It uses point-to-point messaging rather than global broadcast, ensuring transaction confidentiality. With limited throughput (~170 TPS), Corda does not support native tokens but allows custom asset representation, ideal for secure inter-bank or trade operations.

Platform Choices:
Decentralized App: Ethereum—best for open, global, censorship-resistant applications.
Supply Chain Network (Known Partners): Hyperledger Fabric—ideal due to private channels and high TPS.
Inter-Bank Financial Application: R3 Corda—tailored for privacy, regulated environments, and complex financial workflows.
Each selection aligns with the platform’s architectural strengths and intended enterprise or public use case.
