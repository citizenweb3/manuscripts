+++
title = "Evmos explainer guide"
date = 2023-01-30

[taxonomies]
tags = ["evmos", "evm", "cosmos"]
+++

# Evmos explainer guide #

[![EVMOS-1.png](https://i.postimg.cc/J4bQkbky/EVMOS-1.png)](https://postimg.cc/qzvnf6Q0)

## What is Evmos? ##

Evmos is a scalable, high-throughput Proof-of-Stake blockchain that is fully compatible and interoperable with Ethereum. It's built using the Cosmos SDK  which runs on top of Tendermint Core consensus engine.  
Evmos allows developers to make any smart contracts in the native language of Ethereum understandable to the Cosmos with almost no changes to the program code. This allows developers to have all the desired features of Ethereum, while at the same time, benefit from Tendermint’s PoS implementation. Also, because it is built on top of the Cosmos SDK, it will be able to exchange value with the rest of the Cosmos Ecosystem through the Inter Blockchain Communication Protocol (IBC), which is Cosmos's novel solution to the issue of cross chain communication.

<!-- more -->

Evmos is currently the leading Ethereum Virtual Machine-based blockchain in the Cosmos ecosystem. The key difference in Evmos is that it is not a bridge, but a full-fledged EVM on Cosmos. For instance, blockchain DApp developers may use Ethereum’s default programming language, Solidity, to build Evmos DApps.

According to the Evmos team, the end goal of Evmos is to bring together the Cosmos and Ethereum community.

The team is led by Federico Kunze Küllmer, a full-time Cosmos contributor since 2017, having worked on Peggy (former Gravity Bridge), Cosmos SDK, and IBC, and Akash Khosla, who was previously a Software Engineer at Anchorage, a digital asset custodian and bank.  
The Evmos team has been the core development team behind the Ethermint codebase since April 2021.  
The original name Ethermint was changed to Evmos (EVM-on-Cosmos) due to legal delays (a legal entity with that name already existed).

[![pasted-image-0-1.png](https://i.postimg.cc/jSsTP4LC/pasted-image-0-1.png)](https://postimg.cc/Cz69VDCV)

## Evmos Tokenomics ##

EVMOS is the native token used by the Evmos blockchain. It has a maximum (and total) supply of 1 billion. As of the time of this writing (Jan. 17, 2023), the token’s circulating supply is 401 million EVMOS. There are three primary uses for the token — transaction fee payments, staking and governance.

Evmos had an initial supply of 200 million tokens at genesis. There has been no sale or premine.
- 50% was allocated to the airdrop (Rektdrop)
- 40% for the Strategic Fund
- 10% for the Community Pool.  

[![1-V12-En-O6-INv84-KBGu-O3l-VWA.webp](https://i.postimg.cc/65qL3DhQ/1-V12-En-O6-INv84-KBGu-O3l-VWA.webp)](https://postimg.cc/56cFKKTc)

The airdrop claimable as "rektdrop" was aimed at rewarding users that got “rekt” in Cosmos or Ethereum. So, Evmos is distributed based on activity on popular Ethereum or Cosmos dapps like #AAVE , #OLYMPUS, Uniswap, etc. This airdrop welcomes those in the Cosmos ecosystem as well as pulls in ETH users to the Cosmos ecosystem by giving them an airdrop based on their gas expenditure in ETH transactions which can be considerably high and users who were certain rug victims.

[![evmos-3.jpg](https://i.postimg.cc/Vsp5qp8v/evmos-3.jpg)](https://postimg.cc/LhkHRyhF)

Evmos is highly inflationary at the beginning, with over 300 million tokens being issued during the first year. Under the initial token model, the new tokens will be issued under an exponential decay schedule, where the inflation is decreased every year (365 daily epochs). The target will be to issue 1 billion Evmos tokens in 4 years.

[![1-m-S7-Eld-SPs-CVb-WPub-ALRKOw.webp](https://i.postimg.cc/7YS7fw2w/1-m-S7-Eld-SPs-CVb-WPub-ALRKOw.webp)](https://postimg.cc/hfPhYFs5)

Newly released tokens will be distributed in the following way, on a per-block basis:
- Staking Rewards: 40%
- Team Vesting: 25%
- Usage Incentives: 25%
- Community Pool: 10%

[![1-q9sv-Aoilo-FO4-Qx-HFa-EV6-DA.webp](https://i.postimg.cc/pLqmFTXb/1-q9sv-Aoilo-FO4-Qx-HFa-EV6-DA.webp)](https://postimg.cc/18VRxyqJ)

As of the time of this writing, the APR(annual percentage rate) is 110%.  
Сommunity may choose an alternative model of inflation after the 4 years, such as linear-inflationary or even deflationary.

## Evmos Software Upgrade v10.0 ##

Evmos has recently been updated to version 10.0, and many important updates have been made.  
One important innovation is the automatic asset conversion between the Cosmos and Ethereum ecosystems.  
When someone sends a token native to the Cosmos ecosystem to Evmos, it will automatically be converted to an Ethereum-compatible token so that it can be used immediately on Evmos and sent to Ethereum-compatible blockchains. The goal is to simplify the use of blockchains and the movement of assets between Cosmos and Ethereum. No longer will users need to convert their Cosmos assets into their respective EVM asset types and vice-versa. This will be done under the hood for users.

This also means that you will be able to transfer ERC20 tokens to other Cosmos chains with IBC.  
This innovation can be applied on the user facing side for bridging assets to Evmos, in addition to serving as a useful tool for developers to abstract away the complexity of incorporating liquidity from EVM and Cosmos chains within their dApps (e.g. one click to bridge and LP).

Other features of the update include additional support for the Ledger hardware cryptocurrency wallet and some bug fixes.
You can see the full list of updates [here](https://commonwealth.im/evmos/discussion/8501-evmos-software-upgrade-v10).

## Evmos Ecosystem ##

### List of current Projects running: ###

- [Evmos Explorer](https://evm.evmos.org/) - Official Evmos EVM Explorer.

- [Orbitmarket](https://www.orbitmarket.io/) - The first and largest NFT Marketplace in Evmos Ecosystem.

- [OrbitalApes](https://www.orbitalapes.com/) - NFT & P2E game.

- [EvmosDomains](https://evmos.domains/) - Evmos Domains is a decentralized name service for linking .evmos names to data like addresses.

- [DiffusionFinance](https://app.diffusion.fi/#/swap) - Diffusion is an Automated Market Maker (AMM) protocol and liquidity pool designed for efficient trading between crypto-assets. The trading activity on Diffusion captures fees as revenue for liquidity providers, resulting in a decentralized market and trading experience.

- [EvmoSwap](https://app.evmoswap.org/) - EvmoSwap is a decentralized exchange (DEX) on the Evmos.

- [EarnMos](https://earnmos.fi/) - First yield optimizer for Evmos and Cosmos Interchain Ecosystem.

- [CronusFinance](https://cronusfinance.xyz/) - Cronus is an AMM built on Evmos.

- [KinesisLabs](https://www.kinesislabs.co/) - Kinesis is the native stableswap of Evmos, providing users with the lowest slippage when swapping stablecoins.

### List of upcoming Projects: ###

- [SpaceFi](https://www.spacefi.io/) - SpaceFi is a cross-chain web3 platform on Evmos and zkSync, with DEX+NFT+Starter+Spacebase as initial product. Its ultimate vision is to connect Cosmos and Ethereum Layer2 ecosystem, exploring assets cross-chain and interoperability solutions.

- [SoulNetwork](https://www.thesoul.network/) - A cross-chain DID network in Cosmos and Ethereum / EVM ecosystem. Initially built on Evmos.

- TetraSwap by [Cronus Finance](https://cronusfinancexyz.com/) - Swap between bridged & native stables on Evmos, with low slippage.

- [BasinProtocol](https://twitter.com/basinprotocol) - Liquid Staking for Evmos.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

If you would like to support our mission in creating educational content and aligning the goals of different communities, please stake with us [here](https://www.citizencosmos.space/staking) 

- [EVMOS](https://wallet.keplr.app/chains/evmos?modal=validator&chain=evmos_9001-2&validator_address=evmosvaloper1mtwvpdd57gpkyejd566s24afr9zm5ryq8gwpvj) 
- [ATOM](https://wallet.keplr.app/chains/cosmos-hub?modal=validator&chain=cosmoshub-4&validator_address=cosmosvaloper1e859xaue4k2jzqw20cv6l7p3tmc378pc3k8g2u) 
- [BOOT](https://wallet.keplr.app/chains/bostrom?modal=validator&chain=bostrom&validator_address=bostromvaloper1f7nx65pmayfenpfwzwaamwas4ygmvalqj6dz5r)

Join our [community](https://discord.gg/kJaG3EucCX), to build a future where communication is decentralized. May the code be with you! 

This guide was created for [Citizen Cosmos](https://www.citizencosmos.space/) by [Magican](https://t.me/magican_n)
