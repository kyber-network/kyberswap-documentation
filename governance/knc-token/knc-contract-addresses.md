---
description: Trade KNC On Multiple Chains
---

# KNC Contract Addresses

{% hint style="info" %}
#### An upgraded Kyber Network Crystal token

KNC was launched on Ethereum in 2017 and based on the ERC-20 standard. All vested tokens for founders and advisors have been unlocked and distributed since September 2019.

In 2021, [KNC was upgraded](https://blog.kyber.network/knc-token-migration-guide-fda08bfe62c2) with additional functionality and flexibility, and the old token version was renamed KNCL (KNC Legacy). Old KNCL holders can migrate to the current KNC version [here](https://kyberswap.com/kyberdao/stake-knc).

For avoidance of doubt, KNC refers to the current version of the token while KNCL refers to the token version prior to the upgrade.
{% endhint %}

## Native (KNC)

<details>

<summary>Ethereum (ChainID: 1)</summary>

* AdminUpgradeabilityProxy (KNC): [`0xdeFA4e8a7bcBA345F687a2f1456F5Edd9CE97202`](https://etherscan.io/address/0xdeFA4e8a7bcBA345F687a2f1456F5Edd9CE97202)
* KyberNetworkTokenV2 (KNC Implementation): [`0xe5E8E834086F1a964f9A089eB6Ae11796862e4CE`](https://etherscan.io/address/0xe5E8E834086F1a964f9A089eB6Ae11796862e4CE)

</details>

<details>

<summary>BSC (ChainID: 56)</summary>

* BEP20UpgradeableProxy (KNC): [`0xfe56d5892bdffc7bf58f2e84be1b2c32d21c308b`](https://bscscan.com/address/0xfe56d5892bdffc7bf58f2e84be1b2c32d21c308b)

</details>

<details>

<summary>Arbitrum (ChainID: 42161)</summary>

* CloneableBeaconProxy (KNC): [`0xe4dddfe67e7164b0fe14e218d80dc4c08edc01cb`](https://arbiscan.io/address/0xe4dddfe67e7164b0fe14e218d80dc4c08edc01cb)

</details>

<details>

<summary>Polygon PoS (ChainID: 137)</summary>

* UChildERC20Proxy (KNC): [`0x1C954E8fe737F99f68Fa1CCda3e51ebDB291948C`](https://polygonscan.com/address/0x1C954E8fe737F99f68Fa1CCda3e51ebDB291948C)

</details>

<details>

<summary>Optimism (ChainID: 10)</summary>

* L2StandardERC20 (KNC): [`0xa00e3a3511aac35ca78530c85007afcd31753819`](https://optimistic.etherscan.io/address/0xa00e3a3511aac35ca78530c85007afcd31753819)

</details>

<details>

<summary>BitTorrent Chain (ChainID: 199)</summary>

* KNC\_e (bridged from Ethereum): [`0xe467f79e9869757dd818dfb8535068120f6bcb97`](https://bttcscan.com/address/0xe467f79e9869757dd818dfb8535068120f6bcb97)
* KNC\_b (bridged from BSC): [`0x18fa72e0ee4c580a129b0ce5bd0694d716c7443e`](https://bttcscan.com/address/0x18fa72e0ee4c580a129b0ce5bd0694d716c7443e)

</details>

## Axelar Wrapped (axlKNC)

<details>

<summary>Arbitrum (ChainID: 42161)</summary>

* BurnableMintableCappedERC20 (axlKNC): [`0xB448eC505C924944ca8B2C55EF05c299eE0781df`](https://arbiscan.io/token/0xB448eC505C924944ca8B2C55EF05c299eE0781df)

</details>

<details>

<summary>Polygon PoS (ChainID: 137)</summary>

* BurnableMintableCappedERC20 (axlKNC): [`0x46371C90fcCE4D7367a61CB43eA7922406bC707a`](https://polygonscan.com/token/0x46371C90fcCE4D7367a61CB43eA7922406bC707a)

</details>

<details>

<summary>Optimism (ChainID: 10)</summary>

* BurnableMintableCappedERC20 (axlKNC): [`0xB448eC505C924944ca8B2C55EF05c299eE0781df`](https://optimistic.etherscan.io/token/0xB448eC505C924944ca8B2C55EF05c299eE0781df)

</details>

<details>

<summary>Linea (ChainID: 59144)</summary>

* BurnableMintableCappedERC20 (axlKNC): [`0xB448eC505C924944ca8B2C55EF05c299eE0781df`](https://lineascan.build/token/0xB448eC505C924944ca8B2C55EF05c299eE0781df)

</details>

## Multichain Wrapped (mKNC)

{% hint style="danger" %}
#### Multichain ceasing of operations

As of 14 July 2023, the Multichain team has ceased all operations. Wrapped KNC token contracts on the following chains are owned and deployed by the Multichain team. Due to the nature of public blockchains (where contracts are immutable unless written with a specific `selfdestruct` function), these contracts remain callable but users are highly discouraged from interacting with said contracts.

You can view their official announcement [here](https://twitter.com/MultichainOrg/status/1679768407628185600?s=20).
{% endhint %}

<details>

<summary>Fantom (ChainID: 250)</summary>

* AnyswapV5ERC20 (KNCv2 Token): [0x1e1085eFaA63EDFE74aaD7C05a28EAE4ef917C3F](https://ftmscan.com/address/0x1e1085efaa63edfe74aad7c05a28eae4ef917c3f)
* MultiSigWalletWithDailyLimit (DAO Multisig - Treasury): [`0x91c9D4373B077eF8082F468C7c97f2c499e36F5b`](https://ftmscan.com/address/0x91c9D4373B077eF8082F468C7c97f2c499e36F5b)

</details>

<details>

<summary>Avalanche (ChainID: 43114)</summary>

* AnyswapV5ERC20: [0x39fc9e94caeacb435842fadedecb783589f50f5f](https://snowtrace.io/address/0x39fc9e94caeacb435842fadedecb783589f50f5f)
* MultiSigWalletWithDailyLimit (DAO Multisig - Treasury): [`0x91c9D4373B077eF8082F468C7c97f2c499e36F5b`](https://snowtrace.io/address/0x91c9D4373B077eF8082F468C7c97f2c499e36F5b)

</details>

## Native Legacy (KNCL)

<details>

<summary>Ethereum (ChainID: 1)</summary>

* KyberNetworkCrystal (KNCL): [`0xdd974d5c2e2928dea5f71b9825b8b646686bd200`](https://etherscan.io/address/0xdd974d5c2e2928dea5f71b9825b8b646686bd200)

</details>