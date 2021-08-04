[DanaSwap Project Board](https://github.com/orgs/ArdanaLabs/projects/1)

[DanaSwap Spec](https://github.com/ArdanaLabs/DanaSwap-spec)

Phase I - Foundation
 * Solve invariant equation
 * Set up CI
 * Planning and specification
 * Non-parallel contract state machine
 * Metrics APIs

Phase II - Parallelism
 * Parallelize contract endpoints
 * Create services to manage parallelized contract instances
 * Update metrics APIs to handle parallelized contract

Phase III - Integration
 * Deploy and test contract on testnet
 * Create administrative API for parallelized contract instances
 * Fine tuning numerical analysis

Concurrently with this work, we will do security, ops, and auditing work. Roadmap for this work is TBD.

Most of the work on the board has been sized. We have identified an estimated 14.5 person-weeks of work to get all of the smart contract and backend pieces done for a subset of requirements which includes the parallelized DEX for higher throughput (a major source of complexity) but most notably does not include the DANA token. This work covers all of the data points which have red bubbles in Miro and the functionality of trading, adding, and removing liquidity as well as the same administrative functionality available in Curve 3pool. The work that is on the board that has not been sized yet mainly includes integrating with the source of price data, doing any third party wallet integrations, and devops and security related work.

Isaac and Morgan follow an industry standard best practice of doubling our overall estimates to arrive at an all in estimated timeline. This helps to correct for unforeseen / changing requirements, optimism bias, and unknown unknowns, which seems particularly appropriate in doing this kind of work on bleeding edge technology. Only a small amount of backend and smart contract work on the board remains to be sized, so as a rough estimate, we can say that about 30 person weeks of work are needed on the backend and smart contract pieces (exclusive of devops and security work) in order to fulfill the requirements in the scope of this current planning effort which does not include DANA token or third party wallet integrations.

This indicates that at current staffing levels we can reasonably expect to be done with the functionality in the current scope sometime in Q4 2021, or in September if things go very well.

Here is a spreadsheet with a breakdown by issue of this estimate. This spreadsheet is set to "anyone with the link can view."

https://docs.google.com/spreadsheets/d/1INMaknudMs7T7iekwa6TAIWREX0QTBEiUIRwz3C2-6E/edit#gid=0

Here is an approximate breakdown by phases of sized work remaining to be done:

Phase I - Foundation - appx. 3.5 person-weeks left
Phase II - Parallelism - appx. 7 person-weeks
Phase III - Integration - appx. 7.5 person-weeks
