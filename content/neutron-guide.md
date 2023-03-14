+++
title = "Neutron"
date = 2023-03-14

[taxonomies]
tags = ["neutron", "smartcontracts", "cosmos", "ibc", "interchain"]
+++

# Neutron #

[![1-UDYe-Jo-DNI5-ALn-Uw3-Ij-ANOA.webp](https://i.postimg.cc/fyHvdjKj/1-UDYe-Jo-DNI5-ALn-Uw3-Ij-ANOA.webp)](https://postimg.cc/FkLc5Sw7)

## What is Neutron ##

[Neutron](https://neutron.org/) is permissionless smart contract platform for Interchain DeFi built with Cosmos SDK & Tendermint. Neutron allows to deploy smart
contracts to the market in a blaze. Smart contracts can query, transact and manage accounts in remote zones directly from Neutron. 

<!-- more -->

Neutron is the most secure CosmWasm platform because it uses Interchain Security technology. Interchain Security allows Neutron to have the same security as Cosmos hub
(which is 200M+ ATOM tokens). This means that Cosmos hub validators will also secure Neutron, for which they will be rewarded with native tokens distributed from
consumer fees.

Neutron is incubated by [P2P Validator](https://p2p.org/economy/introducing-neutron/) who also were founders of Lido Protocol.

## Interchain Accounts(ICA) ##

Interchain accounts allow modules and smart contracts to execute and track transactions on foreign zones via [IBC](https://ibcprotocol.org/), instead private keys,
and without deploying additional code. Also ICAs allow transactions to be written and transported in a way that can be executed on the host chain.

Neutron will be both a “host” and a “controller” and will launch with a custom implementation that makes Interchain Accounts available to smart contracts.
It means, smart contracts on Neutron will be able to interact with modules and zones from other ICA-enabled Cosmos chains and vice versa.

[![FXeqt-H5-WYAEw-Qb-Z.jpg](https://i.postimg.cc/85w1hjrm/FXeqt-H5-WYAEw-Qb-Z.jpg)](https://postimg.cc/vggFy8h4)

You can read more about Interchain Accounts [here](https://twitter.com/Neutron_org/status/1546893324774260736).

## Interchain Queries ##

A query is a way to retrieve data from a blockchain’s storage. For example, in order to find out about the balance of a certain token or tokens in a wallet,
you need to send a query and get a reply with proof. Queries are widespread in the DeFi sphere and without them its existence is impossible. The problem is that
queries often only work within a single blockchain, but with IBC and ICQ you can solve this problem and send queries between different blockchains connected by IBC.

How this would work:

1. On the querying zone, the ICQ module collects query requests and makes them available to relayers;
2. Relayers go to the queried zones, find a "value" for each "key" and package them with cryptographic proofs;
3. Relayers bring the packaged results back to the ICQ module, which verifies them;
4. Specific smart-contracts get the verified results from the module;
5. They process the raw results into a neat data structure for the author of the query.

[![FW-l-VGXg-AECzbo.jpg](https://i.postimg.cc/85LZ36bL/FW-l-VGXg-AECzbo.jpg)](https://postimg.cc/DJyQ4mHz)

## Why Neutron makes sense ##

The main advantages of Neutron are security and interoperability. 
Neutron will allow you to create applications that run on Neutron, but they will also run on all blockchains that are connected to Neutron via IBC, while having the
same security as the Cosmos hub.

This will lead to significant development of DeFI in the Cosmos ecosystem, and will also make life easier for users, because they won't have to think about which
network they are on now Juno, Cosmos hub or Evmos. Neutron will allow you to use the services you want to use from wherever you are in Cosmos. And then get the
assets you want on whatever chain you want to get them on.

## Roadmap ##

Neutron mainnet is scheduled for launch in the first quarter of 2023, currently undergoing Baryon Testnet.

[![Fa-XEsn8a-MAAy-ZYx.jpg](https://i.postimg.cc/Jh5y27kG/Fa-XEsn8a-MAAy-ZYx.jpg)](https://postimg.cc/p9yX9HkH)



See also our episode with guests from Neutron, where they talk more about the project, validator and user incentives, and $NTRN token:

<iframe id="ytplayer" type="text/html" width="640" height="360" src="https://www.youtube.com/embed/umvecK_toi4" frameborder="0" allowfullscreen></iframe>

-----------------------------------------------------------------------------------------------------------------------------------------------------------

If you would like to support our mission in creating educational content and aligning the goals of different communities, please stake with us [here](https://www.citizencosmos.space/staking): 

- [EVMOS](https://wallet.keplr.app/chains/evmos?modal=validator&chain=evmos_9001-2&validator_address=evmosvaloper1mtwvpdd57gpkyejd566s24afr9zm5ryq8gwpvj) 
- [ATOM](https://wallet.keplr.app/chains/cosmos-hub?modal=validator&chain=cosmoshub-4&validator_address=cosmosvaloper1e859xaue4k2jzqw20cv6l7p3tmc378pc3k8g2u) 
- [BOOT](https://wallet.keplr.app/chains/bostrom?modal=validator&chain=bostrom&validator_address=bostromvaloper1f7nx65pmayfenpfwzwaamwas4ygmvalqj6dz5r)

Join our [community](https://discord.gg/kJaG3EucCX), to build a future where communication is decentralized. May the code be with you!


