# Application

## Challenge: Martian Token Crowdsale

Creating a crowdsale for the token "KaseiCoin".  

### Instructions

Follow the video instructions for information on how to deploy the KaseiCoin crowdsale contract.


#### Create the KaseiCoin Token Contract

In this section, you will create a smart contract that defines KaseiCoin as an ERC-20 token. To do so, complete the following steps:

1. Import the provided `KaseiCoin.sol` starter file into the Remix IDE.

2.  have immported the following contracts from the OpenZeppelin library:

    * `ERC20`

    * `ERC20Detailed`

    * `ERC20Mintable`

3. Define a contract for the KaseiCoin token called `KaseiCoin`, and have the contract inherit the three contracts that you just imported from OpenZeppelin.

4. Inside of your `KaseiCoin` contract, add a constructor with the following parameters: `name`, `symbol`, and `initial_supply`.

5. Then, as part of your constructor definition, add a call to the `ERC20Detailed` contract’s constructor, passing the parameters `name`, `symbol`, and `18`. Recall that 18 is the value for the `decimal` parameter.


#### Creating the KaseiCoin Crowdsale Contract

Screenshot of the successful compilation of the contract.  Added to the Evaluation Evidence section of the `README.md` file for this repository.

### KaseiCoin Compiled
![alt text](https://github.com/madhugirl/crowd-sale/blob/main/Evaluation%20Evidence/KaseiCoin%20compile.png)

#### Creating the KaseiCoin Deployer Contract

Screenshot of the successful compilation of the contract, Added to the Evaluation Evidence section of the `README.md` file for this repository.

### KaseiCoin Crowdsale Compiled
![alt text](https://github.com/madhugirl/crowd-sale/blob/main/Evaluation%20Evidence/Kasei%20CrowdSale%20complie.png)

#### Deploy the Crowdsale to a Local Blockchain

In this section, I have included a video of how I deployed the KaseiCoin Crowdsale contract

### Deploying the KaseiCoin Crowdsale Contract
![alt text](https://github.com/madhugirl/crowd-sale/blob/main/Evaluation%20Evidence/Contract%20Deployment%20for%20Crowdsale%20Final.mp4)

### Interacting with the KaseiCoin Crowdsale and Token Purchases
![alt text](https://github.com/madhugirl/crowd-sale/blob/main/Evaluation%20Evidence/Proof%20of%20Crowdsale%20Token%20Purchases.mp4)

#### Raised Capital from the KaseiCoin Crowdsale

### Total Minted Tokens
![alt text](https://github.com/madhugirl/crowd-sale/blob/main/Evaluation%20Evidence/75000000000000000100%20total%20supply%20minted%20tokens.png)

### Total Wei Raised
![alt text](https://github.com/madhugirl/crowd-sale/blob/main/Evaluation%20Evidence/85000000000000000110%20wei%20raised.png)

