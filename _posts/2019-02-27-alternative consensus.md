---
layout: post
title: "Alternative consensus"
description: "High level consideration about the research in Bitcoin"
comments: false
---

The success of Bitcoin and the so called Nakamoto consensus that scales with thousands of mining nodes caused a renewed interest in consensus protocols. 
<br>
Some have existed and used for many years, each with its system model, strengths and tradeoffs. The most notable examples are Paxos and [PBFT](http://pmg.csail.mit.edu/papers/osdi99.pdf).
<br>
From 2009 onwards, many variants have born, looking for a sweet spot in the wide variety of combinations that separate the opposite extremes of BFT and PoW.

<br>

A first and general distinction can be done about the Identity and access management (IAM) of the participant nodes of the consensus protocols. It could either be decentralized and permissionless like Bitcoin is, or permissioned and in some way managed by an entity or a federation of such.
<br>
In the latter group some prominent examples are Hyperledger, Stellar and Ripple. Those are enterprise/financial industry targeted and aim at filling the gap between companies and a disruptive technology like blockchains and Distributed Ledged Technologies (DLT) in general. 
Hyperledger for example is a modular platform that allows for multiple implementations of its components. It features PBFT in Fabric or Proof of Elapsed Time (PoET) in Sawtooth Lake, just to give an example.

<br>

Standing at the other side of the fence are Algorand and Bitcoin-NG, along with others. 
Bitcoin-NG entitles itself as the evolution of the classic Bitcoin blockchain that we started to know back in 2009. 
<br>
By introducing two types of blocks, one that contains proof of work for leader selection, and the second type collecting and propagating transactions, it reduces chain forks while allowing for faster block rate. It appears to be that the advantages surpass the negative aspects, making Bitcoin-NG an interesting candidate for future solutions.
<br>
Algorand’s approach on the other hand is Proof of Stake based, with a selection of a small committee that should vote for the next block to be appended on the blockchain. I find it to be an interesting solution for scaling Byzantine agreement to many users.


<br>
<br>

[1] <i>Blockchain Consensus Protocols in the Wild - Christian Cachin, Marko Vukolic</i>
<br><br>
[2] <i>Bitcoin-NG: A Scalable Blockchain Protocol - Ittay Eyal, Adem Efe Gencer, Emin Gün Sirer, and Robbert van Renesse</i>
<br><br>
[3] <i>Algorand: Scaling Byzantine Agreements for Cryptocurrencies - Yossi Gilad, Rotem Hemo, Silvio Micali, Georgios Vlachos, Nickolai Zeldovich</i>

