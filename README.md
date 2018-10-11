# Blockchain Learning Path

An opinionated learning path for getting into speed with Blockchain (specially Ethereum). This is a
work in progress, please open an issue or send a pull request to help improving it.

## Pre-requisites

Besides a programming background, this path assumes that the reader is at least a little comfortable
with:

- Public key cryptography
- Digital signatures
- Cryptographic hashing

## Bitcoin

1. Read [How the Bitcoin protocol actually works](http://www.michaelnielsen.org/ddi/how-the-bitcoin-protocol-actually-works/). (Est. time: 45 minutes)
2. Watch [this video](https://www.youtube.com/watch?v=bBC-nXj3Ng4) (lighter than the previous
article but useful to solidify your knowledge). (Est. time: 26 minutes)

## Ethereum
#### Theory
1. Read [How does Ethereum work, anyway?](https://medium.com/@preethikasireddy/how-does-ethereum-work-anyway-22d1df506369) (Est. time: 38 minutes)
2. Read [this article](https://blog.zeppelin.solutions/the-hitchhikers-guide-to-smart-contracts-in-ethereum-848f08001f05)
on smart contracts development. (Est. time: 15 minutes)
3. Read the [Truffle Documentation](http://truffleframework.com/docs/)
4. Read the [Web3 Documentation](https://web3js.readthedocs.io/en/1.0/)

#### Practice
1. Learn Ethereum development by making a [Zombie Game](https://cryptozombies.io/) (Est. time: 8 hs)
2. Read and make and example: [Pet shop tutorial](http://truffleframework.com/tutorials/pet-shop)
3. [Time-locked Wallets: An Introduction to Ethereum Smart Contracts](https://www.toptal.com/ethereum-smart-contract/time-locked-wallet-truffle-tutorial)
4. [The Ultimate ENS and ĐApp Tutorial](https://www.toptal.com/ethereum/ethereum-name-service-dapp-tutorial)

## Courses
1. Do this course [Ethereum and Solidity: The Complete Developer's Guide](https://www.udemy.com/ethereum-and-solidity-the-complete-developers-guide/) (Est. time: 24 hs)
2. Free tutorial  [Learning Solidity](https://github.com/willitscale/learning-solidity)
3. [Blockchain Architecture Design And Use Cases by IITKGP](https://www.youtube.com/watch?v=PPFsG92-HiI&list=PLbRMhDVUMngfxxyVLh2t2gKDUfsOdGn56)


## Concepts
1. [Blockchain Oracles, Explained](https://cointelegraph.com/explained/blockchain-oracles-explained) (Est. time: 4 minutes)
2. [ABI](https://github.com/ethereum/wiki/wiki/Ethereum-Contract-ABI)  (Est. time: 15 minutes)
3. [Keccak256](https://www.slideshare.net/RajeevVerma14/keccakpptx) (Est. time: 15 minutes)
4. [Random numbers](https://ethereum.stackexchange.com/questions/191/how-can-i-securely-generate-a-random-number-in-my-smart-contract) (Est. time: 5 minutes)
5. [Velocity of Tokens](https://medium.com/newtown-partners/velocity-of-tokens-26b313303b77) (Est. time: 9 minutes)
6. [Gas](https://ethgas.io/) (Est. time: 5 minutes)

## Under the hood
1. [Inside an Ethereum transaction](https://medium.com/@codetractio/inside-an-ethereum-transaction-fa94ffca912f)
2. [Diving Into the Ethereum VM](https://blog.qtum.org/diving-into-the-ethereum-vm-6e8d5d2f3c30)

## Best Practices
- [Consensys best practices](https://consensys.github.io/smart-contract-best-practices/) - This document provides a baseline knowledge of security considerations for intermediate Solidity programmers. It is maintained by ConsenSys Diligence, and the broader Ethereum community.
- [Solidity Patterns](https://github.com/fravoll/solidity-patterns) - A compilation of patterns and best practices.

## Libraries
- [dapp-bin](https://github.com/ethereum/dapp-bin) - Ethereum repo providing implementations for many common data structures and utilities in Solidity, Serpent and LLL.
- [Solidity Collections](https://github.com/ethereum/wiki/wiki/Solidity-Collections) - Collections of code snippets and utility libraries.
- [OpenZeppelin](https://openzeppelin.org/) - Framework to build secure smart contracts.

## Examples
- [Solidity By Example](http://solidity.readthedocs.io/en/latest/solidity-by-example.html) - Contract examples from the official docs.

## Toolbox
List of tools curated by Protofire team to better apply best practices to the Protocol and DApps development projects.

#### General
- [eth-cli](https://github.com/protofire/eth-cli) - CLI tools.
- [REPL](https://github.com/raineorshine/solidity-repl) - Solidity REPL.
- [Remix](https://remix.ethereum.org/) - Online realtime compiler and runtime.

#### Audit
- [SmartCheck](https://tool.smartdec.net) - Online tool for checking smart contracts for vulnerabilities and bad practices.

#### Utility
- [solhint](https://github.com/protofire/solhint) - Solidity linter that provides security, style guide and best practice rules for smart contract validation.
- [solium](https://github.com/duaraghav8/Solium) - Linter to identify and fix style & security issues in Solidity smart contracts.
- [sol-tester](https://github.com/androlo/sol-tester) - Utilities for building, linking and testing contracts using go-ethereum and the simulated chain.
- [solidity-coverage](https://github.com/sc-forks/solidity-coverage) - Code coverage tool.


**TODO** Add some resource to learn the differences between the bitcoin and the ethereum blockchains.
