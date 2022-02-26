## Vintage  Investment Protocol 

## Overview
A collective asset ownership protocol where groups of people can invest, manage, and govern assets together as PODS. 
These PODS will serve as mini investment vehicles where owners can submit investments proposals as well as vote on withdrawals and the distribution of funds. 
PODs serve as a private investment vehicle, where owners can collect the cash flows that stem from the underlying investment pool, or sell/trade their ownership stake in the POD with another member of the community. 
The asset will be an off chain, yield generating asset/revenue stream. 

## Features
* The contract is ERC721 compliant and provides NFT's that represent shares of the given asset. POD owners can transfer their NFT to another member of the community.
* The contract will only execute transactions once approved by 2/3 owners
* Collected revenues are made available to POD owners for withdrawl, according to a schedule, via a withdraw() method.
* Owners can withdraw funds during a predefined collection period. Otherwise, they will need to wait until the next collection period.
* Deploy the contract on Arbitrum Mainnet.
### Coming Soon
 - POD owners will be able to earn additional funds on their invested capital by electing to turn their POD into a liquidity pool for others to borrow ETH from and pay interest into. 
 - Prize pool functionality will be added so community members can be awarded interest earned on idle pod funds. 
 - The base Multisig contract will be extended to include the following: 
    * A way to to track revenue events on-chain, such as a streaming payment protocol 
    * A prize pool protocol to invest idle POD funds, and award community members for purchasing the protocol tokens

## External Dependencies
 - Arbitrum