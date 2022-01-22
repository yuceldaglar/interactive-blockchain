# Interactive Blockchain
A New Blockchain Concept

## What is a Blockchain
A blockchain is a list of records, for example a list of money transactions. But this list is grouped into blocks. So the list does not grow by adding a new record but the list grows by adding a new block. 

Every block has some records plus the cryptographic hash of the previous block. By this way blocks are linked together and become a “chain”. So you can not alter a single block. A change in a block will change the hash and the block becomes invalid. Although it is possible to alter a block if you calculate all the following block hashes.

Because of this, bitcoin uses a proof of work (Pow) system. Pow is basically a time consuming mathematical calculation for a block. So if you make a change in a block, all following hashes change. Pow value for all of those blocks must be recalculated. But, because the pow calculation needs time and processing power, it is not possible in practice.
Problems with Bitcoin and Blockchain
For security of the blockchain, bitcoin uses a proof of work algorithm with a high calculation rate. But this comes with some costs, transaction times are very high, also the mining costs are very high. 

## Interactive Blockchain
I think I invented a new kind of blockchain, which I call interactive blockchain. Standard blockchain takes records and makes blocks out of them. Records do not know anything about the chain.

With an interactive chain (or ichain), users add the hash value of the last known block to every transaction. This last known block can be the very last block or one of the N last blocks. It is up to the user to use the most recent block hash, but for timing issues, it is accepted to use one of the last N blocks. (Maybe N can be taken 2 or 3, it is related to the block adding speed)

In an ichain, records know about the chain. So it is not possible to take records from an ichain and build another chain. This is the main goal of this method.

Another advantage of this method can be, to decrease the computation power needed for proof of work algorithms. If we achieve this, it will be a huge improvement for digital currencies, from transaction processing times to mining costs.
