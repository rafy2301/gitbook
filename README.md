---
description: The Frankencoin and its Documentation
---

# 🧀 Overview

This website provides technical documentation for the Frankencoin system, allowing readers to better understand how they can interact with it. For a deeper analysis of its economic properties, we refer to the [research paper](https://frankencoin.com/thesis-preprint-frankencoin.pdf) and for actually interacting with the system, there is a convenient [frontend](https://frankencoin.com). The name Frankencoin hints at its self-governing nature, but also the risks associated with releasing an artificial machinery into the wild.

The Frankencoin is a collateralized stablecoin that is intended to track the value of the Swiss Franc. It's governance is decentralized, with anyone being able to propose new minting mechanisms and anyone who owns more than 2% of the voting power having the power to veto proposals. The initial minting mechanism builds on a novel auction-based price detection and liquidation mechanism first described in the (outdated) [Frankencoin research paper](https://www.snb.ch/n/mmr/reference/sem\_2022\_06\_03\_maire/source/sem\_2022\_06\_03\_maire.n.pdf). A more recent and complete specification can be [found here](https://frankencoin.com/thesis-preprint-frankencoin.pdf). Unlike other collateralized stablecoins, Frankencoin does not depend on external oracles and is therefore also very versatile with regards to the used collateral.

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption><p>Components of the Frankencoin System</p></figcaption></figure>

