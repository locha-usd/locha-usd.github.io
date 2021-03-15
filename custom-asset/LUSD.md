---
layout: page
title: Custom Asset LUSD
permalink: /custom-asset/LUSD
---

# LUSD an asset pegged to USD [_index price_](https://en.wikipedia.org/wiki/Price_index)  



## Overview

### Technology behind LUSD

LUSD is built over [liquid network](https://blockstream.com/liquid/) a bitcoin sidechain 

- Use open source code [Elements](https://elementsproject.org/) as codebase

- An extended bitcoin codebase

- Same bitcoin protocol 

- Transparent transactions & Confidential Transactions

  - Transparent transaction <img class="" alt="transparent tx" src="{{ site.url }}/images/transparent_tx.png" />

  - Confidential transaction <img class="" alt="confidential tx" src="{{ site.url }}/images/confidential_tx.png" />

- Transaction fees 0.000000001 bitcoin per transaction size (1/10 bitcoin fees) 

- Ability to implement LUSD in a private network with [Elements](https://elementsproject.org/) 

- block creation through a federated network decrease transaction confirmation times (1 min blocks but not mandatory) and prevent multi-block reorganizations

- Transaction finality 2 confirmations

- Scalable

- Bitcoin(mainchain) & Bitcoin(liquid) two-way peg allows LUSD run/interact in a network based on bitcoin liquidity.

- LUSD Issuance and re-issuance (confidental and transparet)

  - Transparent issuance picture here

  - Confidential issuance picture here

_WIP_

### [LUSD Asset information](https://blockstream.info/liquid/asset/84467161a382f4b55912805a1ab992c89a7ca126024dbf1463b3d8d5cdf9e68b) 
<img class="" alt="asset info" src="{{ site.url }}/images/LUSD_asset_info.png" />

***
### Why pegged to USD _index price_ and not USD as collateral?
A collateralized digital asset could be designed using the following types of collateral;

|Type            |Collateral|
|--------|--------|
|Money           |dollar, euro, yen, ..       |
|Commodities     |oil, gold, corn, ..         |
|Securities      |stocks, banknotes, bonds, ..|
|Cryptocurrencies|bitcoin, ethereum, ..       |

or be designed by a mixed formula, LUSD uses USDT as collateral to reduce research/development friction, although USDT is collateralized in USD we cannot and should not attest to this statement, for more information about [USDT visit their website](https://tether.to/)

__WIP__

***

### Why not use USDT directly?
To be able to create monetary policies for LUSD, example; control LUSD supply 




