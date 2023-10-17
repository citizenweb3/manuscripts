+++
title = "Citizen Odyssey Simply Staking. Transcript"
date = 2023-08-26

[taxonomies]
tags = ["odyssey", "transcript"]
+++

<iframe width="560" height="315" src="https://www.youtube.com/embed/x2-3bMvF18o?si=B9fxIzGI4EHozuOd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

--------------------------------------------------------------------------------------------------------

Citizen Cosmos:  
After I already realized that it goes live, but this is going to happen. And I think we are already live. Let me just check that it's all working. Let me just see our beautiful faces. There we go. There's our beautiful faces. So hi everybody. It's citizen cosmos with our Odyssey and Isaac today. Hi Isaac. Sorry to interrupt your hello there.

Isaac Zarb:  
Hello, how are you?

Citizen Cosmos:  
Good, good, Isaac. So yeah, for everyone who is watching this stream or recording, as you probably usually would with us. This is of course, exploring validators. And today we have Simply Staking and Isaac is the co founder and the CTO of Simply Staking. And let's do like a traditional typical thing, you know, before we go off into our questions, Isaac, I would like to ask yourself what is Simply Staking for you personally in your own words and why on earth did you one day woke up and decide to be part of this business or endeavor or adventure or whatever. So what is Simply Staking and how did you get here? That is the first question.

Isaac Zarb:  
To me, it's a lot of stress and lack of sleep, I would say. And I guess...

<!-- more -->

Citizen Cosmos:  
I understand.

Isaac Zarb:  
And we decided to get into this because we're crazy, probably. So, simply speaking, well, as a company, it's been founded for quite some time. Back in the day, our original investor and founder was doing some mining, some Bitcoin mining and Ethereum. and he had the idea to build a data center. So this is how we inherited the data center in Malta. So he started off doing like Bitcoin mining, some proof of work mining. And after some years, electricity costs were no longer, it was no longer lucrative to mine in Malta. So he kind of abandoned the project. And then we got introduced to this guy about five years ago. and he gave us a remit like figure out how to make money. Like here you have a data center, figure out how to make money in blockchain. So we started at the time he had a lot of tokens around master nodes. So we started running the first version of proof of stake, which was master nodes. That very quickly became unprofitable and we started looking into how to make money. We got into Cosmos, we were one of the Genesis validators for the Cosmos Hub, and back then there were very little validators, not like today where everybody's a validator. So after starting validating on Cosmos, we had a lot of new chains coming up asking us to validate on their chains, At that time there were a lot of test nets and it was like the thing to do for validators to go into the test nets and go over the challenges. So we did a lot of that and we made a good name for ourselves. Back then I think we were like four people or five people. It was me, myself, Matthew, Francesco, I think, and Daniel back then and maybe Miguel. So then we were Chainlink reached out to us to start working with them. and we did that. And we started adding networks, you know, slowly, slowly. Fast forward five years, we're running like nearly close to 10,000 validators now, like running on about 20-something main nets, pretty much run all the RPC nodes, lots of hardware. So I think the... One of the biggest issues we had was scaling the hardware. Back in the day, a lot of the nodes were running on local disk, but we realized that if we want to be reliable, you cannot have a server fail and you lose all the data on the server, especially when chains started growing, like 30 terabyte chains to sink a new blockchain would take forever. So we started playing around with shared storages and talking to a lot of vendors. And we finally figured out how to run SANS with blockchain nodes. It was very expensive, but today it gives us peace of mind that when we need to do maintenance, we don't need to take a node down and just migrate it to another host, shut down the host to the maintenance. Yesterday. There was that Intel CPU vulnerability, the downfall. So we've been restarting hosts, updating firmware on hosts on these last two days. But the hard work gives us the flexibility to do maintenance without causing any downtime. So very happy and proud of my team for getting us here.

Citizen Cosmos:  
How big is the team now? You said you started four people, how big is the team now?

Isaac Zarb:  
Okay, so now we're like 38th in the company.

Citizen Cosmos:  
Almost 40 people. 40 people.

Isaac Zarb:  
It's not all the staking. So we have multiple teams. So the staking team is around 15 people, if I'm not mistaken. Then we have a blockchain team. We're soon going to test that on our ETF blockchain, index vault blockchain. It's called Entry Point. We've got a data team. who help us figure out all our transactions for our accounts. And who knows in the future. And then we have some HR and the, you know, a finance and the typical management. Pretty much nearly 40.

Citizen Cosmos:  
So basically you're concentrating only on hardware and software, right? In that case, you're not concentrating on any other services, is that correct?

Isaac Zarb:  
uh as myself or as the company you mean

Citizen Cosmos:  
No, I mean, of course, of course, Simply Staking and I'm referring just to Simply Staking. What I mean is, for example, you see some validators choosing to go down the route of we're going to provide an additional service for the blockchain, whether it's media, whether it's blockchain development, whether it's, I don't know, community work, whether it's something else. And there is, let's say the hardware validators, what I like to call them as the validators, who primarily they are concentrating on providing a stable permanent uptime. hardware, whether it's, I don't know, archive nodes, any other nodes or whatever else, you know, the build up as you describe a big, big. So I guess this is what you're mainly concentrated on, right?

Isaac Zarb:  
Well, we do some tooling as well. We've built some tooling

Citizen Cosmos:  
Okay.

Isaac Zarb:  
for Ethereum, some tooling for... We have

Citizen Cosmos:  
Okay.

Isaac Zarb:  
a monitoring system called Panic for Cosmos and Substrate validators. We're building our own blockchain. We've helped like Agoric build their Oracle network. We do quite

Citizen Cosmos:  
Okay.

Isaac Zarb:  
a lot of development. We've built some modules for the Cosmos Hub again, back in the day.

Citizen Cosmos:  
Nice.

Isaac Zarb:  
We helped... blockchain launch. So yeah, quite a lot of development work as well.

Citizen Cosmos:  
nice

Isaac Zarb:  
And we're building our Staking Dashboard now. Still working on the name. Sorry.

Citizen Cosmos:  
which is going to be like a dashboard for delegators or a dashboard for anyone else.

Isaac Zarb:  
Mostly for the initial use case where it is for RPC. So

Citizen Cosmos:  
Okay, RPC.

Isaac Zarb:  
to enable clients to get RPC nodes from us.

Citizen Cosmos:  
Okay,

Isaac Zarb:  
But

Citizen Cosmos:  
nice.

Isaac Zarb:  
we'll expand it as it goes along to have like the delegators and the validators of service business from it. And we'll expand as need be.

Citizen Cosmos:  
There has been a lot of talk in the past. I think the talk kind of stopped with the bear market hitting, but I think before it hit, there was a lot of talk from the larger projects such as yourself, what I mean with the resources by saying larger, of developing validator tools, not so much delegator tools, but validator specifically tools. I'm curious because you did mention that you're developing like a dashboard for clients to take RPC. And what I mean by that was, I think me and Notional, we're talking about the fact that a lot of validators starting out would like to see statistics that they would have helped them to manage their funding and funds, what money comes in, what money goes out, what they earn and so forth. What I'm interested in is what do you think about... is currently like as a big validator who's running, well, helping to maintain almost 50 networks, as you say, and I see we can see this on your website, you have like a huge, huge list of all over, it's not just Cosmos, you know, so we're talking somebody, a big player, in terms of infrastructure, do you think that the space needs such thing as validator tools that will help?

Isaac Zarb:  
Definitely.

Citizen Cosmos:  
Okay.

Isaac Zarb:  
So we've kind of built most of that in-house. Maybe we can actually talk about open sourcing it. So we wanted to figure out like what we're making from each blockchain that we're validating on. And sometimes you'd see like the rewards at the end of the month, but you don't know if they're coming from your own delegations, if they're coming from other delegators. So we've built this tool ourselves that goes through the wallets and tries to figure out if it's commission or

Citizen Cosmos:  
Nice.

Isaac Zarb:  
rewards. Definitely there is a use for that tooling. There's also the issue with finances and taxes, like this is something that all the validators go through. I think in every jurisdiction you need to file some accounting. I think in Dubai you don't, but everywhere else you have to. Unfortunately, in Malta, we have to file a lot of accounting. So we're building the data system that goes over all our transactions, so all the chains, outputs, the data, and then we hand over this to the finance teams to verify. It's a lot of work. We've been working on the system for a number of years. I think finally we have a good... system that allows us to get out the data which we need, extract data and gives us soon meaningful reports. So yeah,

Citizen Cosmos:  
Yeah.

Isaac Zarb:  
we keep ourselves very busy, we're working on a lot of things.

Citizen Cosmos:  
It's cool. It would be cool to see if you guys decide in the future to open source part of it or some of it. I know there have been other big teams working like Notional in the background on similar tools. And there's been a few smaller teams as well, I know, working on similar things. So everybody's in agreement that those tools are definitely needed, not necessarily so much just taxing tools, but... tools that will allow the validators to understand what's happening with their money. Where is this revenue streams? Where do we lose? Where did we gain? So yeah, but let's go back to your initial setup, your data center. I love the story you said, your original founder, sounds a bit like Satoshi left you lots of tokens and left. Out of curiosity, before we go, and of course, this is a kind of private question, you said, the original investor or founder, are they still I'm curious, does that imply that there was a founder who left? Or does that imply that there was just somebody originally an investor who helped to invest and now there is a team running it? And it's a private question. I understand you don't have to answer that.

Isaac Zarb:  
It's public knowledge I can answer. So there was the previous investor who sold his shares to another investor. So that's the story. So there's some of us who are co-founders as well. And there's the UBO, which is the larger.

Citizen Cosmos:  
The one and only.

Isaac Zarb:  
Yeah. Hahaha.

Citizen Cosmos:  
The big guy, yes. I understand totally what you mean though. I totally understand what you're getting with it. A lot of teams especially, I remember I launched my first, I think, node in 2016 on a pitchers type network. It wasn't a master node, it was a depost node. And a lot of the time back then, you would see slowly teams like you described start to arise. But in 2017, you would always see like one person go into the background, who would be the original investor. And then you would have a lot of co-founders and we can see that. So it's definitely something that I can relate to. Um, but you said about the original setup. So it was Bitcoin mining. And then one thing led to another, you end up with, um, electricity costs going up, you end up with some equipment and okay, here you are. How did it develop into what it is today? Like what were the steps sort of to build it, that plays the data center, the third tier data center as you call it.

Isaac Zarb:  
Okay, so the data center was pretty equipped, like there were the generators, EPSs, all the electrical circuits. We had to get out all the mining grigs because they were ASIC miners and DANT miners and stuff, like we had to dump all that crap. We bought some servers, back in the day, it wasn't as hard to run blockchains as it is today, so we bought some Dell servers. and started running some master nodes, like some Linux VMs and some, and the initial Cosmos validator. I think initially we went crazy because we didn't know how difficult it is going to be to run the Cosmos. So we had, I think, like six sentries and like the main validator hidden behind the sentries. And then we even panicked and we were like, maybe let's

Citizen Cosmos:  
It's not enough.

Isaac Zarb:  
runsentries all over the cloud as well. And then we quickly realized that, okay, we don't need all this. You know, so we, we removed all the cloud data centers and we just had our one data center in Malta. And then we started, as I mentioned, moving into other networks. So we started adding hardware as we went along. I think the first thing we did was we bought some really good firewalls, put those in, then like started setting up the segmentation, the networks and then. put the hardware, put the servers in and started increasing our bandwidth slowly. Bandwidth in Malta, unfortunately, is extremely expensive, but it's part of

Citizen Cosmos:  
It's an island life, I imagine.


Isaac Zarb:  
being island. Yeah, so bandwidth is a premium. And then, like when we were running at a good capacity in our data center in Malta, we realized that we need more data centers just to be resilient. So we got a co-located data center in Netherlands and we bought all the hardware, shipped it there, shipped the people there, set everything up. And then we had two data centers. So we were operating out of two. And then like, I think two years ago, we decided to expand into another data center. We got a data center in Canada. We thought the regulation there might be a bit friendlier than the US. We got a couple of cabinets in the data center there, shipped the hardware, and I didn't realize what a nightmare it's gonna be to get hardware in Canada. In Europe, it's much easier to get hardware. Especially all our suppliers were in Europe, so we had to find new suppliers in Canada, and it was quite a nightmare, especially... flying there, it was minus 25. It was really cold when we got there.

Citizen Cosmos:  
And I can imagine for you it was a shock

Isaac Zarb:  
Yes, it was really cold. It was in COVID time, so we were wearing masks and doing tests at the airport. And after like 20 hours not sleeping, it was like, are you going to poke me now?

Citizen Cosmos:  
Ha ha ha.

Isaac Zarb:  
But yeah, we got that data up and running. So now we're running out of three data center. We own all the hardware and the stack from the firewall to the servers, to the storage. The only thing we get from the data centers is bandwidth and power and remote hands sometimes if we need them. I think it's, having our own data centers and our own hardware allows us to be very flexible. Like there were times where For example, running a BSC node was nearly impossible. And at some point, we were running it on commodity hardware because the servers weren't tuned well enough. And we tried actually running it on some clouds, got really big VMs on Azure and AWS, and still syncing this node was nearly impossible. Then we started looking at the stack, we optimized the VMware. VMs that we're using that played around with some settings and we finally got these VMs to sync So we didn't need to buy gaming PCs anymore just to sync this So having our own Obviously, we always never we never want to use gaming PCs or anything like that. We want the enterprise hardware. So We had a need because we needed to run these chains So we did whatever we could to get them running but our goal was to get them on to onto the servers as quickly as possible. That was like interesting. I got to play with a lot of hardware at the time. The newer generation CPUs I think are really great. Like there was a time where AMD was much faster than the Intel, but Intel CPUs have finally caught up. And I think now we can run any chain without any problems on the latest generation CPUs.

Citizen Cosmos:  
actually a lot of questions regarding bare metal as you speak, you're kind of writing some of them, jotting some of them down. And some of them might seem plain, simple, plain silly. But I think it's things that are interesting to a lot of people, especially a lot of people either starting out. So I'm going to ask some questions. And of course, some of them you might find very short. For example, you know, you describe like what to use, obviously your story, and it's kind of like, That's what happened. But a lot of people are like, wow, this guy built his own data centers. These guys are crazy. So there's a lot of questions coming up to mind. For example, if would you say that using... And this is a big discussion I had with a lot of other validators. For example, what about secondhand hardware? Do you guys use secondhand hardware? Do you think it's a good practice to use secondhand hardware? Does that help or no? Or only top of the notch or whatever? What's your opinion on that, for example?

Isaac Zarb:  
We do get some refurbished hardware. I always make sure to get the manufacturer refurbished, not buy them off eBay or something like that. If we do get refurb hardware, it has to be like latest gen. So it would be some company who just bought the hardware and like closed down or something, never buy old servers because they're useless. Like I would say our servers are like... one or two generations old. I think

Citizen Cosmos:  
Okay.

Isaac Zarb:  
we have some older generations, but those are just used to run our monitoring systems and internal stuff. The blockchains really need the latest CPUs. Generally, we tend to go for refurb when we cannot get our hands on new hardware. This happens like what's gonna happen right now after this Intel downfall vulnerability. a lot of companies are going to need new CPUs because the latest Gen 13 CPUs are not vulnerable to the exploit.

Citizen Cosmos:  
Oh,

Isaac Zarb:  
So there's gonna be

Citizen Cosmos:  
and

Isaac Zarb:  
a lot of demand

Citizen Cosmos:  
I

Isaac Zarb:  
for hardware

Citizen Cosmos:  
think

Isaac Zarb:  
and

Citizen Cosmos:  
our

Isaac Zarb:  
you

Citizen Cosmos:  
guests

Isaac Zarb:  
won't be able

Citizen Cosmos:  
lost

Isaac Zarb:  
to.

Citizen Cosmos:  
connection, but they will come back. So if you guys watching it stick with me. There we go. Hello, Isaac.

Isaac Zarb:  
I lost you for a second there.

Citizen Cosmos:  
It

Isaac Zarb:  
Yeah,

Citizen Cosmos:  
happens.

Isaac Zarb:  
I'm back.

Citizen Cosmos:  
No worries. No worries. It happens. You were saying about the new about we're talking about secondhand and new hardware and you're talking about the generations of CPUs. So if you just want to carry on or.

Isaac Zarb:  
Yeah. So generally you'd always want to stick to the latest generation of CPUs. Like within one generation old is usually fine, but anything older than that, you're going to start having problems, especially with new blockchains. Like say, where you have sub one second block times, you really need the latest CPUs to keep up. We generally tend to go for refurb hardware when we need to buy new hardware and there's a chip shortage, which will probably happen now given the Intel vulnerability that came out a couple of days ago.

Citizen Cosmos:  
Mm-hmm.

Isaac Zarb:  
So everybody will want a lot of new hardware, so there'll be a shortage. So your only option would be if you need hardware today to try and find some refurbished hardware.

Citizen Cosmos:  
What about...

Isaac Zarb:  
Never buy refurbished disks, obviously. Hard disks should always be new. because they degrade.

Citizen Cosmos:  
That was actually a question about the disc. Sorry, carry on, carry on, please. It was about

Isaac Zarb:  
Yeah.

Citizen Cosmos:  
the discs.

Isaac Zarb:  
So disks, I would always go for new, like definitely new, especially for our SANs, because those are the hearts of the system. I think the lessons that we learned are switches and stuff like that can be refurb, like Cisco switches never die, but anything else you probably want to get as recent as possible.

Citizen Cosmos:  
What about, I mean, initial, sorry, initial or general costs? I mean, there was, for example, I recently spoke to, it's amazing how many opinions you can get from speaking to so many validators. And of course, the bigger validators and smaller validators have different opinions because they have different goals. And of course, sometimes our opinions... Like, you know, you get, you talk to one person and they're like, oh, you don't need all that. And then you understand, okay, but their goal is different. But what about the initial cost that you, that you, and talk about architecture here, that, um, and okay, let's talk of course, Europe, American kind of, um, realism, because that's where we allocated me and you at least, and it's easier for us to understand it. So it's not that we want to ignore everything else. What is the reality? Let's say there is a team. sitting in a basement and they have hands-on some equipment, but what is the real cost currently that they would need to, if they want to run a couple of top validators and a couple of top networks? I'm not talking about the dockings they need to get into the set, but what would be the cost of running those kind of operations if between something...

Isaac Zarb:  
Okay. So if you're starting out, obviously,

Citizen Cosmos:  
Yeah.

Isaac Zarb:  
I don't think building your data center, it's a huge cost. So had we not had the initial data center, it would have been very hard to say, okay, I'm going to get into this business. Let's spend 300 grand to build a data center. I would say like the setup is like, for example, from our setup, I think the biggest cost would be like the bandwidth. Because we have like, we use multiple ISPs and then we use BGP to bond the links together. So if one, so our, something that is rooted over multiple ISPs, so if one ISP is down, we can continue routing traffic and never change our IP addresses. So you're kind of paying twice for the bandwidth because you get two links from different ISPs. But all these things allow you to be more resilient and up, you know, like increase your uptime. I think if I were starting new until you boost revenue, I would probably use some co-located hardware in a data center. And then once it scales up, maybe get my own data center or maybe use providers where you can rent hardware until you have a steady revenue stream.

Citizen Cosmos:  
It's definitely an interesting case because for a lot of, of course, validators who have started their operations a long time ago, you know, the case can be easier. Like you say, okay, we'll have the data center. Somebody says, well, I had the team, I had the whatever. And that's why I think also the reason why when I speak to a lot of smaller validators, another topic. comes up at hand and actually doesn't come just with smaller validators, it comes up also with big validators, but more rarely. And the top is X is one network one server. And at the beginning, especially like during 2017-18, I think it was kind of like the law was like, hey, you cannot put more than one network on one server. Of course, the market was going up. Everybody was happy. The market changed, the conditions changed. We learned a lot of things in the process of what's harmful, what's not to the networks. And today, what I can see is that we have validators already bragging about putting five, six, seven networks on one server in order to get the costs back. And even then they say, well, I'm running those five, six. I don't want to be... use a bad word here, but you know, low cost, sorry, low cap, low cap, excuse me, networks, and even they don't pay for the servers. What are your opinions on that? What's your opinion on how this should be or shouldn't be or how you guys do it or what you suggest? Any reflection?

Isaac Zarb:  
So the way I see it is that most of the requirements are. I wouldn't say wrong, but you see like most blockchains, they would tell you, you need a terabyte of RAM or you need five, one, two gigs of RAM. That's true for Solana, by the way. You need a server for Solana. Trash is that kind of it. But besides Solana, I would say like, you can like, one thing we figured we did a lot of research on was what kind of storage do you need to... to run these blockchain nodes, because everybody tells you need local NVMe disks, SSDs are, SAS or SATA SSDs are not fast enough, you need NVMe. But the chip on the NVMe and the SSD is the same chip, it's just the interface that's different. So, Andy said you need a million IOPS. It's not about the IOPS, like you can run it with much less IOPS. The problem is latency. So... because you have a lot of reads and writes at the same time. So you have like blockchain reading a whole epoch from disk while writing at the same time. So basically you need a lot of interface bandwidth to talk to the silicon. One thing we were doing wrong in the beginning was we were using iSCSI, which is software based LANS on the storage. So what happens is when you're using a protocol like iSCSI, from the hypervisor or from the server, you're hitting the CPU of the server and then going to the SAN and hitting the CPU of the SAN. So it's not like you have like a middleman, which is the CPU in the way. Then we move to fiber channel. So same hardware, just we went from iSCSI to fiber channel. And that made like, it's like we... changed everything, like it's like

Citizen Cosmos:  
Wow.

Isaac Zarb:  
we had new disks. So the latency went from one millisecond to like 0.01 milliseconds.

Citizen Cosmos:  
Wow.

Isaac Zarb:  
Whereas with Fiber Channel, you're not using the CPU and the hypervisor. So whenever you need to go to storage, you go to the Fiber Channel card and direct to the storage. So over there, we removed a big bottleneck. using NVMe disks in the storage helps because again when you're using SATA or SAS you're passing through the CPU and the controller has like a 12 gigabit bandwidth where you need much more bandwidth so with NVMe you have like the whole PCI express bandwidth. Yeah but like we don't see much difference from our shared story from our SANs to the local NVMe disks. It's pretty much, pretty much the same. It's just getting the right infrastructure deployed and knowing how to maintain it.

Citizen Cosmos:  
Do you still use NVMe disks or do you use all sorts of, or there is a mixture of types of disks that you use across the servers? Considering...

Isaac Zarb:  
We don't run much anything local on the servers because we want the service to be disposable if the server dies, we just run

Citizen Cosmos:  
Mm-hmm.

Isaac Zarb:  
the workload on another server. All the SANs have NVMe disks because

Citizen Cosmos:  
Mm-hmm.

Isaac Zarb:  
they offer better performance. But it's not because the disk is better, it's because their interface offers better performance.

Citizen Cosmos:  
Yeah.

Isaac Zarb:  
We do use some local NVMe disks on some servers where if we have... emergency and we need a little bit extra power we would run something locally something huge like a Solana node or something like that

Citizen Cosmos:  
Let's talk a little bit about, I mean, there's a million questions I can really ask and a couple of questions. I see someone posted one here. And actually let me ask that because I'm going to, it's a good direction to take it in. How do you guys choose the network? I mean, how do you today, especially considering your size and I mean, you know, blockchain, decentralization, but we all understand the power of. every given, any given entity or any given player. So when a player with a lot of force comes in, how do you make your choices? I mean, do networks come to you completely all the time or do you go out and look for networks? That's I guess the first step. And second, regardless, what's the criteria that would make you validate a network today?

Isaac Zarb:  
Okay, so I think we made the mistake in the past where we joined all the networks. Like any network that came up, we were joining, but then you start realizing that you're losing a lot of money from most of the chains you're running and like the bigger chains are subsidizing everything. So now we join chains, which we either invest in, or we would have a good relationship with where we help out in the test net and we know that we're going to get

Citizen Cosmos:  
Okay.

Isaac Zarb:  
a good delegation. Either we have a good delegation, like we know like there's this chain coming up and we have a delegator who has a good position in that. There are some chains which we still join because they're common good chains. So we want to contribute. So we do run these common good chains. Mostly...

Citizen Cosmos:  
What do you call a common good chain? Sorry. What's a common good chain? Example. Can you?

Isaac Zarb:  
For example, like a liquid staking protocol, like

Citizen Cosmos:  
Okay.

Isaac Zarb:  
Stride, for example. And

Citizen Cosmos:  
I understand what you mean.

Isaac Zarb:  
the Cosmos Hub, for example, like you need to run the Cosmos. I think, am I still here? Yeah, my

Citizen Cosmos:  
Yes,

Isaac Zarb:  
video.

Citizen Cosmos:  
yes,

Isaac Zarb:  
Yeah.

Citizen Cosmos:  
sorry, too. No, no, the connection is good. Sorry, I wanted to understand what you mean by public good chain. But you were talking about choosing a criteria of choosing a chain. Sorry. Yeah.

Isaac Zarb:  
Okay, so now when we join chains, like we want to make sure that we'll not be at the bottom of the set and we have to keep worrying about staying in the set. And so we try to work with the team before to understand what we can offer them, what we can bring to the table to help them out. And we think of it as a partnership, like a win-win for both of us. We validate on

Citizen Cosmos:  
Yes.

Isaac Zarb:  
the chain. We help them bring decentralization by not being on the cloud because it is a problem. cloud providers, like we've seen like on Solana, for example, a lot of people were running on Hetzner because it was quite cheap to run on Hetzner. And then one fine day, Hetzner decided to kick out like 20% of the Solana validators. So I think we offer a peace of mind that we're running out of our own data centers and we'll make sure that the data centers we're in have no cloud presence. So the... the co-located data centers we have do not offer cloud services. So if there is a cloud outage, we'll still be producing blocks. I

Citizen Cosmos:  
What about?

Isaac Zarb:  
think that's it.

Citizen Cosmos:  
No, that makes sense. Makes perfect sense. Well, what about the goal? And when I say the goal, this is kind of sometimes confusing for, for not confusing, but it's interpreted very differently. And what I mean by that is I'm going to give you personal example of what, for example, we don't do. And I think that would help you to answer as. precisely is possible to the question that I'm trying to direct you to. So for example, today Citizen Cosmos as a validator, we've been offered, we have been stopped on these offers because we refuse them constantly. But a lot of the times we've been offered to validate certain networks. And a lot of them are not something that aligns with the values of the projects. and doesn't correlate. So for example, when somebody comes to me and says, Hey, we're launching a new Dex, for example, I don't know. So nothing comes to mind right now. Sorry. Let's say Astral port or whatever. I'm making this up. And somebody brings this to me, somebody from the team. And I'm like, well, no, because this doesn't go with the way we want to build, you know, decentralization or blockchain or whatever it is we believe in. So what about your goal? Where is like, especially validating so many networks, do you, does Simply Staking have something like that? Or Simply Staking just wants to be the best and the most reliable staking provider and that's it. Which is also a goal, of course.

Isaac Zarb:  
Well,

Isaac Zarb:  
yeah, so best and most reliable, definitely that's a goal.

Citizen Cosmos:  
Okay.

Isaac Zarb:  
And there's a lot of good validators out there. So I wouldn't say we're the best, but we're, we, at least we aim to be among the best. Um, uh, but like there's a lot of good people out there. So I'm, you know, happy to be in this ecosystem. So, so early, um, we do have values. Um, we, uh, How do I say this? So we definitely would not want to run anything that is considered as like not a value project or like we don't want to contribute to it definitely a scam. So if there's something like offering us higher rewards, but we don't believe in their vision or we think that it's a scam, we'll definitely not put our name on that and not contribute to

Citizen Cosmos:  
Mm-hmm.

Isaac Zarb:  
that. I can't say like there's something. pinpoint like there is this thing that definitely we will not run. It's like we have a committee where we discuss the new changes that are coming up and we all vote if we think we should vote, join. But quality of the team is one thing that we look at. If they have any history with launching projects and then abandoning them. There's a lot of criteria which we look at and the chances of success of the project.

Citizen Cosmos:  
What about, you know, more... more, I don't know what word to pick here to describe it, but I guess validators can be divided according to whoever describes validators into different separate groups. Somebody says validator is purely technical entity. Somebody says it's a social entity, a business entity, a mixture of all those entities. And I guess governance is one of those topics, which is very Well, it has been going shaky from, you know, especially if you've been like yourself, you know, you've been a masternodes, you know, you've seen depots, you've seen witnesses, you've probably been involved in places like EOS, you know, at least maybe not as a validator, but probably, I don't know if you are, but at least you've definitely seen that scene and the difference of all of those things. I'm curious, what's the opinion of yourself, of Isaac and Simply Staking when it comes to what do validators or what should validators do? when it comes to governance, should they participate? Should they stay, I don't know, abstained or whatever? What's your opinion here?

Isaac Zarb:  
Okay. So this is my personal opinion. I think

Citizen Cosmos:  
Please.

Isaac Zarb:  
that especially on big chains, validators should be KYC'd because, or at least like top, there should be a process to KYC or validator. And people have the option to be anon or not. But if these validators are providing security for so much value, you

Citizen Cosmos:  
Mm-hmm.

Isaac Zarb:  
want to know who's running these,

Citizen Cosmos:  
Mm-hmm.

Isaac Zarb:  
you know, these services. Now if. If people want to delegate to a non-validator, they're free to do so. But I think

Citizen Cosmos:  
Mm-hmm.

Isaac Zarb:  
there should be some way of KYCing a validator and having the top validators known. That's one thing. Around governance, I think we've lacked on that in the past. We were very busy focusing on the tech and we did not do a lot of community outreach. We don't... have a good marketing yet. However, I'm very proud of the work Damian and the rest of the team are doing with governance. We've actually put up some proposals lately. And I think that all validators should vote for that's something that we always try to do. And I think validators should be active in governance, especially on things that relate to the network and security of the network. Obviously, maybe not all validators can contribute to tokenomics or the future of a project, because maybe the validator's remit is providing security and running the network. However, they definitely should be involved. I don't like the fact that the exchanges don't vote on governance. However, their excuse is that there's regulators that they might be held liable if they... if they vote. So it's all clear there. So I can understand that nobody wants the SCC knocking down their door. So I understand why they don't vote, but it would be nice to see more participation from validators.

Citizen Cosmos:  
Yet they're okay with taking the risks and running the validator and earning the commission rates.

Isaac Zarb:  
Yeah.

Isaac Zarb:  
That's true.

Citizen Cosmos:  
 They're already taking the risks. No, but okay, without sticking to going into my own opinions, though I have to ask a question from what you reflected on before. I'm going to say story and then you tell me what's your opinion on that. So I think it was back in 2000, wasn't that far away ago it was 2019 or maybe 2020, I believe maybe. And I don't remember what was the context. But the story was that somebody sent me some story from I don't forget, I don't remember where it was, whether it was European or American story, where a provider who was collecting KYC data for, well, they were not doing the KYC. They were just collecting, storing some data, then sending it. There was some cycle of events that led basically to the loss of all the data. And that provider, it was nothing to do with blockchain. It was to do with quite a big bank. And basically, they lost the amount of hundreds of thousands of people of data.

Isaac Zarb:  
or something.

Citizen Cosmos:  
During the same time, we had a conversation of what, imagine something that happens in blockchain where whoever is doing the KYC, let's say for the validators, and there is only about 100 or 150 validators on a given network, they lose all the data. And basically with it, all the private information of where these people live. Who is their daughter's name? What is the dog's name? I don't know, whatever else that KYC information might have. Of course, that's if in open format and considering that if banks lose it, damn it, their security is like, you know, a bit different from at least, so does one hope, to the security of this guy. So do you not think that could potentially, KYC invalidators could potentially create actually a big security risk in terms of... knowing where they are and who they are.

Isaac Zarb:  
I mean,

Isaac Zarb:  
most validators would all have blockchain account, exchange accounts. So I've done so many KYCs.

Citizen Cosmos:  
Of course.

Isaac Zarb:  
Like I mean, for every project, if you're going to get tokens, you have to do KYC. So wouldn't it be better if there was like a blockchain where you could do one KYC and then have zero knowledge proofs across anybody who needs your data just has to... Is this guy valid? Is this guy a PEP? Is this guy a criminal? Is this... and you don't get the data, but you get a yes, like, you know, using ZKs. I think

Citizen Cosmos:  
Mm-hmm.

Isaac Zarb:  
that's the system that we have to go for. It's not that we shouldn't use the system because the way the system currently is, it's much worse because I have to do the same KYC over and over again with the same provider most of the time. Like all the exchanges probably use one or two providers. and you're sending them the same data over and over again. It would be much easier if there was a central place where you could do this. And once you update your data, everybody gets the updated data. This, like I recently moved house and I had to go to all the banks and update my data and then go to the transport, you know, to the DMV and update my license there, update my ID card. So I really think like blockchain could... solve this pain point for a lot of human beings. Having an NFT as your ID card or your passport would probably solve most of these things.


Isaac Zarb:  
I don't think adding verification, because you're still doing, all the validators are still doing the KYC across multiple providers, so I don't think it would weaken security.

Citizen Cosmos:  
I think I think it's a lot of the time that the thought crosses the mind when you're in an office of a lawyer, especially or an accountant. Would have been useful if that was done when I was five and not

Isaac Zarb:  
Yeah.

Citizen Cosmos:  
every now and again. What about the topic of, you know, I want to understand again, as somebody who has such a wide not range of networks, but I guess that Having to validate such a wide range of networks, I know personally, you kind of have to understand what's going on there, which means it gives you a better perspective of the whole space in general. Well, at least so I can, I understand it like that. I envision it that you would. So my question is, what's your vision on, you know, on tribalism? And I mean, to me, it's a very dear topic. tribalism in a bad way, not in a good way. I don't like it. But I'm curious, what's your opinion considering you validate so many networks and you're definitely probably aware of something that's going on in Ethereum, something in Cosmos, something in Polkadot, something in Solana, something there. How do you see that all of those things coming together or never coming together, stay in separate silos? What's your opinion?

Isaac Zarb:  
So... Yeah, like most chains are like separate ecosystems and there's very little interconnectivity between them and there are like these tribal like, no I'm building on Polkadot, I'm better or I'm building on Cosmos or I'm building on ETH. So I think most chains have their pros and cons like building on ETH, you have high gas fees so then you'd end up running on a layer 2. Building on Cosmos, maybe you have the IBC protocol which allows you to connect to many chains. However, I still think the shared security there is not done right. Building on Polkadot, then the blockchain community is still not at the level of the IBC. So I see them as multiple programming languages pretty much like you have Java, you have NET, you have PHP, you have Python, you have Ruby. And they all have something Great. But they all have their own cumbersome things to learn. Yeah, I think the most value right now is on Ethereum. I think it's the heart of blockchain at the moment.

Citizen Cosmos:  
for sure, for sure,

Isaac Zarb:  
I mean, DeFi

Citizen Cosmos:  
it is,

Isaac Zarb:  
definitely

Citizen Cosmos:  
it is, it is,

Isaac Zarb:  
is on Ethereum.

Citizen Cosmos:  
it is definitely, I agree.

Isaac Zarb:  
I don't know how much space for different ecosystems there is, like at some point, how many programming languages can you have? But if we look at the world, like we have Windows, we have Mac OS, we have Linux, and they all survive and they all thrive. So there is space for more than one blockchain, like you have Bitcoin that now has Ordinals and it's like a good store of value and like this legacy thing but everybody trusts it because it's existed for so long. You have Ethereum, which has proven some use cases. But I would like to see more use cases rather than just finance and DeFi. NFTs were a good idea, but they were used as art. Maybe they can be used as tickets or, you know, there's probably a better use case to get them into the hands of everyone. I think we still haven't figured out the thing that's going to get mass adoption. Like with the internet back in the day, everybody, you know, the techies were playing on the internet, like messaging and stuff. But it's not until we gave the public the ability to shop online that we, you know, the internet became widespread. You know, email helped that. So I don't think there is... We went to finance immediately now on the internet finance came later when people trusted the internet and on blockchain we went we skipped the Validity and the onboarding of people and we just said okay, let's get your money here So people obviously are scared like it's very difficult to use blockchain Like I I've you know interacted with all the wallets and sometimes when I need to swap between the layer to It's like confusing sometimes you have to use Metamask and then you get another network in. What the hell am I doing? Am I sending the money to the wrong... And then like I have to use... Now I have to use Kepler and then I have to use Cosmos Station and then I have to jump in and... Oh my God, like why do I need so many wallets and so many ledgers and so many... So that's one thing that makes the user experience really hard. I think like having... universal currency and a wallet where you don't need, if I need to do a transaction on 10 chains, I don't need 10 tokens. So if I can have a USDT or USDC and then the wallet can trade it to whatever it needs rather than I have to trade it, that might make life much easier. Because imagine like on the internet or like on your phone, you want to call the US. You don't need to have like US currency in your phone to be able to make the call in the US. You have a connection with one provider and then they deal with passing through all the countries. Imagine if to route a call you need to have Italian currency in this wallet and then a UK currency in this wallet to pass through all the channels. So I think that's one of the limiting factors we have right now. the infrastructure is still a bit cumbersome to use.

Citizen Cosmos:  
I think it's a good example you gave, especially with when you think about telephone code numbers, you know, and we all still put in, you know, the plus zero one or plus four or four or so when we ring. And it's not that long ago that the currency thing actually stopped because I mean, it's not, it wasn't that long ago when I remember buying, well, okay, not yesterday, of course, but I'm a bit older probably than I look, but I do remember buying, you know, phone cards and then and ringing. top up the phone card and going to ring another country. And I still remember that it wasn't that long ago. So

Isaac Zarb:  
Yeah. That was the VOIP to get cheaper

Citizen Cosmos:  
yes,

Isaac Zarb:  
calls.

Citizen Cosmos:  
foips

Isaac Zarb:  
Yeah.

Citizen Cosmos:  
voips. Yeah, it was a big, big jump, big jump, I think in progress from

Isaac Zarb:  
Yeah, it

Citizen Cosmos:  
how

Isaac Zarb:  
made

Citizen Cosmos:  
we

Isaac Zarb:  
it affordable to call outside of the country because back then it was so expensive. But it was, even though it was expensive, you only had to have one contract with your local provider. And then

Citizen Cosmos:  
Yes.

Isaac Zarb:  
they took care of everything with blockchain. If you need to move from Cosmos to Ethereum, you need to have multiple tokens, multiple wallets. You know, we have to bridge the, yes, it's much harder. So I think that's what we lack. The it's like with the internet. If you want to browse. bbc.co.uk, you don't need a subscription with the British provider where the website is running. It's, you know, your internet provider takes care of routing the traffic.


Isaac Zarb:  
So I think that will unite the tribes. Like, so like having better connectivity will unite the tribes as you were talking. And then it would be easier for the tribes to do business with one another or to trade.

Citizen Cosmos:  
hopefully, hopefully. I think that's a very, not big vision, but sort of hopeful vision in a sense sometimes. But I definitely, I think that like you described, you know, you described the internet epoch, and there was a lot of similarities between that. And I think we're slowly kind of, you know, uh moving into the same on the same paths in terms of development and um yeah so hopefully we will also uh get to the point of like you described you know where people don't think any more of okay maybe I need to think of what code I need to put in whether plus 44 is Solana and plus 45 is uh is tender mint but uh okay apart from that let's go Isaac, in terms of simply staking, is there anything else you would like to share that I didn't ask you?

Isaac Zarb:  
As I mentioned before, we're launching our own blockchain called Entry Point.

Citizen Cosmos:  
Okay.

Isaac Zarb:  
We're going to test that pretty soon, like in September.

Citizen Cosmos:  
Is there any info anyone can find on that?

Isaac Zarb:  
Yeah,

Citizen Cosmos:  
Anywhere?

Isaac Zarb:  
the URL is entrypoint.zone.

Citizen Cosmos:  
Okay?

Isaac Zarb:  
And you could, there's the website, there's the white paper, there's a bunch of documentation. And soon we'll be having a testnet. We'll probably be looking for validators to help us validate. We have a discussion on the Cosmos Forum ongoing to see if we're joining ICS and... we had some controversy because we asked for some funding from the hub and not everybody was keen on that. But it seems like sentiment has changed and like people understand what we're trying to do. We're trying to change the way blockchains are funded and the way that traditionally most blockchains would start off with dishing out a lot of their token to help pay for validation. And then you end up with a lot of validators dumping your token and that causes a problem for your token. So we were trying to find different ways on how to do this. It's an interesting discussion. I look forward to finalizing it and see where we get to that.

Citizen Cosmos:  
So yeah, definitely guys, check out the Cosmos forum. There is a big thread on that there. And of course, there's gonna be a couple of links through the description, because most likely you're watching the recording of this. Do join the discussion. And of course, follow entrypoint.zone, right? And for all other information. And I'm sure you can find the Simply Staking validator on most networks if you cannot. You have to type in Simply Staking. There we go. And you'll find the guys. Isaac, I thank you very, very much for your time and your answers.

Isaac Zarb:  
Thank

Citizen Cosmos:  
And

Isaac Zarb:  
you.

Citizen Cosmos:  
hopefully we get to chat again in the future.

Isaac Zarb:  
I'd love that. Thank you very much.

Citizen Cosmos:  
Thank you. Please don't hang up just a second. I'm just going to stop the stream and thank you everybody for listening.


-----------------------------------------------------------------------------------------------------------------------------------------------------------

If you would like to support our mission in creating educational content and aligning the goals of different communities, please stake with us [here](https://www.citizencosmos.space/staking): 

- [EVMOS](https://wallet.keplr.app/chains/evmos?modal=validator&chain=evmos_9001-2&validator_address=evmosvaloper1mtwvpdd57gpkyejd566s24afr9zm5ryq8gwpvj) 
- [ATOM](https://wallet.keplr.app/chains/cosmos-hub?modal=validator&chain=cosmoshub-4&validator_address=cosmosvaloper1e859xaue4k2jzqw20cv6l7p3tmc378pc3k8g2u) 
- [BOOT](https://wallet.keplr.app/chains/bostrom?modal=validator&chain=bostrom&validator_address=bostromvaloper1f7nx65pmayfenpfwzwaamwas4ygmvalqj6dz5r)
- [FLIX](https://wallet.keplr.app/chains/omniflix?modal=validator&chain=omniflixhub-1&validator_address=omniflixvaloper1wnpak7sfawsfv9c8vqe7naxfa4g99lv7djfn8n)
- [BCNA](https://wallet.bitcanna.io/validators/bcnavaloper1ngt4atd3qlgcwfv7fkjdjxhz7k0vl2rejrvzye)
- [LIKE](https://dao.like.co/validators/likevaloper136r5phdpc02gmtmyampl9qkv0mdq385xxsaadu)

Join our [community](https://discord.gg/kJaG3EucCX), to build a future where communication is decentralized. May the code be with you!

