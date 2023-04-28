+++
title = "Episode #86 Zarko Milosevic. Transcript"
date = 2023-04-28

[taxonomies]
tags = ["podcast", "transcript"]
+++

Episode link:  
https://www.citizencosmos.space/informal

Episode name:  
Zarko Milosevic, verification tools, innovation & Tendermint.

In this episode, Citizen Cosmos talks to Zarko Milosevic, CTO of Informal Systems. In this episode, they explore how an organization that expands can manage to stick to their core founding values and have it drive growth. This episode is also packed full of Alpha and hints at more to come. Zarko is passionate about all the new potential developments and unpacks details of Informal becoming the stewards of consensus engine, Tendermint Core.

--------------------------------------------------------------------------------------------------------

Citizen Cosmos  
Good Spacetime yall. In this episode of the Citizen Cosmos Podcast, I speak to Zarco Milosevic, CTO at Informal Systems, core developer of everything Cosmos. Zarco makes two big announcements, revealing Quint, a TLA+ inspired specification language for blockchain protocols and he updates the news on Informal’s work on the Tendermint code base. We will also discuss Informal’s vision, governance in Cosmos, Verification tools and their importance, advanced indexing and scalability issues.

Zarko  
It’s like the programming language but with some nice superpowers.

<!-- more -->

Citizen Cosmos  
I’m gonna tell you guys a secret right away, listen to this episode.

Zarko  
That’s one of the things we have exclusive announcement to make here in this episode.

Zarko  
It was clear for us from the beginning, it doesn’t make sense to separate the two, they need to coexist with each other and be in love.

Citizen Cosmos  
I hope that the new consensus engine let’s call it like that can handle more drama per second.
Before we rocket off into today’s podcast, here is a round up of the latest news from the sponsor for this episode, Cyber. Cyber Congress DAO has been primarily working on improving the Bostrom hub, This work includes, the testing of the contracts, new UI features, verification tools for on chain governance and polishing the Bostrom DEX. Adding mass protection, new web front and bringing indexing of chain swaps. To try Bostrom, head now to over sig dot ai.

Citizen Cosmos  
Hi everybody welcome to your new episode of the Citizen Cosmos podcast today I have back with me because the last time we recorded was actually two years ago, Zarko the CTO of Informal Systems and I’m going to tell you guys a secret straight away, listen to this episode this is going to be a really good one. So Zarko, hi. Welcome back.

Zarko  
Yeah, hi. No pressure so

Citizen Cosmos  
No pressure, no pressure, I’m sorry.

Zarko  
Okay no pressure. Yeah I’m really happy to be here like has been quite some time and a lot of things has happened in mean time and
 I’m really happy to like chat with you about about this and whatever…

Citizen Cosmos  
 whatever else comes. But before we go into it, Zarko first things first, considering that it's been a while and we have new listeners, I hope, would do you mind reintroducing yourself a little bit more than just the CTO of Informal and tell me and everybody else about what you're working on and what is your role a little bit
 more at Informal and everything else you want to add to that.

Zarko  
 Ah so I’m still Zarko Milosevic,  that hasn't changed.  Last time we talked I think I was still researcher, so my kind of technical background is in this with the systems I did my PHD thesis EPFL in Switzerland. Actually in the area of pesantinfoltor and consensus protocols, this was before before Cosmos and like I’m not sure we can say
 really before crypto but like clearly it was before consensus was used in the production system at this scale and so I’m really happy that that I was sort of like giving a chance to have some follow up on that research in a kind of real world. So, my current role at Informal is CTO formal, I’m overseeing technical work at Informal. Informal is doing like lot of stuff so I’m more trying to catch up with all the stuff we are doing but still in Cosmos still trying to help with public goods infrastructure, still trying to improve the
 security of the systems we build and rely on. Trying also to help with Informal on the business side, creating a sustainable business and also offering interesting services and building cool products for other people.

Citizen Cosmos  
 You make it sound so simple, I like it. so before we go into the cool stuff, I guess, just some general chitchat, considering that Informal works a lot on as far as I know on work ethics and work structures. I’m curious whether Informal is still bound to all the same end of the year trouble as all the other projects in the world are, because I know we tried to meet and you were saying, no there was loads of things end of the year and I was like but you guys have some cool structures, I know that. To be honest the question is more about,  how is that thing progressing? I know we talked about it with you, we talked about it with Bucky, we talked about it with Yelena, about that you guys trying to work a lot in that direction and I know it's not your topic of course but in two words is that something that touches your work?  Is that something
 influences you?

Zarko  
Yeah, I was kind of like involved, so Informal has grown like pretty significantly
 in the course of last year and since we discussed last time.  So we around sixty people now and there have been also some change in terms of like responsibility of Informal
 in Cosmos. So since last year we took the responsibility of being steward for Tendermint Core repository and the and also for Cosmos hub, in addition to the work we're doing on on IBC, and also like what has happened in the last quarter which sort of like made the end of the year a bit like terrible end, was creation of like TAB, technical advisory board at ICF, where I’m member and the ICF is trying to put more structure in the in the way the work on the core infrastructure of public goods is being organized and funded and so this was sort of like a new structure and as Informal is the biggest contributor to the Cosmos public good projects, we were of course like affected by this change and so it
 just took some time to like put things in place. Apart from this like we are still, how to say, we are cooperative, we are still focusing on our members and delivering value to them and also like trying to trying to play ethically nice to people around us. 
We're also trying to build in parallel with work on public goods. We are trying to build as I said like sustainable business and there are several business verticals within Informal,  just like taking care of like this this different concerns is challenging and that's why like the end of the year we were  summing up and making plans and budgets for the next year is always a bit challenging so…

Citizen Cosmos  
I’m just checking that you're still human you know this this is all.
 it was just like, na, joking.

Zarko  
No, we are.  We suffer we cry like the rest of ah… yeah absolutely,


 Citizen Cosmos  
 Last and considering what you just mentioned about the creation of a technical board where you part of it, you mentioned some business verticals and last time I think, if I’m not mistaken and I'd be honest I did have a look of course. I couldn't remember everything, but we chatted a lot at the end about personal values the alignment of personal values and company goals and I’m curious whether the changes that have been well to your own position and I know  that it's just a title, but at the end of the day I think for somebody who does the work that you do, those things could be important.  Well at least it is like that for me and you know you mentioned a lot of things and I’m still curious whether until today those alignments with the values  that you have and the goals that Informal have are still in the same place and whether you feel that what you're doing corresponds to those values?

Zarko  
I haven't really like checked what we talked last time so l can just say then from where I stand right now, values are still there. In terms of like the company mission and vision, I think  like that we manage to like even solidify things even more so we are, I would say even more ambitious. So, like the current way we phrase what you're doing at Informal is trying to transform the three major pillar of society. If you talk recently with Bucky, maybe he said this, but like it's money, software, and organizations. And so this is also related with like the business verticals we are doing . So there is like a
 project on collaborative finance which we are boot strapping at Informal so that fits into the money side. On the software side we probably talked last time about like the
 work we are doing on the formal verification tooling and in general like the security tooling and improvements. 
That’s related with like the software. We believe that the way we develop critical distributed systems is suboptimal and we believe that we have something to say on that front and on the work side excite like we are coop and we are trying to innovate like in house how we govern organizations and also like are trying to participate in the hub governance in general, in Cosmos governess um and trying to sort of like lead by example there. There is the particular the methodology we're using for collaboration called workflow and it's on our website, some people might be reading about this. That's just one element of it, but that sort of the plan. So, like so in terms of the core values I hope that this sounds like similar to what we discussed last time but maybe just like packages in a more structure way.

Citizen Cosmos  
 Last time you were talking about Lambos, no, I’m joking.  Of course not, I don't know for me, I’m going to be honest with you. because the reason I’m asking and it was a personal thing because for me for example even though I still work a lot with the same projects I kind like separated myself from a few projects,  because over the course of two years my values and their goals kind of separated so I was curious whether you're still there and you are and I’m really glad to hear that and you mentioned straight away formal verifications and this was a big big topic we talked about, insurance out its formal verifications and you mentioned on Twitter, verification tools and  I would be very curious to hear and I’m sure everybody else who's listening would be very curious to hear about what are what type of tooling in that direction you've been working on and what is the progress that has been happening in those years and what new things there are.

Zarko  
So that's that's one of the things which we have sort of exclusive announcement to make here, in this episode. So this year we were like the verification tools at Informal were working hard and at the end of the  year, I think in the last days of last year we like open sourced released verification specification language called Quint, which is like one element of the tool chain we were building last years, but Quint is important because the challenges of verification tools in our view and our experience are mostly on like adoption and developer friendliness side of thing. We were lucky to have like some really amazing people and experts in verification formificational fortificational distributed systems and they were able to demonstrate over years that they can bring value with their methodologies and tools but we were not really able to scale that beyond like the small group of people with like that formal training and this is in our view also like the challenge with like most the existing tools out there. There is like a trend in the last year of like trying to like address this issue and there are several other projects which are sort of having like very similar objectives. So if you listen to the the intro talk of like several really strong you know verification groups, or like companies, the first five, ten minutes are almost the same. What differ is the way different teams are approaching these challenges.
It's always about like making like tools more developer friendly, making it
 more efficient, making it more more flexible, making it more like kind of domain specific
 and so what essentially we have to offer on that front is Quint which is a new specification language. It is inspired by TLA+, so like TLA+ was like our starting point and like we have been developing for years model checker called Apalache, which
 is involved model checker for TLA+ and have been using it like in our projects successfully but the challenge with TLA+ was that it was like having very
 steep the learning curve and it was like very different like experience working with like
 TLA+ compared to like modern programming languages and Quint is trying to address
 this. So Quint has like syntax which is like very similar to modern programming languages like Scala or Rust. It has CLI so inter active repel which you can use to like explore the specification of the protocol it can be executed so it's like the programming language but with some kind of nice super powers. It has a built in simulator and it is integrated to the Apalache Model Checker and so you have now possibility to fully type checked. So it has like vs code plug in also so it's really like the feeling of working with Quint when you design protocol is like you are writing your program you have all nice features developer are expecting and in addition to this then you can choose also like how far you want to go in terms of like guarantees. You can track the variance and properties using built in simulator which is super-fast but like does not have the strong
 guarantees. There is a second mode which is Simulation using Apalache, which is a
 bit solid in terms of coverage and a bit faster and then the full model checking its kind of
 the last element and then also like the challenge with TLA+ was that the feedback loop
 was pretty long and now you can sort of like use the tool in real time using like simulation mode and Apalache simulation mode and then you can leave the full model checking maybe to run as part of continuous integration and so that's sort of like kind of one of the main value proposition for Quint. There are some other stuff but maybe we can, we can pause here. There are a few other stuff we are developingin the toolchain but maybe we can so stop here so you , I give you a chance to ask questions about Quint.

Citizen Cosmos  
 I am making notes of course as you speak but thank you, that is something I was going to ask for. My first question was whether Quint is already released and is it on GitHub already. Is it, can you go and use it already.

Zarko  
 yes exactly

Citizen Cosmos   
 Okay

Zarko  
 Informal systems on GitHub, slash Quint and
 it's already there we are working on documentation, tutorials. And like that's the main focus. There is already something there so I hope that like people are already able to go there, download and try the stuff there, like a set of examples but like in the Q1 the plan is to improve the onboarding material and we are also working with some core Cosmos teams to sort of like try to replace the existing specifications with Quint and also like then to try to connect this with like the model based testing tools were also developing parallel. So the idea here is like, if you look at for example at Tendermint or IBS specs, normally the way we were like writing specs is like there is some English description to give like a reader feeling of like what the protocol is all about and we were then normally trying to capture, to write like some you know, in good specks we write like properties which hold and we write like a pseudocode to like give reader or an
 engineer who is like trying to implement a protocol idea how like this should work
 like what are the basic mechanics. So I always have like these two elements like
 the very special cole and like the pseudocode which sort of like shows how things should work. 
What with Quint want we want to do is like we want to replace this and this is just like English, so the pseudocode code is something which cannot be sanity checked, it cannot be type checked, it cannot be executed and it gets it normally gets like very fast out of date. No matter how you know developers are eager to keep it up to date after there is a reference implementation, implementation becomes source of truth ah and this is particularly challenging when we are starting to have like implementation in multiple languages or framework and also for onboarding it's always like challenging because like give engineer something and then we say like but you know implementation is slightly different, So what we want to do to instead is to try and replace the pseudocode code which is essentially like  English with Quint as our hypothesis here is that like the learning curve for Quint will be like very low as that's something people are get used to and so writing like the logic in Quint should be like similar compared to that pseudo code, but then you have like a full tooling support on top of this.

 So you can make sure that it's indeed like works in very unserple. We also captured in Quint so you can track that you're your spec is sane like you know there are there are no like issues with it and then we'd like the other tooling we were developing you can
 generate like what we call model base tests which are essentially scenarios which are trying to exercise the core in variants and they are like expressed in the abstract form
 in a form of like traces there is like we have like the format formal, cole, informal ITF I think which is like essentially Json and that's something then different implementations can use almost as a set of like you know based tests protocols should implement. And it's language agnostic and so like if you have implementation of IBC in  Agora Rust or whatever then you can have like some basic set of like tests which should pass so you can be considered implementing at least like a bare medium of implementing protocol.

Citizen Cosmos   
 I guess so like one thing it comes to mind and it's kind of silly but
 I cannot not help to say that because it just springs to mind and I mean over the past years you know working not just with block chains but generally with anything that requires a certain level of verifiability or auditability and I don't know if I’m pronouncing those words correctly, never mind. There is always kind of I don't know like developers don't like to be verified. Developers like to think a lot of developers they hate that, from my experience like oh I’m going to be using that, that's going
 to verify me no way I’m going to be using what I know. Is that an obstacle that you guys have been like thinking about keeping in the back of the head because I know that this is amazing right, but like maybe you know some people just like oh I don't need that you know, I know what I’m doing you know, I  know what I’m going to be doing and I don't care about verifications.

Zarko  
 Absolutely that was really the main driver for this work, because like that was exactly what was happening with like the TLA+ and original set of tools. Just like
 everyone like need to be frank there like, people hated this and so they were not, although they were able to appreciate the values just the cost of learning and using tools was so high that they were not able and also maintaining it after. It's a very valid concern and that's something we're trying to address so,  the way how we are currently working on like adoption at informal is that informal is offering security audit to our partnership services. We are currently primarily focusing on Cosmos and exclusively working on Cosmos project at the moment to help them you know be more secure and correct and there we have like the model we like most is the partnership model which is like a long term collaboration where we have like a dedicated bandwidth to work with the core teams trying to be almost like you know embedded in a core teams and
 then trying to like understand and listen their needs and then bring like our expertise and knowledge to address the real concern and sort. That’s like a super helpful
 like validation point for us and also like a playground to see like what works,
 what doesn't work that's just sort of like the primer adoption vehicle right now.
We haven't liked tried Quint yet. With TLA+ we were having like sort of this
 concern but with TLA+ we realized this pretty fast and then this was more
 something like we were writing almost like as a kind of back end implementation but what people were seeing was  of like this non trivial traces they can run against their code base to sort see there might be issues there. In almost all projects we try to use this methodology, we were able to find like nontrivial, I would say like critical issues. The depth of the scenarios,  that sort of what is interesting goes up to like twenty and so that's something which is like I think, it's sort of hard to argue against because it's very hard for developer to manually create test scenarios which are kind of so deep, so that's really like the power of tools or for computer assisting us thinking about security where you can declaratively say like what should hold and you allow tools we explore the space. As a developer we are having like, we are biased and so we normally are having like picture of the world and normally when we test stuff, we are how to say we are constrained you know you're always like are making some assumptions implicitly. With these tools you cannot make implicit assumptions, that’s the beauty you know
 it forces you to say even obvious things like you know, I should always be able to reach the state. If you say like declaratively with Quint or TLA+, I should always reach the state then the Apalache in like a bunch of test scenarios which you can run against your
 code to see like even like sometimes we will check your chase like you know you cannot because this is in this case we're not able to reach. This is counter example, and so that's the beauty of the stuff. Even like you know no matter how confident we are in domain and how confident we are in a code base it is very easy considering you know complexity or just like we are humans. As you said at the beginning to make mistakes
 and these tools are here not to replace us but to actually assist people in like hopefully doing their job with more fun and like faster and in more than you know safe and correct way.

Citizen Cosmos  
 Before we moved to the other stuff that you wanted to mention, I do have one more question but before even that I’m just going to say something that I would never say two years ago but this is compliment to all the listeners. Really I know there is developing teams that develop on top of Cosmos that listen to this podcast, I know that so that would be a call to action guys. If you out there still working on a
 project, go to Informal talk with the guys, it's not very hard to find them. If you’re struggling and go to the description of the episode and because I know for sure I know it kind of sounds big headed but I have had teams before coming to me and say, we listened to this and then decided to, for example Stride is one. I’m really proud of that you know, they told me about that so if there are other teams like that, guys go and collaborate, because this will definitely help not just you but think the whole
 echo system. One last question about Quint before we move on to the other stuff.
 Can Quint corporate with CosmWam or…


Zarko  
 Yeah absolutely. So the Quint is like language agnostic and so we on purpose there was a lot of push to do the stuff which are like language specific.  Like that's sort of like the signal we're getting like very consistently from our developers. They are writing tests in the same programming language they write they write the system and like ideally you will just add some kind of library or support there.  However, like the problem with that approach is that it's really hard to do the stuff like on the model checking side.  We need something more scope than constraint and also like if you
 think in general about like the semantics, capturing semantics at that low level is probably not like the best idea. But, like we are working and that's something
 I also wanted to mention that like we don't want like to have specification even
 if they're executable and implementation isolated from each other. That's something like which was our, it was clear for us like from the beginning that doesn't make sense to separate the two they need to like co-exist with each other and be in love
 and be maintained in sync and that's why like we were having like a problem track. We like model-based testing tools and this is also something we also like made a release towards the end of the last year, the model based testing tool call Atom Craft and Atom Craft, I don't know maybe you heard for it. 
So Atom Craft essentially allows you to like take the abstract test scenario, which is generated from the spec using Apalache and then you have like a way to spawn like a test net and then execute the scenarios against the real chain code either over RPC or CLI and that's something which is currently the way we are interfacing with the code,  but that's the level at which we believe it's important to like integrate in the language specific or framer specific stuff and sort of that's where we hope to invest and work with our teams who has interest to like collaborate with us on this to make like the language or framework specific integration points and CosmWasm is one of the
 frameworks which is on that list so we are we're doing something internally like
 atom craft for CosmWasm, there is already like a version we were trying to trying to
 improve the stuff and in show case it on example smart contract
 which actually provided to us by Confio so it should be like a good representative.

Citizen Cosmos  
 They know their smart contract hopefully. Sorry, you mentioned that there are some more stuff that you guys have been working on and that you wanted to to announce, I would be happy to hear that.

Zarko   
So the second I would say the big things is that during the course of the of the last year Informal has become steward of the consensus engine, Tendermint Core and i before Informal it was taken care by IG for a period of time and I am taking this opportunity to thank everyone who was like working hard on the project and so since 2019 or 2020 when Informal was created, we were always like around like the consensus engine. We were like involved in some protocol design work. We were
 trying to like also contribute on implementation side sporadically, but we're not really
 deeply involved with project and since like last year this has changed and now we are the main steward of the project. There is a completely new team and I need to say it's like of course I don't know like if I can be objective here but it's really very very strong team. Have like a very strong like leadership in that team it is really like a group of people who are like super motivated, have like a very clear vision how to evolve the project into like really you know like state-of-the-art consensus engine. 
A lot of people in that group have like formal training in state machine application and so they know the academic side they also have like very strong industrial and engineering experience. So it's really amazing mix of people and so sort of like we are we're transitioning into a new generation of the consensus engine. The world has changed so the project was like existing for years but like fundamentally there haven't been like a major changes in the in the code base and you also like consensus protocol if you want since creation, so like between 2016 and 2022,  essentially we can say that it was more in a kind of maintenance mode. There was like continues try to improve
 the stability and performance but there was no like major really like change in
 the way what the framework offers and last year after like a long time and
 long period of research there is like there is like one big change it's like
 is probably like people know in Tendermint there is application block chain interface which separates consensus engine from the application and this is something which was like from the beginning like very appealing feature of the framework as it allows like applications to be written in different languages and not sort of like delegate the like low level implementation details to consensus engine and last year after like as I said like long time of research and development, we have finally reached the point that there
 is a new version of ABCI,  which is called ABCI++ and which essentially change pretty
 significantly the way application and consensus engine can interact with each other and so this is like a major change the way also like application developers will be like thinking about like building block chains on top of consensus engine and it opens like a lot of new interesting use cases. 
So that's just like a first step the team wants to also address the needs of the you know like the world has changed, we have like many new projects which comes with like different needs and different requirements and what we want to offer is like more
 modular stack, which allow more experimentation. We want innovate both within a team but also allow people to innovate in a safe way on the consensus core on the like
 mem pool,  on the RPC level on the gossip level so now team is essentially having like a two major responsibility of like improving Q A processes and that was already like something I will say the major improvement in in the last release there is a very clear and I invite everyone to take a look at the Q A process in the report there is essentially very  sort of clear expectation in terms of like what the release should satisfy and will
 continue to invest like strongly in Q A, and the second thing is really cleaning up the internal interfaces so people can more easily experiment and like replace or swap like some components,  because right now we still have like plenty of forks, because it's just that's the only way for people to like change this thing, things they need. 
That’s sort of on a technical side on a more administrative side there is the Tendermint brand is owned by All In Bits and sort of like the All In Bits essentially has the different perspective on like where the consensus engine should evolve or Tendermint and how it should evolve and there is like, Jae the already was for some time maintaining Tendermint 2, so it's a different implementation, the same consensus protocol but like lightly different like how to say implementation of it and based on my discussion with Jae my feeling is that like he wants to keep the implementation more minimal so it's like
 more like a kernel which is like having like the minimal set of features and then it's like you know very solid and like secure. On our side we believe that like we need to evolve and we need to better address the needs we also want to treat IBC and cross chain
 as a more like native or first class citizen in the report and Jae decided to essentially archive the existing Tendermint correpository we're a bit forced to like to fork and re
 brand essentially what was the previously considered as Tendermint  core and that's something which we have like a new name but we are in a process of like actually
 essentially doing legal work to properly brand this and so it will be announced in the
 hopefully the following days or weeks, but that's more on a kind of administrative side.

 I want kind of you now to be positive about this and I hope that people will be excited about like this. I heard a good joke that like that you know in Cosmos everything is decentralized and full torrent and now we are having given like full torrent implementation of the consensus engine, so there would be like you know more teams working on this.  But informal and ICFR are committed to still supporting the project and you will hear about like new name and you know the team and everything we are
 preparing communication materials. Also sort of like also kind of a big announcement
 there. So like you know you should expect some really cool research coming from this
 team, innovation on the consensus core innovation on the P2P level, innovation on
 like testing and Q A. Using of formal verification tools. So yeah a lot of really exciting stuff there.

Citizen Cosmos  
 To keep up with the Cosmos jokes, I hope that the new consensus engine let's call it like that can handle more drama per second because the drama per second rate in Cosmos is known to be high. You mentioned some of the use cases, different use cases and some of ways to interact that are might be different. Can you give me a couple of examples of what you're thinking about?

Zarko  
 Sure, so like the with the existing ABCI interface the way consensus engine
 was interacting with the application was pretty much that once block is formed it is
 being like sent to the application in a serialized way and then application execute this like sequentially,  this is how like the gerministic execution was taken care of.  But like application was not having like a good way to inform what is the content of the block
 or to try to do any sort of optimization in parallel with consensus execution, so
 ABCI++ last came with like a slightly different set of API and so first it allow consensus engine to propose or what we call prepare proposal where the set transactions from the mem pool before being proposed as a candidate in consensus are being pushed to the application and application has essentially full freedom to like modify, delete, even add transaction and only then after application essentially respond, the consensus proceeds
 and this is being like proposed. 
On a reception side before participants vote for a block which is being proposed they
 also consult in a process proposal API, they also consult application and give application chance to validate transactions and then only if like there is sort of everything is fine we proceed and so the kind of trivial consequence of this is that you cannot have like a block full of crap which is currently possible as essentially the original consensus  engine care most about like just like that we are agreeing on the same thing consistently but like how you know what we put there and also like if application wants to
 re order stuff that was not really available and there was some idea to with prioritise main pool, to give some flexibility to application but we never really manage to like
 to see this as a kind of interesting and viable option in production. That sort of
 like one kind of basic example, the other one is that like instead of serially
 submitting transaction will be there's like only finalized block now as sort of like
 the API at the end of consensus execution where you essentially give a freedom to application to execute transaction potential in parallel and this is the part
 where I was saying that now it's more on developer to be careful as parallel
 execution  will still need to be deterministic, and now as also with the
 prepared proposal application will be aware of the block candidate application developer can start optimistic execution, in parallel while ordering and so this
 will as in most of the application to the best of my knowledge consensus engine is
 not both alike, this will be like super cool because you can sort of like start doing and processing stuff while consensus is progressing and before block is finalized you can
 already like essentially prepared the new state and then when you see decision then
 you can instantly finalize block.
And the last feature which is experimental future, is called vote extensions and this is essentially way for applications to piggyback on like pre commit messages which are like the last stage of voting in the Tendermint consensus. To piggy back application specific data which will then also be tracked by the application on the reception side and then only essentially if there is two third plus voting power confirming voting this data which are signed by validator then this will be passed to the next block as a sort of
 like extra data and this for example make possible to have implementation like oracles more natively implemented or like to do like threshold encryption or decryption because now you can you can do like these things natively within the consensus engine. 

Citizen Cosmos  
 As a developer you might hate my summary, but I guess it could be like called like a very in depth indexing of the data and that allows in my opinion for a lot of things, flash loans come to mind, right. Like a lot of economical like possibilities I
 think defi applications from what you said.  I’m pretty sure that it will be possible to achieve I’m not sure if it’s possible to achieve now.

Zarko  
 So here, you sort of like give application developer possibility  to get like signals
 from the consensus engine during the consensus execution and it's really like it's a lot
 of flexibilities also a lot of responsibility on application developers.

Citizen Cosmos  
 Yeah

Citizen Cosmos  
 Yes

Zarko  
But I’m sure that there would be like and this is like talking with people, with application developer, like everyone is having a different use case so it seems really like
 something needed also in a request for this change is coming from the community and
 and I’m sure that like we'll be hearing a lot of really cool use cases enabled by this change, by this new P consensus engine API.

 Just even like on a more theoretical side if you look at the the state of the art in terms of
 like state machine application. There is no really any innovation which goes in this direction like all existing like approaches are just like pretty much like you know like agreeing on something and then passing it to the applicational level and then you were having some approaches where you could sort of like maybe execute things in parallel but justreally opening the consensus box and allowing like information to flow during execution is something I’m not aware of and so I think like that how combining this with like optimistic ordering, with like parallel execution, are even like some stuff which I hope we'll see like some really cool research, like fundamental research, because like it has a potential too to change the usability and also performance of why state machine application engines.

Citizen Cosmos  
 That is fascinating, I really also have not heard. I do keep an eye of course unlike yourself in depth, but I do keep an eye on those things and try to read some papers that I understand at least in that direction but I have not really seen anyone working and I know already I can already think of teams that I can definitely go
 to and say hey guys you need to listen to this because this might be interesting for what you are building and especially all the teams that are building even like assets economical stuff but social stuff lot of the social stuff that can really like increase the scalability I think of what people are trying to achieve. I know I don't like numbers and none of us like statistics and numbers and show of things but there is one question that has been on the mind the, I guest of a lot of people who have kind of got pilled by Tendermint since the 2016 and one of them has been the amount of validators that Tendermint can handle. Has that at all is going to be influenced by all those changes or is that one of the changes or currently that is something that is still on hold?

 Zarko  
 That's actually really good question so in principle on the scalability side of the consensus engine we haven't really been making significant progress, in the previous period. There are some teams outside the core team that were sort of doing some really cool research on that front and that's one of the things we plan really to like focus
 like trying to upstream some of this cool research if possible and also
 like do internally stuff there. ABC++ on its own like should make things like more performant but in terms of like number of validators, I think we need to do more research and  like changings also at like a different levels of the stack. Right now the team is focusing on the P2P, peer to peer part of the consensus engine as this was for
 a long time the part of the code no one really understand and like everyone was afraid to touch and there was even like internal joke that whoever you know like work on this left you know abruptly. Really like are now trying to address this tech depth and to enable like to experiment like with new implementations there. 
At the level of P2P, an introduction between P2P and consensus there is almost no research existing, like I was involved in some research where we look at the crestalarm
 systems and so that was like to the best of you know my and our knowledge that was like first research or paper of that kind where you try to look at like how like gossip protocols and peer to peer protocols and consensus protocols, how they interplay because you have redundancy at both levels and it's not clear you know like what is the optimal way of composing the two and to really make like the large scale scalable instances of like these kind of consensus systems, we really need to look carefully what like we are doing at a P2P level what we do at the gossip level and what we
 do at a consensus level and then how it all interface with applications. Even existing
 implementation there are projects which we're using it with like thousands of validators with like still order of seconds latency or finality block time so I think even existing like
 system is able to like be used at a scale but you were mentioning you know this is like social use cases like that something which we are at informal like super interested in and I’m sure that you know Bucky was talking about like supporting local communities. Having used cases which are not justify for those projects the existing implementations are like probably too expensive running like the Tendermint like full node right now is like not cheap it requires like say expensive hardware to run and if you want to scale this to have like good decentralization you probably need to have like at least tens of validators and for like the small socially impactful project this might not be feasible. 
 So that's something we also need I think pay more attention on those use cases, is if you really want you know to make impact to the society we need to allow people to like
 be able to use the stuff in a secure and decentralized way but still you know with a reasonable price and that's one of the like big themes the team will be focusing this year like we want to sort of clean up the API, we want to make things more modular. Hopefully this will allow us to like significantly lower operational costs of Tendermint and also be able to like experiment with like making as I said like new APIs or supporting news cases and also making everything much more performant.

 Citizen Cosmos  
 Since we last spoke you know I think we were just starting to be a
 validator when we last speaking and since then you know we haven't grown much as
 a validator because we don't want to but because well it's more about personal values
 and about what projects I really want to support as a validator, but one of the main reasons to be honest is of course because of those values that I have and because of the amount of work, I want to put into the infrastructure I’m holding is the cost of the infrastructure. For example I remember  this other format where we do like live streams with validators to get to know them and I think it one node or something
 like that and I think it was them and the guy there he is actually from the Balkans if I’m not mistaken or Romania  I think it's Romania but anyways and he is also very much like into bare metal and a lot of things and he when he was telling me their Cosmos, I thought I have a complicated Cosmos set up. When he started telling me his Cosmos set up was, I like oh my god how much the fuck does that cost,  of course we didn't talk
 about the prices but like just hearing those things I was like whoa and considering all the news now with all the cloud providers and nobody really wants to be in a cloud provider in the first place, but considering all those news you know and looking for data centres and yeah those things are really really really not cheap and that is of course I mean on one hand it's good but for the decentralization and for social purposes of
 course that is not something that is a good thing.

Zarko  
As I mentioned like one of the projects we are also like boot strapping right now is like collaborative finance. That sort of cofi that's the code name and this team it's like we're lucky to have like a group of really well known like researchers in this economics theory and also the guys were like having like successful implementation
 of this idea in like Slovenia and Sardinia,  both on credit clearing and mutual credit
 side and they are all supporting like various small communities so there are like communities project which are keen to like using like ideas and these techniques and
 they would really like to have them also on chain but like it's not really
 clear what is sort of like you know can we do this with existing technology
 like because probably the cost would be too high and so that's sort of I think really something to keep in mind and I hope that like will have you know like benita and like chance to improve something on that front.


Citizen Cosmos  
 We  haven't mentioned anything on the economical side let's leave it for the next time of course.  Well of course if you have anything else to add I’ll be happy to hear and I’m sure everybody else is as well. Before that though, let's do a
 quick blitz.
What are currently well at least two or three projects that you are
 well you kind of mentioned already twenty while we were talking but still maybe you
 could some projects that you think are doing really good work in terms of R and D currently, that you are interested in that you are inspired by could you name a few to share with us a few.

Zarko  
 Okay so I’m really bad with names

 Citizen Cosmos  
 it's okay a lot of people cheat
 now I’m joking I’m joking it's okay.

Zarko  
On the consensus side one of the project that we're also looking at is
 Narwal,  Bullshark so it's a paper and the reference implementation which I think really really clever implementation of like I would say relatively aold ideas of like like separating  ordering of transactions from like or like doing pre ordering of transaction in some form of mem pool and then agreeing on ideas it allows for like high throughput, significantly high throughput implementation, using tags in that context is really neat and there are really some nice ideas there and we are also looking at this work. We are also involved in some cool consensus work which also opened last time we talked about like consensus design space and I was saying that it's pretty much you know like clear what we can do there. I was wrong, apparently, and there is still I would say
 room for you know for things to be added there.

 I cannot say unfortunately more about this because things under submission as there are there are some university students involved, but as soon as it's ready I’m happy you know to talk more about this. It's really cool. There  there is s for example Psy has done
 really cool work on performance improvements, it goes along kind of the same line like being more careful how like we disseminate block parts and sort of separating like this dissemination of transactions from like order and trying to order just on ideas so this is on a kind of on the consensus side that what I see is as really cool. Anoma is with Typhoon, also doing really cool work. So it’s more a research project at a stage they are
 like investing to the best of my knowledge also a lot in this like gossip layer and like
 looking at like heterogeneous like gossip networks and how like we can reason and
 like design protocols in in a smart way.  There it's also employment in in Rust
 and I need to say that you know we still have this like this kind of hope that there
 will be at some point in time Rust implementation of consensus engine and we might be
 able to contribute to this. So that's sort of on the consensus side. On the formal verification side.  Okay we stop here

Citizen Cosmos  
 It's good it's good it's good it’s good because you can go into more but the thing is it's cool because I’m talking to Chris next week actually and me and Chris aren't actually familiar with each other but apparently I’ve been following him and i've heard good stuff from the other side so on we kind of finally managed to get a
 recording out so I’m going to be recording and then talking to him about Anoma and a lot of the work that they did.

 Zarko  
Chris is like one of the most smart and amazing people in the
 space so very lucky, He's also part of TAB and so that's probably one of the one of the major achievements of TAB that like we managed to convince Chris to sort of like
 be  somehow formally contribute the he’s of course part of the Cosmos and but this is like somehow bringing him more close to the core but yeah I’m looking
 forward also like hearing your discussion with Chris.

Citizen Cosmos  
 And I’ve actually ironically I spoke to Don just a while ago about say Sei, and we were talking about the performance it was just just as recently so the frequency is working you know it is it's the same frequency wait there are still two more questions in the Blitz they new they're much quicker so the second one, give me two things which motivate you in your daily life too this and this is a strange one I know but that that keeps you motivated in your daily life to keep on you know researching building and changing the world.

Zarko  
 I was actually you know thinking about this like over break because last year
 was like very challenging and alot of work and like significant stress with all the work and I realized that like I’m really lucky you know being surrounded with like the group
 of people I am working with that was sort of like you know my dream when i
 decided to to like leave industry in Switzerland and sort of like I was always
 like hoping that we can we can have like a small R and D team where we can work on a cool stuff and being this bridge between the academia and industry and Informal is not so small but there are really like some brilliant people and I really think that we are you know we're trying to do things which sort of makes sense and that is sort of what drives
 me and what keeps me essentially motivated to work so it's really like you know
 the people primarily and then also the ideas or you know teams on which we
 are working.

Citizen Cosmos  
 Last one, one person dead or alive
 doesn't matter it could be a developer it could be a writer it could be
 an author it could be a blogger I know could not even be a person could be a fictional
 character that somebody could follow and get inspired 

Zarko  
Maybe I can mention Fernando Perdone here. Fo Fernando is a professor at UC Legano,  he's one of the rock star of  distributed system researcher and we were lucky to also have him involved with the interchain foundation so he is also like official role there and I was also lucky to you know collaborate with him and do some research together and so his way of like you know picking topics and like working with people on this is really something which which inspires me so I kind of encourage everyone to like look at the publications of Fernando's group there really very solid like papers there and I have some ideas that you know there might be also some news coming out which will also be like super cool.

Citizen Cosmos  
 Cool. Zarko, thank you again, very very very much. Hopefully next time will not be so far away maybe you will come visit islands and we could either do this in person

Zarko  
Yeah, next time in person

Citizen Cosmos  
 Yes, it has to be. Thank you very much Zarco.

Zarko  
 Thank you, it was happy as always, being here and talking to you.

 Citizen Cosmos  
 Thanks everybody, bye. 
 
 -----------------------------------------------------------------------------------------------------------------------------------------------------------

If you would like to support our mission in creating educational content and aligning the goals of different communities, please stake with us [here](https://www.citizencosmos.space/staking): 

- [EVMOS](https://wallet.keplr.app/chains/evmos?modal=validator&chain=evmos_9001-2&validator_address=evmosvaloper1mtwvpdd57gpkyejd566s24afr9zm5ryq8gwpvj) 
- [ATOM](https://wallet.keplr.app/chains/cosmos-hub?modal=validator&chain=cosmoshub-4&validator_address=cosmosvaloper1e859xaue4k2jzqw20cv6l7p3tmc378pc3k8g2u) 
- [BOOT](https://wallet.keplr.app/chains/bostrom?modal=validator&chain=bostrom&validator_address=bostromvaloper1f7nx65pmayfenpfwzwaamwas4ygmvalqj6dz5r)

Join our [community](https://discord.gg/kJaG3EucCX), to build a future where communication is decentralized. May the code be with you!
