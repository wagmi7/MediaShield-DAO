# MediaShield DAO 🛡️

Welcome to MediaShield DAO, the decentralized autonomous organization built on the Aurora blockchain using the powerful BOS (Blockchain Operating System) framework! 🌟

## 📚 Description

MediaShield DAO is a revolutionary digital media and entertainment solution that addresses the challenges faced by the industry, including data privacy, intellectual property protection, royalty payments, and copyright infringement. Our DAO empowers content creators and users alike, providing a secure and transparent platform for sharing, monetizing, and enjoying digital media.

## 🎯 Purpose

The purpose of MediaShield DAO is to create a decentralized ecosystem that promotes fair and sustainable practices in the digital media and entertainment industry. We aim to:

- Safeguard data privacy and protect user information from unauthorized access.
- Ensure proper intellectual property protection and attribution for content creators.
- Enable transparent royalty payments to ensure fair compensation for creators.
- Combat copyright infringement and establish trust within the ecosystem.

## ⚙️ Built with BOS on Aurora

MediaShield DAO leverages the capabilities of the BOS (Blockchain Operating System) framework to provide a robust and scalable infrastructure for our decentralized ecosystem. Here's how BOS enables us to achieve our goals:

- **Decentralized Storage**: BOS allows us to securely store digital media assets while preserving user privacy through encryption and decentralized storage solutions.

- **Smart Contracts**: With BOS, we created smart contract on the Aurora blockchain to tokenize digital assets, establish ownership, and automate royalty payments, ensuring fair compensation for content creators.

- **NFT Standards**: BOS supports NFT (Non-Fungible Token) standards like ERC-721 and ERC-1155, enabling us to tokenize and protect digital media assets, establish provenance, and facilitate licensing and monetization.

- **Governance and Voting**: BOS provides governance mechanisms, including decentralized decision-making and voting systems, allowing community members to actively participate in shaping the direction of the DAO.

## 🚀 Deployed on Aurora Blockchain

MediaShield DAO is live and deployed on the Aurora blockchain, leveraging its fast and low-cost transactions. Here are the deployed contracts:

Deployed Factory Contract- https://explorer.testnet.near.org/transactions/5zpUGebymD8hm96DFMApRNH5Zh3BCSkrJfhL6xnQvxu3

Initiated - https://explorer.testnet.near.org/transactions/6iKVQTnM4zYnZFDMPGQiatqeAmHuzGEUMe25cioDjUxM

- DAO Contract: [DAO Contract Address](https://explorer.aurora.dev/address/dao-contract-address)
- NFT Marketplace: [NFT Marketplace Address](https://explorer.aurora.dev/address/nft-marketplace-address)
- Royalty Payment Contract: [Royalty Payment Contract Address](https://explorer.aurora.dev/address/royalty-payment-contract-address)

Join us on this exciting journey as we revolutionize the digital media and entertainment industry, ensuring privacy, protecting intellectual property, and fostering a fair and rewarding ecosystem for creators and users alike! 💪🎉

For more information, visit our [website](https://mediashielddao.com) and explore our [documentation](https://mediashielddao.com/docs).

Feel free to contribute and engage with the community. Together, let's build the future of digital media! 🌐🔥

npm install -g near-cli

export CONTRACT_ID=kamaleth.testnet

export COUNCIL='["kamaleth.testnet"]'

export ARGS=`(echo '{"config": {"name": "Mediashield", "purpose": "To create a decentralized ecosystem that promotes fair and sustainable practices in the digital media and entertainment industry", "metadata": "MediaShield DAO is a revolutionary digital media and entertainment solution that addresses the challenges faced by the industry, including data privacy, intellectual property protection, royalty payments, and copyright infringement"}, "policy": '$COUNCIL'}' | base64)`

export ARGS=`echo '{"config": {"name": "Mediashield", "purpose": "Genesis DAO", "metadata":""}, "policy": '$COUNCIL'}' | base64`

near call $CONTRACT_ID create "{\"name\": \"Metashield\", \"args\": \"$ARGS\"}" --accountId $CONTRACT_ID --amount 10 --gas 150000000000000

export ARGS=`echo '{"config": {"name": "MediaShield", "purpose": "To create a decentralized ecosystem that promotes fair and sustainable practices in the digital media and entertainment industry", "metadata":"MediaShield DAO is a revolutionary digital media and entertainment solution that addresses the challenges faced by the industry, including data privacy, intellectual property protection, royalty payments, and copyright infringement"}, "policy": '$COUNCIL'}' | base64`

export ARGS=`echo '{"config": {"name": "<name>", "purpose": "To create a decentralized ecosystem that promotes fair and sustainable practices in the digital media and entertainment industry", "metadata":""}, "policy": '$COUNCIL'}' | base64`

export ARGS=`echo '{ "config": { "name": "MediaShield", "purpose": "To create a decentralized ecosystem that promotes fair and sustainable practices in the digital media and entertainment industry", "metadata": "MediaShield DAO is a revolutionary digital media and entertainment solution that addresses the challenges faced by the industry, including data privacy, intellectual property protection, royalty payments, and copyright infringement"}, "policy": ["0xkamal7.testnet", "kamaleth.testnet"] }' | base64

export ARGS=$(echo '{"config": {"name": "MediaShield", "purpose": "To create a decentralized ecosystem that promotes fair and sustainable practices in the digital media and entertainment industry", "metadata": "MediaShield DAO is a revolutionary digital media and entertainment solution that addresses the challenges faced by the industry, including data privacy, intellectual property protection, royalty payments, and copyright infringement"}, "policy": ["0xkamal7.testnet", "kamaleth.testnet"]}' | base64)

near call $CONTRACT_ID create "{\"name\": \"MediaShield\", \"args\": \"$ARGS\"}" --accountId $CONTRACT_ID --amount 5 --gas 150000000000000

export ARGS=`echo '{"config": {"name": "mediashield", "purpose": "Mediashield DAO", "metadata":""}, "policy": '$COUNCIL'}' | base64`
near call $CONTRACT_ID create "{\"name\": \"mediashield\", \"args\": \"$ARGS\"}" --accountId $CONTRACT_ID --amount 10 --gas 150000000000000

near call $CONTRACT_ID create "{\"name\": \"mediashield\", \"args\": \"$ARGS\"}" --accountId $CONTRACT_ID --amount 10 --gas 150000000000000