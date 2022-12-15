# Kasei Crowdsale Funding
### Johnathan Overton


## Overview of the Analysis

* The purpose of this file is to demonstrate the ability to utilize Solidity in order to create an ERC-20 compliant fungible token, kaseiCoin, in order to deploy a Crowdsales contract.

* In this model, the following technologies were incorporated:
  * Solidity
  * Ganache
  * Remix IDE
  * OpenZeppelin
  * MetaMask

* How to Use
  * Install MetaMask extension on local browser
  * Connect Ganache to Remix IDE
  * Compile solidity files
  * Deploy Deployer and use addresses to deploy Coin and Coin Deployer contracts

## Evaulation Evidence

### Compiling Contracts

![1](https://github.com/Johove83/Kasei-Coin-Crowdsale/blob/main/Images/compileerc20token.png)

![2](https://github.com/Johove83/Kasei-Coin-Crowdsale/blob/main/Images/2_crowdsalecontract.png)

![3](https://github.com/Johove83/Kasei-Coin-Crowdsale/blob/main/Images/3_deploymentcontract.png)

In order of appearance, the previous images show the successful compilation of the token, crowdsale, and deployment contracts.

### KaseiCoinCrowdsaleDeployer Deployment

![4](https://github.com/Johove83/Kasei-Coin-Crowdsale/blob/main/Images/one.png)

![5](https://github.com/Johove83/Kasei-Coin-Crowdsale/blob/main/Images/twocrowdsaleaddress.png)

![6](https://github.com/Johove83/Kasei-Coin-Crowdsale/blob/main/Images/threecrowdsaleaddresscopy.png)

![7](https://github.com/Johove83/Kasei-Coin-Crowdsale/blob/main/Images/fourtokenaddress.png)

![8](https://github.com/Johove83/Kasei-Coin-Crowdsale/blob/main/Images/fivecoincopy.png)

![9](https://github.com/Johove83/Kasei-Coin-Crowdsale/blob/main/Images/sixdeployedcontracts.png)

The first image in this section shows the determination of token name, symbol, and the address which would be assoicated with distributing Kasei Coin and receiving payment.

The following two images demostrate the retrieval of an address from the KaseiCrowdsaleDeployer contract and its implementation into the KaseiCoinCrowdsale address.

The two images following demonstrate the same as the previous two images, except the retrieved address is implemented into the KaseiCoin contract.

The final image in this section demonstrates that the two contracts contained within the KaseiCrowdsaleDeployer have been successfully deployed.

### Original Account Balances

![10](https://github.com/Johove83/Kasei-Coin-Crowdsale/blob/main/Images/originalbalance4.png)

The above image shows that the crowdsale account has a beginning balance of 99.92 ETH and two funding accounts have a starting balance of 100 ETH.

### After Purchasing Token Balances

![11](https://github.com/Johove83/Kasei-Coin-Crowdsale/blob/main/Images/afterbalance.png)

After sending 10 and 28 ETH each funding accounts one and two show balances of 90 and 72 ETH. Further, the crowdsales account shows a gain of 38 ETH. This is further verified by the following image which demostrates that the account has successfully gained 38 ETH.

![12](https://github.com/Johove83/Kasei-Coin-Crowdsale/blob/main/Images/weiraised1.png)
