+++
author = "SongChain"
title = "Consensus Mechanisms"
date = "2021-06-24"
description = "How Blockchain Verifies Transactions"
tags = [
    "blockchain",
    "security"
]
+++

In the traditional banking system, transactions are held on a central ledger at each bank. Banks have full control of this ledger and can modify it as they see fit. However, they are incentivized to ensure the accuracy of the ledger because their reputation is staked on it.

On a blockchain, the transaction ledger is decentralized and requires a consensus mechanism to ensure the transactions are accurately recorded. Three of the main consensus mechanisms include Proof of Work, Proof of Stake, and Proof of Authority. These blockchains face a tradeoff between efficiency and centralization.

Proof of Work (PoW) is the oldest and most commonly understood consensus mechanism. This is the mechanism utilized by Bitcoin and Ethereum to ensure the integrity of the ledger. PoW works by using a network of miners who use computers to solve mathematical problems in exchange for cryptocurrency. These math problems confirm transactions on the chain and take a significant amount of computing power. This consumption of power acts as a barrier to faking transactions as the power to confirm fake transactions would cost more in electricity than was gained in cryptocurrency value. PoW blockchains are very secure and decentralized but take up a great deal of electricity to run. Bitcoin alone uses the same amount of electricity as the entire country of Sweden.

Proof of Stake (PoS) has tried to improve the efficiency of verifications to reduce transaction costs, speed, and energy consumption. Some popular PoS blockchains include Cardano, Dash and NEO. PoS works by having miners stake a given amount of the cryptocurrency they are mining as collateral in order to establish trust as a transaction facilitator. The more coins a miner stakes, the higher chance that they will be selected to process transactions and make profits in the form of network fees. PoS uses far less energy than PoW because there is no need for these math equations miners need to solve. Trust is established through collateral coins that can be lost if the miner acts maliciously or incometently. The disadvantage to PoS is that this dependence of large miners can increase the centralization of the network, which decreases the advantage over traditional payment processing.

Proof of Authority (PoA) is a derivative of PoS that uses a validator’s identity instead of a monetary value as the stake. PoA is a relatively new consensus mechanism and used by SongChain’s blockchain provider, Xooa. On PoS, validators publicly release their identity in order to gain the right to process transactions and earn transaction fees. This mechanism has an advantage over PoS in the increased transparency of validators and the equalization of stakes. A given monetary value of cryptocurrency might mean significantly more to one individual with a small overall portfolio in comparison to someone with a large portfolio. PoA solves this issue of differentiating relative values while also decreasing transaction times and fees in comparison to PoW networks. PoA decreases transaction times from up to 10 minutes per block for Bitcoin to less than 2 seconds. This decrease in transaction time is also reflected in much lower energy consumption per transaction. PoA provides these advantages while keeping the power of the ledger in the hands of a much more secure and decentralized network when compared to the traditional financial system.

All three consensus mechanisms provide a secure, decentralized, and innovative way to process transactions but vary in their efficiency. However, SongChain chooses to utilize a PoA network because of the drastically lower transaction times, fees and energy consumption. A slightly more centralized network is well worth the gains both in terms of sustainability and economics.
