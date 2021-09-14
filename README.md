# Resources For This Course

## What is a Blockchain?
- [Bitcoin Whitepaper](https://bitcoin.org/bitcoin.pdf)
- [Ethereum Whitepaper](https://ethereum.org/en/whitepaper/)
- [Binance Whitepaper](https://whitepaper.io/coin/binance)
- [What is a blockchain](https://www.investopedia.com/terms/b/blockchain.asp)

## Making Your First Transaction
- [Metamask](https://metamask.io/)
- [Test BSCScan](https://testnet.bscscan.com/)
- [Main BSCScan](https://bscscan.com/)
- [Gas and Gas Fees](https://ethereum.org/en/developers/docs/gas/)
- [Wei, Gwei, and Binance Converter](https://bscscan.com/unitconverter/)
- [Binance Gas Station](https://bscgas.info/)

## How Do Blockchains Work?
- [Blockchain Demo](https://andersbrownworth.com/blockchain/)
- [Public / Private Keys](https://andersbrownworth.com/blockchain/public-private-keys/keys)
- [Layer 2 and Rollups](https://ethereum.org/en/developers/docs/scaling/layer-2-rollups/)
- [Decentralized Blockchain Oracles](https://blog.chain.link/what-is-the-blockchain-oracle-problem/)
- [Block Rewards](https://www.investopedia.com/terms/b/block-reward.asp)

## Miscellaneous
- [DAOs](https://www.investopedia.com/tech/what-dao/)

# Section 1:
### Everything in this section can be read about in the [Solidity Documentation](https://docs.soliditylang.org/en/v0.8.6/index.html)
### [Remix](https://remix.ethereum.org/)
### Basic Solidity
- Versioning
- Compiling
- Contract Declaration
- [Types & Declaring Variables](https://docs.soliditylang.org/en/v0.8.6/types.html)
    - `uint256`, `int256`, `bool`, `string`, `address`, `bytes32`
- Default Initializations
- Comments
- Functions
- Deploying a Contract
- Calling a public state-changing Function
- [Visibility](https://docs.soliditylang.org/en/v0.7.3/contracts.html#visibility-and-getters)
- Scope
- View & Pure Functions
- Structs
- Intro to Storage
- Arrays - Dynamic & Fixed sized
- Compiler Errors and Warnings
- Memory
- Mappings
- SPDX License
- Recap
### Deploying to a "Live" network
- A testnet or mainnet
- [Find a faucet here](https://docs.chain.link/docs/link-token-contracts/#rinkeby)
- Connecting Metamask
- Interacting with Deployed Contracts
- The EVM

# Session 2:
### Payable, msg.sender, msg.value, Units of Measure
- Payable
- [Wei/Gwei/Binance Converter](https://bscscan.com/unitconverter/)
- msg.sender & msg.value
### Chainlink Oracles
- Decentralized Oracle Network Chainlink
    - Blockchains can't make API calls
    - Centralized Nodes are Points of Failure
- [data.chain.link](https://data.chain.link/)
- Getting External Data with Chainlink Oracles
    - [Chainlink](https://docs.chain.link/)
    - [Faucets and Contract Addresses](https://docs.chain.link/docs/link-token-contracts/)
        - [Kovan](https://docs.chain.link/docs/link-token-contracts/#kovan)
    - [Getting Price Information](https://docs.chain.link/docs/get-the-latest-price/)
### Importing from NPM and Advanced Solidity
- Decimals/Floating Point Numbers in Solidity
- latestRoundData
- Importing from NPM  in Remix
- Interfaces
    - Introduction to ABIs
- [Getting Price Feed Addresses](https://docs.chain.link/docs/reference-contracts/)
- getPrice
- Tuples
    - Unused Tuple Variables
- Matching Units (WEI/GWEI/Binance)
- getConversionRate
- Matching Units (Continued)
- SafeMath & Integer Overflow
    - using keyword
    - [Libraries](https://docs.soliditylang.org/en/v0.8.6/contracts.html#libraries)
    - SafeMath PSA
- Setting a Threshold
- Require
- Revert
- Withdraw Function
- Transfer
- Balance
- this
- Contract Owners
- Constructor
- ==
- Modifiers
- Resetting
- for loop
- Array Length
- Forcing a Transaction
- Recap

### Installing VSCode, Python, and Web3
- [Developer Bootcamp Setup Instructions (metamask, vscode, python, nodejs..)](https://chain.link/bootcamp/brownie-setup-instructions)
- [VSCode](https://code.visualstudio.com/download)
- Extensions
- ShortCuts:
    - [VSCode Shortcuts](https://code.visualstudio.com/docs/getstarted/keybindings)
    - [VSCode MacOS Shortcuts](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf)
- [Python](https://www.python.org/downloads/)
    - Install Troubleshooting
- Terminal
- Making a directory/Folder
- Opening the folder up with VSCode
- Creating a new file
- Syntax Highlights
- Remember to save!
- Setting linting compile version
- VSCode Solidity Settings
    - Formatting & Format on Save
    - Solidity Prettier

# Session 3: NFTs
### Non-Technical Explainer
- [End-to-end article](https://www.freecodecamp.org/news/how-to-make-an-nft-and-render-on-opensea-marketplace/)
- What is an NFT?
- [ERC721](https://eips.ethereum.org/EIPS/eip-721)
- [ERC1155](https://eips.ethereum.org/EIPS/eip-1155)
- Token URI
- [Token Metadata Example](https://docs.opensea.io/docs/2-adding-metadata)
- [IPFS](https://ipfs.io/)

### Simple NFT
- [OpenZeppelin ERC721](https://docs.openzeppelin.com/contracts/3.x/)
- [OpenZeppelin ERC1155](https://docs.openzeppelin.com/contracts/3.x/)
- [TokenURI used for the demo: https://ipfs.io/ipfs/Qmd9MCGtdVz2miNumBHDbvj8bigSgTwnr4SbyH6DNnpWdt?filename=0-PUG.json](https://ipfs.io/ipfs/Qmd9MCGtdVz2miNumBHDbvj8bigSgTwnr4SbyH6DNnpWdt?filename=0-PUG.json)
- [IPFS Companion](https://chrome.google.com/webstore/detail/ipfs-companion/nibjojkomfdiaoajekhjakgkdhaomnch?hl=en)
- Rinkeby Deployment
- [Opensea Example](https://testnets.opensea.io/assets/0x8acb7ca932892eb83e4411b59309d44dddbc4cdf/0)

### Creating Metadata & IPFS
- [Download IPFS Command Line](https://docs.ipfs.io/install/command-line/)
- [Download IPFS Desktop](https://docs.ipfs.io/install/ipfs-desktop/)
- [HTTP IPFS Docs](https://docs.ipfs.io/reference/http/api/)
- [Pinata](https://app.pinata.cloud/)
- [Pinata Docs](https://docs.pinata.cloud/)

# Session 4: Upgrades
### Introduction to upgrading smart contracts
- [Original Video](https://www.youtube.com/watch?v=bdXJmWajZRY)
- Smart Contracts can be upgraded!
- Does this mean they are not immutable?
- [Trail of Bits on Upgradeable Smart Contracts](https://blog.trailofbits.com/2018/09/05/contract-upgrade-anti-patterns/)
- The "Not Really Upgrading" / Parameterization Method
- The Social Yeet / Migration Method
- [Contract Migration](https://blog.trailofbits.com/2018/10/29/how-contract-migration-works/)
- Proxies
    - DelegateCall
    - Terminology:
        - Implementation Contract
        - Proxy Contract
        - User
        - Admin
    - Gotchas:
        - Storage Clashes
        - Function Selector
        - Function Selector Clashes
    - Proxy Patterns:
        - [Transparent Proxy Pattern](https://blog.openzeppelin.com/the-transparent-proxy-pattern/)
        - [Universal Upgrade Proxy Standard](https://eips.ethereum.org/EIPS/eip-1822)
        - [Diamond/Multi-Facet Proxy](https://eips.ethereum.org/EIPS/eip-2535)
