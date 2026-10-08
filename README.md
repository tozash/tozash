# Sandro Tozashvili

Blockchain developer and co-founder of [Stickets](https://stickets.ge), event ticketing built on Solana. Based in Tbilisi, Georgia.

## Stickets

Ticketing where every ticket is an NFT, built for an audience that is mostly not crypto-native. I designed the architecture and the product, and wrote the smart contracts and the Solana programs.

**Status:** pre-launch. The Solana programs are heading to mainnet; the earlier EVM version ran on Polygon Amoy testnet. The code is private company code; I'm happy to walk through it on a call.

**What I built**
- **Event entry that works offline.** QR ticket generation and verification, plus the scanner staff use at the door. Scanners can work offline, and proof of each QR is available on a public blockchain, using encryption and partial key distribution across the buyer's app, the scanner and public data.
- **Wallet-free onboarding (EVM version).** A custom ERC-4337 flow with a custom paymaster on EntryPoint v0.7, because off-the-shelf smart-account services cost too much to run for ticketing.
- **EVM → Solana migration.** I chose Metaplex Bubblegum V2 compressed NFTs after a cost analysis that put the cost per minted ticket roughly 260–450× lower.

## How I work
- **AI coding agents, with a plan first.** Before any Claude Code session that touches the codebase, I write a Work Order: the scope, the constraints, and an approach chosen after comparing the alternatives on cost and risk. If an agent wants to deviate, I stop the session and evaluate the deviation separately. Often the agent is right, and then the Work Order changes.
- **Issues written for people and agents.** I wrote our team's Linear issue standard (issue types, a fixed shape, required information), so a developer's agent can pick up an issue and act on it without a round trip.

## Stack
Rust / Anchor · Solidity / Hardhat · TypeScript · Next.js · Node.js

## Contact
[LinkedIn](https://www.linkedin.com/in/sandrotozashvili) · sandrotozashvili@gmail.com
