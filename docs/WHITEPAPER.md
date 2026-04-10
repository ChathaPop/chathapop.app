# Whitepaper ChathaPop protocol v1.0.

## Introduction 
Official Document ChathaPop Platform Whitepaper A decentralized communication and finance ecosystem built on the Stellar blockchain — combining E2EE messaging, a non-custodial wallet, Proof of Presence mining, a DEX, and DAO governance.
Table of Contents :
01 Summary 
02 Problem & Solution 
03 Technology Stack 
04 Chatha Token Economics 
05 Proof of Presence (PoP) Mining 06 DEX & DeFi 
07 DAO Governance 
08 Security & Privacy 
09 Roadmap 
10 Legal Disclaimer

# ChathaPop 
is a decentralized super-app built on the Stellar blockchain that unifies secure peer-to-peer communication with a comprehensive financial layer. It bridges the gap between messaging apps and financial tools by offering both in a single, privacy-focused, non-custodial platform. 
CHATHA — At the heart of the platform is the CHATHA token — a native Stellar asset that powers all in-app interactions: staking, mining rewards, governance votes, DEX liquidity, and user-to-user micropayments. 
Proof of Presence (PoP) — ChathaPop introduces Proof of Presence (PoP), an innovative mining mechanism that rewards users for their genuine engagement with the app rather than computing power — making blockchain rewards accessible to everyone, regardless of hardware.
# E2EE Chat
# WebRTC Calls
# Soroban Smart Contracts
# IPFS Storage

## Problem & Solution                    
The Problem Fragmented Experience Users juggle 5+ apps for chat, wallet, trading, file sharing, and governance—each with separate accounts and keys. Custodial Wallets & Surveillance Most financial apps store users' funds and data on centralized servers, exposing them to hacks, censorship, and privacy breaches. Mining Exclusivity Traditional crypto mining requires expensive hardware (ASICs/GPUs), excluding billions of potential participants. Fragmented Web3 Governance DAO tools are typically standalone dApps disconnected from the community they serve, resulting in low participation.
# The ChathaPop Solution 
One platform, everything Chat, wallet, DEX, mining, IPFS storage, and DAO—all in a single, cohesive app sharing a unique identity and key. Custodial by design Private keys never leave the device. Users have full sovereignty over their funds and data. No central server holds assets. Proof-of-Presence Mining Anyone with a smartphone earns Chatha simply by using the app—democratizing crypto rewards without hardware costs. Integrated governance DAO proposals and votes take place within the same app the community uses daily, maximizing participation and trust.
## Stack Technologique

# Blockchain Layer 

# Stellar Network
Settlement layer — 3-5s finality, near-zero fees.

# Soroban Smart Contracts
Staking, DEX, DAO voting, token minting.

# Stellar Asset Contract (SAC)
CHATHA as a native SAC for interoperability.

## Communication Layer

# WebRTC P2P
Voice/video calls peer-to-peer, no central server.

# AES-256 + ECDH E2EE
Per-conversation keys, never stored server-side.

# TLS 1.3 Transport

# All API traffic secured with TLS 1.3.

## Storage Layer

# IPFS via Pinata Decentralized, censorship-resistant, content-addressable media. 

# PostgreSQL Metadata, encrypted chat history, platform state. 

# Context Storage Session data isolated per browser context. 

## Application Layer 

# React + TypeScript Type-safe, powerful UI across all devices. 

# Express.js + Node.js Lightweight API: auth, relay, blockchain interactions. 

# TanStack Query Caching, background refresh, optimistic updates.


## CHATHA Token Economy

# ChathaPop Ecosystem Native Utility Token 

1,000,000,000 Total Supply 

Stellar Network 

SAC (Soroban) Standard

7 Decimals

## Token Allocation
● PoP Mining Rewards 40% 
● Community & DAO Treasury 20% 
● Staking Rewards Pool 20% 
● Development & Team 10% 
● Ecosystem & Partnerships 10%


## MethodologyToken Utility 

●In-app microtransactions between users (ChathaTransfer) 

●DEX liquidity provisioning and swap fee reductions via Soroswap 

●PoP mining reward denomination — all payments in CHATHA 

●Staking with up to 70% APY for 365-day lock-up periods 

●DAO governance voting — 1 CHATHA = 1 voting unit Purchases

●of virtual hardware nodes for improved mining rates

## Proof of Presence (PoP) Mining 

●Proof of Presence is an innovative mechanism that distributes CHATHA rewards based on verified user activity rather than computational work. This democratizes mining by eliminating hardware barriers. 

# How it works 

01 
# Session Detection The application detects the user's active presence through interaction signals (sent messages, application focus, browsing events). 

02 
# Opening a Mining Session When presence is confirmed, a mining session begins. Rewards accumulate every minute at the user's current mining rate. 

03
# Rate Calculation Base rate × hardware multiplier × energy node boost × synchronized mining bonus = final earnings per minute. 

04 
# Withdrawal Accumulated CHATHA can be transferred to the in-app wallet at any time (minimum 1 CHATHA).


■Base CPU Free tier — every registered user mines at the base rate with no hardware required. 

■Virtual Hardware Purchase virtual GPU/CPU nodes to multiply your mining rate (1.2x to 8.0x). 

■Energy Nodes Limited-time boosts that are added to hardware multipliers for maximum yield.

## DEX & DeFi 

●ChathaPop integrates with Soroswap, Stellar's leading DEX, to bring full decentralized trading directly into the chat app—no external applications, no bridging risks. 

●Swap Token-to-token swaps with slippage protection and real-time quotes. 

●Liquidity Provide liquidity to Soroswap pools and earn 0.3% of the swap fees. 

●Staking Lock up CHATHA for 7 to 365 days to earn up to 70% APY from the staking pool.

●Ramp On/off ramp support for BTC and ETH payments via secure payment processors. 

●Fee Structure: DEX swaps incur a total fee of 0.8%, broken down as follows: 0.5% platform fee (DAO treasury) and 0.3% to liquidity providers. Internal transfers within CHATHA between users are always free.


## DAO Governance 

●ChathaPop's governance is managed by a decentralized autonomous organization where all CHATHA holders can participate in platform decisions—from fee changes to prioritizing new features. 

●On-Chain Voting Votes are anchored to verified CHATHA balances via the Soroban SAC contract—no manipulation is possible. Quorum Requirements A minimum of 1,000 votes is required for a proposal to be valid. This ensures significant community engagement. 

●Transparent Results All proposals, votes, and results are publicly verifiable on the Stellar blockchain explorer. Treasury Management 20% of the total CHATHA supply is held in the DAO treasury, deployed solely through community voting.



# Security & Privacy 

●Security isn't an optional feature in ChathaPop—it's the foundation upon which every layer of the platform is built. AES-256 E2EE Messages are encrypted before leaving the device. Only the intended recipient can decrypt them. 

●Non-Custodial Wallet Private keys are generated locally and never transmitted. No server holds user funds. 

●TLS 1.3 All API traffic uses TLS 1.3 with robust cipher suites—no legacy SSL/TLS. 

●PIN + 2FA In-app access is protected by a 4-digit PIN with optional two-factor authentication. 

●Server-Side Key-Free Cryptic keys for messages and wallets are derived client-side using ECDH and BIP standards. 

●IPFS Content Addressing Media files are addressed by content hash (CID), not by URL — impossible to manipulate in transit


## Roadmap Phase  

○1 — Foundation 
Q1–Q2 2026 ✓ Done P2P E2EE Chat with WebRTC Voice/Video Non-Custodial Stellar Wallet (XLM + CHATHA) Proof of Presence Mining Engine Virtual Hardware Marketplace Full i18n (IT/EN/ES/FR/PT/DE) IPFS Media Storage via Pinata 

○Phase 2 — DeFi Layer Q3 2026 In Progress Soroswap DEX Integration (Live) CHATHA Staking Pools (Live) DAO Governance Module (Live) BTC/ETH On-Ramp Integration Synchronized Mining with Partner Pools Mobile PWA Optimization 

○Phase 3 — Expansion Q4 2026 Planned Native iOS & Android Apps Smart Contract Auditing Soroban Cross-chain bridge (Ethereum <> Stellar) ChathaPop SDK for third-party integrations Community developer grants (DAOs) Institutional staking and liquidity programs 

○Phase 4 — Ecosystem 2027+ Planned ChathaPop App Store (community dApps) Hardware wallet integration (Ledger/Trezor) Privacy-preserving identity layer (ZK proofs) Decentralized video streaming infrastructure Global expansion of the PoP mining network

## Legal Disclaimer No Financial Advice. 
This white paper is provided for informational purposes only. Nothing in this document constitutes investment advice, an offer of securities, or financial recommendations. Holders of the CHATHA token assume full responsibility for their financial decisions. Regulatory Status: The CHATHA token is a utility token used exclusively within the ChathaPop platform. It is not intended to be a security, investment vehicle, or store of value outside the ecosystem. Technological Risk: Blockchain, smart contracts, and decentralized systems carry inherent risks, including bugs, network congestion, regulatory changes, and market volatility. Forward-Looking Statements: The roadmap and feature descriptions represent current intentions and may change based on technical, legal, or market conditions. Privacy: ChathaPop does not collect, sell, or share personal data. All communications are end-to-end encrypted. The platform is GDPR compliant by design.

## Built on Stellar 
# ChathaPop is powered by the Stellar network and the Soroban smart contract platform. Fast, affordable, and green by design. 

#    ChathaPop White Paper v1.0                     April 2026 
      All rights reserved
