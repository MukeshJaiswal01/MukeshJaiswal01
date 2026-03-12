# Mukesh Jaiswal
I am a security engineer specializing in protocol-level blockchain infrastructure and execution environments. My work focuses on analyzing adversarial behaviors in decentralized systems, modeling state transitions, validating cross-component invariants, and identifying architectural failure modes before deployment.

I work across EVM and Rust-based environments and have experience auditing DeFi protocols, cross-chain systems, and Bitcoin-adjacent infrastructure.



 ## Expertise  

- State Transition & Accounting Invariants  
- Cross-Component Trust Boundary Analysis  
- Access Control & Privilege Escalation Modeling  
- Cross-Chain Message Validation & Bridge Safety  
- Execution Environment Assumption Analysis (EVM, WASM, Rust-based systems)  
- Bitcoin-Adjacent Infrastructure & Indexing Security

## Projects


- **AI-Guided EVM Fuzzer** ( Research Project - Internal Tooling )

   AI-Guided EVM Fuzzer is a research tool designed to identify edge-case vulnerabilities in EVM execution environments by combining coverage-guided fuzzing with ml driven input   generation. The system executes contracts in a local REVM environment and analyzes `opcode traces`, `storage writes`, and `gas usage` patterns to guide intelligent transaction generation.

   The framework targets execution edge cases such as gas exhaustion paths, `storage inconsistencies`, reentrancy scenarios, `delegatecall misuse`, and multi-transaction state transition failures. By learning from `execution traces`, the model prioritizes unexplored `opcode paths` and complex `transaction sequences` to expose hidden protocol vulnerabilities.


-  **AI Security Agent** for EVM Audit Automation (Agent based security research assistant - Internal tooling)

     AI Security Agent is a research project exploring how agent-based AI workflows can assist security engineers during EVM audits and protocol security reviews

-  **AI Evm Vulnerability Analyzer** (AI-assisted audit tooling - Internal)
     
     AI Evm Vulnerability Analyzer is a tool designed to assist security engineers during EVM audits by combining static analysis with generative AI reasoning. The system analyzes identifies potential vulnerability patterns such as `race conditions`, `identify possible bottlenecks` that can lead to `Denial-of-Service`, Unnecessarily `large memory allocation`s,      `CORS`,  `pseudo-random number generation` etc.


- [Building Bitcoin with Rust](https://github.com/MukeshJaiswal01/building_bitcoin_with_rust)

  This project explores the implementation of core Bitcoin protocol components using Rust, including a simplified miner, wallet, and node.

   The goal of this repository is to understand how Bitcoin works at a protocol level by implementing key building blocks such as transaction validation, block construction, mining logic, and peer-to-peer networking.

   The project focuses on:

   - Bitcoin transaction structure and validation
   - Block creation and proof-of-work mining
   - Wallet implementation and key management
   - UTXO model and transaction accounting
   - Peer-to-peer node communication
   - Block and mempool propagation
   - Protocol-level security considerations

    By building these components from scratch in Rust, the project provides insight into how decentralized systems maintain consensus, validate state transitions, and ensure network security.
   




  ## Competitive Audits

| Platform | Profile      | Rank |
| ------- | ------------- | -----|
|  CodeArena | [Jmukesh](https://code4rena.com/leaderboard?timeframe=2021)  |  Top 13 Rank (2021)  |  


 ## Tech Stack
| Programmming Language         | 
| ------------------- | 
| **Rust**    |   
| **Solidity/EVM** | 
|  **Clarity**  | 
|  **Bitcoin Script**  | 
| **Javascript / Typescript**  | 
|  **Python** | 




## Public Audit Reports:

| Client | Project Name | Date | Report |
|-----------|---------------|-------|-----------|
|[Mezo](https://mezo.org) | Mezo  | November-December 2025 | Private |
|[tLabs](https://threshold.network) | RebateStaking & Bridge | November 2025 | Private |
|[tLabs](https://threshold.network) | MintBurnGuard | November 2025 | Private |
|[tLabs](https://threshold.network) | WalletRegistry & EcdsaDkg | October-November 2025 | Private |
|[tLabs](https://threshold.network) | Beta Signer Allowlist & Bridge Fee Rebates | September 2025 | Private |
| [Midl Execution Layer](https://midl.xyz/) | Midl Runes Indexation | September 2025 | [:page_facing_up:](https://github.com/Thesis-Defense/Security-Audit-Reports/blob/main/PDFs/250917_Defense_by_Thesis-Midl_Runes_Indexation_Final_Security_Audit_Report.pdf) |
| [Mezo](https://www.mezo.org/) | MezoBridge | September 2025 | [:page_facing_up:](https://github.com/Thesis-Defense/Security-Audit-Reports/blob/main/PDFs/250910_Defense_by_Thesis-MezoBridge_Smart_Contract_Final_Audit_Report.pdf) |
|[Templar Protocol](https://www.templarfi.org) | Templar Smart Contracts | April-July, 2025 | [:page_facing_up:](https://github.com/Templar-Protocol/contracts/tree/dev/audits/2025-07-01/thesis_defense) |
|[NEAR Satoshi Protocol](https://www.ref.finance/) | NEAR Satoshi Bridge | November 2024 | Private |
|[Velar Labs](https://www.velar.co/) | Vyper Smart Contracts | June 2024 | [:page_facing_up:](https://github.com/Thesis-Defense/Security-Audit-Reports/blob/main/PDFs/240717_Thesis_Defense-Velar_Vyper_Smart_Contracts_Security_Audit_Report.pdf) |
|[Velar Labs](https://www.velar.co/) | Clarity Smart Contracts | May 2024 | [:page_facing_up:](https://github.com/Thesis-Defense/Security-Audit-Reports/blob/main/PDFs/240711_Thesis_Defense-Velar_Clarity_Smart_Contracts_Security_Audit_Report.pdf) |
|[Diva Staking](https://divastaking.com/) | Diva Staking| April-May, 2024 | Private |
|[Zest Protocol](https://www.zestprotocol.com/) | Zest Protocol Smart Contracts | April-May, 2024 | [:page_facing_up:](https://github.com/Thesis-Defense/Security-Audit-Reports/blob/main/PDFs/240509_Thesis_Defense-Zest_Protocol_Smart_Contracts_Security_Audit_Report.pdf) |
|[Threshold Network](https://threshold.network/) | tBTC Base Smart Contracts | March 2024 | [:page_facing_up:](https://github.com/Thesis-Defense/Security-Audit-Reports/blob/main/PDFs/240411_Thesis_Defense-Threshold_tBTC_Base_Smart_Contracts_Security_Audit_Report.pdf) |
|[Hermetica](https://app.hermetica.fi/earn) | Hermetica Smart Contracts | March 2024 | [:page_facing_up:](https://github.com/Thesis-Defense/Security-Audit-Reports/blob/main/PDFs/240405_Thesis_Defense-Hermetica_Labs_Hermetica_Smart_Contracts_Security_Audit_Report.pdf) |
|[Mezo](https://info.mezo.org/) | Portal Smart Contracts | March 2024 | [:page_facing_up:](https://github.com/Thesis-Defense/Security-Audit-Reports/blob/main/PDFs/240314_Thesis_Defense-Mezo_Portal_Smart_Contracts_Security_Audit_Report.pdf) |
|[Cube3 Protocol](https://www.cube3.ai/) | Cube3 smart contracts | November 2023 | [:page_facing_up:](https://leastauthority.com/wp-content/uploads/2023/11/Cube3_Smart_Contracts_Final_Audit_Report_Least_Authority.pdf) |
|[The Axelar Network](https://www.axelar.network/) | Axelar Smart Contracts | October 2023 | [:page_facing_up:](https://github.com/axelarnetwork/audits/blob/main/audits/2023-10%20Least%20Authority.pdf) |
|[NEOKingdom DAO](https://www.neokingdom.org/) | DAO smart contracts | October 2023 | [:page_facing_up:](https://leastauthority.com/wp-content/uploads/2023/10/NEOkingdom_DAO_Smart_Contracts_Final_Audit_Report_Updated.pdf) |
|[FilFi](https://filfi.io/) | Filfi smart contracts | October 2023 | [:page_facing_up:](https://leastauthority.com/wp-content/uploads/2023/10/FilFi_Smart_Contracts_Final_Audit_Report_Least_Authority.pdf) |
|[Keep Network](https://keep.network/) | Solana smart contracts | September 2023 | [:page_facing_up:](https://leastauthority.com/wp-content/uploads/2023/08/Thesis_Keep_Network_Solana_Smart_Contracts_Final_Audit_Report_Least_Authority.pdf) |
|[Generative Labs](https://www.generativelabs.co/) | Web3MQ MetaMask Snap Implementation | September 2023 | [:page_facing_up:](https://leastauthority.com/wp-content/uploads/2023/09/Generative_Labs_Web3MQ_Snap_Final_Audit_Report_Least_Authority.pdf) |
|[Golem Foundation](https://golem.foundation/projects) | Octant smart contracts | July 2023 | [:page_facing_up:](https://leastauthority.com/wp-content/uploads/2023/07/Golem_Foundation_Octant_Smart_Contracts_3rd_Review_Final_Audit_Report.pdf) |
|[Ava Labs](https://avalabs.org) | Teleporter Bridge| July 2023 | [:page_facing_up:](https://github.com/ava-labs/teleporter/blob/main/audits/historical/Bridge%20Smart%20Contracts%20Audit%20Report%20(July%207th%202023)%20-%20Least%20Authority%20.pdf) |
|[Zest Protocol](https://www.zestprotocol.com/) | Zest Protocol smart contracts | March 2023 | [:page_facing_up:](https://leastauthority.com/static/publications/230316_Zest%20Protocol_Trust%20Machines_Updated_Final_Security_Audit_Report_march_2023.pdf) |
|[Data Lake](https://data-lake.co/) | Token Vesting smart contracts | December 2022 | [:page_facing_up:](https://leastauthority.com/static/publications/LeastAuthority_Data%20Lake%20Token_Vesting_Smart_Contracts_Final_Audit_Report.pdf) |
|[Data Lake](https://data-lake.co/) | Consent smart contracts | December 2022 | [:page_facing_up:](https://leastauthority.com/static/publications/221222_Data_Lake_Consents_Smart_Contracts_Final_Audit_Report.pdf) |
|[POAP](https://poap.xyz/) | POAP Smart Contracts | December 2022 | [:page_facing_up:](https://cantina.xyz/portfolio/784bde12-36c6-4469-8dfa-50b1ae830f9d) |
|[Lyra Finance](https://lyra.finance/) | Lyra Smart Contracts | June 2022 | [:page_facing_up:](https://github.com/sherlock-protocol/sherlock-reports/blob/main/audits/2022.06.27%20-%20Final%20-%20Lyra%20Audit%20Report.pdf) |
|[Lock Protocol](https://twitter.com/lockeprotocol) | Locke Smart Contracts | February 2022 | [:page_facing_up:](https://cantina.xyz/portfolio/da4ec996-9e8f-4beb-8fe0-32e1c87e4ddb) |
|[Tempus finance](https://tempus.finance/) | Tempus Smart Contracts | February 2022 | [:page_facing_up:](https://github.com/sherlock-protocol/sherlock-reports/blob/main/audits/2022.02.09%20-%20Final%20-%20Tempus%20Audit%20Report.pdf) |
















