---
layout: post
title: "Scaling Blockchain"
description: "No description"
comments: false
---

One of the most limiting property about Blockchain is the number of transactions per seconds that can be processed, often referred as the scalability problem of DLTs. The most obvious modification that comes to mind like increasing block size and block proposal frequency solves only partially the issue, and at the expense of security and efficiency, because of the increased branching rate.<br>
<br>
Different investigated solutions explore the use of different kind of data structures. Instead of a one-dimensional, linear blockchain one could imagine applying a Directed Acyclic Graph. In this case the proposed block would reference numerous previous blocks, with the main caveat that consensus delay might be long, in principle even infinite. Iota’s tangle is one of the proposals in this direction.<br>
<br>
Alternative approach is to create some sort of partition in the blockchain domain, usually referred as sharding. Limiting the domain has the advantage that nodes don’t need to be aware of the overall status of the network, but only have to receive and process a fraction of the blocks. Ethereum is experimenting in this direction.<br>
<br>
Let’s now introduce the concept of Pegged Sidechain. Basically, instead of creating an altcoin from scratch, pegged sidechain anchor their value and coin generation to a parent chain, such as Bitcoin. The major property is that, despite allowing bidirectional exchange of coins between the pegged sidechains, security is siloed, preventing a breach to damage the other chain.<br>
<br>
Finally, the Lightning Network is an overlay platform that allows for quick transactions. Transacting peers generate a multisignature wallet and deposit a certain amount of coin there. From now on they can send transactions as fast as the network allows without incurring in the consensus delay because the transfer is completely transparent and orthogonal to the blockchain. Just once in a while they broadcast the account status to secure it on the blockchain.<br>
<br>

