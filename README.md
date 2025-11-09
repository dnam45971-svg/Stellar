StellarFan: Smart Contract for Fan Interaction

This project is a smart contract built on Stellar's Soroban platform, designed to help creators (artists, musicians, etc.) connect with their fans through NFTs (Non-Fungible Tokens) and ensure they receive royalties automatically and transparently.

Objective

In the Web3 economy, empowering creators is a key goal. This contract addresses that goal by:

NFT issuance: Allows creators to mint their works as unique NFTs on the blockchain.

Ownership management: Records and enables secure transfer of NFT ownership.

Automated royalties: Provides a mechanism to simulate royalty payments to the creator each time an NFT is resold.

Main Features

The contract includes the following core functions:

initialize: Initializes the contract with a single admin address.

mint_nft: Mints (creates) a new NFT, assigning an owner, creator, and metadata URL.

transfer_nft: Allows the current owner to transfer their NFT to another address.

get_nft: Queries and views detailed information about a specific NFT.

pay_royalty: Simulates payment of royalties to the NFT creator.

set_royalty: Allows the admin to set royalty parameters.

Requirements

To run and interact with this project, you need:

Rust programming language

Soroban CLI

A Stellar Testnet account funded via Friendbot
