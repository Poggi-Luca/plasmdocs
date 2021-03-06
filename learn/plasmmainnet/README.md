# Plasm Mainnet

This page describes the specs of Plasm mainnet in detail. In addition, the behavior of Plasm mainnet changes as the Network grows. Note that the past status is also listed here. Each detailed spec is annotated at the beginning of the page, whether it is "Latest" or "Deprecate".

## Version

* authoring\_version: 1
* spec\_version: 1
* impl\_version: 1

### Core modules

* System - core substrate functionality.
* Timestamp - timestamp runtime oracle.
* Session - authority session keys management.
* Babe - block producing consensus engine.
* Grandpa - block finalizing consensus engine.
* Indices - account indexing engine.
* Balances - native asset operations.
* RandomnessCollectiveFlip - source of random numbers.
* Contracts - smart contract support.
* Sudo - superuser actions.

### StakeTechnologies modules

* Operator - smart contract operator support.
* **In preparation**: ~~DappStaking - stake on decentralized application to collect operator rewards.~~
* PlasmValidator - authority manager for Plasm network.
* PlasmRewards - this module split block rewards between dapp operators and validators.
* **In preparation**:~~PlasmLockdrop - multi-lockdrop token distribution.~~

## [Plasm Network ChainSpec](chainspec.md)

This item explains the chain spec of the genesis plasm mainnet.

## [First Rewards](firstrewards.md)

This item explains the first rewards of genesis plasm mainnet.

**Run mainnet since 2020 May 1**

## Future Works

### 2020 Q2

* [Dapps Staking](../plasmnetwork/dappsrewards.md) module will be avalable.

### 2020 Q3

* [Ovm + Plasma](../ovm.md) module will be avalable.
* [Real time Lockdrop](../plasmnetwork/realtimelockdrop.md) module will be avalable.

### 2020 Q4

* First L2 application will be released.
* L2 interoperability between ETH.
* Migrate to NPoS from PoA.

### 2020

* Plasm Network as Parachain join the Polkadot.

