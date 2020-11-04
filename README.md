# Smart-Contracts-with-Solidity-

Smart contracts to automate payroll

## Background 

Using Solidity to construct smart contracts, we are able to create multiple types of profit splitting contracts

## Contracts 

### First Contract: Associate Level 

The `AssociateProfitSplitter` contract accepts Ether into the contract and divides the Ether evenly among the recipient associate level employees. This will allow the Human Resources department to pay employees quickly and efficiently.

This contract was deployed and tested on a local Test Network.

contract address : 0xF17832732c2fFb5E159D912B9ae2Db675283990e

### Second Contract: Tiered Level 
The `TieredProfitSplitter` contract distributes different percentages of incoming ether to employees at different tiers/levels. For example, the CEO gets paid 60%, CTO 25%, and Bob gets 15%.

This contract was deployed and tested on a local Test Network.

contract address : 0xFA1Ecc9F9C160eE9f7F04aEA2a67DFAda2F0d34d


### Third Contract: Equity Plan

The `DeferredEquityPlan` contract models traditional company stock plans. This contract will automatically manage 1000 shares, with an annual distribution of 250 shares over four years for a single employee.

This contract was deployed and tested on a local Test Network.

contract address : 0xbCa0b66B49593Adbd1Cb2ae4468CC735762A89F3