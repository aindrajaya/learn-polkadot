# [INTRODUCTION](https://learn.figment.io/tutorials/polkadot-101)
Learn how Polkadot works and what makes it Special

## What is Polkadot?
Polkadot enables scalability by allowing specialized blockchains to communicate with each other in a secure, trust-free environment. Polkadot is built to connect and secure unique blockchains, whether they be pulbic, permission-lss networks, private consortium chains, or oracles and other Web3 technologies. It enables an internet where independent blockchains can exchange information under common security guarantees.
Polkadot is a living network with the core pillars of governance and upgradeability. The network has an advanced suite of governance tools and, using the WebAssembly standard as a "meta-protocol", can autonomously deploy network upgrades. Polkadot adapts to growing needs withou the risks of network forks.
By connecting the dots, Polkadot serves as a foundational part of a decentralized web, where users control their data and are not limited by trust bounds within the network.

### Why Build in the Polkadot Ecosystem?
Polkadot is a shareded blockchain, meaning it connects several chains together in a single network, alowing them to process transactions in parallel and exchange data between chains with security guarantees.
Developers can build application-specific chains use Substrate optimized for their unique use case. Here are the advantages of the subtrate framework and the Polkadot ecosystem:
1. Native Polkado compatibility: Any blockchain bulit with Substrate will be natively compatible with Polkadot, so when the mainnet comes you can connect to Polkadot as a parachain.
2. Interchain Connectivity: By connecting your blockchain to Polkadot, your blockchain will be able to pass arbitrary messages to other chains in the Polkadot network.
3. Fork-free upgrades: Upgrade your blockchain without a hard fork. Your runtime is a Wasm binary store on-chain and can be updated using your chain's governance mechanism.
4. Instant security: Simply by connecting your blockchain to Polkadot, your blockchain will be secured by Polkadot's pooled security.
5. Plug-and-play modular framework: Substrate allows you to simpli plug in the functionalities you need, while also giving you the freedom to customize as needed. 
6. Mulitple Languages: With Substrate, you can write your blockchain logic in any language that can compile to WebAssembly (Rus, C/C++, C#, Go, etc).

### What can you Build on Polkadot?
Substrate comes with everything youned to build your blockchai. Use Substrate's pallets to easily create what you want, or craft your own custom logic. The Polkadot ecosystem already hosts over 100 application-specific blockchains in development, focus on smart contracts, DeFi, IoT, governance, identity, privacy, and more.

## Network Specifications
### Transaction Fees
Pollkadot uses a weight-based fee model as opposed to gas-metering model. As such, fees are charged prior to transaction execution, once the fee is paid (in DOT), nodes will execute the transaction.
Fees on the Polkadot Rlay Chain are calculted based on three parameters:
  - A peer-byte fee (also known the "length fee")
  - A weight fee
  - A tip (optional)
The length fee is the product of constant per-byte fee and the size of the transaction in bytes.

### Transaction Speed & Finality
While custom consensus mechanics can be implemented for your application-specific blockchain, Polkadot's finality protocol finalizes batches of blocks based on availability and validity checks that happen as the proposed chain grows.
The time to finality varies with the number of checks that need to be performed (and invalidity reporst cause the protocol to require extra checkts). The expected to finality is 12-60 seconds on the relay chain.

### Languages Supported
Polkadot has implementation in various programming languages ranging from Rust to JavaScript. Currently, the leading implementation is built in Rust and built using the Substrate framework.
With Substrate, you can write your blockchain logic in any language that can compile the WebAssembly (Rust, C/C++, C#, Go, etc).

##EVM Compatibility
Substrate ECM will allow Substrate-based blockchains, inlcuding Polkadot parachains, to host a nearly-complete instance of the Ethereum state transition function on-chain, alongside any additional Substrate modules as requred for custom functionality.
Existing Soidity applications can be deployed and executed in this environment, and will gain the added benefits of being part of a Substrate-based blockchain.

## Role of the DOT Token
DOT serve three key functions in Polkadot:
  - to be used for governance of the network,
  - to be staked for operation of the network,
  - to be bonded to connect a chain to Polkadot as a parachain.
DOT can also server ancilarry functions by virtue of being a transferrable token. For example, DOT stored in the Treasury can be sent to teams working on relevant projects for the Polkadot network.







