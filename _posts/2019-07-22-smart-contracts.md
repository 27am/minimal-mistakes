---
layout: post
title: "Smart Contracts"
description: "No description"
comments: false
---

A Smart contract is a computer program executed in a distributed fashion, more precisely by peers participating in the blockchain. The same computation is thus executed by a group of nodes that run post-facto consensus protocols to agree on the current state of the blockchain. The decentralization provides an increased fault tolerance, availability and assurance of execution. Indeed, no authority is in charge and able to arbitrarily prevent a smart contract to finalize the execution, provided that enough resources (e.g. gas) have been allocated for its completion.<br>
<br>
Although powerful, smart contracts are not suited for every use case, at least to a first degree of approximation. Most notably, external data feeds, which would allow the possibility of envisioning very cool decentralized applications, introduce tradeoffs in the system. To give an example, if a smart contract requires to access a weather forecast, it can be done basically in two ways: either each miner accesses the data by its own, performing independent requests that might fetch different forecasts (perhaps simply because it has been updated), or every miner relies on a single source of truth, sometimes referred as “oracle”. It is easy to notice that we are compromising between centralization/decentralization advantages and disadvantages.<br>
Programming smart contract has become notoriously difficult for numerous pitfalls that make it different from standard programming. A few examples among the others is relying on an ordered transaction execution, which is not guaranteed in real world blockchain since miners take free decisions with this regard. Additionally, smart contracts have to be extra careful trying to foresee and handle every possible kind of exception, otherwise the risk is to lose the funds.<br>
<br>
Ekiden is a proposal to improve privacy and performance of current smart contract platforms. It uses a Trusted Execution Environment to enforce privacy, indeed outgoing data is encrypted by the hardware module and stored like that on the blockchain. The system distinguishes 3 different roles: clients, compute nodes and consensus nodes, thus decoupling the two different tasks. Comparing Ekiden with Ethereum, a performance gain of about three orders magnitude has been measured.<br>
<br>