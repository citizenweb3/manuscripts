+++
title = "Episode #82 Boris Mann. Transcript"
date = 2023-04-20

[taxonomies]
tags = ["podcast", "transcript"]
+++

Episode link:  
https://www.citizencosmos.space/borismann

Episode name:  
Boris Mann, storage, web applications & decentralization of web3.

In this episode, Citizen Cosmos speaks to Boris Mann, co-founder at Fission nodes, building protocols for the future of the Internet and web3.
Boris shares his passion for the use of content addressing as a potential solution to storage on web3. If you do not know what content addressing is, I would suggest
listening to the podcast for the concise and elegant manner in which it is explained.
Boris also delves into what he believes the future of the internet is and how we can get there.
During the Blitz, Boris reveals his motivations for crusading for user privacy and social responsibility.

--------------------------------------------------------------------------------------------------------

Citizen Cosmos  
Good space-time y'all. In this episode of The Citizen Cosmos podcast, I speak with Boris Mann from Fission Codes. Powering hub decentralized web applications. We discuss the future of Web 3 marketing, the steps needed to get away from Web 2 and where we are on our Web 3 journey. We also talked about interoperability, DID's, decentralized storage and the pros and cons of IPFS.


Boris  
IPFS is awesome, works everywhere in many ways. Content addressing has won and continues to win, in really interesting ways. It's a commons network. It's best effort. People say, "That's terrible. What if it goes away?" And I say the flipside, "Literally any piece of content that any human on the planet cares about, they can keep it online themselves effectively for free, effectively forever."

<!-- more -->
 
Boris  
I think we're in a really tough spot in this Web 2 ad supported world, where a lot of people in the world have been trained that everything on the Internet is free. They start needing to think about how they help themselves, their users, their partners, their friends, their countries, their regions, do stuff. That's the part that we need to start making 100% the part of Web 3.


Boris  
I will advocate and shill for content addressing.


Citizen Cosmos  
Before we rocket off into our next episode. Here are some news from the sponsor of this episode Cyber Congress DOA , the foundation has started its delegation's policy for validators on the Bostrom Blockchain, and the Space Pussy Network was launched with 96% of its supply to be dropped to various cosmos ecosystem chains. 

Hi everyone. Welcome to another episode of Citizen Cosmos podcast.


Citizen Cosmos  
I have with me Boris Mann from Fission today on the show. Boris Hi, welcome to the show.


Boris  
Hello, Thanks for having me.


Citizen Cosmos  
Do you want to first of all, introduce yourself and tell us about what you do exactly?


Boris  
Sure. Absolutely. So I'm the founder and CEO of Fission. What Fission is doing is building a full edge computing stack of identity data and compute, to equip front end developers with the stack that lets them build these edge applications, all on top of ipfs and content addressing. We've been doing that since 2019. I have a long history of being involved in open source, and so we believe what we're doing is very important to basically empower more user privacy and encryption and make it easier for devs to do the hard things like implement those right from the beginning when building an application.


Citizen Cosmos  
Yeah, that is actually a lot of the things we connect to. Obviously, open source, content addressing and trying to make developers life easier. I guess it's not an easy task that you have there, especially in a Web 3 world. How do you find it so far? The task?


Boris  
Well, I think my co-founder, Brooklyn Zelenka and I, we did some core work with Ethereum. I helped run some of the early Ethereum Magicians Unconferences, helped make the Three Magicians Discourse Forum a place for discussion, and Brook ended up doing poor work on the Ethereum Virtual Machine. What we found, is obviously a lot of these things with smart contracts and blockchains has lots of new things that you have to learn, not just new things to learn, but that are themselves just in the process of being built and evolving, so new for everyone.


Boris  
So everyone starting on the ground floor. What we found is that a lot of the time, a lot of the challenges came with the regular Web 2 stuff. It's too hard to build a full stack application. As a developer, you have to become the full stack developer to build full applications. So while blockchains and similar systems add a sort of back end as a service, there's still all of these other components.


Boris  
And so what we realized is that perhaps there was a way to use these distributed systems and cryptography and content addressing to make these things easier, so that developers wouldn't have to end up running Ruby on Rails or Python or Node.js server, which sort of defeats the purpose of having a decentralized back end. And I'd say generally, yes, this is a hard task, a big step, a task of doing things differently, but also that it's important that we have these things as components, when in comparison we look at the three American corporations that run the major hyper clouds and say maybe we want some edge computing to be run more broadly than just those three companies.


Citizen Cosmos  
That is something that is like music to my ears, man. Seriously, because I have been in this field for a long time and I think unfortunately, a lot of projects, developers, they really don't make the distinguish between Web 2 and Web 3 stack, and a lot of them assume that by building certain something that they can label it as Web 3.


Citizen Cosmos  
And very often as we have seen, that is not the case. And very often, it leads to really big problems in the industry and misleads where people take it. In your personal opinion, do you think that today what we label as Web 3 or call Web three, I mean, you mentioned yourself, it's very difficult to create that stack. How far away do you think we are on our journey as Web 3, to really become Web 3 and not Web 3 dependent on Web 2?


Boris  
So I was around in building software in the transition, open source software, and then in the transition from Web 1 to Web 2. And I remember at a certain point, a lot of people really hating on the term Web 2, in part because it had been captured. There was a Web 2 conference in San Francisco that I remember, that I think tickets were $2,000 and I was in San Francisco at the time.


Boris  
So I just hung out in the lobby outside of where the paid area was. And and so we hung out with some of our friends, I think Web 3, unfortunately, I think it's something important for us to address. I ended up choosing to use that term. I believe that edge computing, which is where Fission focuses, is a superset of just blockchain technologies, distributed systems, cryptography, content addressing. These are computer science and programing language primitives.


Boris  
They're not owned by anyone, and it should be a kind of purity test of Are you web three enough? So in some ways we have to go back and say, "What do we mean by this? And so how far along are we in our journey?" Well, we're currently in the journey where a bunch of grifters and various bad actors have made the term Web 3 be, a bad term for many people.


Boris  
I don't really know what to do about that other than to showcase good things that are happening. There's a parallel or related movement that, we'll call the label, D Web. And I'd say another related term would be Fediverse, originally meaning activity hub standards. That's happening with Mastodon, there's  a lot of people migrating to that.


Boris  
But also other P2P systems like Secure Scuttlebutt or Matrix Protocol or the P2P and so on. So lots of words, lots of different directions. Web 3, D Web Fediverse. So in some ways I think that we have to go back to first principles and say what we mean by these things. Let's make it so that we have portable identifiers.


Boris  
DID's is one of the things that Fission focuses on, that's not just blockchain accounts. Let's focus on user privacy. Most blockchain systems are completely transparent. You see every single transaction and every single action you take can be fully correlated. That's bad. It's really bad and we just accept it as normal, right? And so we need to work on some of those things.


Boris  
So what Fission is doing is,  it's focusing on building a stack that is an edge computing stack, that can address Web 2 blockchain, but also Web 3. If you want to add encrypted data, you can include some of the stacks and standards that we built on top of IPFS. If you want to have actions that happen off chain, which we do, the entire web is off chain if you think about it.


Boris  
So I think we need to have a more nuanced approach to some of these things. I'd like to see a focus on user owned data. So many people in the blockchain centric space are like, I have my account, so I own every single one of those transactions that I made on there. Not wrong based on cryptographic principles and everything else like that, but it's still far away and usually the user doesn't cache that stuff locally.
So things like, Lite clients are going to be interesting to me. But to more correctly answer your question and shop for a moment rather than just monologuing, I think we've made really good progress. I think right now when you're interviewing me, we're ten days, two weeks into this amazing flourishing of people looking past Twitter and saying, "Maybe I do want to join a shared server and move onto social media that is run by small servers powered by Mastodon or Pleroma or other activitypub software.


Boris  
And I think that's a really exciting turning point, that I personally haven't seen since the early 2000.


Citizen Cosmos  
A lot of things resonate there because, I'm making notes as we go, as I usually do,  and I don't know which way to go because a lot of the things you mentioned, I'm like, I need to get that.  I'm going to try. I'm going to try. So first of all, about terms and I mean, I can go further.
There is the term metaverse, which is a synonym for the Internet, in my opinion, being sold under a crazy source of, I don't even know what source it is. But that is one thing, you know, that is crazy thing. But one thing I did want to get more into is that you mentioned the whole case with Twitter and Mastodon and the centralized social service thing, social networking. It is interesting because I have partially as a project and me personally, we have worked very closely with a project that is working also with content addressing and creating a distributed model of communication, but not not talking about that. What I do want to mention is that what I have personally found when I was trying to work with the guys and what we are still finding very hard and this is something I've seen in your blog, is about marketing decentralization that people were completely unready and just really, not wanting to use that because it's simply doesn't matter if it's decentralized, they don't care.


Citizen Cosmos  
It doesn't matter if  nobody owns your data that you own all the data. People just do not want to simply touch things, they don't want to touch. They don't want to go beyond their, and I'm really sorry, apologies to say that to everybody, but beyond the responsibility bubble. So the question is, how do we proceed on with marketing?


Citizen Cosmos  
And I'm going to put a label on it, but how do you proceed on with explaining to everybody that what we are labeling here as Web 3, that it's not a bad thing, that, yes, there is going to be some responsibility, there is going to be some differences, but in the long term, this is what's going to benefit you.


Citizen Cosmos  
This is what's going to help those companies, those big three companies, five companies, stop from using you to their own desires as they intend. So the question is very long term resume, how do we go on about marketing? And this is something I've seen in your blog that I would love to hear more from your opinion here.


Boris  
Sure. First of all, walk the talk. How many Web 3 companies published to Medium without even bothering to map their own domain to it? You can't even be bothered to do it yourself. So, I think that's the start. Walk the talk in those sorts of ways. From my long involvement with open source. One of the phrases that I like to say is when I got started in open source in the early 2000, it was still a radical act. It isn't anymore today, and it leads to , a lot of developers, not really engaging with it in a certain way. Some of this is just simply, how do we work together, how do we pool effort? There are a lot of financial incentives for everybody to build their own thing, but for the long term, what you really want is high quality standards and implementations that  have a diverse set of maintenance and contributions over time.


Boris  
So I would also ask, how many of your upstream opensource dependencies are you supporting? If you're not supporting them, why not? So I think a lot of thisis movement building, is what it comes down to. Movement building takes a long time. To the point of marketing, you can't just keep telling people well in the long term it's the right thing to do. And that applies to open source software as well. What are some things that you can get immediately, that are different, that enables different things? I hear a number of projects who talk about thingslike banking the unbanked. I'm like, that's amazing. That's an amazing focus.


Citizen Cosmos  
I was just making a comment. I wasn't gonna interrupt you, but I was saying, Let's do the opposite. Let's unbanked the banked and not bank the unbanked.


Boris  
Oh,  that's a great.


Citizen Cosmos  
Let's, do the opposite.


Boris  
Unbanked the the banked. Yeah.


Citizen Cosmos  
I love that is what we need to do. Not bank the unbanked. Let's not give them banking, they don't need it. They need to unbank the banked, But I'm sorry to interrupt you. Sorry. 


Boris  
No, not at all.It's fantastic. Let's at least get some fun clips out of this, right. So I'm like, that's amazing. Are you spending some time on the ground in Southeast Asia or Africa or parts of South America or other places like this? I think that's another thing that I'd like to see more of. When I was getting started with open source since the early 2000 and frankly, the vast majority of people participating in open source were young white males in North America and Western Europe, because also those were the areas of the world that were online, who had high speed Internet at the very beginning that was connected and so on.


Boris  
Early 2000, where barely out of the dial up times at that point. And so today we really do have the whole world online. So we have a responsibility to get more people involved in different ways and then really address local problems, right. We have members on our team in Africa who don't have stable home Internet. They actually use a mobile hotspot to connect, and that's fairly common. So can we use edge applications and IPFS to message and share data, peer to peer? So those are the sorts of things that I'd want to be looking for. Yes, it's incredibly hard, but a lot of the Web 3 space is developers sitting in front of a laptop or desktop with a large professional desktop operating system, building applications in fullscreen.


Boris  
If your stuff doesn't work on mobile and you only can use it with a browser extension, you're not building for the whole world.


Citizen Cosmos  
I would go absolutely further here. You know, you're saying build it in fullscreen. We'd be lucky if some people test on certain, like safari even. That don't bother you know. I'm not an Apple user myself but still Jesus at least, Jesus, has got nothing to do with it. Test him as well. Definitely.


Citizen Cosmos  
But exactly. This is ridiculous. It's a lot of people when you start to talk to people more and more and I have been myself down that road, I have been in Middle East, I have been living the Middle East, I've been in Asia, living in Asia, in Africa. And you see those things. This is a different world. And you know, when you're born today, a white male in Europe, or in the States, you're a very lucky person, to be honest.


Citizen Cosmos  
You're like in the 5%, if not less. And people just really don't want to see beyond that. They forget the 80-20 parroted that the 80 and the people forget that it applies to everything, not just to finance. It's interesting.


Boris  
Yeah. And I think I can rant a lot on mobile. I was onboarding people and explaining what was happening with blockchains, and there's this interesting stuff that was happening and I was onboarding people initially with Dogecoin. There's a good app on iOS and I'd get people to download an Android or iOS wallet and I'd send them. I get them to set up a wallet and I'd send them some Dogecoin and I onboarded tons of people in person.


Boris  
And then when I started working with Etherium, I created my own Boris coin. Just as an example, same thing, and I would get people to download a wallet at the time, Trust Wallet, when it was an open source project before it got purchased by Binance, really great mobile, open source on iOS and Android, and I'd get them right there, to do that.


Boris  
And of course, a lot of people who were deep into crypto were like, I don't have a wallet on my phone. Again, this is how people primarily out of the world, is they have a mobile phone as their one and only computing device, that is the majority of the planet. And so we have to practice these things. So again, what is the immediate utility?


Boris  
And in fact there's some interesting surprise and delight that you could do when you start to understand the system. You could do some of these things with a regular website or a database or so on, but it starts to click after a while where it's like, Oh, you have this QR code and you can scan something and I could pass you something back and forth. How do you create Boris coin? Why does it have your face on it? And I've been doing that, you know, I've onboarded three or 400 people in person to encourage them to create a wallet on mobile. So I think those are the sorts of things, again, okay, now that we're out in the real world with a public private key pair on a secure operating system, that is biometrically locked, that can backup encrypted to cloud services. Frankly, that's better than a desktop with a browser extension.


Boris  
And I'm really excited my friend Pedro, building Wallet Connect. That of course, connects those phone wallets to browsers and lots of other things as well. Right. We've come a long way and what are we going to do with it?


Citizen Cosmos  
I think that is actually the biggest question. But this is interesting that you say that because the next question I have for you, you know, I like to go on projects', websites. I like to think of myself as a little bit of a product person. And so one of the things I do is I go on to project websites and one of the first things, what they say too, I'm looking at one of some of the first things they say and like you said, what are we going to do with it?


Citizen Cosmos  
And this is the question exactly. So the Fission website says building protocols for the future of the Internet. What is the future? What future is the correct one? How do we know that it's correct? And where is that future?


Boris  
Yeah, great question. So I think we're a bit of a funny company and we are ultimately one of the core things that we do right now. We're a protocol engineering team. So I talk to you about building this edge app stack of identity data compute on top of IPFS. We really think that content addressing is huge, unlike location based addressing. Right now, If you run a server at example dot com, no one else can help you host example dot com. Let's say an actual file, example dot com slash forest dor jpeg. No one else can help host that file. They could download it and they can put it on their own server. My server dot com slash forest dot jpeg, but we don't know it's the same one.


Boris  
In fact, it doesn't share between the two. And once you put content, whether it's an app or files or data or something that's encrypted onto content addressing, amazing. We do all sorts of different interesting caching. So if you have a podcast that I really like, I can help keep it online. I know that that podcast hasn't been edited because it has a unique content address and I can save it, literally even just on my desktop or on my phone.


Boris  
And then when people around me are requesting it, I'm helping keep it online. That's this really nice commons network of IPFS. However, in practically leaning in and and trying to use IPFS for apps for an entire apps and for read right of IPFS and adding that, we found that the IPFS protocol itself still needed work, so we ended up getting sucked in and rather than just working on our dev tool stack, we went on a multi-year journey of working with extended IPFS and file point ecosystems, in improving the protocol itself.


Boris  
So that's kind of what we mean by that. Brooklyn's Zelenka my co-founder and CTO, she developed UCAN, which is decentralized off protocol that's getting some really good adoption. All of these things we end up developing is open standards. One of the downsides of IPFS was that everything was made public, so Brook developed the web native file system IFS, which is a way for users, apps and servers to have encrypted data on top of IPFS in a turnkey way.


Boris  
And so what is the future of the Internet? I think part of it is having things more user centric, having portable data, having something that's content address. That means you could do everything from mobile, to servers, to embedded devices and everything else like that. In a way that is a really interesting open way, including self verifying data. And a lot of things need to be secured by cryptographic tokens and signing in different ways.


Boris  
So killing the password. I think also today that user data has become a toxic asset. If you are running a service that has lots of user data, you can get hacked and if you don't keep it encrypted, it can get stolen. So I think it's important for more and more data to be end to end encrypted and encrypted at rest.


Boris  
I sometimes joke and I say that if Apple of Apple's iCloud and their system in general was open source, then Fission wouldn't have to build what it's building, right? That mode where instead of everything going through separate servers, you've got your own devices at the edge, you've got local computation doing things like machine learning and other things like that and things being fully encrypted.


Boris  
And so what we want to do is both build protocols and that needs standards. So it's not just us, it's not just a chunk of open source code. It's one level more important than open source code, which is the spec. So multiple people can implement it in multiple different programing languages and know that they have interoperable and then use those building blocks to build these more user  Protecting applications and services. That's where we're heading.


Citizen Cosmos  
I like this future and hopefully it doesn't contain the word on chain status, because it's one of the biggest scams right now, on chain. You're on chain. What? I mean, I'm on chain. I've already been on chain all my life, and the computers are connected. Sorry, I'm going in on a different thing. I do want to talk a little bit about storage and about the IDs.


Citizen Cosmos  
But you mentioned the word interoperability. And of course, you know, having such a name is Citizen Cosmos. I cannot help to ask, are you guys currently ,I know you are because of been on your GitHub, but let's make it public or let's talk about it. Are you guys at all building anything for the Cosmos ecosystem? Are you currently working just with Etherium?


Citizen Cosmos  
Well, of course not, because we also are working with IPFS, which means you're kind of working with anything that wants to store anything, which means you are working with Cosmos. But I'll shut up and let you answer. Sorry.


Boris  
So we're really focusing on stack right at the edge, and it composes well with any blockchain. So we've done a proof of concept that we call Wallet Off, where people can use existing blockchain what's on any chain to use their existing keys as a DID. And then we pair that with an encrypted winifest file system on IPFS. We haven't done this yet for any Cosmos based chains.


Boris  
Theoretically, parts of this should work with the EVMOS and other chains that include an EVM. This is a public call. All of our stuff is open source. We'd love to see some proof of concepts of doing that. We also work with the Chain Agnostic Standards Alliance, CASA. That's something I was involved with with the very beginning with Pedro from Wallet Connect and now Wigi from the Ethereum Foundation to not have to reinvent the wheel.


Boris  
We're having a discussion with Brave and their built in wallet . Met with the Metamask team and others on on standards for using wallets and the public private keys there, to the proper way to encrypt and decrypt data in a standardized way. So we're always working on those sorts of things. And then personally, just having come back from Lisbon, IPFS Camp Protocol Labs Summit of Filecoin Lisbon, lots of things happening there.


Boris  
We think Filecoin is unique. So IPFS is awesome, works everywhere, in many ways. Content addressing has won and continues to win it really interesting ways. It's a commons network. It's best effort. People say, "That's terrible. What if it goes away?" And I say the flip side, "Literally any piece of content that any human on the planet cares about, they can keep it online themselves effectively for free, effectively forever." That's a really good use case. Incentivized Persistence. Paying for persistence is also very important and Filecoin being a chain that has focused on that is great. And the next challenge is interacting with lots of other systems of all kinds. So one of the things that we kicked off is a new working group. There's going to be a Filecoin interchain and bridge working group.


Boris  
I know where there were some early discussions already of Cosmos Ecosystem as one of the first places to bridge into. That's really where I see this work. Happy to talk more about this, come see us come check out our code and our stuff composes really, really nicely with any sort of chain.


Citizen Cosmos  
I think I'm definitely going to try and get the cyber team to look at what you do, and I suggest you guys look at them because they were. Yes, I'm a bit biased, but they were the first Cosmos chain to work with IPFS  three or four years ago already, and they use IPFS as basically the heart of the system.


Boris  
Amazing.


Citizen Cosmos  
That's all built on that. So yeah, I think you guys might have a lot of... it's completely open source. So maybe there are some libraries that you use then I'll definitely do the same thing for them. Talking though, about file coding and about storage. DID's is another topic I would love to talk about, but for a second about file coding and storage. So there is the devil's advocate thing and there's the good thing, the devil's advocate thing, which I would also love to hear your opinion is that I would like to separate, IPFS and Filecoin, right? I think it's like IPFS is a cool thing in there is Filecoin with a little bit of, well, I don't know, there is questions to be asked and there's questions to be answered and this is actually a question to you, not to me. Do you think that if Filecoin would go away tomorrow, including the foundation and the money the foundation has, would IPFS still be around considering what it is?


Boris  
Yeah, it's commons network. It literally can't go away at this point. So a lot of people point at it as saying that as a downside. Oh well how do you know it's going to stay online? Well, how do you know a website is going to stay online? It's the same. Someone has to do work, possibly pay for resources to keep things online, keep things fast and everything else like that.


Boris  
I think we're in a really tough spot in this Web 2 ad supported world, where a lot of people in the world have been trained that everything on the Internet is free. And there's two parts to this. One is let's use a completely made up example, a JPEG on the Internet. It doesn't cost anything. It doesn't hurt anyone if you copy those bits.


Boris  
Amazing, abundance. Creative commons licensing, a bunch of other things like this that allows for reuse and mixing, it doesn't cost anything. That's amazing. That's a fantastic place, that we should have this abundance mindset around it. Same thing with open source code. The bits of code that you have checked in the GitHub repository, download it, make a copy.


Boris  
It doesn't hurt, doesn't subtract from that. But, at scale this does cost a lot. And in fact the interesting thing is that bandwidth, if you have some services at at Amazon and you're using S3 and S3 was the first service that Amazon launched. I launched some Drupal hosting services in the early days in 2005. So this was about 18 months before Amazon launched S3 or any other AWS services.


Boris  
So we had to run a lot of bare metal or vps's and do all that stuff ourselves, and it was a lot harder. But anyway, with Amazon S3, you pay a relatively small amount for storage and the cost for bandwidth is five X that. I actually had someone approached me. They're were like, Oh, Fission, you know, we're trying to check out at IPFS.


Boris  
Really interesting things. You know, we're hosting some stuff on vsekl right now, but we got a bandwidth bill for $1,000 last month. I'm like, Yeah, can IPFS make that cheaper? I'm like, Probably not. It depends on the use case and a bunch of other things like that.There's some really interesting deduplication use places for IPFS, but if you need to persistently keep something online, whether it's IPFS or a commercial hosting service like those things vsel.
You still going to have to pay for bandwidth in some ways, unless you and if you want it to be fast, you may need to do some caching and that's either running stuff yourself or paying someone to run it. And this comes down to I'll do the open source thing again, right? So the code is free. If you file an issue, there's only so many maintainers with only so much time. Being in the community writing documents and troubleshooting things, maintaining it, right?


Boris  
If you build something in JavaScript approximately a week later, if you have any sort of normal dependencies, you'll need to update five different dependencies. And that's work that has to be done by someone.  I think that's something to keep in mind generally that protocols like IPFS are not going to go away and they give us the capabilities to work on a commons network together.


Boris  
But people shouldn't be surprised if they start needing to think about how they help themselves, their users, their partners, their friends, their countries, the regions, do stuff. That's the part that we need to start making 100% the part of Web 3. Not the lip service part, but saying a responsibility to work together with others to maintain the things that are important.


Citizen Cosmos  
I think that people really underestimate how much, myself included.,I think, to be honest, until a certain point in my life, how much of a big a role communication is in everything. Whether it's money, whether it's religion, whether it's software, whether it's anything in relationships, it's all communication. And when we have a middleman there, then we shouldn't be surprised that something doesn't go our way.


Citizen Cosmos  
There's a middleman there, that has a subjective opinion. Whether it's God or whether it's somebody, an administrator on a server, it's still a middleman. So...


Boris  
Exactly. And I wanted to bridge it a little toFilecoin. So we can say things like storage is effectively free, asterix. We have terabytes on our local machines. We've terabytes on our phone and other things like that. But the people time for maintaining servers and services and code, that's not free. And then if you scale it up, if you say I need to keep around petabytes of climate data, okay. Okay, Now we're talking about we need raid arrays and we need servers and we need someone has to do the work and oh, you know what? It's really important data. So we should probably make sure that we have at least one offsite backup. That's somewhere else as well. That's work, right? We've had this long phrase where we considered the cloud to be this thing over the air that someone else takes care of.


Boris  
And you could do that. There's a bunch of people that will pay you services that you pay for, for those things. So I see Filecoin, that let's make sure this is backed up in three locations and there is a marketplace where multiple providers can say, I have a good data center and I'll properly back it up and all that stuff. Something like that, if that layer needs to exist, which is why Fission chose to work with Filecoin.


Boris  
Basically, if Filecoin didn't exist, it's the exact sort of thing that we would work on building. And whether it's IPFS or Filecoin, I think that's the other thing is we looked at it and of course one or two years ago, I'd be on here shilling Fissioncoin, and Fissioncoin was going to solve storage and a lot of the stuff doesn't work very well yet.


Boris  
So where are we in our journey? We're in our journey that we need to pick some solutions that are going to work, that are going to survive into the future. And we need to make them better and we need to keep solving people's problems. And whether it's fiat dollars or tokens, we need to pay for services, so that other people keep servers on and files online.


Citizen Cosmos  
I guess this was my initial question and I might have asked i t a little bit wrong, but what I was trying to get at is exactly the right word is not whether if Filecoin will go and IPFS will disappear, but more as what if there will be no market that will reward that work? Will it still? I mean, of course something else will be invented.


Citizen Cosmos  
That is the obvious answer. And this is how markets work and live. So I guess, yeah, the question you already already answered.


Boris  
So yeah, you could persist IPFS in a number of different ways. One of those things is that you could, Fission essentially has had an extremely long extended beta where we persist things for people that have accounts on our system and we run on a number of different services, including AWS and there's people that you could pay a regular style subscription to get persistence as well.


Boris  
So I think that's the important thing for protocols, is that you can mix and match these things. I think it's really interesting and important to not just have, once you have open protocols and markets around things like storage for Filecoin, then you can have people who take a whole different set of approaches. Some people might build a commercial offering for enterprise for self-driving cars.


Boris  
I think they do something. I think I was reading four terabytes of data, per day in telemetry and sensor readings. And again, imagine building an offering just for that data. Yeah, there's a great business there, and if for that business using Filecoin or some other decentralized storage is a good fit and works for them, and just because it's decentralized isn't going to make it win.


Citizen Cosmos  
It's another topic, I think a huge hot topic for discussion of decentralization and philosophy and blockchain are not the same thing and people really need to get to that. While still we on the topic of storage, one last question, I guess on storage, I have seen several different solutions so far into storage and whether it's Storj or a Sia or a Blue Zelle or Zero Chain or IPFS or whatever, I'm trying to look for the right word not to offend anyone here, but there is always something like economics and Filecoin or like nothing is working in Storj.


Citizen Cosmos  
There's always something out there that is I mean, there is I don't know if you're familiar with CKB Nervos Network, and I guess that is a very elegant solution that I've seen. But still, it's not exactly storage. It's just an interesting solution to what they're building. But it's an independent silo, I guess, in terms of what they are doing now.


Citizen Cosmos  
So the question is, isn't this the most simple solution here? I mean, the question is what would be the most simple solution? But I'm going to try to give an example of what comes to my mind as a simple is instead of making decentralized computation machines, why not also make decentralized disks, machines? You know, we already runingblockchains machines which make decentralized, distributed computations.


Citizen Cosmos  
Why not distribute the storage as well? Why not, each machine is just a hard drive, you know, why not? It sounds simple, but so the question is like, which way do you think we should go? Or should we just stay right now with the Commons network that we have with IPFS and everybody should really chip in and develop that.


Boris  
Why not both? So I think a bunch of people are going to, I will advocate and shill for content addressing. Content addressing is amazing. I'm going to keep saying this. It has a way for us to any file in the universe, has a hash, has a content address that's self verifying, and it won't change. That's amazing. And as an attribute it means you can do some really, really interesting caching and transmission, in different ways.


Boris  
So that's the promise basically of some of these things. So some of this is the long steady work of standards and any interop where all of the systems that you mentioned could expose their persisted content as the content address. And then all of a sudden we can have a number of different... we can come together and know that the content address is unique, how we fetch it, whether we have permission to fetch it, whether because of the type of account we have, it might be faster or slower to fetch such a thing.


Boris  
All of those things can be layered on top in different ways, but we know that this content address is the address of that asset, that media, that content, whatever it is, and wecan go to multiple different places and get it. We don't really have that today at that layer. So that's why I try and open people's minds is that, oh yeah, this is possible.


Boris  
There is a way you can see if you can fetch that thing. And the answer might be, I don't have it. You need to find it somewhere else or it's permissioned or other things like that. So I think that ultimately that's one of those pieces that come together. And it's very important for me because even without export formats or anything else like that for the user, if their data is not tightly coupled to a server address, a location address, if it instead is used as a content address, that already means that systems that understand content addressing, that data will just work with those systems.


Boris  
So again, that sidesteps the whole question of use chain X use company Y, and be like, how do you speak content addressing?


Citizen Cosmos  
I definitely agree, to be honest, was just like a question to go further. Start with saving snapshots in IPFS blockchain snapshots, because I think that is one thing that is really missing. Another thing is every thought has a hash, Jesus, everything has a hash. Jesus has a hash probably and you know, again, I'm sorry to offend all the religious guys out there, but it'strue, you know, every thought has a hash and we can connect it all into the big brain and work together with it.


Citizen Cosmos  
Quick question on the DIDs before we resume. I had an interesting podcast guest. We had a very fascinating conversation. It was about a year ago, I would assume, and it had a very certain approach to the DIDs and into the way they deal with it. And one question that I would like to ask you that I asked them is, isn't the best kind of the DIDs just a private and a public key pair?


Citizen Cosmos  
And that kind of solves pretty much everything out there. Do we need anything beyond that?


Boris  
These are some of the areas where we bridge to different standards in different ways. So DIDs are a recommendation now from the W3C, which works on web standards. The stuff that Fission works on goes beyond the web, at the network layer and other layers. So we look at and use standards when we can, when it makes sense, when it fits our requirements.


Boris  
So for example, the web crypto API is built into every browser, including mobile browsers and what the web native stack, the SDK that the developers can use from us today uses by default out of the box. So there's a non exportable private key in your browser that web crypto API, but not in userspace were it can stolen, but not exportable.


Boris  
So every browser has that. So Mobile Safari or Brave on your desktop. All of these things support the web crypto API. And so we use that to derive a DID from just that public private key pair. So DID Key. I think there's over 200 different DID types. A lot of people think about identity and authentication services and they say, if I could charge just a few cents for every identity in the world, I will make a lot of money.


Boris  
So there's a lot of motivation to do a number of different DIDs. And there's the XQCD comic with lots of different standards and so on. We find it useful to have a decentralized identifier, a decentralized identifier, not identity. Your browser is not you. Especially we have browsers on multiple same, you have multiple identifiers. Right? That and that's not even talking about username or anything else like that.


Boris  
Blockchain space unfortunately has over focused on, I use the same goddam public private key pare for every single app and then if it's compatible I cross chains and use it again for every single app. Thus opening. We've done a terrible job of advocating for the user here and it's going to have to evolve beyond that. We have to have some privacy in there.


Boris  
So DID Key is a good starting point. It's pretty bare and you don't really know what you're getting, so there's not many constraints on it. DID PKH is one that works across chains and generally you should be able to use any blockchain key type and derive an address that you can then use DID PKH. I think there's some other useful ones.


Boris  
I don't have the whole list in front of me. There's some web based stuff that have some tradeoffs of ease of use versus possibly people hosting stuff for you and another stuff like that. But ultimately reusable identifiers controlled by the user that they can take with them, is how you should think about it. And of some of the existing DID work has been around very large enterprising systems.


Boris  
What Fission has worked on, is running code and rough consensus. That's the phrase from the ITF of like this should be something that should be drop in simple that frontend developers can just use to create accounts for their users. A hackathon right? If we don't get that right, if the first step is run a giant Java server in a corporate data center, you're not going to get adoption, because it's going to be too hard. And we'll see where the rest of the 200 list of the DID types end up.


Citizen Cosmos  
I guess the answer here is basically usability and privacy, right? This is why it's not the point, you need usability and privacy. By the way, talking about a person who wanted to give a couple of cents their identity, some comes to mind here. You know, maybe that's the way is giving 8 billion back to the world. Now I'm talking about from FTX of course but yeah a bad joke. I know, bad joke. Boris. I still have a lot of questions to ask, but to resume, I'm going to do a quick blitz that we do with every guest podcasts and their abilities and then blitz. Can you plural the word blitz? God knows. 


Boris  
Sure. 


Citizen Cosmos  
Give me three projects, outside of the top 20 preferably. So not Filecoin and Etherium and Bitcoin that you are interested in terms of what they do technologically these days, watching them and watching what they're building.


Boris  
Yeah, I met the team at the KOII Network. They're doing some very interesting things and lots of people, even running servers at home. So I think there's some interesting stuff that they are doing, KOII dot network. I'm literally just going to list you people that I met in Lisbon, the Function Land team also thinking about some home storage in different ways.


Boris  
And then the last one is one that I'm really excited about, that we're going to be doing some more support for, which is Cappy Loon. So Cappy Loon is taking the original Firefox OS and a mobile operating system. It's since been forked called KaiOS and is used heavily in India with tens, hundreds of millions of feature phones in India.


Boris  
And so Fabrice from Cappy Loon has in turn forked it. And he's building a mobile Firefox OS called Cappy Loon that includes D Web built in. So things like IPFS out of the box all and I think hardware and open hardware and mobile app stores, that's a whole other battle to fight that you can't really fight head on for a variety of reasons, including user safety.


Boris  
You know, those mobile operating systems are in fact quite safe and secure for the average user. But Cappy Loon is very exciting, and I think there's some really interesting things that that might be coming in that direction.


Citizen Cosmos  
It's a shame we didn't meet in Lisbon because I was also there but we didn't cross pths there. Second question, give me two things on top of your mind right now that motivate you to do what it is you do. And I'm not talking about writing code, I'm talking about Believing in all the values that you've been talking about over the past hour and building what it is you're building, the two daily things that motivate you in your daily life, To do whatever it is you do.


Boris  
So I started building in open source that was more around like the basics, getting content online with blogging and CMS platforms like Drupal and WordPress and others, and standards like RSS. I've been blogging for over 20 years and RSS was an amazing entry into that, talking to people all over the world again, which is commonplace today.


Boris  
But think of like a cozy group of pen pals around the world that you mayberead three posts a day rather than three posts a second, as we do today. And so that motivation was important for everyone, for individuals to be able to put stuff online and communicate that way directly. And what we've seen is ultimately a lot of those platforms are too complicated to run their security issues.


Boris  
The lamp stack architecture means you're running these entire servers and we need to make it ever more simple so that people can communicate directly and share things that they care about and communicate about very important topics. And so in many ways, I'm back because mission wasn't completed the first time around. And I think it's important that we have easy ways for people to communicate to collaborate, to work on things together.


Boris  
Sometimes that means facilities for pooling capital together. That other thing has been perhaps made easier by parts of Web 3. For, and now the pause to solve the really hard problems that we have ahead of us. So can we connect in our local community? Can we support and buy local? Can we then connect to other people who are on the other side of the world who are in their own local area, but maybe facing similar challenges?


Boris  
And can we share the knowledge and information that we have from code to apps to capital to to anything else to build together? And can we demand more of our local, regional and national governments to act in the same way? Here's a weird thing. In the U.S. lots of information, lots of data is required to be publicly available, that's paid for by government funds. In Canada, where I live, things that are produced by the government are usually by default, covered under King's Copyright. But I literally fucking paid for this. It should be available to the country. So even some of these principles of design, of decentralized systems, of open information, you know, how do we bake these in?


Boris  
In a way, you're going to hear me say it again. That protects user privacy, that keeps people from harm. That means collectives of people can work on things and support each other in getting stuff done. If it doesn't fall into those categories.


Citizen Cosmos  
I just want to say like one more in the belief, the question. But before I say that's one thing, as an Islander, I definitely understand about what it means to connect local communities. And you're talking about just pay for the thing. Well. What surprises me more is that when you have your own land and then you have to get paid to get buried on the cemetery. But wait a second, I have my own land. I want to get buried here. I don't want to go to the cemetery and. No, no, no, no, no. That doesn't work like that. Last question. One person. Does it matter? Developer, writer, philosopher, Bitcoin or not? Crypto guy, medium GitHub account. Twitter doesn't matter. A book. One person you suggest everybody else out there to follow or to read.


Boris  
I'm going to say two.


Citizen Cosmos  
Okay, two is good, two is better.


Boris  
Firstly, everyone should read, Ostrom. Elinor Ostrom wrote about Commons and how to sustain Commons. And then the other one is Christine Lemmer-Webber. She is the architect of the activitypub spec. She's done a amazing work around Ocap capabilities model for security. She's got a new nonprofit called The Spritely Institute that is working on doing secure capabilities in a distributed way.


Boris  
And I'm really excited to see how her work powers a number of different things. So check out Christine  Lemmer-Webber at Sprightly and Read Ostrom.


Citizen Cosmos  
Boris, thank you very, very much. Of course, the show notes will contain all that and of course all the links to Fission. So thank you very, very much for finding the time to join me. Everybody else, thank you too. Thank you for listening.


Boris  
It's been awesome. Thank you very much for the opportunity.


Citizen Cosmos  
Thanks. Bye.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

If you would like to support our mission in creating educational content and aligning the goals of different communities, please stake with us [here](https://www.citizencosmos.space/staking): 

- [EVMOS](https://wallet.keplr.app/chains/evmos?modal=validator&chain=evmos_9001-2&validator_address=evmosvaloper1mtwvpdd57gpkyejd566s24afr9zm5ryq8gwpvj) 
- [ATOM](https://wallet.keplr.app/chains/cosmos-hub?modal=validator&chain=cosmoshub-4&validator_address=cosmosvaloper1e859xaue4k2jzqw20cv6l7p3tmc378pc3k8g2u) 
- [BOOT](https://wallet.keplr.app/chains/bostrom?modal=validator&chain=bostrom&validator_address=bostromvaloper1f7nx65pmayfenpfwzwaamwas4ygmvalqj6dz5r)

Join our [community](https://discord.gg/kJaG3EucCX), to build a future where communication is decentralized. May the code be with you!