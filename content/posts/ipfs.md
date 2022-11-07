---
title: "Modern Peer to Peer?"
date: 2022-11-06T20:41:07-07:00
draft: false
tags: ["p2p"]
---

Last time I wrote about _modern peer to peer_ software techniques.
So what do I mean by _modern_?
Well a lot has happened in the peer to peer space since I first learned about it as a teenager (90s) when my dad was building a desktop genealogy app that would allow you to network with relatives to share your family trees.
First there are software frameworks and protocols that abstract the core composable components of peer to peer networks.
[Libp2p](https://libp2p.io/) is one such protocol.
Second blockchains became mainstream.
If I were to over simplify why blockchains have created a new wave of interest and investment in peer to peer technologies here is what I would say:
We have had the technology to create large robust peer to peer networks but we didn't have a reason too.
More specifically we didn't have a reason to create free and open networks where anyone could join.
There are challenges with such a large open network, to name one: what happens when someone joins who only wants to troll everyone else on the network or worse harm other users?
Additionally the internet was relatively simple and quite decentralized to begin with, so in some ways we already thought we had robust peer to peer networks.
However eventually the internet became very centralized around a few actors with immense control and influence over how the internet operates.
Blockchains provide a new solution to both of these problems by creating an incentive structure that means both consumers and providers want to participate in the same network.
The network becomes this environment where users can join the network to get access to services from providers who they do not have to trust beyond their observable behavior on the network.
So now with both the incentives and the investment in network protocols we can start to build networks and provide services on those networks outside the centralized internet of today.

In fact this blog is one such example, it is hosted on a peer to peer network called [IPFS](ipfs.io).
However unless you already know what that is it is likely you are viewing this site via a gateway that exists on the _centralized_ part of the internet, like any other site you have ever visited.
So let's try something new: connect to this site using the IPFS network in two steps:

1. Download and install the [Brave](https://brave.com/) browser
2. [Open this link in Brave](ipfs://bafybeid67ux4amfz6n5bscpqgc43pexweiyj6q5hyn4ayum4fdjgqruv6y)

Brave is one of the early adopters of this technology and they have implemented native support for connecting the IPFS network.
There are many things different between the _centralized_ internet and the IPFS peer to peer network, we can cover those in a later post, but one thing they have in common are links.
Both networks use links to navigate between content on the network.
As a result browsing this site via the IPFS network will look and feel exactly the same as the normal internet because its the same content with slightly different links.

One last thought, do you remember the early days of search engines? Altavista is the one I remember using, anyways IPFS doesn't really have a search engine today.
So to use it you need someone to share a link to some content that exists on the network and go from there.
But we are in luck, [Wikipedia](ipfs://bafybeiaysi4s6lnjev27ln5icwm6tueaw2vdykrtjkwiphwekaywqhcjze) exists on IPFS so you can go down rabbit holes forever until you forget that you are even using a new peer to peer technology.
Oh and IPFS can be slow, so pretend you are on a nostalgic trip where you are browsing the internet without search engines and on a 56Kbps modem.

