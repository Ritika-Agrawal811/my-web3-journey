# How Blockchain Works :zap:

Day 2 starts with understanding how the blockchain works. How it solves the problem of double spending that comes with electronic transactions.

### Table of Contents :sparkles:

- [A chain of blocks](#a-chain-of-blocks-🔗)
- [Genesis block](#genesis-block-🌱)

## A chain of blocks 🔗

_Blockchain is a chain of blocks that record the data._ Each block contains _data_, a _unique_ hash indentifying that block and hash of _previous block_.

**Data** that a block holds depends on the type of blockchain.

- Bitcoin, for example, stores details about a transaction like the sender, the receiver and the amount of coins.
  <br/> <br/>

**Hash** is like a finger print of a block. It identifies a block and all of its contents. Once a block is created, its hash is calculated based on its contents.

This **hash** is stored in the next block to form a chain just like a _linked list_. This link is called **nonce**.

Changing any data from a block will cause its _hash_ to change. Now, its changed hash will not be the same as the one stored in the next block. Hence making it very easy to detect frauds.

## Genesis block 🌱

Since all the blocks in a blockchain store the hash of _previous block_ to form a chain, then what about the first block?

Genesis block is the very first block of a blockchain. Since it is the very first block, it doesn't have a hash of previous block. It is structured differently from other blocks.

The first genesis block, known as the "Block 0" or the "genesis block," was minted on January 3, 2009. It marks the beginning of the Bitcoin blockchain.
