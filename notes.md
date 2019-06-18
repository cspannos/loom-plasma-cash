# Outline

- Introduce Loom Network's implementation of Plasma Cash (ERC721/ERC20/ETH compatible, etc.);

- Review how Sparse Merkle Trees improve the Plasma specification;

- Overview the flow:
	- exclusion proofs;
	- exits;
	- challenges;

- Provide overview of how to install Loom's Plasma-CLI;

- Show how to use Plasma-CLI to deposit, transfer, withdraw, and exist coins;

- Review differences/trade offs between Loom's Plasma Cash and other implementations by OmiseGo and Plasma Group;

- Where is Plasma Cash live? What is it doing in the wild? Plasma Cash on Loom's dAppchain;



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
