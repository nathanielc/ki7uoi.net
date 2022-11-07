---
title: "o/"
date: 2022-11-06T17:18:43-07:00
draft: false
tags: ["p2p", "ham"]
---

However you found this blog, welcome!
I am Nathaniel Cook, call KI7UOI.
This blog represents an experiment in documenting my journey learning how to bring peer to peer software to the world of amateur radio.
Here are some of my initial thoughts many of which are likely naive and ignorant at this stage in my journey.

Most ham radio software uses ad hoc peer to peer networking.
For example the [APRS-IS](https://www.aprs-is.net/) system is a peer to peer software system that propagate APRS packets around the world.
There are [8 core servers](https://www.aprs-is.net/APRSServers.aspx) that serve APRS traffic for the whole world.
They can be found using the `rotate.aprs.net` DNS name that has 8 A records.
Beyond those 8 core servers there are ~20 tier 2 servers that are regionally based.
I believe the core servers are a fully connected network and then the tier2 servers connect to exactly one core server.
Then clients connect to a tier2 server and supply a filter for the subset of the traffic they wish to consume.
In short, the network topology is static, the routing between tier2 servers does not handle loops, hence connecting to exactly one upstream server.
Additionally core servers use the [q algorithm](https://www.aprs-is.net/qalgorithm.aspx) to communicate and forward packets to each other and to tier2 servers.
A quick read of the algorithm shows its a basic set of ad hoc rules.

Ham Operators are inherently familiar with peer to peer communication.
After all talking on a radio with someone is peer to peer.
Additionally hams are familiar with different network topologies, i.e. repeaters, reflectors etc.
Even talking peer to peer between two radios there might by third parties listening in.
In other words hams are operationally familiar with networks and the ways they can fail.

When you combine these two assertions about the amateur radio community they don't seem to fit.
Why do a group of people who find RF (radio frequency) networks so natural create ad hoc networks over the internet?
Perhaps that is the reason itself, RF networks are more ad hoc and so the software networks mirror that nature.
Or likely there is a desire to keep the internet side of things simple so more time can be spent working with RF.
Anyways I have two goals, understand better how hams use software networks and find places where applying more modern peer to peer networks could be a benefit to the community or at the very least be a fun space to explore.

That's it for now. I have no idea how often I'll update this, I guess we will find out together.
