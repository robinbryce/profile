---
layout: cv
title: Robin Bryce, CV
---

# Robin Bryce

[GitHub](https://github.com/robinbryce/) • [LinkedIn](https://www.linkedin.com/in/robin-bryce-02b3464/) • [Medium](https://robinbryce.medium.com/) • [Games Credits](https://www.mobygames.com/person/120567/robin-bryce/credits/)

> **Robin is a prolific, creative, and driven builder and entrepreneur.** He thrives in highly dynamic, fast-paced environments and enjoys working alongside like-minded, high-caliber individuals. His work spans applied cryptography, digital transparency, and blockchain gaming, where he brings deep expertise in protocol architecture, distributed systems, and smart contract development. Robin is particularly passionate about building systems that align technical innovation with user trust—whether through scalable cryptographic infrastructure, decentralized identity, or game mechanics that push the boundaries of autonomous worlds.

## Currently

Principal Engineer, [Datatrails](https://www.datatrails.ai/).
Co-Founder, [Polysensus](https://www.polysensus.io/).

## Career Summary

* **2018 - Principal Engineer**, leading the research and development of Datatrails' digital provenance solution. Responsible for product architecture. Subject matter expert on applied cryptography, distributed consensus, verifiable transparency, and smart contract programming.
* **2005 - 2018**: Enjoyed a 13-year freelance contracting career specializing in security applications and HSM firmware, with some exposure to medical devices and post-processing of enormous data sets in the form of gene sequencing data.
* **2003: Founded Wiretooth**, initially conceived as a maker of multiplayer SMS games.
* **1994 - 2003**: Early career in the games industry, credited on many successful and popular console and PC games, primarily as a graphics engine programmer responsible for maximizing performance across various hardware platforms.

\newpage

## Leadership & Impact

* **Technical Vision & Architecture**: Served as design authority across all aspects of the Datatrails platform. Defined the architecture for a highly scalable, cryptographically verifiable provenance system adopted in enterprise settings and presented at IETF.
* **Inventing Under Constraints**: Patented an MMR-based ledger (Forestrie), enabling blockchain-grade transparency with 10–100× performance improvements and 1000× cost reduction compared to traditional L1 systems. Work published through IETF and adopted in production.
* **Consensus & Scale**: Designed a custom BFT-style consensus layer for go-ethereum/go-quorum, increasing validator capacity from ~20 to 1000+ while maintaining <2s latency and 500+ TPS. Implemented and validated in production environments.
* **Product Leadership**: Led the Media Authenticity & Auditability product line at Datatrails—integrating watermarking tech into a white-label platform, managing external contributors, and aligning diverse stakeholder needs into a deliverable product.
* **Performance Engineering**: Delivered a 1000× platform throughput improvement by re-architecting internal messaging, reducing broker overhead, and scaling system components.
* **Federated Identity & Onboarding**: Delivered OAuth2, SSO, and social login integration for multi-tenant systems. Reduced enterprise onboarding from days to hours and supported commercial deployments.
* **Standards & Influence**: Authored multiple IETF drafts, presented at Google Transparency Dev 2024, and contributed to COSE and SCITT standardization efforts, positioning Datatrails as a thought leader in transparency infrastructure.
* **Composable Game Clients**: Built an independent, real-time rendering client for Dust (DagCity) based solely on on-chain smart contract state—demonstrating autonomous world UX can be built without any backend or privileged infrastructure.
* **Funding & Entrepreneurship**: Secured £15,000 Optimism Foundation grant for Chaintrap, a choose-your-own-adventure blockchain game implementing novel commit-reveal and merklized move validation mechanisms.
* **Team Development & Mentorship**: Mentored all engineering hires at Datatrails and managed challenging HR cases with discretion. Built a cohesive, high-trust team culture.

\newpage

## Mentorship & Team Development

* Responsible for onboarding and mentoring all new engineering hires at Datatrails, helping them integrate quickly and contribute effectively.
* Experienced in handling sensitive HR matters, including performance management and dismissal processes, with professionalism and discretion.
* Personally mentored two A-Level students: one secured a degree apprenticeship with IBM; the other gained admission to a finance degree program with support and a reference.

## Key Skills & Domain Expertise

- **Languages**: Go, Solidity, TypeScript, Python, Bash  
- **Smart Contracts & ERC's**: ERC-721, 1155, 4337, 6551; non-custodial wallet solutions (zerodev, web3auth) and onboarding, foundry-rs
- **Storage, Persistence & Application Security**: Redis, MongoDB, PostgreSQL, Traefik, Istio, Cert-Manager/LetsEncrypt, Azure Blob Store, Google Object Store
- **Infrastructure**: Kubernetes, Terraform, Flux, Flagger, GitOps; Azure, GCP  
- **Frontend**: SvelteKit, TailwindCSS, SkeletonUI, Vite  
- **Identity & Standards**: TLS auth, OAuth2, OpenID Connect, IETF COSE & SCITT  
- **Applied Crypotography**: ECDSA, VRF's, Arithmetic circuits, polynomial commitments, verkel trees
- **System Design**: Distributed systems, applied cryptography, consensus algorithms, verifiable data structures, GPU rendering

\newpage

## Selected Open Source & Standards Work

- [**go-datatrails-merklelog**](https://github.com/datatrails/go-datatrails-merklelog) – Production-grade MMR library  
- [**COSE MMR Proofs (IETF)**](https://datatracker.ietf.org/doc/draft-bryce-cose-merkle-mountain-range-proofs/) – Author of standards-track draft  
- [**Chaintrap Game Contracts**](https://github.com/polysensus/chaintrap-contracts) – On-chain narrative game (Optimism Grant)  
- [**RRR Consensus**](https://github.com/RobustRoundRobin/go-rrr) – High-throughput BFT consensus implementation  
- [**Iona Infra**](https://github.com/robinbryce/iona/) – GitOps-based, zero-cost-at-idle deployment infra


## Blockchain Gaming & Writing

- [**The Persistence of Ten-Year-Olds**](https://robinbryce.medium.com/the-persistence-of-ten-year-olds-and-reading-trie-leaves-in-fog-40417f9c85bf) – Background and narrative design for Chaintrap, an on-chain choose-your-own-adventure game funded by Optimism.
- [**From Pages to Tree Leaves**](https://robinbryce.medium.com/from-pages-to-tree-leaves-c44ea9c81fa2) – Explores commit-reveal mechanisms for branching narratives on the blockchain.
- [**Autonomous Worlds Hack 2024**](https://robinbryce.medium.com/autonomous-worlds-2024-c7833daa111a) – Used ERC-6551 on Redstone to allow cross-game world token interactions without code changes.
- Finalist in the Redstone launch hackathon, contributing the frontend for AW Tug of War—a dual-world on-chain game mechanic using a shared “rope”.

\newpage

## Career Highlights

### Polysensus – Co-Founder (2021–Present)

* Founded a blockchain gaming R&D studio focused on smart contract-based autonomous game mechanics.
* Delivered [Chaintrap](https://chaintrap-ifw.vercel.app/) – an on-chain, branching narrative game using commit-reveal and bespoke system for merklized proof of valid moves. [Grant Application](https://gov.optimism.io/t/final-chaintrap-builders-cycle-11/5526)
* Explored novel cross game mechanics using MUD2 and ERC-6551, including cross-world item ownership and interaction.
* Actively contributes to the Autonomous Worlds community through hackathons, demos, and ecosystem experimentation.
* Delivered the first independent, interactive client for an autonomous world (Dust x DagCity) using only the on-chain smart contract interface. Demonstrated real-time rendering, state sync, and gameplay in a system not built by us — without backend or internal access.

### Datatrails – Principal Engineer (2018–Present)

* Invented and developed [Forestrie](https://www.datatrails.ai/we-are-not-a-blockchain-company/), Datatrails patented digital provenance ledger
* Invented and developed a patented, privacy preserving, auditable transparent smart contract system for digital provenance in enterprise ethereum EVM systems which support private transactions.
* Design authority for all aspects of the Datatrails transparency ledger
* Subject matter expert for applied cryptography, blockchain, smart contracts, and distributed consensus protocols
* Drove performance, cost optimization, and protocol innovation
* Delivered IETF contributions and open source adoption strategies
* Program manager for Media Authenticity & Auditability product line
* Lead developer of the open-source [Merkle Mountain Range](https://github.com/datatrails/go-datatrails-merklelog) library used in Forestrie

### Contracted Roles (2005–2018)

- **Thales / Entrust**: HSM firmware, Python runtime in secure enclaves, delivered EIDAS re-certification for nShield HSMs in Brazil by defending firmware in lab review
- **Illumina**: Gene sequencing application platform, hardware buildout & software.
- **nCipher / Thales**: Apache + PKCS#11 HSM integrations, distributed key management, cross-platform builds

During this time, I worked 8-10 months of the year in Cambridge UK, then spent the remainder working in the French or Swiss alps as a Ski instructor. Amongst other elite level ski qualifications I obtained a Eurotest Pass. A ski racing speed test measured against the worlds best ski racers.

\newpage

## Patents

- **2021** – Digital provenance with smart contracts – [GB2614297](https://www.ipo.gov.uk/p-ipsum/Case/PublicationNumber/GB2614297)  
- **2024** – MMR + cloud storage for transparency logs – [PC933720GB]


## Publications & Talks

- [**COSE MMR Proofs (IETF)**](https://datatracker.ietf.org/doc/draft-bryce-cose-merkle-mountain-range-proofs/)  
- [**MMRs vs RFC 6962**](https://www.datatrails.ai/if-you-go-down-to-the-woods-today/)  
- [**Google Transparency Dev 2024**](https://www.youtube.com/watch?v=pfMVQBUZfbQ)  
- [**Autonomous Worlds Hack**](https://robinbryce.medium.com/autonomous-worlds-2024-c7833daa111a)

## Early Career – Game Development (1994–2005)

### Wiretooth Ltd – Co-Founder (2003–2005)

- Created multiplayer SMS games with innovative payment integration  
* Traveled with China-UK ICT delegation; negotiated partnerships for games and book content, proposed sms game launch for chinese olympic games.
- Closed after early traction but limited funding, and the emergence of large screen phones.

## Game Development (1994–2003) - Revolution Software, Kuju Limited, Frontier Developments

- Credited in roles including Lead Programmer, Graphics Engine Lead, and Project Lead on 7 tripple A games.
- Delivered console ports (Dreamcast, Xbox, PS2)
- Developed neural net-based AI behavior models for DTI SMART Award-winning project


## Education & Legacy Skills

- **Education**: 3 years of (Hons) BSc Computing (1994), 5 Higher Grades (Scottish A-levels)  
- **Legacy Tools**: C/C++, DirectX, device drivers, Ansible, Jenkins, bespoke kernels

\newpage

| Description | URL |
|-------|-----|
| GitHub | https://github.com/robinbryce/ |
| LinkedIn | https://www.linkedin.com/in/robin-bryce-02b3464/ |
| Medium | https://robinbryce.medium.com/ |
| Games Credits | https://www.mobygames.com/person/120567/robin-bryce/credits/ |
| Datatrails | https://www.datatrails.ai/ |
| Polysensus | https://www.polysensus.io/ |
| **go-datatrails-merklelog** | https://github.com/datatrails/go-datatrails-merklelog |
| **COSE MMR Proofs (IETF)** | https://datatracker.ietf.org/doc/draft-bryce-cose-merkle-mountain-range-proofs/ |
| **Chaintrap Game Contracts** | https://github.com/polysensus/chaintrap-contracts |
| **RRR Consensus** | https://github.com/RobustRoundRobin/go-rrr |
| **Iona Infra** | https://github.com/robinbryce/iona/ |
| **The Persistence of Ten-Year-Olds** | https://robinbryce.medium.com/the-persistence-of-ten-year-olds-and-reading-trie-leaves-in-fog-40417f9c85bf |
| **From Pages to Tree Leaves** | https://robinbryce.medium.com/from-pages-to-tree-leaves-c44ea9c81fa2 |
| **Autonomous Worlds Hack 2024** | https://robinbryce.medium.com/autonomous-worlds-2024-c7833daa111a |
| Chaintrap | https://chaintrap-ifw.vercel.app/ |
| Grant Application | https://gov.optimism.io/t/final-chaintrap-builders-cycle-11/5526 |
| Forestrie | https://www.datatrails.ai/we-are-not-a-blockchain-company/ |
| Merkle Mountain Range | https://github.com/datatrails/go-datatrails-merklelog |
| GB2614297 | https://www.ipo.gov.uk/p-ipsum/Case/PublicationNumber/GB2614297 |
| **MMRs vs RFC 6962** | https://www.datatrails.ai/if-you-go-down-to-the-woods-today/ |
| **Google Transparency Dev 2024** | https://www.youtube.com/watch?v=pfMVQBUZfbQ |
| **Autonomous Worlds Hack** | https://robinbryce.medium.com/autonomous-worlds-2024-c7833daa111a |

