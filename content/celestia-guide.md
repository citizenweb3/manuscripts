+++
title = "Celestia"
date = 2023-03-02

[taxonomies]
tags = ["celestia", "modular", "cosmos", "rollup"]
+++

# Celestia #

[![maxresdefault-2.jpg](https://i.postimg.cc/HxmNk6xX/maxresdefault-2.jpg)](https://postimg.cc/CZv7vHbx)

## What is Celestia ##

[Celestia](https://celestia.org/) is the first modular blockchain network. By decoupling consensus from execution, Celestia enables anyone to easily deploy their own
blockchain, without the overhead of bootstrapping a new consensus network. Blockchains on Celestia are simultaneously scalable, sovereign and secure.

<!-- more -->

[![Fppxn1-TXg-AQh9-Eb.jpg](https://i.postimg.cc/brhtZFS0/Fppxn1-TXg-AQh9-Eb.jpg)](https://postimg.cc/Hc6xKz2j)

Most existing blockchains are monolithic - meaning that the execution and validation functions are performed by the same powers, leading to scalability issues.
Scalability is the ability to increase the number of transactions, without a equal increase in operating costs. If a blockchain can increase the number of transactions
it processes without equally increasing the cost for nodes to verify the transactions, it is scaling. The idea of modular blockchain is to divide all tasks into smaller
ones, to concentrate on solving specific tasks rather than all in a row. This is made possible by combining several specialized blockchains.

[![AK534-BRVUZH3-DG7-NRZVMJ26-Z4-I.png](https://i.postimg.cc/vm4qhDqq/AK534-BRVUZH3-DG7-NRZVMJ26-Z4-I.png)](https://postimg.cc/XZ0k7N0d)

Celestia is an example of a modular blockchain that provides the other functions that rollups depend on, like consensus and data availability.
So Celestia, being a modular blockchain and focusing on data availability and consensus, is a highly scalable modular blockchain. Other chains (L1 and L2) can use
Celestia to scale data availability while focusing on execution. Celestia will become sort of the foundation for the rest of the chains, with other blockchain developers
being able to rely on celestia for data availability and consensus while focusing on execution.  This is possible since Celestia’s light clients do not verify
transactions, they only check that each block has consensus and that the block data is available to the network.

## Data availability ##

The problem of data availability is this: how can nodes be sure that when a new block is produced, all the data in that block has actually been published on the
network. Specifically, a node will verify data availability when it receives a new block that is getting added to the chain. The node will attempt to download all the
transaction data for the new block to verify availability. If the node can download all the transaction data, then it successfully verified data availability, proving
that the block data was actually published to the network. 

Celestia uses what is called Data Availability Proofs. These and fraud proofs are key to enabling on-chain scaling of blockchains. Data Availability Proofs allow for
nodes to download and sample a small portion of random chunks from each block in the chain. If any full node detects something suspicious they can notify light
clients with a data availability fraud proof.

[![11ed712ba60978f7a8e6023f659fee92.jpg](https://i.postimg.cc/BZFvygPs/11ed712ba60978f7a8e6023f659fee92.jpg)](https://postimg.cc/kDn9RWyh)

Beyond their security advantages, Celestia light clients play a fundamental role in the security and scalability of the network as a whole. Celestia light clients
rely on security in numbers. There must be a minimum number of light clients to ensure that the original block data is recoverable from all the samples they take
individually.

On the other hand as the number of light clients increases, then the size of each block can also increase without compromising the security or decentralization of the
network. Larger blocks means more data throughput and more scaling.

## Sovereign rollups ##

A type of rollup that does not use a settlement layer to determine its canonical chain and validity rules. Instead, the canonical chain of the rollup is determined by
the nodes in the rollup's peer-to-peer network. This means that settlement occurs on the rollup, rather than a separate settlement layer.

Sovereign rollups on Celestia do not post their blocks to a smart contract, but directly onto the chain as raw data. The Celestia consensus and data availability
layer does not interpret or perform any computation on the rollup blocks, nor run an on-chain light client for the rollup.

Instead, the rollup effectively operates like a layer 1 blockchain: full nodes and light clients download the blocks of the rollup directly from the rollup's own
peer-to-peer network. The main difference is that they also verify that the rollup block data was included and ordered on the Celestia data availability layer via
a Merkle proof. Therefore, similar to a layer 1 blockchain, the canonical chain is determined by nodes that locally verify the fork-choice rule and the transactions
of the rollup, rather than an enshrined on-chain light client.

Fraud and validity proofs also work similarly to how they would work in a layer 1 blockchain. Fraud proofs are gossiped to clients directly via the peer-to-peer
network, and validity proofs are simply included with the block header (for example, see Mina Protocol). Because the network synchrony delay in a peer-to-peer
network is likely to be significantly smaller than the delay of getting a fraud proof included on-chain, this means that the challenge period for peer-to-peer
fraud proofs can likely be much lower, leading to faster finality for light clients.

A rollup chain is sovereign if it does not enshrine a settlement layer to determine the canonical chain and the transaction validity rules of the rollup. Rather, the
canonical chain of the rollup is determined by the nodes in the rollup's peer-to-peer network (provided that the blocks are available on the data availability layer).
This means that the settlement layer cannot force inclusion of transactions into the rollup.

Sovereign rollups can also use Ethereum as a data availability layer only without enshrining Ethereum for settlement, however this adds more overhead compared to
using a “pure” data availability layer such as Celestia, because the rollup nodes need to take an interest in the validity of all the transactions in the Ethereum
settlement layer, in order to run a node for the Ethereum data availability layer.

It is also possible to construct a “settlement rollup” on Celestia, which is a type of a sovereign rollup. A settlement rollup can have non-sovereign rollups that
use it as an enshrined settlement layer. However, the settlement layer is sovereign in the same way that the Ethereum L1 is sovereign as its community often upgrades
it with hard forks via social consensus.

You can read more about sovereign rollups and how they work [here](https://blog.celestia.org/sovereign-rollup-chains/#rollups-on-celestia).

## Celestia Tokenomics ##

At the moment there is no tokenomics, but it is known that Celestia will have its own token, which will be used to secure the network via Proof of Stake, and to pay
for transaction fees on the network. Also Celestia plans to implement a fee-burn mechanism similar to EIP-1559 in Ethereum so that burnt fees will offset new token
issuance as Celestia gains adoption.

## Why Celestia makes sense? ##

As we said above, the key advantages of Celestia are:
[![Fpp0-OV-Xs-AMrx-Nf.jpg](https://i.postimg.cc/NFRCqVmW/Fpp0-OV-Xs-AMrx-Nf.jpg)](https://postimg.cc/5QNS8sP3)

***Scalability*** - Separate functions across different layers and Celestia's focus on data availability allows you not to worry about transaction execution and smart
contracts, which increases scalability. 

***Shared security*** - The lack of cost to attract and maintain validators, and the overall security that Celestia provides for the blockchains built on top of it,
makes it easy for everyone to run their own blockchain.

***Sovereignty*** - Unlike monolithic blockchains, where applications must follow the rules of the blockchain on which they are built, blockchains built on Celestia
can set their own rules through sovereignty. Developers can change the way a transaction is processed or anything else that gives independence to blockchains built
on Celestia.

## Roadmap ##

The launch of the main celestia network is scheduled for 2023, and preparations are now underway for a test network in which those who filled out a form in advance
to participate in the test network will be able to participate.

[![Screenshot-604.png](https://i.postimg.cc/fTrCqDGJ/Screenshot-604.png)](https://postimg.cc/hfVVfWPB)

-----------------------------------------------------------------------------------------------------------------------------------------------------------

If you would like to support our mission in creating educational content and aligning the goals of different communities, please stake with us [here](https://www.citizencosmos.space/staking). 

- [EVMOS](https://wallet.keplr.app/chains/evmos?modal=validator&chain=evmos_9001-2&validator_address=evmosvaloper1mtwvpdd57gpkyejd566s24afr9zm5ryq8gwpvj) 
- [ATOM](https://wallet.keplr.app/chains/cosmos-hub?modal=validator&chain=cosmoshub-4&validator_address=cosmosvaloper1e859xaue4k2jzqw20cv6l7p3tmc378pc3k8g2u) 
- [BOOT](https://wallet.keplr.app/chains/bostrom?modal=validator&chain=bostrom&validator_address=bostromvaloper1f7nx65pmayfenpfwzwaamwas4ygmvalqj6dz5r)

Join our [community](https://discord.gg/kJaG3EucCX), to build a future where communication is decentralized. May the code be with you!
