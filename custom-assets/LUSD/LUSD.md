---
layout: page
title: Custom Asset LUSD
permalink: /custom-assets/LUSD/LUSD
---

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
# [Exchange & supply control](https://blockstream.info/liquid/address/Gvnfud1pAvxp156XZA76UutKCHndsj46N5)

## Exchange

##### !warning only 1 way ready if you send USDT now will not be able to exchange back till method implemented.
##### !warning only ["Confidential Transactions"](https://docs.blockstream.com/liquid/technical_overview.html#confidential-transactions) accepted by now.

<img class="" alt="LUSD asset info" src="{{ site.url }}/images/LUSD_fx_green.png" />


```
1 USDT ----> 
       <---- 1 LUSD - network fee - fx fee

```

<img class="" alt="LUSD fx address" src="{{ site.url }}/images/LUSD_fx_address_m.png" />



* verify the USDT collateral         [here:](https://blockstream.info/liquid/address/Gvnfud1pAvxp156XZA76UutKCHndsj46N5) 
* verify the LUSD circulating supply [here:](https://blockstream.info/liquid/asset/84467161a382f4b55912805a1ab992c89a7ca126024dbf1463b3d8d5cdf9e68b)

## Supply control by collateral

<img class="" alt="LUSD asset info" src="{{ site.url }}/images/LUSD_supply_green.png" />

```
initial supply: 100,7503 LUSD

105 USDT ---->
              <---- 104.6020 LUSD 

final circulating supply 104.6020
```

* verify the USDT collateral         [here:](https://blockstream.info/liquid/address/Gvnfud1pAvxp156XZA76UutKCHndsj46N5)
* verify the LUSD circulating supply [here:](https://blockstream.info/liquid/asset/84467161a382f4b55912805a1ab992c89a7ca126024dbf1463b3d8d5cdf9e68b)


##### TODO* LUSD ---> USDT fx 

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




