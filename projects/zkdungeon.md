# zkDungeon

*A Zero-Knowledge Dungeon Crawler*

## Overview

zkDungeon is an experimental on-chain game that uses zero-knowledge proofs to enable fog-of-war mechanics in a fully transparent blockchain environment.

## Technical Details

- **Proof System**: Groth16 via snarkjs
- **Smart Contracts**: Solidity + Circom
- **Frontend**: Rust/WASM

## How It Works

Players generate ZK proofs locally to prove they can see certain tiles without revealing their position. This creates a trustless fog-of-war where the game state is fully on-chain but player positions remain private until revealed.

## Links

- GitHub: github.com/example/zkdungeon
- Play: zkdungeon.eth

---
*Press `q` or `Esc` to return to terminal*
