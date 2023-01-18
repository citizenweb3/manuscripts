+++
title = "Bostrom-Cyber: a complete guide. Part 1 - Description"
date = 2022-11-28

[taxonomies]
tags = ["guide", "cyber", "bostrom", "spacepussy", "ai"]
+++

[![Screenshot-430.png](https://i.postimg.cc/V6zW89PN/Screenshot-430.png)](https://postimg.cc/8Fn6d658)
### Bostrom
Bostrom is a superintelligence, with a permissionless knowledge graph at its core built on a blockchain (cosmos-SDK) and content addressing mechanism (with the current implementation of IPFS protocol).Bostrom allows adding knowledge (creating cyberlinks between particles) to the knowledge graph verifiably. By "verifiably" we mean that it is guaranteed by blockchain design that the holder of a particular private key added specific content into the blockchain at the known time.

<!-- more -->

The knowledge graph is a directed weighted graph between particles (CIDs or Content-ID of files, also known as content addresses, IPFS-hashes, IPFS-links).
Cyberlinks are the edges of the knowledge graph, particles are the vertexes (aka nodes). In order to create cyberlinks in Bostrom, user accounts (so-called neurons) must have VOLT and AMPERE tokens. By definition, created cyberlinks cannot be deleted. This means, among other things, that they will always be taken into account in cyberrank (until "forgetting" or "pruning" functions are introduced).

<!-- more -->


IPFS (interplanetary file system) is a distributed (decentralized) file system within which files are stored on network members' computers. Files are received by their CID (cryptographic hash, particle in Bostrom's terminology) using software that supports IPFS protocol.
Files are downloaded from network participants' nodes. Therefore, the more devices have the file, the higher chances it can be downloaded (and potentially faster).

### Cyber
Cyber is a distributed, self-sustainable computer for answers, managed and governed by its users. It is structured to resemble a superintendent AI organism, which can learn from the data it taught by its users. Cyber is able to provide answers to questions without blackbox intermediaries and already has MVP's, such as, an alternative to Google and Twitter.
You may think of Cyber akin to a huge Wikipedia without censorship, which is at the moment waiting to be filled with knowledge from the current web, or even by a transition of data to the new, transparent web. A web in which you control your own dataset. A web that is free of censorship. A web where the internet works for you and not the other way around.

Cyber is basically a big decentralized knowledge graph, to which users add and read information from. While validators (of Cyber) use their machines to rank and index the user provided information in a trustless manner. For now, Cyber works with a technology called [IPFS](https://ipfs.tech/), which is basically, a distributed P2P storage where users can safely store and exchange data, but Cyber can work with any similar technology such as DAT, GIT, Bitcoin, Ethereum, Swarm, etc.

[Cyb.ai](https://cyb.ai/) - is a WEB interface to the Bostrom blockchain developed by the cyber~Congress DAO. Among Cyb.ai's many functions are:

-receiving data on cyberlinks recorded by Bostrom blockchain from the node

-creating cyberlinks

-receiving and sharing objects in the IPFS network using library ipfs-js

### Bostrom and Cyber tokens
There are several native tokens in the Bostrom network: BOOT, HYDROGEN, VOLT, AMPERE, TOCYB. Each of its own usage.
Cyber Congress governance tokens : GOL and THC.

**BOOT** is the main token of Bostrom. The token's name BOOT symbolizes the BOOTloader nature of the Bostrom network for the future Cyber network.

With BOOT one can:

-"hire a hero"(to delegate tokens to a validator), being paid rewards in return (risk fee)- for each staked BOOT a HYDROGEN is minted (with a 1 to 1 ratio)

-pay for network transactions (pay for gas). Though now, many validators accept transactions with 0 gas fee

-vote for protocol changes and public goods

With **HYDROGEN** one can:

-"investmint" HYDROGEN for a limited period to produce VOLT and AMPERE tokens

-exchange it back for delegated BOOT to transfer BOOT into a liquid state

**Volt** token:

-is needed to create cyberlinks

-amount of Volt tokens on a balance of the selected neuron regulates how many cyberlinks per day the neuron can submit

Each Volt token on the neuron's balance allows creating 1 cyberlink per day. The ability to create cyberlinks is restored within a day.
If the network is underloaded, one can produce more cyberlinks (up to 4 cyberlinks for each Volt on balance per day).

**Ampere** token:

-is needed to create cyberlinks

-amount of Ampere tokens on a balance of the selected neuron is used to compute "ampere-per-cyberlink metric", which is used in cyberrank algorithm

The more Ampere tokens the neuron has, the higher his cyberlinks would be ranked. Cyberrank is recalculated for each cycle so that the changes in the amount of Ampere tokens on the neurons' balances that produced cyberlinks would influence the cyberrank of the whole graph. It's reasonable to think of Ampere tokens as a measure that characterizes the impact of cyberlinks created from the account on the knowledge graph.

**TOCYB** token is a token of a future Cyber network. Everyone who has TOCYB will be able to convert it at a 1 to 1 rate into CYB tokens through the private exodus. The contract will be developed by cyberCongress.

All the tokens can be in two states: frozen and liquid (except TOCYB which is always in liquid state).

When tokens are in liquid state they can be:

-transferred to other addresses in the Bostrom or other blockchains of Cosmos network

-swapped to other tokens using liquidity pools. Other tokens can be non-native Bostrom tokens transferred by IBC protocol from other blockchains of the Cosmos network

**More** tokens:

**THC** is the main governing token of Cyber. THC is an ERC-20 token and lives in the Ehereum mainnet. THC has utility value in the form of control over cyber~Foundation(is the community governing DAO behind cyber).

**GOL** tokens are the testing equivalent of THC.

**PUSSY** tokens are the main tokens of the [space-pussy network](https://space-pussy.cyb.ai/). This is a CosmWasm and IBC enabled network that is supposed to help to test Bostrom, Cyber and launch new communities and contracts.

You can read more about cybernomics on [Github page](https://github.com/cybercongress/cybernomics/blob/main/bostrom/README.md)

-----------------------------------------------------------------------------------------------------------------------------------------------------------

If you would like to support our mission in creating educational content and aligning the goals of different communities, please stake with us [here](https://www.citizencosmos.space/staking): 

- [EVMOS](https://wallet.keplr.app/chains/evmos?modal=validator&chain=evmos_9001-2&validator_address=evmosvaloper1mtwvpdd57gpkyejd566s24afr9zm5ryq8gwpvj) 
- [ATOM](https://wallet.keplr.app/chains/cosmos-hub?modal=validator&chain=cosmoshub-4&validator_address=cosmosvaloper1e859xaue4k2jzqw20cv6l7p3tmc378pc3k8g2u) 
- [BOOT](https://wallet.keplr.app/chains/bostrom?modal=validator&chain=bostrom&validator_address=bostromvaloper1f7nx65pmayfenpfwzwaamwas4ygmvalqj6dz5r)

Join our [community](https://discord.gg/kJaG3EucCX), to build a future where communication is decentralized. May the code be with you! 

This guide was created for [Citizen Cosmos](https://www.citizencosmos.space/) by [Magican](https://t.me/magican_n)
