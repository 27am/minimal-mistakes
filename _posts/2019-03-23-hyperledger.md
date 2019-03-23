---
layout: post
title: "Hyperledger"
description: "An introduction"
comments: false
---

Hyperledger is an umbrella framework that encompasses a multitude of protocols for Distributed Ledger Technologies (DLTs).<br>
<br> 
It is aimed to satisfy as many industry use-cases as possible, thus avoiding the specialization on a single one as Corda did with finance. To achieve the proposed flexibility, it is structured in different projects and modules that can be selected depending on the needs. One project example is Hyperledger Fabric which is built as plug and play components such as storage type, consensus protocols etc.

Hyperledger is divided in four logical services:
* Identity services: they provide authentication and authorization for every component. Since most Hyperledger’s use cases are consortium blockchain, this is a fundamental building block
* Policy services: they encode the rules for security guarantees in the blockchain
* Blockchain service: is composed of three submodules
** Peer to Peer
o	Distributed Ledger
o	Consensus Manager
* Smart contract service: manages the decentralized programs that run on the nodes<br>
<br>

Nodes in Hyperledger’s network have different roles. Clients act on behalf of the users and send transactions to the network. The execution is “simulated” by Endorsing peers and sent back to clients who in turn ask Orderers to order them, to guarantee a global and agreed upon sequence. The final step is a validity check with respect to the encoded policies.<br>
<br>

This approach is called execute-order-validate and is a main differentiator of Hyperledger Fabric with respect to other blockchain that are based on the more traditional validate-execute paradigm. This choice is the result of the desire to boost the throughput in a real word environment, where many times the execution of non-deterministic programs leads to inconsistencies in the ledger and the consequent destruction of the security assumption.<br>
<br>

### References
