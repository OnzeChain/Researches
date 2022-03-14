# Tools and Solutions

In this document we try to research the useful things we probably will be using in development.

## What exchange are we forking?

### Uniswap:

The original DeFi liquidity protocol built on Ethereum. Today's standard for easy cryptocurrency trading using ERC-20 tokens and mostly ETH pairs.

Language: 
Front-End: TypeScript
Back-End: Solidity

Github: https://github.com/Uniswap

### PancakeSwap:

Uniswap clone built on BSC to deliver fast and inexpensive trades using BEP-20 tokens and the BSC←→ETH bridge.

Language: 
Front-End: TypeScript
Back-End: Solidity

Github: https://github.com/pancakeswap

### SushiSwap:

A community-governed Uniswap fork that has evolved into a DeFi hub offering token swaps, farming, and crypto lending/borrowing.

Language: 
Front-End: TypeScript
Back-End: Solidity

Github: https://github.com/sushiswap

While all three enable decentralized exchange, community governance, yield farming, and LP (liquidity provider) opportunities, only Sushi and PancakeSwap pay rewards back to token holders who stake their tokens.

After looking into the code I discovered that they equal to each other.

### QuickSwap:

Language: 
Front-End: TypeScript
Back-End: Solidity

Github: https://github.com/QuickSwap


## What SDK’s will we use?

### Moralis: 

Moralis is the fastest way to build and deploy dApps on Ethereum, BSC, Polygon, Solana, and Elrond (more coming). All Moralis dApps are cross-chain by default. Building on Moralis ensures that your dApp is future-proof. Even if new blockchains are invented, your dApp will instantly work on any chain.

Moralis provides an SDK: https://docs.moralis.io/moralis-server/web3-sdk

Moralis' SDK is how they tie all of this together. Their JavaScript SDK is how our dApp interacts with our Moralis Server. Using the SDK, you can authenticate users, either through username and password or through a crypto wallet like MetaMask You can also use the SDK to get and set user data to fetch balances, NFTs, events, or transactions.

### Polygon Edge:

Polygon SDK vision is to effectively transform Ethereum into a full-fledged multi-chain system (aka the Internet of Blockchains). By doing this, it will at the same time further establish Polygon as the leading scaling and infrastructure platform of Ethereum.

A little-known fact is that Ethereum is already the biggest multi-chain system in the world! This multi-chain system has organically developed and grown to host a multitude of chains that are all adding value and strength to the Ethereum ecosystem.

Polygon Edge is for making your own SideChain so it might be possible for in the future.

https://edge-docs.polygon.technology/docs/overview/

## What wallets are we going to support/use?

There are a lot of wallets available on the polygon Blockchain below I have link to list of wallets:

https://docs.polygon.technology/docs/faq/wallet-list/

As you can see the most used wallets are available on Polygon.

## Truffle suite

https://trufflesuite.com/index.html

https://www.youtube.com/watch?v=62f757RVEvU
