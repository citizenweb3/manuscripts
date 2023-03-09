+++
title = "The stablecoins debate FAQ"
date = 2023-02-11

[taxonomies]
tags = ["stablecoins", "cosmos", "defi", "debate"]
+++

**[Interchain debates:Knights of the IBC, Stablecoins.](https://www.youtube.com/watch?v=nf9Ty8JoTYc)**

<iframe id="ytplayer" type="text/html" width="640" height="360" src="https://www.youtube.com/embed/nf9Ty8JoTYc" frameborder="0" allowfullscreen></iframe>

Stablecoins - a cryptocurrency with a fixed and stable rate, pegged to the price of fiat currency and with different collateral and reserves
(whether cryptocurrency or fiat money). It is a popular and liquid medium as it is a convenient way to trade, store and protect your portfolio from volatility.
After the collapse of UST,  there was a debate about what a stablecoin really should be. We spoke with ***[Youssef Amrani](https://twitter.com/youssef_amrani)***
representing $IST, ***[Chad Barraford](https://twitter.com/CBarraford)*** representing Thorchain, ***[Siddarth Patil](https://twitter.com/SidP95)*** representing $CMST,
***[Carter Woetzel](https://twitter.com/l_woetzel)*** representing $SILK, ***[Dove](https://twitter.com/deadrightdove)*** representing $USK, about what stablecoins are for,
the different designs of stablecoins, what their purpose is, and the dangers of centralization.

[![Screenshot-592.png](https://i.postimg.cc/nVBTJwFm/Screenshot-592.png)](https://postimg.cc/dDQGR6TQ)

<!-- more -->

***Q: What are stablecoins and what are they for?***

According to ***Youseff***, stablecoin is a cryptocurrency that serves as a stable reserve asset, like the dollar, as well as a medium of exchange for daily transactions.
It can also be a means to store value in the short term (because in the long term, stablcoins are often subject to inflation as well, though not as volatile as other
cryptocurrencies) and a bridge between cryptocurrency and fiat currencies.
***Dove*** added that capital efficiency is really key, and that trading in a stablecoin pair obviously carries much less risk compared to pairs with two volatile assets.  

According to ***Chad***, it's also a way to change your risk profile.
If you expect the markets to go down, you can sell your asset(bitcoin or whatever) and then buy again at the bottom.
What ***Carter*** is saying is that we need decentralized stablecoins, not just stablecoins, because stablecoin with no decentralization is not much different than a regular
real world dollar. Unlike decentralized stablcoins, which have the advantage of open source, transparency, and no censorship.

***Q: Is there a risk of repeating the failures of previous algo-stablecoins and how to avoid repeating such scenarios?***

***Youseff*** agreed that after the algo-stablecoin incidents (mainly the Terra crash and their algo-stablecoin UST) there may be some concern.
But that doesn't mean that experiments should stop, because such things take time to build something that works perfectly.
Most likely, the design of the UST stablecoin was not entirely successful, and the new algo stablecoins can learn from that experience.
In the opinion of ***Chad***, there have been 4 or 5 different stablecoins in the last few years, and they have all failed for various reasons.
All of the algo-stablecoins have a different structure, a different design, and when a particular stablecoin fails, it informs the rest of the industry about what
didn't work and why it didn't work. This gives developers of new stablecoins a chance to look at the failed experience and not make the same mistakes, but to move on.
And the designs of subsequent stablecoins will already protect against such scenarios.
But if it didn't work 5 times before, that doesn't mean that it won't work the 6th time. So you shouldn't discard algo-stablecoins just because Terra or someone
else had a problem before.

***Q: What's the special design of your stablecoins that you represent? And why do you think it should and will work?***

In our particular project, the stablecoin is in its own chain - said ***Chad***. If you sell a coin that's tied to an asset on the secondary market at a different price
than the primary market, that's not a problem. But people get scared when they look at coinmarketcap, for example, and they see a different price than the primary
market, they think it's depeg, but it's not. For example, when I buy an Apple computer, and then sell it for $400 cheaper, it doesn't mean that the Apple computer is
depegged. It's just that I'm selling the asset on the secondary market at a different price than the primary market. So there was often a problem in the secondary
market. When the secondary market could squeeze the primary market. The tail was wagging the dog. So the first thing that Thorchain makes is the absence of secondary
markets, that is, you can only buy and sell in our own Thorchain. In our case, we have no external dependencies, and nothing in Thorchain depends on anything.
We design the stablecoin in a way that eliminates price manipulation to make it economically unprofitable. So that if someone wanted to profit from Thorchain,
they would lose more money than they would make. So we have USDC, we have USDT, we have DAI, we have FRAX, maybe others will be added, then the network takes their
aggregate, Takes the median, not the average, but the median of these things to understand the price of RUNE in dollars. So to make a depeg, you have to manipulate
the price of 51% of the pools and if you try to do that, the trading volume, the commissions will go up very high, the fees go up like crazy. That makes it
impractical to manipulate these pools.

According to ***Siddarath***, when they first announced their intention to create their own stablecoin, they looked at various models and realized that the most
reliable model at the time and which had stood the test of time against volatility was the overcollateralized model that MakerDAO created for DAI. It is important
for them not to try to stray too far from what has already proven to be effective. So broadly because they have a fully functioning dex, they have a fully
functioning money market on their chain as well. They want to unlock for users different types of leverage strategies that they could create themselves. So one
example is you start with stAtom, you collateralize, you mint the stablecoin, with the stablecoin you buy more ATOM, which you turn into stAtom and so on. Similarly,
you could do that with, let's say, you know, providing liquidity to an stAtom-Atom pool on the DEX where you have the LP token. When it comes to $IST, we're not
trying to reinvent the wheel, and we're also inspired by DAI Stablecoin because it just works. At IST, we are also aiming to have use cases from day one. In our
case, we're doing something that hasn't launched yet, but will very soon, where all payments will be made on the Agoric blockchain. So we will have a lot of
applications built on Agoric that will use IST to pay for gas.

As for $SILK, the key difference is that Silk is private and tied to a basket of world currencies and commodities, says ***Carter***.

We have a queue based approach and then people can bid on those liquidations at the asset values, 
if that capital falls bellow the threshold then the regular liquidate is come in. We've seen it in the most extreme scenario ever. And it's interesting because you
still get people really wanting to buy that collateral. Obviously, Terra was a pretty extreme example. It's not that often that a project like that just unwinds to
zero basically. I think it's always good to kind of let you know have a backstop of some kind. And in this case it can just these like heavy hitter liquidators that
come in. I don't think I'm saying anything new, but I mean the DAI model has been proven and of course you always have to be on your toes - ***Dove*** said.

***Q: And yet, why do we need stablecoins, since no perfectly stablecoin has ever existed in the world?***

When we say stablecoin, we mean a relatively stable coin. That doesn't mean it can't go up or down in value. Nothing can be 100% stable, as far as I can tell.
It's a question of how volatile the asset is, high volatility or low volatility, says ***Chad***.

***Youseff*** gave the example of fiat currency, where the transfer fees reach 3% or even 10% and this is a very large amount. And stablecoins in this direction can be an
interesting option to use.

I think I've said this before, but it makes a lot of sense. I agree with Youseff, because when you live in South America, in addition to the 10% commission, you also
get inflation. So like I said, even in the Kujira ecosystem it's an important thing. Why do we need stablecoin? Well, we think it's a more efficient way to use
capital, but more importantly, it allows people to transact with something that they're familiar with and then move through an ecosystem like Kujira or, you know,
like Shade, like Comdex, like Thorchain, and be able to use their money effectively, even if it's pegged to the dollar, it's important for people to have something
with which they can say, "Okay, here's my paycheck, it's worth it". I think having a stable stable fin ecosystem is a big deal.  And, as we've all said, there will be
many iterations of all of our stablecoins. And you know, things like that get a little safer over time, so I think the Terra case was an exception and a lesson - ***Dove*** says.

So, you have a community gathered around a token, but if you can also have a secondary token on top of that token, which is a stable currency, then you can close the
loop. So you'll have a community culture, you'll have the token itself that you can make money from because you believe in the community, you believe in the project.
And you also have a stable currency for transactions between the two. And, on top of that, you can do it locally. We can imagine a world where you have tens of
thousands of stablecoins, each one meeting a specific need in the local community, say 10,000 or 100,000 people. And then you can connect them with more global
stablecoins, and all these stablecoins coexist peacefully and are a fulcrum for the community. So even in that respect, I think stablecoins can have an interesting
purpose - added ***Youseff***.

***At the end, we asked for tips that relate to stablecoins:***

***Dove's*** advice is to double check the project. You can find out what the project is set up for, how the oracles work, design issues, and so on. You don't need to know
too much about technology, just ask "how it should work and how it will protect us".

***Chad*** said he wouldn't invest much money in any new stablecoins. In his opinion, the credibility of stablecoins increases over time. So yes, don't invest your savings
in stablecoins, probably anytime soon. And the older the coin, the more trustworthy it should be. I would say don't get too involved in any stablecoins, including my own too
early on.

***Carter*** also agreed that this is a very young industry and mechanisms will get better and more perfect over time. And it is not worth investing your money in
stablecoins at such an early stage. Even so, ask questions about the mechanics, learn as much as you can, and realize that you are still an early innovator.
Enjoy this time in history.

***Siddarath*** also agreed with Dove. And he added that we need to ask questions and dig deeper.  And if you can't find answers to your questions, it's probably done on
purpose.

I think everything that has been said has been pretty well said by people here, just be careful. The type of collateral backed by stablecoin, as well as the
minting limits, is an important marker - says ***Youseff***.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

If you would like to support our mission in creating educational content and aligning the goals of different communities, please stake with us [here](https://www.citizencosmos.space/staking): 

- [EVMOS](https://wallet.keplr.app/chains/evmos?modal=validator&chain=evmos_9001-2&validator_address=evmosvaloper1mtwvpdd57gpkyejd566s24afr9zm5ryq8gwpvj) 
- [ATOM](https://wallet.keplr.app/chains/cosmos-hub?modal=validator&chain=cosmoshub-4&validator_address=cosmosvaloper1e859xaue4k2jzqw20cv6l7p3tmc378pc3k8g2u) 
- [BOOT](https://wallet.keplr.app/chains/bostrom?modal=validator&chain=bostrom&validator_address=bostromvaloper1f7nx65pmayfenpfwzwaamwas4ygmvalqj6dz5r)

Join our [community](https://discord.gg/kJaG3EucCX), to build a future where communication is decentralized. May the code be with you! 



