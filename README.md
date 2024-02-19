
# BXN Blockchain Documentation

## Introduction

BXN is an EVM (Ethereum Virtual Machine)-based PoSA (Proof of Staked Authority) blockchain that incorporates its economy logic and functionality through a comprehensive set of smart contracts, akin to the Binance Smart Chain (BSC) architecture. It offers compatibility with the Ethereum ecosystem, allowing developers and users to interact with its network using the standard Ethereum API via RPC (Remote Procedure Call) endpoints. The network supports the deployment and operation of decentralized applications (DApps) and smart contracts, leveraging Vanilla Geth clients for node operation.

## Getting Started

This document serves as a starting point for new users to the BNB Chain ecosystem. General knowledge of cryptocurrency is assumed, and in particular familiarity with the Ethereum ecosystem.

### What can users do with BXN?
BXN is equipped with the smart contract functionality and compatibility with the Ethereum Virtual Machine (EVM) and is used for developing various kinds of decentralized applications. The design goal of BXN is to leave the high throughput and introduce smart contracts into the BXN Chain ecosystem. Being EVM-compatible, other than easy portability, BXN enjoys support of the rich universe of Ethereum tools and dApps.

The three founding cornerstones of the BXN Chain are:

#### BXN
The native layer 1 Token of BlackFort, holds a central and dynamic role within our thriving ecosystem. Beyond its foundational value, BXN offers a versatile range of utilities that are designed to cater to a broad audience.
BXN's multifaceted utility spans both on-chain and off-chain applications, positioning it as a token of choice for both experienced and novice investors. This strategic approach underscores our unwavering commitment to principles of transparency, accessibility, and the continuous growth of the BlackFort community. Notably, in 2024, we are planning to introduce BXN as a means of payment for asset-backed real estate tokens, further expanding its use cases.
At the core of the BlackFort blockchain, the BXN token plays a pivotal role by serving as the currency for transaction processing fees, commonly known as gas fees. Every transaction initiated on the BlackFort blockchain involves the expenditure of BXN tokens, which compensate the validator nodes for processing these requests. BXN, in this way, drives all transactions and smart contract interactions, ensuring a reliable and efficient platform. This dedication to providing an accessible and cost-effective blockchain environment highlights our commitment to fostering the growth and sustainability of the broader blockchain ecosystem.

#### BXN VOTE Token
Within our blockchain, every BXN node holder receives a complimentary amount of VOTE tokens. These tokens grant voting power in a direct-democratic voting system, ensuring that each node holder has an equal voice in network decision-making. This approach aligns the interests of node holders with the BlackFort community's long-term success, fostering innovation and collaboration within our ecosystem.

#### BXN Node NFT
BXN utilizes a unique system of nodes, where there's a fixed total of 304,000 nodes available for distribution. Each node represents a non-fungible collection of native tokens (nNFT) and holds a specific weight referred to as Tokenlock. Nodes cannot be divided into individual coins and are a single entity. These nodes play a crucial role in validating transactions within the Proof-of-Staked-Authority (PoSA) mechanism, adding to the authority and weight of the holder. 

Each node is designated to receive a fixed amount of BXN Tokens that are released as block rewards to the holders’ BXN Address. Once activated, every node is going to claim its block rewards starting the block after successful activation and delegator rewards (Aliquoted transaction fee earnings). Block rewards are set out to be distributed automatically by the algorithm for ten years with a halving time of one year (Number of blocks 6,000,000). This is calculated from 5 second block times, to be halving the result yearly until the tenth year. After the tenth year is over, block rewards for that node are going to stop. Aliquoted transaction fee collections are enabled for lifetime of the blockchain and start upon node delegation. Base production is calculated from the smallest Node Hever in Weight of 5K BXN upwards to the highest weighted Node Chillon in weight of 2.5M BXN. Each increment in node weight class has an increase of BXN production of 2%. Example: Vianden has a weight of 10k, produces 1.02x of two Hever 5K. Trakai Has a weight of 50k and produces 10.2x of five Vianden 10K etc.

### Tokenization​
On the BXN, users can:
- Send and receive, Nodes, BXN and BXP20 tokens (in future).
- Claim BXN rewards from Nodes and Delegate them to earn some block rewards.
- Issue Fungible tokens like BXP20 Tokens to digitalize assets.
- Issue Non-Fungible Tokens (NFTs).
- Extensive support of Cross-Chain Bridges for cross-chain transfers of tokens (FUTURE).

### Blockchain Explorers

Mainnet - https://explorer.blackfort.network/
Testnet - https://testnet-explorer.blackfort.network/

### Wallets Support

- Metamask (add network manually)
- BlackFort Wallet (native support)
- Coinpayments (merchant wallet)

### Building dApps
BXN empowers developers to build dApps of different kinds. You can use ChainIDE, RemixIDE, TruffleSuite, HardHat and so on

### Node RPC and Explorers
| Network | Symbol | Chain ID | RPC Endpoint                          | Explorer                                    |
| ------- | ------ | -------- | ------------------------------------- | ------------------------------------------- |
| testnet | TBXN   | 4777     | https://testnet.blackfort.network/rpc | https://testnet-explorer.blackfort.network/ |
| mainnet | BXN    | 4999     | https://mainnet.blackfort.network/rpc | https://explorer.blackfort.network/         |

Mirrors for mainnet are available on subdomains ranging from mainnet-0 to mainnet-3. For example, https://mainnet-2.blackfort.network/rpc provides an alternative access point to the mainnet.

### Rate Limiting
The BXN network imposes rate limits on the number of requests to its services to ensure stable and equitable access for all users. Should you require increased limits for your applications or services, please reach out with your specific needs for further assistance. You may send request for this to dev@blackfort.exchange

### Additional Information
For developers and users looking to integrate or interact with the BXN blockchain, the network supports the use of regular [Ethereum APIs](https://ethereum.github.io/execution-apis/api-documentation/) through the RPC endpoints. This compatibility facilitates a seamless transition for those already familiar with Ethereum's infrastructure and looking to explore or migrate to BXN.

To start interacting with the BXN network, you can use the provided RPC endpoints to connect your applications or services directly. This enables you to perform transactions, deploy smart contracts, and access blockchain data using familiar tools and libraries from the Ethereum ecosystem.

### Support and Community
For further assistance, support requests, or to join the BXN community, please visit our official channels (not listed here, but typically includes forums, Discord or Telegram groups, and GitHub repositories). Our community and support team are ready to help with any questions, technical issues, or guidance you may need as you explore the BXN blockchain.
