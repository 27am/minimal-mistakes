---
layout: post
title: "Advanced Blockchain Storage"
description: "No description"
comments: false
---

InterPlanetary File System (IPFS) is a peer to peer distributed file system. It provides storage models that are content addressed and take advantage of cryptographic data structures as Distributed Hash Tables and Merkle Directed Acyclic Graphs (MDAGs) with the declared purpose of constituting the filesystem of all the connected computers.<br>
<br>
Filecoin is a cryptocurrency that lays on top of IPFS as incentive layer to host files in exchange for valuable tokens. It builds a marketplace for bidding between providers and consumers.<br>
There are two kind of nodes in the system: Storage nodes and Retrieval nodes, since the philosophy of the solution is to separate the roles.<br>
When a client wants to upload a file, it is encrypted and fragmented and the pieces are sent to different Storage nodes. In this phase the level of redundancy is selected, and data chunks are replicated accordingly. Moreover, the location of those nodes can be extracted only knowing the private key of the file, as an additional safety and privacy precaution. This association is kept in the so-called allocation table and is stored on the Filecoin Blockchain.<br>
<br>
StorJ and Sia are similar to, and competitor of Filecoin. They are both decentralized cloud storage products although the first takes advantage of the Ethereum blockchain while the second builds its own. <br>
<br>
Finally, BigChainDB is a data storage solution that stands in a common ground between databases and blockchain. It inherits several good properties from the two worlds: decentralization, high transaction throughput, small delay, quick query and response time. Moreover, it has recently been extended to be Byzantine Fault Tolerant for up to one third of nodes.<br>
<br>