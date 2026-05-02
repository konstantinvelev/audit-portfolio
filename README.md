<div align="center">

# **Velev** — Smart Contract Security Researcher

Solidity / EVM · Cairo · DeFi protocol security · Private engagements

[![X / Twitter](https://img.shields.io/badge/-velevvv-black?logo=x&logoColor=white)](https://x.com/velevvv)
[![Telegram](https://img.shields.io/badge/-velevvv-2CA5E0?logo=telegram&logoColor=white)](https://t.me/velevvv)
[![Email](https://img.shields.io/badge/velev.sr%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:velev.sr@gmail.com)
[![GitHub](https://img.shields.io/badge/konstantinvelev-181717?logo=github&logoColor=white)](https://github.com/konstantinvelev/web3)
[![CV](https://img.shields.io/badge/CV_--_Resume-2EA043?logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1OSKol8gJ_sE1TEp45LkupEls--X1b-CL/view?usp=sharing)

</div>

---

## About

I work with protocol teams on pre-launch and pre-upgrade security reviews of Solidity and Cairo systems — primarily DeFi: lending, perpetuals, stablecoins, DEXs, staking, and cross-chain infrastructure.

My approach is deep-dive over breadth: fewer engagements per quarter, more time per codebase, direct collaboration with the dev team on mitigations and invariant design. I care about the bugs that don't show up in pattern matching — economic exploits, accounting drift, broken invariants under adversarial sequencing.

Background: 25+ public contests across Sherlock, Cantina, Code4rena and Immunefi before transitioning toward private engagements. 30+ confirmed findings, multiple top-10 placements including 2x 5th place finishes.

**Currently accepting private audit engagements** for Q2–Q3 2026. DMs open.

---

## 🔒 Private Audit Engagements

| # | Protocol | Scope | Stack | Date | Firm |
|---|----------|-------|-------|------|------|
| 1 | ShiftProtocol V2 | Vaults, bridges, off-chain integration | Solidity | Mar 2026 | [SBSecurity](https://www.sbsecurity.net/) |
| 2 | ShiftProtocol V2 | Vaults, bridges, off-chain integration | Cairo | Apr 2026 | [SBSecurity](https://www.sbsecurity.net/) |
| 3 | [SnuggleFi](https://www.snuggle.fi/) | Staking, DEX integrations (UniswapV3, Aerodrome, Pancake) | Solidity | Apr 2026 | [Valves](https://valvessecurity.com/) |

> Reports available on request where NDA permits. For ongoing engagements I publish redacted writeups of notable findings — see [Selected Findings](#-selected-findings) below.

---

## 🎯 Selected Findings

> Detailed writeups of representative bugs across recent work. These illustrate how I think about a codebase, not just what I found.

**Uniswap V2 pair state manipulation breaking core protocol invariants** *(High severity)*
An attacker can create a Uniswap V2 pair for a target protocol token and manipulate the pair's reserves to break a downstream invariant the protocol assumes about price oracles / reserve ratios. *Writeup coming soon — `findings/uniswap-v2-pair-manipulation.md`*

*More writeups in progress.*

---

## 🤖 Open Source AI — powered by Velev

As an auditor, I saw firsthand how much time is lost to repetitive analysis patterns — so I built the tooling to fix it. After investing in learning AI systems, I distilled that knowledge into a production-ready skill library: structured prompts, agent pipelines, and methodology frameworks designed specifically for smart contract security research. Plug-and-play for any auditor, any codebase, any platform.

[![GitHub](https://img.shields.io/badge/-konstantinvelev/AI-181717?logo=github&logoColor=white)](https://github.com/konstantinvelev/AI)

---

## 🛠 Focus & Methodology

| | |
|---|---|
| **Languages** | Solidity / EVM, Cairo |
| **Protocol types** | Lending & borrowing, perpetuals, stablecoins, DEXs & AMMs, staking, yield, options, cross-chain bridges |
| **Integrations covered** | Uniswap V2/V3, Aerodrome, Pancake, Sushi, Liquity-style CDPs, bonding curves, Governor frameworks |
| **Ecosystems** | Ethereum L1/L2, Solana, Sui, Starknet, Cosmos |
| **Focus areas** | Economic exploits, accounting bugs, broken invariants, access control, adversarial sequencing, MEV-adjacent issues |
| **Methodology** | Manual review (primary), Foundry-based PoC development, fuzzing, invariant testing, custom AI tooling for repeated patterns |
| **Engagement style** | Direct dev collaboration on mitigations · iterative review on fixes · post-audit availability for follow-up questions |

---

## 🏆 Public Contest History

Background context — competed across Sherlock, Cantina, Code4rena and Immunefi between 2024 and 2025 to build pattern recognition across protocol types before moving toward private work.

| Date | Protocol | Type | Platform | Confirmed | Earned | Place |
|------|----------|------|----------|-----------|--------|-------|
| Jan–Feb 2026 | Fluid DEX V2 | DEX | Sherlock | 1 | $2,516.24 | 🎖️ 9th |
| Nov–Dec 2025 | Mento | CDP Stablecoin, FX | Cantina | 1 | $256.78 | 🎖️ 6th |
| Nov 2025 | Alignerz | Fair-Launch, Vesting | Dual-Guard | 8 | $958.48 | 🏅 5th |
| Nov 2025 | Firelight | Liquid Staking, DeFi Insurance | Immunefi | 1 | $1,000.00 | 🏅 5th |
| Oct 2025 | Avon | Lending Order Book | Cantina | 5 | — | 🎖️ 26th |
| Aug–Sep 2025 | GTE Perps & Launchpad | Perpetuals CLOB, Launchpad | Code4rena | 2 | — | — |
| Jul 2025 | Succinct Network | ZK Proof Infrastructure | Cantina | 1 | $298.24 | 🎖️ 16th |

*Total across all contests: 30+ confirmed findings, 2x 5th place, 5x top-10.*

---

## 📚 Background & Continuous Learning

**Cyfrin Updraft** — completed tracks: Blockchain Basics, Solidity Smart Contract Development, Foundry Fundamentals, Advanced Foundry, Smart Contract Security, Assembly & Formal Verification, Uniswap V2, Uniswap V3, Chainlink Fundamentals, Web3 Wallet Security.

**RareSkills** — low-level EVM internals, gas optimization, advanced Solidity patterns.

**Solodit** — systematic review of past audit findings across major platforms; ongoing reference and pattern source.

Coursework and practice repositories: [github.com/konstantinvelev/web3](https://github.com/konstantinvelev/web3)

---

## 📫 Contact

For private audit inquiries, the fastest channels are Telegram or email. Please include: protocol description, scope (LOC and contracts), preferred timeline, and whether you have an existing audit report I'd be reviewing alongside.

| | |
|---|---|
| **Telegram** | [@velevvv](https://t.me/velevvv) |
| **X / Twitter** | [@velevvv](https://x.com/velevvv) |
| **Email** | velev.sr@gmail.com |

---

<div align="center">

*Available for solo engagements and team collaborations with established audit firms.*

</div>
