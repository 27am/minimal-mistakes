---
layout: post
title: "Mining in Bitcoin"
description: "None yet"
comments: false
---


The term “mining” evokes the image of somebody looking for something valuable, pretty much as it has been for the gold rush in the 19th century.
<br>
In Bitcoin, mining is not performed by digging a hole with a shovel but instead by computing cryptographic hash functions as quickly as possible in order to find our gold: the solution to a crypto puzzle. The output of a hash function is called digest, and for us to be valid it must belong to a limited set of solution whose value has to be lower than an adjustable threshold, i.e. it should, at least in the case of Bitcoin, begin with a certain number of leading zeros. 
The solution for this cryptographic puzzle is a scarce resource (exactly like diamonds) which makes it valuable.
That’s the ingenious trick devised to give Bitcoin an economical value while remaining just a sequence of bits in somebody’s hard drive. It emulates in a digital environment the pile of gold that has been hardly and over time accumulated in a bank’s vault.   
<br>
<br>

That’s not the only possible type of Proof.  In general, in order to be a viable mining technique, it should satisfy some properties:
1.	Be easy to verify, although moderately difficult to calculate
2.	The effort to find a solution should be adjustable
3.	The chance to find a solution should be proportional to the resources spent in mining, preventing one single miner to always win the race just because it’s the fastest. This property is called progress-free, memoryless or stateless.

<br>
<br>

Using mining techniques limits consistently the impact of Sybil attacks while giving a way to reach a consensus through the simple rule of expanding the longest chain. Indeed, without mining, any malicious actor would be able to destroy the system by creating fake identities. 
It’s still possible to subvert the system by owning large part of it, namely 51%, but it would be highly costly and, since it would destroy the trust and the profitability of the system right afterwards, it’s considered totally irrational from an economic point of view.
This is linked to the concept of Nash equilibrium, where each stakeholder has the interest of following the rules of the system.

<br>
<br>

[1] Bitcoin and Cryptocurrency Technologies - Arvind Narayanan, Joseph Bonneau, Edward Felten, Andrew Miller, Steven Goldfeder 
[2] Bitcoin and Beyond: A Technical Survey on Decentralized Digital Currencies - Florian Tschorsch, Björn Scheuerman
