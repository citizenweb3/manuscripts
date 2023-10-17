+++
title = "Neutron: Airdrop and Staking"
date = 2023-05-29

[taxonomies]
tags = ["neutron", "cosmos", "airdrop", "staking"]
+++

[![1-UDYe-Jo-DNI5-ALn-Uw3-Ij-ANOA.webp](https://i.postimg.cc/t46d5rMs/1-UDYe-Jo-DNI5-ALn-Uw3-Ij-ANOA.webp)](https://postimg.cc/gxY6cKdp)

## About Neutron ##
[Neutron](https://neutron.org/) is permissionless smart contract platform for Interchain DeFi built with Cosmos SDK & Tendermint. Neutron allows to deploy smart contracts to the market in a blaze. Smart contracts can query, transact and manage
accounts in remote zones directly from Neutron.

<!-- more -->

## Airdrop ##

The Neutron Token Airdrop for ATOM stakers is currently live, You can check Your eligibility and claim the Airdrop [here](https://launch.neutron.org/). You can find a full guide on how to do this
[here](https://launch.neutron.org/).

## Staking ##

As such, the concept of staking in the usual sense (PoS) in Neutron is not provided (reward for staking in Neutron is not provided), but with the help of locked NTRN we can get the voting power and participate
in the governance of the Neutron DAO.

Neutron does not use standard Cosmos SDK governance module. Neutron governance is based on [DAO DAO](https://daodao.zone/) contracts. Neutron DAO core contract interacts with the Voting Power Registry contract that keeps
track of multiple Voting Vaults:
1. Real vaults - is the Neutron Vault, which allows its users to directly bond and unbond NTRN tokens.
2. Virtual vaults - not directly storing user funds in the vault:
- Credits Vault - airdropped NTRN tokens in vesting.
- Lockdrop Vault - LP tokens from axlrUSDC/NTRN and ATOM/NTRN pools.
- LP Vesting Vault - LP tokens from axlrUSDC/NTRN and ATOM/NTRN pools that are being vested during TGE.
- Investors Vault - NTRN tokens that are being vested according to investors agreements.
The overall voting power of a given address is a sum of the voting powers that the address has in real and virtual vaults, 1 NTRN = 1 vote. Real value will always hold voting rights whereas the virtual valuts can be added or removed as per the governance.

Currently governance is not live on Neutron.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

If you would like to support our mission in creating educational content and aligning the goals of different communities, please stake with us [here](https://www.citizencosmos.space/staking): 

- [EVMOS](https://wallet.keplr.app/chains/evmos?modal=validator&chain=evmos_9001-2&validator_address=evmosvaloper1mtwvpdd57gpkyejd566s24afr9zm5ryq8gwpvj) 
- [ATOM](https://wallet.keplr.app/chains/cosmos-hub?modal=validator&chain=cosmoshub-4&validator_address=cosmosvaloper1e859xaue4k2jzqw20cv6l7p3tmc378pc3k8g2u) 
- [BOOT](https://wallet.keplr.app/chains/bostrom?modal=validator&chain=bostrom&validator_address=bostromvaloper1f7nx65pmayfenpfwzwaamwas4ygmvalqj6dz5r)
- [FLIX](https://wallet.keplr.app/chains/omniflix?modal=validator&chain=omniflixhub-1&validator_address=omniflixvaloper1wnpak7sfawsfv9c8vqe7naxfa4g99lv7djfn8n)

Join our [community](https://discord.gg/kJaG3EucCX), to build a future where communication is decentralized. May the code be with you!

