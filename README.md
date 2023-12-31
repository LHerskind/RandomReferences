# Random References [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)]()

A list of random but hopefully awesome references. Some read, some put here for later reading.

---

## Contents 

- [Blockchain](#blockchain)
  - [Censorship Resistance](#censorship-resistance)
  - [Data Analysis](#data-analysis)
  - [Data Availability](#data-availability) 
  - [Execution Layer](#execution-layer)
  - [Fee Design](#fee-design)
  - [MEV](#mev)
  - [Rollups](#rollups)
  - [Smart contracts](#smart-contracts)
    - [Huff](#huff)
    - [Solidity](#solidity)
    - [Security](#security)
    - [Vyper](#vyper)
  - [Thought pieces](#thought-pieces)
  - [Upgrades](#upgrades)
  - [Vulnerabilities](#vulnerabilities)
- [Cryptography](#cryptography)
- [Data Structures](#data-structures)
  - [Trees](#trees)
- [Misc](#misc)

---

## Blockchain
Contains blockchain topics, mostly from the Ethereum sphere.

### Censorship Resistance
- 📃 [Censorship... wat do?](https://joncharbonneau.substack.com/p/censorship-wat-do)
- 📃 [State of research: increasing censorship resistance of transactions under proposer/builder separation (PBS)](https://notes.ethereum.org/s3JToeApTx6CKLJt8AbhFQ#State-of-research-increasing-censorship-resistance-of-transactions-under-proposerbuilder-separation-PBS)
- 📃 [No free lunch - a new inclusion list design](https://ethresear.ch/t/no-free-lunch-a-new-inclusion-list-design/16389)
- 📃 [PBS censorship-resistance alternatives](https://notes.ethereum.org/@fradamt/H1TsYRfJc)
- 📃 [Fun and games with inclusion lists](https://ethresear.ch/t/fun-and-games-with-inclusion-lists/16557)
- 📃 [Encrypted Mempools](https://joncharbonneau.substack.com/p/encrypted-mempools)

### Data Analysis
- 🛠️ [Cryo](https://github.com/paradigmxyz/cryo)
- 🛠️ [Cryogen](https://github.com/banteg/cryogen)
- 📃 [DefiLlama](https://defillama.com/)

### Data Availability
- 📃 [EIP-4844](https://eips.ethereum.org/EIPS/eip-4844)
- 📃 [PeerDAS – a simpler DAS approach using battle-tested p2p components](https://ethresear.ch/t/peerdas-a-simpler-das-approach-using-battle-tested-p2p-components/16541)
- 📃 [Danksharding](https://ethereum.org/en/roadmap/danksharding/)
- 📃 [Dankrads notes on Danksharding](https://notes.ethereum.org/@dankrad/new_sharding)
- 📃 [An explanation of the sharding + DAS proposal](https://hackmd.io/@vbuterin/sharding_proposal)

### Execution Layer
- 📃 [Execeution Specs](https://ethereum.github.io/execution-specs/)

### Fee Design
- 📃 [EIP-1559](https://eips.ethereum.org/EIPS/eip-1559)
- 📃 [Has anyone checked on EIP-1559 recently?](https://prestwich.substack.com/p/has-anyone-checked-on-eip-1559-recently)
- 📒 [Transaction Fee Mechanism Design with Active Block Producers](https://arxiv.org/abs/2307.01686)
- 📃 [Exponential EIP-1559](https://dankradfeist.de/ethereum/2022/03/16/exponential-eip1559.html)

### MEV
- 📃 [MEV List](https://thedailyape.notion.site/MEV-8713cb4c2df24f8483a02135d657a221)

### Rollups
- 📃 [Rollup Centric Ethereum Roadmap](https://ethereum-magicians.org/t/a-rollup-centric-ethereum-roadmap/4698)
- 📃 [Rollups Are L1s (& L2s) a.k.a. How Rollups *Actually Actually Actually* Work](https://dba.mirror.xyz/LYUb_Y2huJhNUw_z8ltqui2d6KY8Fc3t_cnSE9rDL_o)
- 📃 [The Rollup Multiverse](https://dba.mirror.xyz/hyRKK4_PDrO2FKpF6eIRvnq8sA_Mx7dXtQf_MWzSWTU)
- 📃 [Rollups, Rigor, and Reality](https://kelvinfichter.com/pages/thoughts/rrr/)
- 📃 [Rollups are Real -- Rollup Economics 2.0](https://davidecrapis.notion.site/Rollups-are-Real-Rollup-Economics-2-0-2516079f62a745b598133a101ba5a3de)
- 📺 [How to think about PBS on L2](https://www.youtube.com/live/WYH7n4M016A?si=3h26RqDW-wEDgoWN&t=21963)
- 📺 [A Better Mental Model for Rollups, Plasma, and Validating Bridges](https://www.youtube.com/watch?v=Z1dDVW7QTTM)
- 📃 [Rollups as Sovereign Chains](https://blog.celestia.org/sovereign-rollup-chains)

### Smart Contracts

#### Huff
- 🛠️ [Huff docs](https://docs.huff.sh/)

#### Solidity 
- 🛠️ [Solidity docs](https://soliditylang.org/)
- 🛠️ [Foundry book](https://book.getfoundry.sh/)
- 📃 [Solidity considered harmful](https://makemake.site/post/solidity-considered-harmful)
- 📃 [Solidity Data Representation](https://ethdebug.github.io/solidity-data-representation/)

#### Security
- 📃 [Nascent Simple Security Toolkit](https://github.com/nascentxyz/simple-security-toolkit)
- 🛠️ [Pyrometer](https://github.com/nascentxyz/pyrometer)
- 🛠️ [Slither](https://github.com/crytic/slither)
- 🛠️ [Echidna](https://github.com/crytic/echidna)
- 📃 [Trail of Bits building secury contracts](https://github.com/crytic/building-secure-contracts)

#### Vyper
- 🛠️ [Vyperlang docs](https://docs.vyperlang.org/en/stable/)
- 📃 [How 🐍 compiles into bytecode](https://hackmd.io/@pcaversaccio/how-vyper-compiles-into-bytecode)
- 📃 [The Vyper compiler](https://jtriley.substack.com/p/the-vyper-compiler)
- 📃 [Vyper deepdive](https://github.com/jtriley-eth/vy-deepdive)

### Thought pieces
- 📃 [Blockchains are for settlement; or using the right tool for the job](https://makemake.site/post/blockchain-bad)

### Upgrades
- 📺 [Tim Beiko - Ethereum Protocol Upgrades: Past, Present & Future](https://www.youtube.com/watch?v=HoclxIBR2EM)

### Vulnerabilities
- 📃 [Ethereum public disclosures](https://github.com/ethereum/public-disclosures/)

## Cryptography
- 📃 [KZG polynomial commitments](https://dankradfeist.de/ethereum/2020/06/16/kate-polynomial-commitments.html)
- 📃 [SUMCHECK Quickie](https://dankradfeist.de/ethereum/2023/08/08/sumcheck-quickie.html)
- 📚 [Proofs, Arguments, and Zero Knowledge](https://people.cs.georgetown.edu/jthaler/ProofsArgsAndZK.pdf)
- 📃 [Delendum knowledge-base](https://kb.delendum.xyz/)

## Data Structures

### Trees
- 📺 [ZK8: Tiered Merkle Topiary – finch – Penumbra Labs](https://www.youtube.com/watch?v=mHoe7lQMcxU)

## Misc
- 📃 [The Documentation Compendium](https://github.com/kylelobo/The-Documentation-Compendium)
- 📃 [Awesome blockchain rust](https://github.com/rust-in-blockchain/awesome-blockchain-rust)
