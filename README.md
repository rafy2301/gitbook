---
description: Introducing the two tokens and the overall structure of the system
---

# 🧀 Overview

## Structure and Purpose

The purpose of this page is to provide potential users of the Frankencoin system with everything they need to know to meaningfully intereact with it. For a deeper analysis of its economic properties, we refer to the [research paper](https://frankencoin.com/thesis-preprint-frankencoin.pdf) and for actually interacting with the system, there is a standard [frontend](https://frankencoin.com). The name Frankencoin hints at its self-governing nature, but also the risks associated with releasing an artificial machinery into the wild. If you encounter errors or if things are not clear to you, you can [reach out to us in the Telegram group](https://web.telegram.org/a/#-1001924255643) or [file a suggestion for improving this page on github](https://github.com/Frankencoin-ZCHF/frankencoin-dapp/issues).

## **Frankencoin (ZCHF) and Frankencoin Pool Shares (FPS)**

The Frankencoin system comes with two ERC-20 tokens, a stablecoin called [Frankencoin (ZCHF)](https://etherscan.io/address/0xB58E61C3098d85632Df34EecfB899A1Ed80921cB) and a governance token called [Frankencoin Pool Shares (FPS)](https://etherscan.io/address/0x1bA26788dfDe592fec8bcB0Eaff472a42BE341B2). Unlike other collateralized stablecoins, Frankencoin does not depend on external oracles, making it less susceptible to certain attacks and also more versatile with regards to the used collateral. The disadvantage of that approach is its speed, performing liquidations over the course of days whereas oracle-based systems might react within minutes.

The Frankencoin is a collateralized stablecoin that tracks the value of the Swiss franc. There is no hard peg to the Swiss franc, but a set of economic constraints that incentivizes the market to softly push it towards parity from two sides. Most importantly, the system is [over-collateralized](positions/): for each Frankencoin in circulation, there must other tokens worth at least one Frankencoin backing it. Furthermore, FPS holders have a number of ways to influence the long term price of the Frankencoin by making it more or less expensive to mint Frankencoins, similarly to how a central bank keeps the exchange rate of its own currency in balance. The underlying assumption here is that the FPS holders recognize that the system (and therefore also their tokens) is the most valuable when the Frankencoin tracks the Swiss franc as reliably a possible, and that they use their power to govern the system accordingly.

Frankencoin Pool Shares are the [governance ](governance.md)token of the system. Anyone can obtain newly minted FPS by providing equity capital to the system (or later return them again to get their share of capital back). The FPS holders benefit from the earned fees and liquidation profits, but they are also the ones that carry the residual risk of liquidations, similar to the shareholders of a bank. Therefore, FPS holders have an incentive to grow the system and ensure its stability. The governance process is veto-based: anyone can propose new types of collateral or even completely new methods to bring Frankencoin into circulation, but already 2% of the voting power suffices to veto such proposals.

## System Modules

\[TODO, refine] It's governance is decentralized, with anyone being able to propose new minting mechanisms and anyone who owns more than 2% of the voting power having the power to veto proposals. The initial minting mechanism builds on a novel auction-based price detection and liquidation mechanism first described in the (outdated) [Frankencoin research paper](https://www.snb.ch/n/mmr/reference/sem\_2022\_06\_03\_maire/source/sem\_2022\_06\_03\_maire.n.pdf). A more recent and complete specification can be [found here](https://frankencoin.com/thesis-preprint-frankencoin.pdf).&#x20;

<figure><img src=".gitbook/assets/image (1) (1).png" alt=""><figcaption><p>Components of the Frankencoin System</p></figcaption></figure>

