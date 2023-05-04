+++
title = "Episode #93 Benjamin. Transcript"
date = 2023-05-01

[taxonomies]
tags = ["podcast", "transcript"]
+++

Episode link:  
https://www.citizencosmos.space/benjamin

Episode name:  
Benjamin, Adoption, Censorship resistance & Composability.

In this #citizencosmos podcast episode, Benjamin, co-founder of ArweaveNews, permacastapp, and [decent.land](https://www.decent.land/), discusses various web 3 and decentralization topics. They talk about creating web 3 social media with current tools and debate the readiness of web 3 for everyone. The conversation also covers decentralized identities, merging account identities, friction in using web 3 tools, and the possibility of decentralizing everything and everyone. They further debate how to incentivize users to move to web 3 and why users should use Areweave instead of IPFS.

--------------------------------------------------------------------------------------------------------

Citizen Cosmos  
Good space time yall in this episode of The Citizen Cosmos podcast, I'm joined by Benjamin, a.k.a. xylophonezy. He's the founder of Decent Land a Tool for Building Decentralized Communities Arweave news and Permacast podcast Storage Protocol. Along with Benjamin, we discussed storage development Dao tooling, decentralized frontend, the state of web2 and web3, and the adoption of the latter. We also spoke about interoperability and whether or not decentralization should be the end goal of everything.

Benjamin  
I kind of felt uncomfortable about the fact that we were like all about decentralization, price is almost like a crutch for, you know, a project that might just be an EVM fork that can't offer anything else. Having your DAO discussions on Web2 puts the transparency at risk. The incentives in Web2 are anti-user Social media is pretty much controlled by five or so companies, all of which use closed source non interoperable protocols.

<!-- more -->

Citizen Cosmos  
Before we rocket off into today's podcast. Here is a round up of the latest news from the sponsor of this episode, Cyber. Cyber Congress Dao has been primarily working on improving the Bostrom hub. Its work includes testing of the contracts, new UI features, verification, tools for online governance and polishing the Bostrom Dex protection new web front and bring in indexing of chain swaps to try Bostrom head now to over Cyb.ai.


Citizen Cosmos  
Hi everyone. Welcome to a new episode of the Citizen Cosmos podcast. Today I have Benjamin with me, the founder of Areweave News and Decent land. I hope I pronounce them correctly. Benjamin Hi. Welcome to the show.


Benjamin  
Did I? Yeah, you did. Yeah, absolutely fine. Most people call it descent land, I don't know why.


Citizen Cosmos  
I almost said Decentraland, of course, but then I was like, Nah, nah. Well,


Benjamin  
Yeah, that’s another one.You nailed it.


Citizen Cosmos  
Benjamin, you know, let's get the first thing out the way. I mean, I mean, I did say produce you as the founder of Areweave news and Decent land, but please, could you elaborate a little bit on that? What do you do? What are you busy on with working on anything else you want to add and make Like a cool introduction for me and for all of the listeners, please, if you can.


Benjamin  
The backstory is that I kind of came into the Areweave ecosystem off of a job where I was working in like marketing and and development like so a 5050 split between the two and I sort of had met the founder of Areweave like two years before I left my day job and found Areweave news and he kind of said, Well, if you want to leave your day job, then there is an opportunity to come in like co-founder Areweave News, which somebody has already like set set a bit upon.


Benjamin  
So I was one of the first journalists like previous to that in my previous jobs to cover Areweave like before we had done a launch before even main net launch. And I guess Sam remembered Sam being the founder of Areweave remembered that that I’d like, you know, been involved for quite a while. And so that was like my first professional step, I guess, into the Areweave ecosystem, kind of setting up a new source which would do longform articles on on everything that had been happening in the ecosystem, started then looking at like how we can decentralize this because honestly, it was just a WordPress site that we found.


Benjamin  
We kind of felt uncomfortable about the fact that we were like all about decentralization, but we were actually running this off of like a, you know, super centralized, vulnerable site and we realized that, you know, there are already other Areweave based CMS is like WordPress competitors like Mirror, but so we would go after podcasting instead. So we actually decided let's like make podcasting on Areweave sort of spun out what we had built with Areweave news, partially at least like some of the teams like forked and went off to build permacast which was, you know, just a way to get your podcast onto Areweave then feed it off to


Benjamin  
any distribution source that you might need to like via an RSS feed, like a really pretty simple offering. During that time I was working with Darwyn, his who at the time was going through like the initial proof of concept for decent land. He originally needed somebody to that wasn't afraid of getting on the phone with VCs to raise seed money.


Benjamin  
And so I, I kind of came on board as like the person who will do the talking for decent land. But in all of the talking and in all of the thinking and, you know, telling VC's this and that angle, I realized, you know, I really don’t understand the product and was able to like, influence its vision and joined the CEO shortly after that, you know, found myself being able to hand Areweave news off to this like core team that we'd built over the previous like 18 months, which is now all running smoothly.


Benjamin  
Similar with Permacast like that has its own dedicated team and now I would say 80% of my time is focused on building out decent land, which started from a vision of how can we do decentralized social media pivoted to like, Oh, wait a minute, like decentralized social media needs, so much infrastructure needs, like DID’s it needs, you know, cross-chain stuff to verify your identity regardless of like which chain the dapp is on and all that.


Benjamin  
All of these kinds of pieces came. And we eventually, where we are now, sort of made this pivot to where we can be infrastructure, social infrastructure for dapps, that want social elements in them that could be like a DAO tooling thing, or it could be like, you know, an NFT marketplace or whatever like that. Like from the beginning I would say my, my focus has always been and before I even knew about Web3, like I was always upset with how centralized and walled.. got walled off.


Benjamin  
You know, social media was and gravitated towards like, why is this not just like an open protocol rather than, you know, permissioned thing? I didn't know that Web3 social was kind of where I was going to end up. But like looking back, it was clear that that that was where it was all like leading to.


Citizen Cosmos  
You mentioned a day job before. Before I go into all the other questions, what was that day job? I'm curious.


Benjamin  
I had a couple of roles in in early stage startups. Like I came my first role, like straight out of university. I was I worked up to at least head of marketing at a SAS company software as a service in Silicon Valley. That was like pure marketing stuff. Then I my next job was another Silicon Valley SAS company, but this time I kind of bargained in the interview that I didn't want to just be doing pure marketing because I'm I'm, I actually was really just interested in writing code and doing product side stuff.


Benjamin  
And so they said, well, you know, we know what you're good at, so let's like take you on at least for the marketing with possibility to, to work on, you know, development stuff that supports the marketing. Over time I kind of became the head of growth analytics implementer slash like you know, customer implementation engineer for this is a small company.


Benjamin  
So we, we kind of all they all did a lot of different things. But generally my role, my most recent role before I left to join the Areweave ecosystem was a growth engineer. So I would be coming up with ways that we could get the product adopted by users and then running like code experiments like as to change the front end in this way or like, do this and talk to the users like this and etc. in a way that where if I were to just have marketing skills, I wouldn't actually be able to carry those things through to the final stages.


Benjamin  
I was able to like, you know, come up with the idea and implement it on the front end and measure the analytics that I'd implemented as well. So that was the kind of the role that I was in that sort of workflow.


Citizen Cosmos  
Before you, you started to do. I mean, for web projects, have you done any community management work? The reason I ask is that I noticed that a lot of the times, the journey for a lot of CEOs in Web3, especially when it comes to social media, social networking and and this is my journey was my journey as well is starting with like community management and going to CEOs and it looks like it works really well as well in a lot of cases.


Citizen Cosmos  
That's why I asked.


Benjamin  
Yeah I would actually was terrified interacting with end users. I always kept myself at a distance with it and to be honest, in a B2B SAS role, all I really had to do was it was kind of abstracted. You would interact with companies and whoever represents them. It wasn't very much a community thing and actually it was a system shock coming in to Web3 because it's entirely community.


Benjamin  
It's like everything's B2C, even if it's B2B, that that was really different and it made me like completely, like rethink as to as to how things work, what I was used to, which was, you know, getting adoption via maybe like SEO or like search marketing. These things are all like completely out the window. It's like, what discord is this person in and what like thing are they look into?


Benjamin  
Like how are they looking to farm this protocol? Right. Is like totally different.


Citizen Cosmos  
It's really like interesting you talk about it because, I mean, I think those questions have changed like over the space of the last like ten years. But have they remained the same in terms of the community and the social aspect of field, you know, of of of blockchain? I mean, blockchain is communication, right? So, I mean, it's not a surprise that it's all built around the communities.


Citizen Cosmos  
But, but absolutely, like I also noticed that and I think that it's really cool though that you spoke about journalism and and everything like that, because I think that's what this industry's missing a lot is like really a place where I'm I'm not against all like, you know, content creators kind of thing. But there is a specific field in blockchain and crypto industry of content creators that seem to go kind of one way and talk about prices and stuff like that.


Citizen Cosmos  
Instead of talking about journalism.


Benjamin  
Definitely. I was completely like, I just had an intuition that when we started out, we knew that that is not what it should be about, because when you've got more to talk about than price, as in like, look at this amazing piece of infrastructure that does things that has never been able to be done before. You don't really need to talk about price.


Benjamin  
Price is almost like a crutch for, you know, a project that might just be an EVM fork that can't offer anything else.


Citizen Cosmos  
Absolutely. Absolutely. No, I absolutely agree. Let me go a little bit. I mean, I do have questions, but the thing is, in your intro, you said some kind of things which are noted down. And I was like, but I would like to talk about those, not about the questions I have damn I was like, Those are the cool things.


Citizen Cosmos  
I'm really curious about them. You mentioned a decentralized social media and this is to my ears are a very touchy feely subject that I would love to ask you some questions about because I have some experience with that. I have had the personal experience in 2016 with launching a fork of Steemit, the first, the first fork of steemit the first and the only official fork of steemit because then they open source them.


Citizen Cosmos  
And I mean the code was always open source, but the block, the initial the the genesis block wasn't MIT sorry not MIT so it wasn't open license. And then when we did, the fork it wasn't open and after we did the forum completely open. But anyways, the point, the point was to question to you and the question to you is how do you find the journey of creating the centralized social media?


Citizen Cosmos  
Because from what I have experienced and from what I have seen over the last like, let's say ten, 11 years, that for now I internally don't have a feeling that it's possible to create with the infrastructure and the tools that are in place today. What do you think?


Benjamin  
MM Yeah, there's this, there's loads of different points that I mean with the infrastructure and tools part. So you see there being issues even for like lens, which is a big one. Right. They exist on Polygon, even with Polygon being as fast and cheap as it is, it still needs like this centralized relay piece in order to make it so that you don't have to sign a transaction every single time that you post something or like something more like, you know, do a micro interaction that would, you know, need blockchain confirmation.


Benjamin  
So from that perspective, like a lot of the existing models of Web three social are just like more of a difficult thing to do do than than to use Twitter. I think people are very conditioned to how simple their social media apps are. And so if you're trying to add something into it, which could be any level of friction and then try to push it off to a mass market, then it becomes really just too much friction to bear to switch when there is something is good out there already as Twitter.


Benjamin  
And so that's that's the reason why we both took an why we took an infrastructure first approach and also why we took a DAO specific approach. And so the way the way that I'm seeing a lot of Daos operating right now is that they do their communication and collaboration in Web two and their actual proposals and all of that sort of stuff in Web3.


Benjamin  
And I'm not going to name ecosystem names, but there are some where having your DAO discussions on Web two puts the transparency at risk. So it's actually possible for moderators to hide threads and comments. So it's possible for the trail of history to get lost and and for it to, you know just kind of become a black box when really it should have all been happening on chain in the first place.


Benjamin  
And so what Areweave enables is you're able to store a huge amount of data very cheaply on chain forever. That's perfect for DAO tooling. And so there is a tool on NIA called Asteroidal, which is a very typical barebones, robust Dao tooling thing, saying proposals, reaching quorum, doing token votes, all of that kind of thing so it doesn't have a conversation feature or any kind of user identity pieces to it.


Benjamin  
It's like, well, it addresses votes, did it execute, did it not? And so what we're trying to build a decent land is something which could hook into that, or it could hook into any other kind of down tooling piece like that, which is going to be able to provide a on chain decentralized discussion feature with identities with all kinds of different features which could tap into, you know, just the basic mechanism of a proposal to add more, I guess, reliability to it because it's on chain also to add more color to it because you can, you can discuss, etc..


Benjamin  
So I think that that is the niche in social that we're attacking. It's not trying to make a new Twitter, it's more trying to make infrastructure which existing dapps that need that on chain feature for their social can plug in and take advantage of.


Citizen Cosmos  
Absolutely because like I have been also part of a of a team and I'm still as ... today as it is in Cosmos, as a validator and as an ecosystem developer. We still help that team, another team out there not building social tools or social infrastructure, and I don't want to like shill that at all. But the idea was that they have something similar to Twitter already kind of working.


Citizen Cosmos  
But in Web3. And that thing is not really used by people because people are terrified. I mean, it's like it's really extreme as well. It's like kind of the thing you have to use with a ledger. It's super extreme, like you have to tweet with a ledger. So like, it's cool, but it's extreme and obviously people don't go that way.


Citizen Cosmos  
So I absolutely understand what what what you're getting at there. I have a question for you as to before we go in a little bit deeper into all of the discussion, what is your opinion on I mean, if we were to abstract right now from from the state of Web3, right. I mean, you already already kind of been like talking about it.


Citizen Cosmos  
What is your opinion on the current state of the whole social infrastructure and media? I mean, obviously this is why we're here and obviously you're not happy with it, but if you can elaborate on what you really think about what's happening in the Web two world, I mean, and what's what's your opinion on all of that big, big, big subject?


Benjamin  
Yeah, I'd say, you know, just right now, social media is pretty much controlled by five or so companies, all of which use closed source non interoperable protocols and make a living off of locking people in and hiding information away. It's completely the antithesis of what the Internet was supposed to be. Even, you know, the original, as clunky as it is, like protocols that powered emailing at least talked to each other, at least could have data retrieved from from different, you know, user interfaces or whatever.


Benjamin  
Now even in the last few years, it's got worse. You know, Twitter has shut down API access, which means you can't get third party clients. I don't know whether Facebook ever had anything like that, and neither neither did the rest. I mean, Instagram has always been very locked down from the start. It's that business model, really medium that went haywire as well, prioritizing Paywalled content, making it so you can only read a few free articles a month, all of this kind of thing.


Benjamin  
They're realizing that if you don't want ads, which nobody wants, then you need to start locking things down, which can be a really great revenue model for some creators. but I don't think that it should apply to the whole of the Internet. What I was really interested in and didn't realize that I was kind of having web3 tendencies at this point was Mastodon came back in, I think around 2017 or something.


Benjamin  
I discovered it and I thought, okay, this is this is actually really amazing because it's built on the activity pub protocol, which is like this is the standard. It's a it's an app app agnostic standard. Instead of being interoperable with itself, you can create all kinds of different apps on it. So there was like Mastodon, and then there's like Ploroma, I think, which is like it's a different app with different everything, but you can still like pull Mastodon posts into it and you can vice versa.


Benjamin  
You can have one identity that's consistent across both it just from the ground up. It's a much more scalable and sane way of doing things. Companies want to make incompatible standards just because it benefits them, because it locks you on the platform. And so that's kind of my my take on on the whole of the Internet almost nowadays, the incentives in Web 2 are anti user and that they're making it very they're making it very difficult on purpose to to to build things which users might want.


Benjamin  
You know whether they want to expand, whether they want to filter the thing, make a different UI for it, even something as simple as literally making a Twitter that has a different UI is like made deliberately difficult because then that means that you could hide ads on the platform. Well then that means that you could change the algorithm in a way that might not be favorable to Twitter, HQ, etc. And you just, you know, you get get it get lost in that.


Benjamin  
And the apps themselves are dictators almost.


Citizen Cosmos  
And I think end of the day, like the problem is for the content creators who are like, like myself, for example, who are curious, not curious, but because I'm not curious in Web3, I work in Web3 and for many years, but you know, for me what I realized that I still have to use like 85 to 90% of Web two tooling because either I'm sacrificing because this is what we are talking about.


Citizen Cosmos  
Yeah, Web two is fucked. In fact, two two completely fucked. But today I have no idea how to get my message across to my target audience without using web two tools. Like it's just literally impossible in my opinion. And I've tried for years, you know, and I've put I've been put in some of the citizens of Citizen Cosmos on IPFS and retrievable and IPFS for a while.


Citizen Cosmos  
Then I stopped and, you know, and then I use like different tools here and there. And, and I've tried and I've tried and I've tried and I've tried. But what I came to realize is that end of the day, if you today are podcast, then you're not using, you know, all your aggregators, you're not using, you know, YouTube for God's sake, I mean, or something crazy, like even even stupid, like Instagram, which I have never had Instagram in my life as a person.


Citizen Cosmos  
But then I realized that I have to ask my marketing team or the person who's helping with marketing to create it. It was like, Whoa, that's a shot in the head because you're really like, you sell yourself. You feel uncomfortable because you're kind of like, Hey, I'm kind of talking about this. But then, I don't know, like, what do you think about it?


Citizen Cosmos  
Do you think it's a appropriate for projects that that try to like, let's use that scary word shilling to shill web, two use web tools? Or do you think that we should all move to Web three tomorrow? You know fuck how difficult those those products are. You know, what's what's your opinion there?


Benjamin  
Yeah, well, my opinion is, unfortunately, that's why the audience are it's probably where the general audience is going to be, because it's just where you expect the information to find. Like you you expect to find information on Twitter, therefore you post it. They're expecting other people will find it there I get my podcasts on Spotify. But that's also different because I don't really know whether it's podcast hosted.


Benjamin  
They could actually be hosted on Permacast They they could. They could indeed be secretly Web three RSS feed. are one of the last bastions of decentralization that the Internet has, everything else has been made proprietary and locked down. But but yes, I think podcasting is like it's still relatively decentralized. You know, you can you can get your content wherever.


Benjamin  
And so for audio, I think that the state of things is pretty good for video. I mean, there is peertube, there is Odyssey, there are these kind of very niche self-hosted or decentralized services. But really the killer is do they integrate with Web two? Do they integrate with where my audience already knows right now? I don't think that there are many people in the world, if any, where the majority of their audience knows them on Web three only.


Benjamin  
And that's really nothing like that is going to happen for the next decade or something. When you get your killer apps where people really can get more value, whether it's monetary or whether it's attention based value off of posting on Web three purely than on Web two. But there are lots of stuff where it's like this, you know, blends Twitter bridge.


Benjamin  
We do imports on Permacast so you can import all of your existing RSS feed stuff onto Palmer Cast and then switch the RSS feed URL over, So it's using something decentralized, but then it's delivered through all these different web to clients and the web to clients for now are a must have. It's just too ingrained right now.


Benjamin  
Like until super mass adoption end user focused things come through, then that's just the reality, I think. But it doesn't mean we can't use better infrastructure to actually hold the stuff.


Citizen Cosmos  
This is, this is actually like a good point about infrastructure. And you mentioned before or in my opinion, a crucial part of the infrastructure, but I seem to have a different opinion from what other people have to have. And what I wanted to ask you about is DID’s decentralized identities. Right. And I have had numerous guests on and all the guests that I have that talk about decentralized identities.


Citizen Cosmos  
I like to ask one question and hence I would like to ask you as well, do you think that considering we're talking right now about decentralization of infrastructure a little bit, right. And we're touching on such big things, do you think that a pair of private public key could be more than enough? You have an identity and you don't really need more than that.


Citizen Cosmos  
You have a private key and a public key. We have cryptography. They match fantastic. We don't need anything else. Why? Or rather is. Let me ask you the question, why do we need anything beyond that? Why is there a need for a lot of infrastructure to create a bigger identity than just the private and public?


Benjamin  
Key Yeah, it's a great question because like for one, you've got no lack of metadata in a private public keeper, which means no universal way for a Dapp to know who you actually are. They may be know, you're wallet address, which is fine, but they maybe don't know your username, your bio, etc.. And then another thing is that private public key is, well, I imagine from the way that you're describing it, locked to one chain only we right now, at least that might be this might be funny point to make in ten years time when when things are a bit more chain agnostic.


Benjamin  
Right now we split our web three lives across multiple different chains. I have history and assets and identity on a whole ton of different chains. I've got my Areweave dot ar name, I've got my dot eth name, I've got I've got NFT Holdings on near my dot near name. All of these things are scattered all over the place. And if I want to, you know, use my DID even just in net in any kind of sense of the word on one of those chains, it doesn't reference my full existence on other chains.


Benjamin  
And that that's just a fundamental flaw. And also like an actual technical flaw, if if I were to want to do token voting with my eth crypto punk on near or if I were to want to join a guild that requires a certain amount of tokens and the guild, you know, Dapp was hosted on a chain that doesn't even know what my private public key pair means on another app.


Benjamin  
Right all in non interoperable again. And so I think these I've got to just a general problem with things that are not like built to be interoperable with other things like you know iPhone chargers and like that That's the stupid simple example but it's almost like what what a lot of things are and well, web3 protocols are built to be composable or at least they very much should be.


Benjamin  
You still got the issue of what chain is it on? Okay, it's on this chain. Well, then it's not composable with most with 90% of the world of the web three world that would be my thesis of of why it's not enough to have just that you can have a protocol on top of that. So ark protocol, which is a decent land identity attestation protocol is a way to take your Areweave private public


Benjamin  
Key pair just your Areweave address, and use that as the master key for all of your other things as well. So attached to my Areweave address on my near address, my Ethereum address, my address on evmos, and as such, all of my asset holdings are able to be verified back to my key on an account which actually would not be able to otherwise talk to those chains.


Benjamin  
So it is enough, but it does need something to resolve those, you know, that matter data. So so that can be that it can be broadcast between apps which might not otherwise be interoperable. Otherwise we kind of end up with silos everywhere again. And the reason why I said this is funny is, you know, in the in the late nineties there was like wars over which database technology things used like do you use like post-crash, do you use microalgae Cassandra or whatever it may be that is going to be as like nerdy as blockchain was.


Benjamin  
All right. Now, like, does it, does it matter? Like what base layer this data lives on? It might not in the future or it really might, but it depends on who wins.


Citizen Cosmos  
I think we will see a lot more things. We don't expect when it comes to database wars and to, you know, database decisions. So to call them, I think we still have something to see that we haven't. But to go back to you to play a little bit devil's advocate, you said, you know, the problem with public and private keeper is technically not having metadata.


Citizen Cosmos  
And, you know, like let's say I have one identity account on the Ethereum and then another one on I don't know, on Monero. They're not the same now, the question I have to you is I mean, let's go back to the iPhone Chargers and okay, don't get me started on Iphone Chargers. I personally prefer Android, but I do have one iOS device and it's really annoying because that iOS device has a separate charger.


Citizen Cosmos  
And if I don't have the charger, then I can charge this and when I forget it, it's a pain in the ass. But but that iOS device is still a separate device that has its own existence and has its own kind of like digital soul, so to speak. And what I'm trying just to be devil's advocate, what I'm trying to say here is that like, okay, so we have all those identities on all it's like hallucinations right?


Citizen Cosmos  
That happen in my head. Is it real or not? Well, my brain says it's real. It says it's happened. And, well, lately, like if you look at like all the psychological studies of DSM five, you will see that it is now not considered unreal. It's considered real. Now, those things, because, hey, they happened, the person experienced them. So being devil's advocate, my question is, well, all those separate silos and all those separate accounts and all those separate chains, well, they are real aren’t they


Citizen Cosmos  
Even if they're run by the same person, they have an identity, they do something. Why cannot they be considered real? Why do they have to be combined into one account? Why does it have to be one identity that says, those are all my accounts? Why cannot those accounts exist as separate organisms?


Benjamin  
Mm hmm. No, they for sure can. And in a way where I have four different transfer accounts in a in a way where I would want that to be the case, even that totally makes sense. But in a case where you have a niche chain, like here is already a concrete example as to as to why this maybe doesn't need to go as philosophical


Benjamin  
as that because it already has technical need to exist? So an example is there is a nifty collection on Aurora, which is a EVM. I guess it's I guess it's an EVM like EVM compatible contract. It lives on the near blockchain and there's those can actually talk to each other apart from on a really low level. So if I own a NFT on Aurora near doesn't know that I own that and it can't know.


Benjamin  
And so the Dao tooling on near is unable to take my Aurora NFT and use it as a membership criteria for this Dao. So now if I decide right, well I want to associate my near account with my Aurora EVM address so that I can use this token as a as an access pass to this Dao on near, then I can using something like that.


Benjamin  
Now obviously the choice is up to the user as to whether they decide to attest that they own this. But it has. Yeah, definitely has, you know, technical underpinnings rather than this sort of idea that you sort of like maybe identity separation or something like that, that that's completely valid as well. And I agree with that. It's like it's all up to the users choice.


Benjamin  
Like we don't use this to detect who you are between chains, where you use it to facilitate somebody wanting to attest to who they are.


Citizen Cosmos  
Absolutely. I love I love the bird sounds, by the way. No, no, no. This is I really do. I like I like. Is that is it like are you to someone next to nature? This is like a serious questions. This is not a joke question. I thought it was a bird of birds.


Benjamin  
They all it's I'm signed my my garden and loved animals in the.


Citizen Cosmos  
Desert It's lovely but it's lovely but it's lovely. It's a question that I have. I have to you the next question is and this is something you mentioned and in Cosmos, in my opinion, this is a very big discussion considering Cosmos is all about interoperability and about function and interoperability, which is a big surprise, I think, to everybody, even to to everybody who was following Cosmos for years when it started work.


Citizen Cosmos  
And I was like, Oh my God, it actually does work. Really. Look, to go to detail.


Benjamin  
Of my my Cosmos history is patchy.


Citizen Cosmos  
We can talk in detail on that. But before we do, like you mentioned something really cool there, which in my opinion is really important and relevant to Cosmos today. And I'm sure that everybody who is Cosmos cosmonaut and listening to us will will relate to that. You mentioned governance threads and you mentioned projects that use and this is, in my opinion, atrocious in my opinion to be able to use sorry to not to be able, but to still use things like.


Citizen Cosmos  
But anyway, let me ask the question and then you voice their opinion because I really want to understand what you think about this. So we spoke about, you know, the difficulty of using Web three tools when, you know, Web two kind of offers you much easier solution. But at the same time, you know, well, we want to target the audience, which is on web, too.


Citizen Cosmos  
So that's why we use in Web two still. So the governance is kind of in a way the same, but it's not because those users are already aware of Web three tools. They're already aware of what onchain discussion can look like. And in Cosmos, that exists the most I mean, any blockchain, you can create an easy on chain discussion.


Citizen Cosmos  
It's not very difficult at all today. And still people keep on not just using forums and and other tools to to discuss governance, but they insist on that. In fact, I've seen chains making proposals like on chain proposal to say, let's go and use this web two to discuss our governance. And if you don't use it, we will not consider you part of our community.


Citizen Cosmos  
And you're like, What the hell are you doing guys? Like, can't you see that this is really like a step backwards? And this is my this is I know I'm kind of like being loud and opinionated about this right now. And I guess I have been a little bit today. But still, what's your opinion of that? Is that in your opinion, okay, in order to get people who cannot use Web three, but it's a bit strange because.


Citizen Cosmos  
Well, they already are Web three users, Right. So what's your opinion here?


Benjamin  
It's yeah, I think I think we might be in a strange transitory period where early software developers in the seventies making operating systems that and they enforce that things needs to be sent over mail right and put this to me in writing that there were very much like you know, the magazines are like Linux zines with things. It wasn't all done online immediately.


Benjamin  
And I would say it's probably just this adoption barrier of, you know, what we want to get like so the incentives of the thing. So we want to get people involved in this forum. We want them to engage in it as much as possible. So let's here's the easiest thing with the least friction so that we will get the highest turnout on this proposal that so we'll get the best user engagement.


Benjamin  
It purely to me speaks to the fact that these Web three tools are not ready yet to take on like an to basically be an analog to these to the web three solutions. It might be anything from slow UX to it costs me a few pennies to post my comment, whereas it would cost me nothing otherwise. One possible solution is the exact opposite of what you mentioned, where instead maybe protocols should enforce that things are done on chain instead of trying to get people off chain onto web.


Benjamin  
Two things. It might just be a matter of like the leadership needs to take a stance of like, let's get this on chain just the same way they took a ... took a stance to say, let's get this off chain. But yeah.


Citizen Cosmos  
Absolutely.


Benjamin  
It's kind of my my diagnosis of it.


Citizen Cosmos  
I think it's a person I definitely go I mean I mean, there was the whole Ava talk right on Ethereum recently about the centralized frontend and yeah I'm absolutely all for it I think that.


Benjamin  
Yeah, me too.


Citizen Cosmos  
Them.


Benjamin  
Me too. Having that, that's really all, all I can say is, is it should be done in a way where the data is able to be pulled into any frontend. It's it all kind of comes back to these shared publicly accessible protocols rather than you know, having some some tool own the data on a database somewhere.


Citizen Cosmos  
We kind of like a little bit harsh, I guess, about the centralization in the last like 40 minutes. Do you think that decentralization is a spectrum or in. I don't know, in ten years time everybody must be decentralized? Or is that even a decentralized thing to say that everybody should be decentralized? I mean, what's your take on that?


Benjamin  
Yeah, no, it's a good question. I think it's again, sort of like having to look at the incentives of the thing. So I'm not sure, you know, if you're if you're a corrupt Dao, you might want to be able to hide people's comments in the forums. But you know, in general there's a huge necessity, decentralized finance stuff, you know, that's why that blossomed so early.


Benjamin  
You know, there was there was nothing like it previous to that. I mean, there is there is social media still. And the fact that it's decentralized is almost hidden from the user. There's no obvious benefit. It's not like now now I don't have to go through a bank to do my things. Now I can just like do it with a wallet on my laptop.


Benjamin  
I could go on Twitter, on my laptop, or I could go on a decentralized social media thing on my laptop. So it's sort of like the incentives of people, people maybe aren't quite there yet, like in there on the on the adoption curve in order to like fully see the benefit of like my history lives forever. I'm on chain.


Benjamin  
Or this is as transparent as it possibly could be with no tampering able to happen, etc.. Yeah. So I mean, I think there's still going to be stuff that's that's that is centralized. Probably always like I imagine just for like legal reasons, stuff like Spotify and Netflix may well always be just because you can't have that content, you know, publicly available because it's a copyright infringement.


Benjamin  
But you know, there are some arenas of the Internet that could be far more decentralized than they are and should be.


Citizen Cosmos  
I have one question. You mentioned the word incentives several times. I'm one of those people who believes that incentives are kind of in built into the you know, we have the rewards cycle. And if you don't have the rewards cycle, you'll be just in a mobile, you will be a plant. So it's kind of been built into us.


Citizen Cosmos  
And I think one of the biggest issues that I told you, I was part of a team as early as 2015/16 to launch decentralized social network and experiment sorry. And the biggest issue in my opinion, and I had the biggest issue in my opinion to till today with social networks is the economical and incentive side. How do you guys solve that?


Citizen Cosmos  
What's your approach on that matter in terms of economy behind all that and incentives?


Benjamin  
Yeah. So as far the actual is the as well. Okay. So for permacast, I can, I can give you a straight answer for decent land not so much so for Comcast, what we do is we do a system where the amount that you spend uploading on an episode is dropped back to you. In our native token relative to the amount that you spend.


Benjamin  
So it is possible to earn back either the same less or more depending on the token price at launch. Then you upload it. That is one of the incentives essentially earn to decentralize, earn to earn to upload. But then also we plan on further than that having token economy basically within that where if you buy somebody NFT episode using these tokens that you get from uploading, then it could be something like you get access to like a private feed of that podcast or something like that.


Benjamin  
And so that kind of gives you an economy in there. Now, decent land is definitely more difficult because you want you don't want is people doing incredibly low cost actions repeatedly and just basically farming the protocol in order to get tokens out of it, it has to be based on quality. And so I'd say that's an unsolved question right now.


Citizen Cosmos  
Rather worry about it.


Benjamin  
Yeah. One incentive that we have for decent land is actually ANS which is Areweave named services dot AR domains. So you know I'm sure you're familiar with dot eth domains they expire and they really need the incentive to hold them is because you hope to sell them at a later time. Now what we have with ANS is a different kind of incentive mechanism.


Benjamin  
So say I meant Benjamin Dot AR that is then written into the blockchain that I own this particular string of characters. Somebody comes along and mints like Benjamin one or Ben or Jamal or any of these these puts plots, sort of some strings within it apart a portion of the minting fee would be attributable back to the original owner of that substring based on, you know, how close of a match they are.


Benjamin  
So you're incentivized to hold your username in order to accrue these percentages of minting fees back off of of of new mints as well. So this is this is kind of identity incentives rather than social incentives the way we're talking about here on the on the social incentive side. Now actually what we've what we've realized we've more created is almost like a disincentive for bad behavior, like slashing around the social things.


Benjamin  
So on the social model in decent land, it's possible to create a token gated community, but where you would need to own a particular NFT from a collection, maybe even filtered by traits in order to get into this community on decent land. But to be a moderator of that community, you would need to be staking tokens on that community's contract in order to continue being able to moderate it and to keep it open.


Benjamin  
And so what this creates a disincentive from kind of like rash hand of God Reddit style moderation that could actually help, you know, keep more of a balance in these decentralized communities. Because, you know, I referenced Reddit. The moderators are able to, you know, basically run wild with that power. The same with Twitter. You can get suspended and you have no recourse.


Benjamin  
Say enough people get enough, people get suspended from particular decent land community, they have recourse to be able to vote to slash that moderator and reshuffle the governance and take a vote as to who should actually be the moderator. And so there's kind of a built in rebellion mechanism for these for these kinds of communities. Now, as the actual incentive to do that, I mean, we hope that is that you can use the tooling rather than say that you can get money.


Benjamin  
And yeah, I mean, obviously there's still more thinking to be going to be to be gone into that. But that is one of the cool things that we'll be the as far as like the token economics of it from.


Citizen Cosmos  
A perspective of a person who has been around it for the last like several, much more years, I think you're on the right track. I think that the things I'm surprised, the things that you're saying, for example, you know, NFT episodes or you know moderator tokens, this is things that in my opinion are like make common sense.


Citizen Cosmos  
And I'm surprised that I haven't seen those implemented on a big scale yet. I'm really I'm like, it's just makes perfect sense in my opinion, what you say. So, Benjamin, there is one more small thing I want to ask you about before I go into the Blitz, which was about storage and ipfs and Areweave. And my question is why Areweave and why not IPFS?


Benjamin  
Yeah, sure. So as we know, IPFS is free and that makes it a pretty attractive option for many, many use cases. But I don't know whether many people do now. But it's not. There's no incentives for the for the hosts to keep it around. It's almost like you're asking a stranger and holding them on trust that they're going to keep your files.


Benjamin  
The incentives, again, are very important and there is essentially for IPFS, I believe, no incentives In the case of all we've what we have is a 200 year guarantee of data availability based on the amount of people who are currently mining AR people who are mining AR token. They have these huge rigs with multiple terabytes of space.


Benjamin  
They store, you know, the whole blockchain multiple times on their machines and they are incentivized to be able to quickly provide the piece of data that you want when you ask them for it, when you pay for storage on Areweave you slightly overpay and and the slight overpay goes into a wallet called the endowment fund and the endowment fund where I get 200 years from is that if nobody ever uploaded anything to all we've ever again, there would be enough money to incentivize miners to keep mining for 200 years, at least at all times.


Benjamin  
Now, that was the figure from a while ago. I've heard 500 years, 1000 years now, Areweave, keeps growing. So essentially what it creates is a, you know, cryptic cryptographic assurance that that your data is going to be there. Right now, we have, I think, between the hundreds and thousands of nodes, which all all store multiple copies of Areweave blockchain and are incentivized to do so monetarily.


Benjamin  
And even if they were to stop receiving rewards from blocks because the blocks are all empty, they would still receive rewards from the endowment for many, many, many years to come. So that's that's why I find Areweave to be extremely robust and waterproof. It's like if you were to have an incentive layer on top of torrenting that would keep people seeding because it's keeping is making them money.


Citizen Cosmos  
I see. I see. Makes sense in that case. I guess I mean, I have questions like when you say 200 years, you know, when you say the amount of money there is, it's an AR token. And what would be the cost of AR token in 200 years? But I guess that is very speculative and we can discuss this for a long time.


Citizen Cosmos  
And of course, you could change whatever currency you keep in that in. So I guess it's it's kind of makes sense. Let me, if you don't mind, like going to the Blitz too, too quickly, ask a three questions. Feel free to answer them short and quick like a blitz or feel free to open the answers up and go into detail.


Citizen Cosmos  
So the first one is could you give me three projects outside of the top 20, preferably that you are interested in What they are developing and currently and working on.


Benjamin  
Outside of the top 20 are? I don't keep up with with rankings. I think I think around the 30 mark Areweave round around 70 at this point. I'm quite interested in in Ton the telegram network because it's got this built in web two identity link to your telegram username which which which we find to be an interesting part of identity.


Citizen Cosmos  
I've already seen projects. One of the projects I was talking about today, I was actually I was in purchase identity link. It's interesting. I think you guys might have crossings that are give me to add two things that motivate you to keep on doing what you do in daily life.


Benjamin  
My my family very much. And generally the goal of turning things into a protocol rather than a walled garden.


Citizen Cosmos  
That is actually very cool answer I like that. The last one person that you think that for anybody who will, if it's a book, they will read it or if it's somebody they will follow, that they will benefit in their daily life and will help them to be more concentrated, motivated, more successful in whatever it is they do.


Benjamin  
Okay, Got it. Yeah, I think there's a book, The Cathedral and the Bazaar. It is a book, I can’t remember who's by first names, Raymond? It's a book written, I think maybe 20 years ago, maybe even older about open source software being having inherent virtues. I suppose it would almost be said against closed source. The idea basically being that when you are there's a great quote from it, something like with enough eyes on the problem, all books are shallow.


Benjamin  
I'm essentially talking about how that once you open source something, once you get the community's eyes on it, problems are basically the solutions to problems that become decentralized. And the problem is one that can be decentralized almost. When you take it out of the corporate sphere, the whole thing is kind of talking the cathedral being something like Microsoft Windows, this huge proprietary, impenetrable black box of binary verses, the bazaar, the free trade market of different pieces of software, different components here and there, each of which are, you know, adopted and used.


Benjamin  
And they have got a lot of eyes on the code themselves, which means, you know, you can you can more easily debug them, you can more easily reuse them, etc.. I think that book has been like one of the most influential. My thinking.


Citizen Cosmos  
I love it. I love it. I absolutely will definitely find it and definitely included to the podcast notes for sure. Benjamin Is there anything else I didn't ask you that you would like to mention?


Benjamin  
I don't think so. I feel like we had a really good, freeform, wide ranging conversation that's pretty much covered everything that's been on my mind lately as well. So nice job.


Citizen Cosmos  
Cool. I like hearing that. Thank you, by the way. And thank you for your time, of course. And thank you for joining us. Thank you. Everybody else who's listened to the episode and tuned in. Thank you very much.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

If you would like to support our mission in creating educational content and aligning the goals of different communities, please stake with us [here](https://www.citizencosmos.space/staking): 

- [EVMOS](https://wallet.keplr.app/chains/evmos?modal=validator&chain=evmos_9001-2&validator_address=evmosvaloper1mtwvpdd57gpkyejd566s24afr9zm5ryq8gwpvj) 
- [ATOM](https://wallet.keplr.app/chains/cosmos-hub?modal=validator&chain=cosmoshub-4&validator_address=cosmosvaloper1e859xaue4k2jzqw20cv6l7p3tmc378pc3k8g2u) 
- [BOOT](https://wallet.keplr.app/chains/bostrom?modal=validator&chain=bostrom&validator_address=bostromvaloper1f7nx65pmayfenpfwzwaamwas4ygmvalqj6dz5r)

Join our [community](https://discord.gg/kJaG3EucCX), to build a future where communication is decentralized. May the code be with you!