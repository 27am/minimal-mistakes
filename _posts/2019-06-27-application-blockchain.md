---
layout: post
title: "Applications for blockchain"
description: "No description"
comments: false
---

Blockchain has revolutionized the financial industry, providing a technical way to overcome previously unsolved problems. The same technology has been investigated for applications in different areas, most notably energy, supply chain, healthcare and internet of things. <br>
<br>
Internet of Things (IoT) in particular, presents traits that at first sight might be incompatible with the hypothesis required by the classical Bitcoin’s blockchain. IoT devices are computationally bounded and might be unavailable/offline for an arbitrary amount of time. A solution that has been proposed is to cluster group of devices and delegate demanding tasks to Head nodes that provide characteristics more suited to participate in the consensus of a blockchain. This has been done for example in [2] where, as an optimization, the authors introduce a reputation system to prevent a node having to validate all the transactions. Basically, what happens is that nodes responsible to execute the consensus algorithm, keep and update a trust table with information about the nodes that proposed both valid and invalid blocks. The principle behind the table is that if the node believes another peer to be trustworthy, it can skip some validation work. Another feature presented is the Dynamically Adjusted Throughput algorithm, put in place to facilitate scalability in presence of big numbers of participating nodes. Moreover, the consensus algorithm is a breed similar to Proof of Elapsed time without the deployment of the Trusted Execution Environment (TEE). Security properties hold because head nodes keep a list about the allowed participants, making the system a permissioned blockchain. <br>
<br>
Authors of [3] investigate improvements in the energy trading system of smart grids. Finding a way to exchange dynamically shares of electricity is the core idea behind a healthy green-energy ecosystem based on the concept of prosumer. Problematic are privacy aspects of the participants, as energy production patterns might leak personal information. In that case blockchain is used because of its anonymization properties, coupled with mixing services and the like.<br>
<br>
### References
[1] <i>K. Christidis and M. Devetsikiotis, "Blockchains and Smart Contracts for the Internet of Things," in IEEE Access, vol. 4, pp. 2292-2303, 2016.</i><br>
<br>
[2] <i>Dorri, Ali, et al. "LSB: A lightweight scalable blockchain for iot security and privacy." arXiv preprint arXiv:1712.02969 (2017).</i><br>
<br>
[3] <i>Aron Laszka, Abhishek Dubey, Michael Walker, Douglas Schmidt, "Providing Privacy, Safety, and Security in IoT-Based Transactive Energy Systems using Distributed Ledgers".</i><br>
<br>
