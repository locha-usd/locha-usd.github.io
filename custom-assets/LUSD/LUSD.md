---
layout: page
title: Custom Asset LUSD
permalink: /custom-assets/LUSD/LUSD
---
##### Warning dont buy LUSD you will not get rich with it, while its collateralized by USDT at this moment is only for research & development purposes and anything could go wrong at this point cause we are lazy engineers who leave services open without the proper attention.  
# LUSD an asset pegged to USD [_index price_](https://en.wikipedia.org/wiki/Price_index)  


### [LUSD Asset information](https://blockstream.info/liquid/asset/84467161a382f4b55912805a1ab992c89a7ca126024dbf1463b3d8d5cdf9e68b) 
<img class="" alt="LUSD asset info" src="{{ site.url }}/images/LUSD_asset_info.png" />


### Monetary policy

- initial supply                          : 100,7503 LUSD
- initial collateral                      : 100,7503 USDT
- LUSD / USDT ratio                       : 1:1
- network fee + two ways exchange fee     : network fee + 0,05% fx amount 
- transparent exchange address            : `Gvnfud1pAvxp156XZA76UutKCHndsj46N5` 
- confidential exchange address           : `VJLDMxaN3Y54vJyHqwQ4mCWXBaiqCFxxahP2h9CaXNLkbtMRjRMqyEUDgJjE6gRKMwiZExs5x9Hhbsny`
- decimal precision                       : 4
- max transaction amount per transaction  : 210.000.000.000,0000
- max re-issueance amount per transaction : 210.000.000.000,0000

***
# Verify Total Supply

[LUSD circulating supply:](https://blockstream.info/liquid/asset/84467161a382f4b55912805a1ab992c89a7ca126024dbf1463b3d8d5cdf9e68b)

***
# Verify USDT Collateral

[USDT collateral:](https://blockstream.info/liquid/asset/84467161a382f4b55912805a1ab992c89a7ca126024dbf1463b3d8d5cdf9e68b)
##### !need a custom block explorer to show the confidential txs there or a service to publish blinding keys 
***
# Public Address USDT - LUSD exchange 
##### !warning only ["Confidential Transactions accepted by now"](https://docs.blockstream.com/liquid/technical_overview.html#confidential-transactions).

Works through specific addresses only for two-way exchange:

exchange address: 

[Gvnfud1pAvxp156XZA76UutKCHndsj46N5](https://blockstream.info/liquid/address/Gvnfud1pAvxp156XZA76UutKCHndsj46N5)

<img class="" alt="LUSD fx address" src="{{ site.url }}/images/LUSD_fx_address_m.png" />

two ways exchange model :

```

1.9966 USDT    ----> exchange address 
user address  <---- 1,8154 LUSD (fx amount - fx fees - tx network fees) 

```
```

1.1630 LUSD    ----> exchange address
user address  <---- 0.9902 USDT (fx amount - fx fees - tx network fees)

```
example using [green wallet](https://blockstream.com/green/):


<img class="" alt="LUSD asset info" src="{{ site.url }}/images/LUSD_fx_green.png" />

***
# Atomic swap USDT - LUSD exchange

_WIP_


***
# FAQ 
##### Why pegged to USD _index price_ and not USD as collateral?
A collateralized digital asset could be designed using the following types of collateral;

|Type            |Collateral|
|--------|--------|
|Money           |dollar, euro, yen, ..       |
|Commodities     |oil, gold, corn, soja..     |
|Securities      |stocks, banknotes, bonds, ..|
|Cryptocurrencies|bitcoin, ethereum, ..       |

or be designed by a mixed formula, LUSD uses USDT as collateral to reduce research/development friction, although USDT is collateralized in USD we cannot and should not attest to this statement, for more information about [USDT visit their website](https://tether.to/)

__WIP__

##### Why not use USDT directly?
To be able to create monetary policies for LUSD;

- control the custom asset supply by owner is key  
- define specific spendable locations
- . . .

_WIP_




