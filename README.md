# The Graph (for Querying Blockchain Event Data)
> WAGMI, Keep Buidling!

## LIVE AT: https://mumbai.polygonscan.com/address/0x35A8d1E76e505E0f4b7be227f19FF0222f443366

## About

![logo](https://github.com/0xWick/TheGraph/blob/03524bff10f500d13616b0d40a74ed74fa83087e/graph-dapp/public/1%20(1).png)

## The Graph

* The Graph is used to query blockchain data without using centralized providers.
* They help you to index the events emitted by your contract and query them.
* Anyone can build open api's on the graph which are called subgraphs.
* To query the data, graph asks the developer to use a subset of GraphQL

How to use The Graph to index our events and query them.

## Stack

* The Graph (graph protocol)
* GraphQL
* Hardhat The Graph (graph protocol)
* GraphQL(Solidity)
* Polygon (Mumbai testnet)
* Chainlink VRF

![logo](https://github.com/0xWick/TheGraph/blob/03524bff10f500d13616b0d40a74ed74fa83087e/graph-dapp/public/1%20(2).png)

## How does Graph work?

* A dApp sends a transaction and some data gets stored in the smart contract.
* This smart contract then emits one or more events.
* Graph's node keeps scanning Ethereum for new blocks and the data for your subgraph that these blocks may contain.
* Graph node on finding events for your subgraph runs the mapping handlers that we provide. The mapping is a WASM(Web assembly)
  modules that creates or updates data entities on the Graph Nodes in response to the event.
* Think of these data entities as a structure for letting the graph know how we want our data to be stored.
* Now that the Graph has stored the data in its node's in the form of entities we defined, we can query the
  Graph's node for this data using the GraphQL Endpoint

Let's start building 🚀

Complete track for learning Web3 and make these amazing projects

_For more examples and usage, please refer to the [Wiki][wiki]._

## Development setup

Follow the above link for complete setup!

<!-- Markdown link & img dfn's -->
[wiki]:  https://www.learnweb3.io/tracks/sophomore
