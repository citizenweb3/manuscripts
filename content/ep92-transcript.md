+++
title = "Episode #92 Denis Fadeev. Transcript"
date = 2023-04-30

[taxonomies]
tags = ["podcast", "transcript"]
+++

Episode link:  
https://www.citizencosmos.space/denisfadeev

Episode name:  
Denis Fadeev, Cosmos, Tribalism & Motivation.

In this episode of Citizen Cosmos podcast, the host interviews Denis Fadeev, developer of Ignite. They discuss the importance of valuing developer’s time, providing users with a feedback loop, and the necessity of tutorials and documentation in building a blockchain. Fadeev shares his passion for building for developers and the role of the CosmosHub in the ecosystem. They address the issue of tribalism in crypto and how Cosmos is working to fix it. The conversation then shifts to Ignite, a marketplace of sovereign blockchains, and how it helps projects build. They highlight the motivation to keep on building and the flexibility of Cosmos that keeps it interesting.

--------------------------------------------------------------------------------------------------------

Citizen Cosmos  
Good space time, y'all. In this episode of The Citizen Cosmos podcast, I speak to Denis Fadeev ex VP of product at Tendermint and creator of Ignite CLI. Along with Denis, we discussed time and value developers Users and feedback and the passion to build tools working remotely, and the steps in building blockchains. We also talk about the Cosmos Hub, tribalism, marketplaces and sovereign blockchains, motivation and flexibility.

Denis  
And this is the crucial thing, I think in the beginning you need to make the developer experience as smooth as possible. Building a blockchain is not everything you also need to build end user applications. If something doesn't work, you are free to create something that is better, that has functionality that he wants, and you don't have to ask anyone. The decisions made through governance actually change the course of events.

<!-- more -->

Citizen Cosmos  
Before we rocket off into today’s podcast, here is a round up of the latest news from the sponsor of this episode, Cyber. Cyber Congress Dao has been primarily working on improving the Bostrom hub. This work includes testing of the contracts, new UI features, verification, tools for online governance and polishing the Bostrom Dex adding MEV protection. New web front and bring in indexing of chain swaps. To try Bostrom head now to over Cyb.ai.


Citizen Cosmos  
Hi everybody. Welcome to a new episode of the Citizen Cosmos podcast. Today I have with me Denis Fadeev the creator of Ignite, Denis Hi.


Denis  
Hey Thanks for having me. Excited to be on the podcast and.


Citizen Cosmos  
Glad to have you on because we have had the connection with you over work. Well, sort of a work, I guess, right? For a while now and we've been talking so much and you've been doing so much in terms of building and everything. And finally we have you.


Denis  
Yeah. .


Citizen Cosmos  
Would you like to Tell all the listeners and myself what is going on in your life right now? What are you busy with? What are you working on? Maybe what you worked on before as well for people who don't know you, please?


Denis  
Sure. So I'm going to introduce myself a bit, give some context, some history, and then we'll talk about current situation, what I'm doing. So I joined Tendermint in 2019 as a front end developer. I worked with the design team Pong ..... websites and Web applications for Tendermint Core and the Cosmos ecosystem in general. So we built websites and then we worked on a documentation system which was used by pretty much all the projects in Cosmos ecosystem in 2020 and 2021.


Denis  
So it featured some functionality that wasn't available at the time with popular documentation systems. So we had that and just recently switched to Docus.Rs because nobody has the time to maintain our own documentation system. And yeah, basically I worked on web related projects for about seven or eight months and then at some point I looked into building blockchains.


Denis  
We had this idea of building social network kind of application. We're just exploring kind of R&D work to that, and we wanted to use Cosmos Hub as essentially the memo field of Cosmos Hub blockchain transactions, right? So every transaction we have this Memo field, I think that was recently renamed to note, at least on the CLI so that people don't insert mnemonics in this field and expose themselves.


Denis  
But yeah, we thought about using this memo field to contain extra information basically encoded as Json and put it there. But very quickly realized that that's not at all what you should be doing because even on the the website Cosmos dot Network it said building sovereign blockchains and we were taking a blockchain and shoehorning something that wasn't supposed to be there into the application.


Denis  
So I decided to look into how to build my own blockchain and discover that what wasn't actually all that straightforward. So the only tutorial that was available back then was a name service tutorial, which which is a good tutorial. It was very long in that you had to dedicate time to go through it and it didn't explain all the details about how to build blockchains.


Denis  
Right? It gave you a glimpse of what it takes, but wasn't a foolproof tutorial. So I looked into cosmos SDK and and I didn't see I mean, it wasn't obvious how to how to build a blockchain from cosmos SDK because it just had the docs that described this framework and there it was no Main dot go, no way to start a blockchain cosmos SDK


Denis  
And I looked into Gia and it didn't have any modules and cosmos SDK docs specify that you need to build your functionality in modules. So it's very, very confusing. I spent a couple of weeks kind of learning or reading the docs and figuring things out, and then I realized there has to be a better tool for Cosmos developers that didn't require you to go through all of this and read the documentation in its entirety and understand what's the difference between Gia and CosmosSDK like it should be.


Denis  
The experience. Developer experience should be similar to what developers in Front end world enjoy, right? Where they have a framework and they also have a companion CLI tool that essentially guides you through the process and at least takes some of the burden when you're just starting And this is the crucial thing. I think in the beginning you need to make the developer experience as smooth as possible because what people do is they dedicate a weekend, for example, to learn Cosmos, right?


Denis  
And they only have a weekend. And it's actually very valuable, right? We as people who are building frameworks and enabling developers like we need to really value their time and not require them to jump over hoops and spend countless hours figuring things out right. So we need a very straightforward onboarding process for developers. And once I figured out how to build a basic custom blockchain with Cosmos SDK, I decided that I CLI tool that would help people like me to start their Cosmos developer journey and have this tool.


Denis  
So I spent a couple of months working on that, featured some, so I decided to understand like what makes a CLI tool good, right? And I came up to a list of features that I wanted to have in the very beginning, right? It should create any blockchain, which is pretty trivial operation, but blockchain should be complete, right? It should be.


Denis  
It should spit out a software project that you can build right away. You don't have to make any modifications. No, nothing. Just run a command. You get a blockchain and the next thing that people would do is they would start their chain, right? So I wanted to have a command that will start a blockchain node, initialize it, install dependencies, build it, initialize it, do all these things that you typically want to do.


Denis  
We could have done this with Makefile of course, but at the same time, this iterative approach to development that is very common in front end development and I wanted to bring that to blockchain development as well. So you have the source code and every time you make a change to the source code, everything restarts, rebuilds, re initializes and you can, you can experiment very quickly.


Denis  
And that was crucial, right? So having the command to create a blockchain, having a command that will start a blockchain node of your custom blockchain without any configuration required, that was very important. The next part was providing users with a complete feedback loop because what took me long time and I apologize if I'm going into details, but I just wanted to describe the functionality of the first version because I think it's quite important.


Denis  
So the next piece of functionality was a complete feedback loop. So when you're building an application, I think it's very valuable to be able to get to a point where you can submit data to your application, to your blockchain, read it back up data, delete it, these sort of things. So .... operations on a very simple data type.


Denis  
So I added the functionality to generate that code. So you would be able to, to say back then and right now the project is called Ignite, but back then it was called Star Port. So you would type star port scaffold post with a title in the body and it would generate all the code you need to write blog posts to your blockchain to read them.


Denis  
Right? And that gave you like a micro application that you can study, modify and you can see how the changes that you make to this small application affect the outcome. So maybe you would add you would create this type with two fields and then you would manually add a third field just to know how it's done. And since all the code was there is very easy.


Denis  
So it functioned as a quick prototyping tool because this is something you would do as a developer when you need to build a project. But at the same time, it also worked as an educational tool because you would create something and then you would study it, modify it. So that was these pieces were very important. Then of course added a web template because we all know that building a blockchain is not everything writing it.


Denis  
You also need to build end user applications. You need to make it possible for users to actually interact with what you build. And I use Cosm.js as a library from confio and shape a first templates based on view and cosm.js So that was basically the functionality of the CLI when I first released it in late July 2020 and after it's been released, we've seen people using it and several big projects actually use the first version to scaffold their own chain.


Denis  
The CLI didn't have that many features besides what I talked about, but it was still a very convenient way to get a new blockchain up and running. So crypto work used the CLI sifchain Mid-Corner in some others. It also wrote tutorials to help people get onboarded because you can write the best tool in the world, but if you don't have tutorials, if you don't have documentation, people really not, you're not going to know how to use it.


Denis  
You're not going to spend time exploring this right? So I prioritize that as well. Yeah, that's how it started. And after we realized, well, back then it was just me. But once we realized in the company that this was this was cool, this is valuable, people are interested in using it. We decided to create a whole team around it, started hiring developers to essentially implement the vision that we had for, for the tool.


Denis  
And yeah, after that I focused solely on the on the CLI and team was called Developer Experience Team because even though our project, our main project was the CLI the mission behind the team was to improve developer experience of blockchain developers.


Citizen Cosmos  
Then why did you I mean I'm going to get to ignite in a little bit, but I have some questions to get to know you a little bit first. So first of all, why did you decide to concentrate on building for developers? I mean, I understand the importance of foundation, but if you were to draw an analogy, you know, I mean, any work in the house is important, not just the foundation, right?


Citizen Cosmos  
Building the doors, the windows, working with the wood, with the stone. Also important. So why did you have this passion to concentrate? Because what you did before was also kind of building for building. So I'm curious, where did this passion come from that you have to concentrate on the developers, on the builders, and not the people who come already after?


Denis  
Sure. So, well, first of all, I think I saw the opportunity like this area was really lacking. Of course, back then. But really even right now you can focused on great many things. You can focus on on building wallets, on the building. I don't know. End user dapps, there's just so much stuff you can build. But I just realized that this area was really lacking and this is something that I think prevented Cosmos from growing because you need to give the tools to people to to let them experiment and build.


Denis  
And if you don't have that, you're limiting the potential of the whole system, right? So Cosmos SDK is great, but at the same time, if the barrier to entry is very high, then we're kind of artificially preventing people from experimenting with cosmos and building. The more people who get engaged into building, the more dapps eventually you will have.


Denis  
So to be honest, I think the reason why I also decided to focus on this because before joining Tendermint I actually participated in a hackathon during Paris Blockchain week in 2019 and we built a blockchain with Cosmos SDK actually, and it took us forever and it was very difficult and it was very unintuitive. And we won the first prize of this hackathon, right?


Denis  
We got first place, but I also saw how other teams were doing and they weren’t doing great. So some teams, most teams basically were just able to go through half of the tutorial like that's all they did and that's why we won. We were we didn't build anything great. We we just managed to build something that compiled and worked.


Denis  
It was a two day hackathon, so it wasn't that much time. But still you should be able as a participant to go through, I don't know, a 30 minute tutorial and get to a pretty good understanding how to build with a tool. Hackathon is only two days. So basically one year later I focused on fixing that problem.


Citizen Cosmos  
I get it, I get it. Then I also saw like from your history that. But the thing is, I'm going to try to dig in these questions. I know, I know when you ask guests the question and they answer, you're not supposed to re-ask them. But I really want to get I'm really curious. So because I know that working for Tendermint that you did when you did design like you also build for builders over there.


Denis  
So the company I worked before, Tendermint was a decentralized CDM for video and product was in a way for builders, but I was a front end and before that I focused on prototyping for enterprise companies and I think that experience also kind of helped me understand the pain points that developers face in enterprise. You get to experience that quite a bit, right?


Citizen Cosmos  
It's interesting how sometimes the reason I'm asking is it's a cool thing. Like I, I'm older than I look. We'll probably some more or less the same age, but I'm older than I look. But anyways, quite a bit older. And I realized over the time I had a couple, a couple of careers which at first seemed completely different.


Citizen Cosmos  
But then I was having this conversation once with somebody and I realized that there was just like an obvious thing from inside my head that connects all of those things together. And this is when I was looking at your history, trying to do my homework a little bit, I noticed that you almost always concentrated on creating a tool that will help somebody else to create something.


Citizen Cosmos  
So it's like I was trying to get curious Inside You head where is like the passion maybe when you were two and you're putting already Lego blocks together, you know? All right.


Denis  
So I had basically a dream before I learned how to code. I really wanted. After I started learning how to code, I realized that I wanted to build something that other developers would use. So I thought that would be a library of some sort. I started learning actually with Ruby and Ruby on Rails. And Ruby on Rails actually was the inspiration for this CLI tool because it had all this functionality, but for traditional applications, and I, after going through Cosmos Docs, I realized like, yeah, it's, it's actually very similar to traditional applications except in Web 2.0.


Denis  
We had the tools and here we you don’t have the tools. So. So yeah, I always wanted to build something that other developers would find useful. And that kind of that was just a good opportunity for me to build something that is totally needed and also will fulfill this kind of desire to build something useful for other developers.


Citizen Cosmos  
It makes perfect sense. I understand totally what you mean. I have a bit of a strange question for you, which is not actually work related, but I would like to ask you and you feel too free to answer however you wish to answer. So I know that just for listeners who don't know, a few years ago I was trying to was as one of the community members.


Citizen Cosmos  
I was helping out the guys at Cosmos Hub with some of the Russian things and translations. And one of the things we did with another team was one of the hackathons, which was concentrated on the Russian audience developer sorry, not Russian, but Russian speaking developers, should I say correctly. And Denis was actually the key person to help us.


Citizen Cosmos  
And this is why the question is going to be asked. So I'm curious with all of the latest and we hate politics here, but this is not a politics question. This is a question about your work and about your experience and about general like observation of things. How does it I don't know if you still are based within Eastern Europe, but regardless of whether you are or not, you don't have to answer that because I know you were for a while.


Citizen Cosmos  
How did it feel lately? Is that a problem for work to to to work in this field in Eastern Europe? Did you have obstacles? Are you still if your base there have been obstacles? I'm very curious about that.


Denis  
Yeah. So I left Russia in February 2022. I lived a while in Armenia and then I took some time to travel Europe and now I'm based in Istanbul, Turkey. So I mean, I'm not going to comment on politics, but personally I'm just working on the same projects, but from from a different location. And what I love about decentralized nature of working because Tendermint inc has always been a decentralized company.


Denis  
It's well, we had an office at some points in Berlin, but we've always been working remotely and I created a team also remotely. So for actually two years I hadn't seen people that were working with me for two years, right? So that was an interesting experience. So nothing changed from relocating That's all I can say. Yes.


Citizen Cosmos  
Oh, no worries. Like I said, it's a personal question, so feel free to answer as many detail as you want. I totally understand because I've been working remote with teams, managing remote teams and working for remote teams for over six years now. And it's strange, you know, sometimes, but then you get used to it and you like and I actually for the record, for for everybody out of like a fun trivia fact, the first ever episode of Citizen Cosmos was recorded in the Berlin Tendermint office, uh, during COVID in 2020.


Citizen Cosmos  
It was with remote guests, but it was in that office, that recording.


Denis  
So I well, yeah, I remember. I remember this office. I it was, I didn't have a chance to visit the office because, well, because of the lockdowns. So it started. So the only time I got to visit people from Cosmos was in late 2019, before before the pandemic in San Francisco and during the hackathon. So that was a great experience for me as well.


Citizen Cosmos  
Here's a question for you just came out. Now, I'm curious, while we on the same topic, how do you feel now, considering you've spent working, you know, I mean, I know my experience, but I'm curious. And yours, of course. And you know, you just said you've met these guys in 2019, then you met them, I guess, during Cosmoverse


Citizen Cosmos  
Right. Like because I did see you talk at Cosmoverse. So how does it feel to work so much with people to create so many things? And considering Cosmos is not, you know, projects on the 10th page of Coingecko? You know what I mean by that? I mean, it's a lot of stress still to be working for something which is bigger.


Citizen Cosmos  
I guess it feels a lot more that you need to not to at least for me, this is like how I would feel if I were you. How does it feel not being seen, these people, but working so close with them? And you know what's inside?


Denis  
Yeah. So I always been comfortable with remote work and I think the events in 2019 and 2020 changed the way many people work. So initially it was not surprising. But I guess I mean, before that I worked in an office and then when I joined Tendermint the work was all remote. So I guess there was like a period of one month where I had to adapt.


Denis  
I don't have to go anywhere and meetings and there were people in everything is in English. And it took me around a month, I think, to adapt to this. But after that it's pretty much the same thing, except it's more efficient because you don't spend time. You can have short meetings without going anywhere and you really focus on the code or on documentation or on supporting users.


Denis  
So I just think is generally a better way of working. However, I would say that's after two years of leading the team, what I realized having occasional meetups and time working together is incredibly valuable. So I wish we had more opportunities to do that, but we couldn't because every everything was lockdown. But now I would advise to remote teams to occasionally, like every quarter, have a week where everyone can be in the same room and can really discuss things and just socialize.


Denis  
This is a crucial element of team building, but it's also very important for the product because there is a difference between meeting a person on a videoconference and in-person.


Citizen Cosmos  
And then you spoke to work back to reality, you spoke about Cosmos Hub mentioned several times and of course you've been involved within the Cosmos Hub since the very beginning, almost or since the very beginning. Apologies if I underestimated that the Cosmos Hub, a role in the ecosystem has been spoken about, But I don't know how many times by many people, and it's changed over the last couple of years.


Citizen Cosmos  
The ideas, and especially though with Proposal 81, 82, 83 that recently were and regardless of their outcome, regardless of what we think of them, not the point. I'm curious about your personal opinion for the Cosmos Hub, especially somebody who well, it's partially your child kind of thing. So like, you know, I would like to know, what do you think is the role of the Cosmos hubs and what is your personal vision, if you can talk about it, of course, for the Cosmos Hub.


Denis  
Yeah, just a small correction here. I actually joined the company, I think, after a month after the launch of Cosmos Hub. So Cosmos Hub launched I think in April 2019, and I joined actually a couple of months later. So just to set the record straight, I haven't participated in the development of the original Cosmos Hub. As for Cosmos Hub as it is right now, I think it's an incredibly valuable and important project and it will hopefully forever remain a heart of the ecosystem.


Denis  
I think it's incredibly important to understand that it doesn't have a CEO and it doesn't have a single company behind it. It has a community of people and they're passionate. They're ready to express their opinions on very controversial questions about how it should be developed, how the how in which direction it should go. And these directions are very different from one another.


Denis  
Right? People have different visions. How it should expand, should it be a minimalistic hub with almost no features at all? Should it have a specific function in the Cosmos ecosystem? Should it be a blockchain for for everyone with all the features? I don't think it matters all that much. What I what I believe Cosmos Hub should be, because Cosmos is more than Cosmos Hub, and that's why I want to focus on the project that is my metaphorically child, because I want to give developers the tooling to be able to expand the cosmos, right?


Denis  
And experiments and not have to be confined to a single chain because that's what Cosmos is all about, right? If something doesn't work, you are free to create something that is better, that has functionality that that he want. And you don't have to ask anyone and you have to pay anyone. That's true importance for me. I like to say that Cosmos has no competitors, not because it's better, but because the goal is not to outcompete another ecosystem.


Denis  
It's actually to connect all the ecosystems and expand the applications of blockchains in general. So going back to Cosmos Hub, it's really up to the community. And we can I try to vote as often as possible unless I say forget or unless the issue is irrelevant. But but yeah, what I do love is the passion of people who are voting.


Denis  
I think Cosmos probably has Cosmos as an ecosystem, has the most active governance systems in crypto, and these governance systems are actually consequential, right? The decisions made through governance actually change the course of events, right? It's not just the forum post with thumbs up and thumbs down. It actually changes how the blockchain will be upgraded and what features it will have.


Denis  
And I think I just love to watch this system evolve. And that's also one more interesting aspect of Cosmos is that it was designed, but not all the bits of Cosmos were designed the way they are right now. Some things evolved, right? So we at some point we saw that there will be hubs right there. All the zones will connect to each other with hubs


Denis  
But that didn't happen exactly this way, right? Because this has been evolved differently. And the fact that Cosmos allows for that is incredibly powerful because you can see how the system involves and and change what you're building based on that. So maybe the hub idea and I'm not talking about Cosmos Hub specifically, I'm talking about the idea of blockchains acting as hubs.


Denis  
Maybe that will change as well. Maybe right now we just didn't get to a point where blockchains are hubs because they're only 50 plus blockchains. And when you have thousands and I do believe that we will have thousands and tens of thousands of blockchains, eventually the hub idea will become more important because you cannot connect all of them to each other.


Denis  
But what will remain unchanged, hopefully, is that people will still need the tools to expand this ecosystem. Tools might change the way people build, blockchains might change. But yeah, I really like this idea of an expanding ecosystem where you don't have a single blockchain, but rather you have a network of blockchains that you can contribute to and you don't have to ask anyone for permission.


Citizen Cosmos  
Well, I always make notes. While I we speaking the first note when you said the word hub, I was like hubs, comma yet. And then you said, Not yet. And I was like, okay, okay, okay. So I don't have to discuss this now. Joking. This is actually something I would like to hear your opinion about because, well, you already mentioned it, but just to reflect on what you said, I just don't think that the tools are there yet.


Citizen Cosmos  
I agree. Like the communities are not there yet. The tools are not there yet. I think that we will definitely, as those blockchains develop, like from a personal perspective, I feel like we will see those blockchains become hubs and more applications, kind of like being built on top of these blockchains rather than separate blockchains separate. But IBC enabled blockchains with other connected blockchains.


Citizen Cosmos  
I think it will get there. I kind of have the feeling, but I'm not sure it's then. Do you then think that tribal is the worst enemy of the community that we could encounter in this case then?


Denis  
Well, I think every community eventually gets to a point where there are kind of coalitions and they compete with each other. I think the problem is not that these coalitions or tribes exist, but rather situations where you cannot really participate unless you belong to a tribe. Again, this what makes Cosmos different is that you can so if you have an idea of an application and you can't find a blockchain community, that would accept it, you can just do your own thing and launch your own application.


Denis  
So this way of kind of going around these tribes or coalitions is just building our own thing and attracting people to your own idea. And what you basically need is good idea implementation and you need to convey this message to validators. And if they are convinced and users are convinced, then you will have your own saying without having to join any tribe or coalition.


Denis  
If you don't want to, you can do your own thing. And that's very cool, I think.


Citizen Cosmos  
Absolutely. I think we have exercised it so far to an extent, but one of our goals, I think, is to be the bridge between layer zero. So in this case, layer zero. So the community, not the the underlying technology, because I think that is very important because a lot of the bridges that will exist and as they get stronger, I mean, the technological bridges, these communities have to talk to each other.


Citizen Cosmos  
These communities have to coexist in one big ecosystem. And I'm not talking about just IBC, I'm talking about generally, you know, whether it's grand power or, I don't know, Near or IBC or whatever, they somehow have to coexist. And so some have to develop things. And this is actually a very good point to come to ignite, I think, because well, before I ask any questions, maybe you can introduce Ignite in like two words what it is, and then I can ask a couple of questions about launching communities and launching blockchains and the importance of it.


Denis  
Sure. So Ignite is a tool for building and launching sovereign blockchains. That's basically the shortest description I can give. But it's made up of two projects. One is the CLI that lets you build blockchains and the other one is the ignite chain which is currently under development. So the CLI was released in August of 2020 and actually three weeks after release I came up with the idea of a blockchain to launch blockchains.


Denis  
So we kind of started working on that pretty soon after and we demoed a proof of concept in late 2020. And for a while we've been working on chain as well. So the chain, the purpose of the chain is, is very simple. It's to coordinate launches of new blockchains. So instead of using centralized services like GitHub, you would use the CLI or web interface to publish your blockchain on Ignite.


Denis  
Validators will see that, and if they're interested, they will apply to become validators. And there are many interesting pieces of functionality that we added to the system, for example, incentivized test nets and you could essentially distribute your token supply to validators and users even before your chain is live, which is something you can only do by using a blockchain, which is why we built this system as an as a blockchain.


Denis  
So of course we're using the ignite CLI to build the ignite chain. We've announced the ignite chain and Launchpad, which is a graphical interface web interface to the Ignite chain in September, at Cosmosverse and it's already available, so it's not yet in main net phase, right? It's currently running on just a couple of servers, but soon we'll entered the testing phase.


Denis  
But what's important is that the functionality is and has been available for months now, so people are actively using it to launch the test nets we're getting feedback and we're iterating and making sure that the system works well for both for coordinators. So teams who are launching chain as well as validators, because those are two groups that we want to build our product for, right?


Denis  
Those are main audiences that we want to cater to.


Citizen Cosmos  
Can I try to look at it, if you don't mind, from a different angle? So is the whole like I know the launch by CLI the chain are different products. I understand it just for the sake of conversation. For some stigmas, if we were to put that this one product, could you look at it as some sort of like a marketplace to launch your chain?


Denis  
Yes, it can be considered a marketplace. And you have two sides. One side is coordinator, so a team building a chain and they're announcing a chain on this marketplace and they're trying to attract validators and validators supply ends. They launch test nets and they get tokens in return for their participation and for their trust. So, yes, it's it's a way to match good projects with good validators, right.


Denis  
So if you build something, you can publish this on on Ignite and expect validators that validate for other projects in the Cosmos ecosystem to apply and become validators for your project. And the key point here is that it's for initial, it's built for sovereign blockchains because we think that this is something that is truly aligned with the Cosmos vision.


Denis  
So it's not an it's not a shared security story. It's it's all about empowering developers and teams to launch their sovereign chain. So once you launch from Ignite, you actually are not connected back to Ignite chain, which I think is very important because it's like commercial launchpad is a blockchain is a rocket and it takes off from the launchpad and then it travels independently.


Citizen Cosmos  
You said there was no connection and there are controls and independently can I ask, is there an economical connection?


Denis  
No. After blockchain is launched, it's no longer owe’s anything to ignite. It's not connected. But we kind of realized pretty early on that it's not about launching a single main net right rarely does a project launch a main net as the first network, right? That like that never happens. You build a project then you launch a very rough test net just for your friends and family where stuff is not working and you want to make it public, then you make a better test net and then you go through a series of test nets and that's what Ignite is built for, right?


Denis  
So when these test kits are launched, they do have connection to Ignite. Well, some of them, if you want to incentivize validators, Ignite keeps track of who signed which blocks straight. So if Validator was performing well and they were proposing blocks and signing blocks, they will get rewarded. So during testnet, during incentivized testing period, your testnet is connected to ignite.


Denis  
And that's one of the ways Ignite Token will accrue value and show you I'm not going to talk about the token, but there is an economic system behind this because Ignite is going to be an independent proof of stake blockchain. It's going to have its own token and their tokenomics system behind it.


Citizen Cosmos  
Sure, I'm not going to ask anything questions about a token plus we don't usually do. So if you do want to mention anything else, please do one more question though about Ignite. And we are not in Citizen Cosmos. We don't like legal things, but I know that a lot of developers do find those things important. So I'm going to ask will ignite as a launchpad.


Citizen Cosmos  
Also help teams on that side of the questions. Or is that the kind of things that the teams are? This is a building tool. You guys build the blockchain and everything else, whatever it is you do, economics, legals, I don't know, whatever it's out there, we can help with the validators, we can help with the CLI with a tool, with a chain, but that's it.


Citizen Cosmos  
Or is it a bit more than that?


Denis  
Yeah, I think it's important for Ignite to also help teams build. So we started focusing on the tooling because that's what you need, that's what skills best for a team. We built a tool and literally thousands of experiment projects used it, right? We're built with the CLI and dozens of projects are in production right now thanks to the CLI


Denis  
But eventually I think is going to be very important for us to also support teams that want some help from the people who are experts on building blockchains. Right? So we have an accelerator program right now and you can learn more about this on the website. And we are looking into providing more help to developers and teams who want to get more from the CLI


Denis  
But I think building the tooling first was the right approach because we've been using the CLI for building the chain every day and that's what allowed us to improve the CLI and that's what allowed us to build the chain so much faster and iterate quicker.


Citizen Cosmos  
Quick original blades than is. Because I know your you have timings. So three questions. Feel free to answer the sharpness up to you. Three projects. This is the first question outside of the top 20 Technologically, you're curious about.


Denis  
Three Pro... within the Cosmos ecosystem.


Citizen Cosmos  
No, no, no, no, no, no, no, no, no. It's not that easy. Come on, let me see you. Make it harder. Come on.


Denis  
Okay. Well, I'm still very biased towards the cosmos ecosystem.


Citizen Cosmos  
Let's go in Cosmos.


Denis  
Okay, so aside from .... obviously, obviously, I think Celestia is doing great work. And again, this is not endorsement of any project purely on the technological merit. I think Celestia is doing exceptional job. They're doing roll up some Cosmos data availability layer. It's a different way of thinking about building decentralized systems. So I have huge respect to that team and their project stats are very interesting in terms of how fast they were able to implement their vision.


Denis  
So I have a lot of respect to this Stride team, for example, for building a liquidity solution. Liquid staking. Yeah, it's just I just really enjoy watching this project kind of develop from from 0 to 2. STATER And right now, other than that, I would say actually cosmos SDK itself. It's not a chain, but I think I just want to give props to the decentralized group of people working on these technologies that make all of this possible, right?


Denis  
Introduction of IBC and interchange counts and soon Interchain queries like all of this opens so many possibilities that will make it fun to build in Cosmos for years to come. So I really appreciate the work that's different companies are doing to push the state of the art forward.


Citizen Cosmos  
Two motivational things that in your daily life help you to achieve results and to keep on building and, create and things.


Denis  
Well, that's an interesting question. I guess the first one is that we're building open source and decentralized systems that hopefully will outlive us, not in the way they are right now, but the fact that what we're doing is not going into some proprietary system, black box sort of thing that someone else, some for profit company will benefit from.


Denis  
But everything we're doing is is in the open and it's valuable and people are using it to build other cool things. And that's what's motivating for me, right? The fact that no effort is wasted, everything is invested into building this open system and we don't know what it's going to be used for. But the fact that Cosmos is so malleable, right?


Denis  
So so flexible and can be adapted into different use cases, like that's that keeps it interesting for me for more than three years now. And I think that's the main thing that motivates me.


Citizen Cosmos  
I love that answer. Last one one person to follow that will help people to stay cool and happy. And it doesn't have to be developer. It could be actually a dead person that wrote the book. It doesn't have to be a social media account. Could be a GitHub page. I don't know somebody you think that you would recommend to follow.


Citizen Cosmos  
It doesn't have to be a number one priority, but somebody that inspires you.


Denis  
Hmm. That's an interesting question. Well, I don't think putting like this pressure on a single person is is wise like, I don't have an idol, I don't have idols, I don't have people that I believe in unconditionally. And this changes so changes quite frequently. So if you want to know who I follow, well you can just go to Twitter dot com slash my surname and then you will see a list of people I follow right now and any changes.


Denis  
And I think there are bunch of smart people in this list and that's my I understand that's not exactly an answer and kind of.


Citizen Cosmos  
It's a perfect answer. It's a perfect answer. I think I think I love them. Guests have a different way to answer the question rather than just the typical answer, because it gives a whole different perspective. But my idea is not to give the person you follow is to get your answer. So just perfect. Thank you. And then if I like I said, I know you have certain time.


Citizen Cosmos  
If I didn't ask something and you want to mention it, please do. Other than that, thank you very much for this conversation. But please, if I didn't ask something and you still have some minutes left, please feel free to mention it.


Denis  
Yeah, I guess if what I talked about was interesting for you and you want to explore more about how to build in Cosmos, you may be a developer, maybe, or not even a developer, and you want to get into this. Is it GitHub dot com slash ignite slash CLI or ignite dot com and read the documentation. It's all free and open source and we'll have it will be happy to see you on discord answer any questions we're just building the tooling for the Cosmos ecosystem and then we would love to see more people building and exploring with us now guys.


Citizen Cosmos  
And just for everybody, all the links Denis is mentioned, it will be in the description to the episode. So if you don't catch anything, just look at the description of the episode on the website and you will find it. There Denis Thank you very, very, very much for finding the time and thank you very much for answering the questions and for clearing some things up.


Citizen Cosmos  
Thank you.


Denis  
Thank you for having me.


Citizen Cosmos  
Thanks, everybody. Bye.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

If you would like to support our mission in creating educational content and aligning the goals of different communities, please stake with us [here](https://www.citizencosmos.space/staking): 

- [EVMOS](https://wallet.keplr.app/chains/evmos?modal=validator&chain=evmos_9001-2&validator_address=evmosvaloper1mtwvpdd57gpkyejd566s24afr9zm5ryq8gwpvj) 
- [ATOM](https://wallet.keplr.app/chains/cosmos-hub?modal=validator&chain=cosmoshub-4&validator_address=cosmosvaloper1e859xaue4k2jzqw20cv6l7p3tmc378pc3k8g2u) 
- [BOOT](https://wallet.keplr.app/chains/bostrom?modal=validator&chain=bostrom&validator_address=bostromvaloper1f7nx65pmayfenpfwzwaamwas4ygmvalqj6dz5r)

Join our [community](https://discord.gg/kJaG3EucCX), to build a future where communication is decentralized. May the code be with you!
