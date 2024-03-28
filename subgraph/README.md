# Subgraph 101

## Basic subgraph with `graph init`

We'll be indexing an [ERC-20 token contract](https://modescan.io/token/0xcDd475325D6F564d27247D1DddBb0DAc6fA0a5CF) on Mode.

What you'll need for your own:
- Contract Address
- ABI
- Start Block

Caveat: Mode isn't included in The Graph CLI's list of supported networks so some manual editing is needed.

Much of the code for this example was borrowed from [Chainstack](https://docs.chainstack.com/docs/subgraphs-tutorial-indexing-erc-20-token-balance).

## Other fun subgraph resources

- [The Graph's](https://thegraph.com/docs/en/quick-start/) documentation for subgraphs.
  - [Creating a Subgraph](https://thegraph.com/docs/en/developing/creating-a-subgraph/).
  - [AssemblyScript API](https://thegraph.com/docs/en/developing/graph-ts/README/).
- [Messari subgraphs](https://github.com/messari/subgraphs): A collection of hand crafted subgraphs that cover a lot of different protocols. Lots of tooling is involved to build these, ping me if you need help.
- [Nouns](https://github.com/nounsDAO/nouns-monorepo/tree/master/packages/nouns-subgraph): A solid example of a DAO subgraph.
