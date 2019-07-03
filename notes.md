# Outline/Draft: Work in Progress

- Introduce Plasma and Plasma Cash

- Loom Network's implementation of Plasma Cash (ERC721/ERC20/ETH compatible, etc.);

- Review how Sparse Merkle Trees improve the Plasma specification;

- Overview the flow:
	- exclusion proofs;
	- exits;
	- challenges;

- Provide overview of using Loom's Transfer Gateway;

- Show how to use deposit, transfer, withdraw, and exit coins;

- Review differences/trade offs between Loom's Plasma Cash and other implementations by OmiseGo and Plasma Group;

- Where is Plasma Cash live? What is it doing in the wild? Plasma Cash on Loom's dAppchain;


# Draft

As an Etherem second layer blockchain scaling solution, [the promise of Plasma](https://kauri.io/article/3103de2a3a874f348013b96d157451be/v7/plasma-roundup:-from-mvp-to-mainnet) lays in its potential to help boost transaction throughput per second, thus enabling mass adoption of decentralized financial applications worldwide.

Plasma has so far come in stages. While the [MVP specification](https://ethresear.ch/t/minimal-viable-plasma/426) was designed to offer simplicity and basic security properties to kickstart development, Plasma Cash was designed to solve the mass exit problem.

The mass exit problem    



Plasma is a layer two scaling technology that....

Plasma Cash is a contsruction designed to overcome the problems with with Merkle Tree growth... It does so by using sparse Merkle trees. Sparse Merkle trees have the added benifit of...

The Loom Network Plasma implementaion ....

The flow of the Loom's implementation is... Ethereum chain, Oracle, Plasma chain

In this design users can

deposit, transfer, withdraw, and exit coins;

Let's walk through these....

These steps assume that you have:

1)

2)

3)

4)










# Notes:

"We at Loom are using Truffle to build, test, and deploy our smart contracts. To make our life easier, we developed something called a provider that lets Truffle deploy to Loom PlasmaChain just like it deploys to Ethereum.

Without delving too much into details, the provider works like a bridge that makes Web3.js calls compatible with Loom PlasmaChain."
Source: https://loomx.io/developers/en/intro-to-loom.html#deploying-your-first-app

Interact with Loom DappChain? Is this relevent for Plasma Cash?
Link: https://github.com/loomnetwork/loom-truffle-provider

- Future work
	- atomic transactions
	- payment channels
	- defragmentation (change)
	- state channels + plasma?

# Links to consider for addition

https://www.youtube.com/watch?v=e1dJTfDnPPE&t=163s

https://loomx.io/developers/docs/en/transfer-gateway.html

https://loomx.io/developers/docs/en/extdev-transfer-gateway.html

https://ethresear.ch/t/loom-network-plasma-cash-for-erc721-tokens/2385/1
