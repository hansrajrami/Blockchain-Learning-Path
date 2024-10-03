# Blockchain Learning Path - 2024

This learning path is divided into 4 sections as follows. Please follow the section which suits your profile the most.

1. Blockchain for everyone
2. Private Blockchain Developer - Hyperledger Fabric
3. Private Blockchain Administrator/DevOps - Hyperledger Fabric
4. Public Blockchain Developer - Ethereum

## Blockchain for everyone

##### Introduction to Blockchain:
- Overview of Blockchain technology: History, key concepts, and types of blockchains
- Key terms
  - Cryptography
  - Decentralization
  - Consensus mechanisms
  - Smart Contracts
  - Tokens
- Blockchain vs Traditional Systems (Comparison of centralization vs decentralization)

##### Cryptography Essentials:
- Symmetric vs Asymmetric encryption
- Hashing functions: SHA-256, Merkle trees
- Digital signatures and public key infrastructure
- Popular Cyyptography algorithms
  - ECDSA (Mostly used in signing and verifying transactions)
  - RSA (Mostly used in encryption and decryption of data)

#### Consensus Algorithms:
- Proof of Work (PoW)
- Proof of Stake (PoS)
- Delegated Proof of Stake (DPoS)
- Byzantine Fault Tolerance (BFT)
- Others

##### Blockchain Use Cases:
- Real-world applications in Finance, Healthcare, Supply Chain, and other industries

## Private Blockchain Administrator/DevOps - Hyperledger Fabric

##### Introduction to Hyperledger Fabric:
- Overview of Hyperledger ecosystem
- Hyperledger Fabric - Key Concepts
- Fabric architecture: Nodes, channels, peers, ordering service, and membership service providers
- Key differences between Public and Private Blockchains

#### Installation and Setup:
- Prerequisites: Docker, Docker Compose, Fabric binaries
- Setting up a local Hyperledger Fabric network
- Understanding configuration files
  - crypto-config.yaml
  - configtx.yaml
  - core.yaml

#### Network Administration:
- Certificate Authority (CA) for issuing and managing certificates
- Managing organizations, peers, and ordering services
- Channel creation and management

#### Chaincode Deployment and Lifecycle Management:
- Installing, approving, committing, and invoking chaincode
- Managing chaincode versions and updates

#### Monitoring and Scaling Hyperledger Fabric:
- Tools for monitoring (Prometheus, Grafana)
- Best practices for scaling the Fabric network

#### Security Best Practices:
- Securing communication using TLS
- Managing identities, ACLs, and access control policies

## Private Blockchain Developer - Hyperledger Fabric

#### Chaincode Development Basics:
- Introduction to Chaincode (smart contracts in Fabric)
- Chaincode Development using (Go, Java, Node.js)
- Key chaincode components: State database, transaction processing, endorsement policies

#### Chaincode Writing and Testing:
- Writing basic chaincode to manage assets (CRUD operations)
- Implementing endorsement policies within chaincode
- Unit testing chaincode using Fabric’s built-in testing framework

#### Advanced Chaincode Concepts:
- Chaincode upgrades and versioning
- Event handling and triggers within chaincode
- Implementing complex logic, ACL and Multi-signature requirements

#### Interacting with Hyperledger Fabric:
- Writing client applications (Node.js SDK)
- Integrating Hyperledger Fabric with web applications

#### Privacy and Confidentiality in Hyperledger Fabric:
- Managing data privacy across multiple organizations using channel
- Implementing private data collections
- Managing access control using Chaincode
- Using ABAC in chaincode for custom privacy rules

#### Performance Tuning and Optimizations:
- Optimizing chaincode for better performance
- Handling large-scale data with Hyperledger Fabric

## Public Blockchain Developer - Ethereum and Other EVM Compatible Blockchains

#### Ethereum Basics:
- Introduction to Ethereum: History, Ethereum Virtual Machine (EVM)
- Ethereum accounts, transactions, and gas fees
- Setting up a Ethereum node or using services like Infura, Alchemy

#### Solidity Programming:
- Writing basic smart contracts
  - ERC20 Tokens
  - Voting systems
  - Escrow services
  - ERC721 NFT Tokens
- Solidity syntax, contract structure, and events
- Contract inheritance, libraries, and using external smart contracts

#### Tools for Ethereum Development:
- Development Tools (Truffle, Hardhat, Remix)
- Testing contracts using frameworks like Mocha, Chai
- Deploying contracts using CLI tools and web3.js/ethers.js libraries

#### DeFi and DApp Development:
- Building Decentralized Applications (DApps) on Ethereum
- Interacting with DeFi protocols (Uniswap, Aave, Compound)
- Writing contracts for liquidity pools, staking, lending protocols

#### Security in Ethereum Development:
- Common vulnerabilities: Reentrancy, integer overflows, front-running
- Using tools like OpenZeppelin, Slither for secure smart contract development
- Auditing smart contracts and security best practices

#### Interoperability and Layer 2 Solutions:
- Introduction to Layer 2 solutions (Polygon, Optimism, zkRollups)
- Bridging assets between Ethereum and Layer 2s

#### Advanced Topics:
- Understanding gas optimization techniques
- Exploring Ethereum 2.0: Proof of Stake and shard chains
- Governance in public blockchains: DAOs and voting mechanisms

#### Other EVM Compatible Blockchains:
- Overview of Binance Smart Chain (BSC), Avalanche, Fantom
- Deploying and optimizing smart contracts on other EVM-based chains
- Cross-chain bridges and asset interoperability
