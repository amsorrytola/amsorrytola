# 💫 About Me
🏛️ 4th year student at **IIT Roorkee** (Integrated BS-MS, Economics). <br>
💻 I build at the intersection of **AI · Blockchain · Backend · DevOps** — agentic systems, sovereign-memory frameworks, on-chain AI, and high-throughput data pipelines. <br>
🥇 EthOnline 2025 • 🥇 Starknet ReSolve 2025 • 🥇 ETHGlobal New Delhi 2025 • 🥇 StackTooDeep 2024 • 🥇 Syntax Error 2024 • 🏆 Coinbase Prize Pool (Agentic Ethereum) • 🥇 Bit-by-Bit 2025 • 🥇 Technical General Championship (Polkadot) • 🥈 RuleZ x AI Hackathon (OpenZ) <br>
⚒️ Open-source contributor at **Protocol Labs Dev Guild (PLDG)** · Buidler at **BuidlGuidl Batch 15** <br>
👯 Open to collaborate on **AI agents, multi-agent systems, DeFi, on-chain AI, and backend/infra** projects.

---

## 💼 Experience

- **Protocol Labs Dev Guild (PLDG)** — *Open Source Contributor* &nbsp;·&nbsp; *Jan 2026 – Mar 2026*
  Cross-chain message decoders (Wormhole, Chainlink CCIP v1.2, LayerZero) in Go, AkaveLog distributed log-ingestion system, and the Storacha rclone cross-cloud CLI. PRs listed below.

- **Freelance (Contract) — AI Backend Engineer** &nbsp;·&nbsp; *Dec 2025 – Feb 2026*
  Built an **agentic AI backend** for CPA-firm benchmarking: FastAPI + **LangGraph** + Gemini, **natural-language-to-SQL**, multi-step tool-calling state machine, persistent multi-turn sessions over MySQL, dockerized deployment.

- **Freelance (Contract) — Full-Stack AI Engineer (LekhaPal)** &nbsp;·&nbsp; *Sep 2025 – Nov 2025*
  Mobile-first **OCR + data-extraction** backend (Node.js, Express, Prisma) powered by **Gemini multimodal AI**. Converts PDFs/Excels/CSVs/photos into editable tables with **Hindi + English OCR**; ships to a production React Native client.

- **BlockSeBlock** — *Blockchain Developer Intern* &nbsp;·&nbsp; *Jun 2025 – Jul 2025*
  Built **LexAI**, an on-chain AI assistant on **ICP** using Rust with persistent state, LLM workflows, and full-stack Next.js integration.

---

## 🚀 Featured Projects

- 🛡️ **SovereignClaw** — Sovereign-Memory Multi-Agent AI Framework on 0G
  [GitHub](https://github.com/lalla-ai/SovereignClaw)
  → Open-source multi-agent framework: encrypted sovereign memory on 0G Storage (AES-256-GCM, wallet-derived KEK), **ERC-7857 iNFT** lifecycle with **EIP-712 oracle proofs**, **TEE-attested LLM inference** via 0G Compute Router, and a Next.js visual builder (**ClawStudio**) with drag-and-drop → code → one-click iNFT deploy. **5 npm packages**, 2 Solidity contracts live on 0G Galileo, **1.5 s** cryptographic memory-revocation latency.

- 🤖 **YieldCraft**
  [GitHub](https://github.com/YieldCraft-AI) • [Demo](https://ethglobal.com/showcase/yieldcraft-ai-96iaa) — Won 🥇 1st at ETHGlobal New Delhi (Hedera Track — **$2,000**).
  → AI-powered cross-chain DeFi yield optimizer for all your assets.

- 🛡️ **SaucerHedge**
  [GitHub](https://github.com/SaucerHedge) • [Demo](https://ethglobal.com/showcase/saucerhedge-4mzv0) — Won 🥇 1st at ETHOnline 2025 (Hedera × Lit Protocol — **$1,000**).
  → AI-powered hedging protocol against IL for SaucerSwap LPs on Hedera.

- ⚡ **BitYield Protocol**
  [GitHub](https://github.com/CodeBlocker52/BitYield-Protocol) • [Demo](https://devpost.com/software/bityield-protocol) — Won 🥇 1st at Starknet ReSolve Hackathon (StarkWare Prize Pool — **$2,500**).
  → Bitcoin-native yield optimization protocol with AI agents automating strategies across multiple Starknet protocols.

- 🧠 **Hyperion RuneLand**
  [GitHub](https://github.com/amsorrytola/Hyperion-RuneLand) — Won 🥇 Technical General Championship (Polkadot Problem Statement), IIT Roorkee 2025.
  → 2D decentralized game running on Bitcoin via the Runes Protocol.

- 🌉 **Secure Invoice — On-chain Real-Time Payments & Invoicing**
  [GitHub](https://github.com/arsh0429/Bit-by-Bit) — Won 🥇 at Bit-by-Bit, Cognizance.
  → Invoicing + real-time payments for freelancers, private tutors, mentors, and gig workers.

- 🔋 **Gas Abstraction Wallet (ERC-4337)**
  [GitHub](https://github.com/Av1ralS1ngh/Gas-Modulation-App) — Won 🥇 at Syntax Error 2024.
  → Account-abstraction wallet that auto-pays gas fees for small transactions using a local pool.

- 🧠 **AI Agent–Assisted DeFi Learning Platform (DeFi Dojo)**
  [GitHub](https://github.com/arnavkirti/DeFi-Dojo) — Won 🏆 Coinbase Prize Pool, Agentic Ethereum.
  → Interactive platform where AI agents guide users through DeFi concepts, simulate strategies, and tailor learning paths.

---

## 🛠️ Open Source

#### A selection of PRs shipped for [OpenSre](https://github.com/Tracer-Cloud/opensre) -- The open-source framework for AI SRE agents, and the training and evaluation environment they need to improve. Connect the 60+ tools you already run, define your own workflows, and investigate incidents on your own infrastructure.

- [PR #2891](https://github.com/Tracer-Cloud/opensre/pull/2891) -- This PR delivers the P1 scope of [issue #2831](https://github.com/Tracer-Cloud/opensre/issues/2831) — three read-only Redis investigation tools that extend coverage beyond the baseline diagnostics (server info, slowlog, replication, key scan). Following the issue guidance to "start with P1 and ensure a demo is there e2e", it targets the highest-signal diagnostics for the most common Redis incidents: queue backlogs, connection-pool exhaustion, and latency spikes
- [PR #2747](https://github.com/Tracer-Cloud/opensre/pull/2747) -- Adds a thin, planner-selectable CloudTrail wrapper tool — OpenSRE's first AWS change-causality source — so an investigation can answer "who changed what, and when?" (IAM changes, security-group mutations, EKS/Lambda config updates, deletions) at the start of an AWS post-mortem.
- [PR #2679](https://github.com/Tracer-Cloud/opensre/pull/2679) -- Adds a Jenkins CI/CD integration — OpenSRE's first CI/CD source — so investigations can answer "was there a recent build or deployment that coincides with this alert?"
- [PR #2663](https://github.com/Tracer-Cloud/opensre/pull/2663) -- Adds short terminal GIF demonstrations after the first three Quickstart steps, as requested in #2658, so new users can see the expected workflow and a successful run of each step — now with both macOS/Linux and Windows demos



#### A selection of PRs shipped during my Protocol Labs Dev Guild cohort across three flagship repos.

##### Storacha / rclone — cross-cloud CLI (S3 ↔ Storacha ↔ IPFS via CIDs)
- [PR #6](https://github.com/gulshanpr/storacha-rclone/pull/6) — `cp` command (S3 → Storacha) with streaming upload
- [PR #7](https://github.com/gulshanpr/storacha-rclone/pull/7) — S3 object deletion with batch support
- [PR #8](https://github.com/gulshanpr/storacha-rclone/pull/8) — `storacha-rm` command for removing uploads from a Storacha space
- [PR #9](https://github.com/gulshanpr/storacha-rclone/pull/9) — `storacha-get` command to download files from Storacha
- [PR #10](https://github.com/gulshanpr/storacha-rclone/pull/10) — Bidirectional `cp` command (Storacha ↔ S3)

##### AkaveLog / akave-pldg — distributed log ingestion in Go
- [Issue #24](https://github.com/akave-ai/akave-pldg/issues/24) — Phase 3: Storage Layer (Akave O3 integration)
- [PR #14](https://github.com/anuragShingare30/akave-pldg/pull/14) — Phase 4: Metadata indexing layer (PostgreSQL)
- [PR #15](https://github.com/anuragShingare30/akave-pldg/pull/15) — Phase 5: Streaming query engine
- [PR #16](https://github.com/anuragShingare30/akave-pldg/pull/16) — Phase 6: Log Explorer frontend
- [PR #17](https://github.com/anuragShingare30/akave-pldg/pull/17) — Phase 7: Alerting layer (threshold/keyword workers)
- [PR #20](https://github.com/anuragShingare30/akave-pldg/pull/20) — Phase 8: Identity layer / API-key auth

##### Akave Crosschain Archive — Go decoders + REST APIs
- [PR #29](https://github.com/Patrick-Ehimen/akave-crosschain-archive/pull/29) — Wormhole protocol decoder (VAA parsing, address normalization)
- [PR #31](https://github.com/Patrick-Ehimen/akave-crosschain-archive/pull/31) — Chainlink CCIP v1.2 decoder (ABI decoding via reflection)
- [PR #40](https://github.com/Patrick-Ehimen/akave-crosschain-archive/pull/40) — Address History + Message Trace REST APIs
- [PR #41](https://github.com/Patrick-Ehimen/akave-crosschain-archive/pull/41) — Analytics & stats layer (WIP)

---

## 💻 Tech Stack

**Languages**
![Go](https://img.shields.io/badge/Go-00ADD8.svg?style=for-the-badge&logo=go&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000.svg?style=for-the-badge&logo=rust&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-323330.svg?style=for-the-badge&logo=javascript&logoColor=F7DF1E) ![Python](https://img.shields.io/badge/Python-3670A0.svg?style=for-the-badge&logo=python&logoColor=ffdd54) ![Solidity](https://img.shields.io/badge/Solidity-363636.svg?style=for-the-badge&logo=solidity&logoColor=white) ![Cairo](https://img.shields.io/badge/Cairo-001E36.svg?style=for-the-badge&logo=starknet&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)

**AI / ML**
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C.svg?style=for-the-badge&logo=langchain&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C.svg?style=for-the-badge&logo=langchain&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2.svg?style=for-the-badge&logo=google&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991.svg?style=for-the-badge&logo=openai&logoColor=white)

**Backend / Infra**
![Node.js](https://img.shields.io/badge/Node.js-339933.svg?style=for-the-badge&logo=node.js&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000.svg?style=for-the-badge&logo=express&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688.svg?style=for-the-badge&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748.svg?style=for-the-badge&logo=prisma&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D.svg?style=for-the-badge&logo=redis&logoColor=white)

**Blockchain**
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D.svg?style=for-the-badge&logo=ethereum&logoColor=white) ![0G](https://img.shields.io/badge/0G_Chain-FF6A00.svg?style=for-the-badge&logo=ethereum&logoColor=white) ![ICP](https://img.shields.io/badge/ICP-29ABE2.svg?style=for-the-badge&logo=internetcomputer&logoColor=white) ![Hedera](https://img.shields.io/badge/Hedera-000000.svg?style=for-the-badge&logo=hedera&logoColor=white) ![IPFS](https://img.shields.io/badge/IPFS-65C2CB.svg?style=for-the-badge&logo=ipfs&logoColor=white) ![Foundry](https://img.shields.io/badge/Foundry-2D2D2D.svg?style=for-the-badge&logo=foundry&logoColor=white)

**Cloud / DevOps**
![AWS](https://img.shields.io/badge/AWS-FF9900.svg?style=for-the-badge&logo=amazonaws&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=docker&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000.svg?style=for-the-badge&logo=vercel&logoColor=white) ![Railway](https://img.shields.io/badge/Railway-0B0D0E.svg?style=for-the-badge&logo=railway&logoColor=white) ![GitHub_Actions](https://img.shields.io/badge/GitHub_Actions-2088FF.svg?style=for-the-badge&logo=githubactions&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624.svg?style=for-the-badge&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05033.svg?style=for-the-badge&logo=git&logoColor=white)

---

## 🌐 Socials
[![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/amsorrytola) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ansari-talha/) [![Telegram](https://img.shields.io/badge/Telegram-26A5E4.svg?logo=telegram&logoColor=white)](https://t.me/tolaamsorry) [![Farcaster](https://img.shields.io/badge/Farcaster-674FFB.svg?logo=farcaster&logoColor=white)](https://farcaster.xyz/amsorrytola)
