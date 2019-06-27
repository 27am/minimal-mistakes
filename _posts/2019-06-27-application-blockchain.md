---
layout: post
title: "Applications for blockchain"
description: "No description"
comments: false
---

Blockchain has revolutionized the financial industry, providing a technical way to overcome previously unsolved problems. The same technology has been investigated for applications in different areas, most notably energy, supply chain, healthcare and internet of things. <br>
<br>
IoT in particular, presents traits that at first sight might be incompatible with the hypothesis required by the classical Bitcoin’s blockchain. IoT devices are computationally limited and might be unavailable/offline for an arbitrary amount of time. A solution that has been proposed is to cluster group of devices and delegate demanding tasks to Head nodes that provide characteristics more suited to participate in the consensus of a blockchain. This has been done for example in “LSB: A Lightweight Scalable Blockchain for IoT Security and Privacy” where, as an optimization, they introduce something similar to a reputation system to prevent a node having to validate all the transactions. Basically, what happens is that nodes responsible to execute the consensus algorithm, keep and update a trust table with information about the nodes that proposed both valid or invalid blocks. The principle behind the table is that if the node believes another peer to be trustworthy, it can skip some validation work. Another feature presented is the Dynamically Adjusted Throughput algorithm, put in place to facilitate scalability in presence of big numbers of participating nodes. Moreover, the consensus algorithm is a breed similar to Proof of Elapsed time without the deployment of the Trusted Execution Environment. Security properties hold because head nodes keep a list about the allowed participants, making the system a permissioned blockchain. <br>
<br>
Different, investigated scenario is the Energy system. Finding a way to trade dynamically shares of electricity is the core idea behind a healthy green-energy ecosystem based on the concept of prosumer. The problem there concerns privacy of the participants, as energy production patterns might leak personal information. In that case blockchain is used because of its anonymization properties, coupled with mixing services and the like.<br>
<br>
### References
[1] <i>first</i><br>
<br>
[2] <i>second</i><br>
<br>