# Solidity-Contract-Creation- "Looks like we've made our first contract!"

![contract](https://image.shutterstock.com/z/stock-photo-two-hands-handshake-polygonal-low-poly-hud-illustration-smart-contract-agreement-blockchain-and-1161295627.jpg)

## Background

A new startup has created its own Ethereum-compatible blockchain to help connect financial institutions, and the team wants to build smart contracts to automate some company finances to make everyone's lives easier, increase transparency, and to make accounting and auditing practically automatic.

Fortunately, I've been learning how to program smart contracts with Solidity! In this project,  a few `ProfitSplitter` contracts would be created using Solidity in Remix, Ganache and Metamask. These contracts will do several things:

* Pay the associate-level employees quickly and easily.

* Distribute profits to different tiers of employees.

* Distribute company shares for employees in a "deferred equity incentive plan" automatically.

## Files

* [`AssociateProfitSplitter.sol`](CodeFiles/AssociateProfitSplitter.sol) — Level 1 contract code.

* [`TieredProfitSplitter.sol`](CodeFiles/TieredProfitSplitter.sol) — Level 2 contract code.

* [`DeferredEquityPlan.sol`](CodeFiles/DeferredEquityPlan.sol) — Level 3 contract code.

## Instructions

This profit sharing contract has three levels of difficulty, with each contract increasing in complexity and capability. 

* **Level One** is an `AssociateProfitSplitter` contract. This will accept ether into the contract, and divide it evenly among associate-level employees. This will allow the human resources department to pay employees quickly and efficiently.

* **Level Two** is a `TieredProfitSplitter` that will distribute different percentages of incoming ether to employees at different tiers/levels. For example, the CEO gets paid 60%, CTO 25%, and Bob gets 15%.

* **Level Three** is a `DeferredEquityPlan` that models traditional company stock plans. This contract will automatically manage 1000 shares, with an annual distribution of 250 shares over four years for a single employee.


