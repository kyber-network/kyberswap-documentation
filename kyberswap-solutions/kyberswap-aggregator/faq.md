---
description: Your KyberSwap Aggregator Questions Answered
---

# FAQ

<details>

<summary>Which chains does KyberSwap Aggregator support?</summary>

The full list of supported  chains can be found on [Supported Exchanges and Networks](../../getting-started/supported-exchanges-and-networks.md).

</details>

<details>

<summary>Which tokens does KyberSwap Aggregator support?</summary>

KyberSwap whitelists well-known tokens for ease of access, but you can import custom tokens that meet the ERC20 standard via our user interface. For more information on how to do this, please refer to [Add Your Favourite Tokens](../kyberswap-interface/user-guides/add-your-favourite-tokens.md).

</details>

<details>

<summary>What fees do I need to pay to use the KyberSwap Aggregator?</summary>

### Network Fees

KyberSwap is a fully onchain service. Everyone who creates transactions on the blockchain will need to pay network fees associated with their transactions. These fees vary depending on

1. The network being used
2. Network congestion at the time
3. Complexity of the smart contract transaction being executed

### Trading Fees

KyberSwap does not charge fees to users using the protocol to swap tokens. However Liquidity Providers are allowed to set fees on their liquidity pools and traders who choose to use these pools to perform swaps will need to pay trading fees to the LP, along with any associated network fees.

It should be noted that of these Trading Fees collected by LPs, 10% goes to KyberSwap’s governance DAO, KyberDAO.

</details>

<details>

<summary>How do I change slippage tolerance?</summary>

Slippage tolerance for swaps defaults to a conservative 0.5%, but you can change this in Swap settings. From the Swap page, click on the Swap Settings button.

<img src="https://support.kyberswap.com/hc/article_attachments/13785737074585" alt="SwapSettingsButton.png" data-size="original">

This brings up the Swap settings page. You can use the selection buttons to specify your slippage tolerance. You can also enter a custom percentage in the field on the right.

<img src="https://support.kyberswap.com/hc/article_attachments/13785759119257" alt="SwapSettingsScreenSlippage.png" data-size="original">

For more information on completing a swap, you can refer to [Instantly Swap At The Best Rates](../kyberswap-interface/user-guides/instantly-swap-at-the-best-rates.md) for a step-by-step guide.

</details>

<details>

<summary>Why is my transaction stuck in "Pending" state?</summary>

### Reasons for stuck transactions

If your swap transaction was successfully accepted by the KyberSwap platform but you see on your transaction history and on blockchain explorers that the transaction has been stuck in a “pending” state for more than a few blocks, this could be due to one of several reasons:

#### Low Gas Limit

During periods of high network activity, gas prices tend to increase. If you’ve set your Web3 wallet to use a gas limit that is relatively low, it may take some time before miners pick up your transaction from the mempool.

#### Multiple Transactions Held Up by One Slow Transaction

If you have sent several transactions within a short amount of time, some of your transactions could be held up behind one or more transactions that are pending due to low gas limits.

### How to fix stalled transactions

If the transaction is stalled (stuck in a pending state) in the mempool and has zero block confirmations, you can either cancel it or expedite it be rebroadcasting the transaction using the same nonce as the pending transaction. This action will incur its own network fee and is performed through your Web3 wallet software.

If you have a queue of stuck transactions, you may only need to cancel/expedite the first few transactions before the rest get unstuck on their own.

Here are links to instructions on how to perform this action on some of the more common Web3 wallets.

* [1inch iOS Wallet](https://help.1inch.io/en/articles/5211509-how-to-cancel-or-speed-up-a-pending-transaction-in-the-1inch-wallet)
* [Crypto.com Defi Wallet](https://help.crypto.com/en/articles/4476691-how-do-i-cancel-or-speed-up-my-pending-eth-erc-20-transaction-on-crypto-com-defi-wallet-with-replace-by-fee)
* [Metamask](https://metamask.zendesk.com/hc/en-us/articles/360015489251-How-to-Speed-Up-or-Cancel-a-Pending-Transaction)
* [MEW](https://help.myetherwallet.com/en/articles/5461454-canceling-or-replacing-a-transaction-after-it-s-been-sent)
* [Trust Wallet](https://community.trustwallet.com/t/pending-stuck-transactions/126)

</details>

Still can't find what you're looking for? Check out the [KyberSwap Help Center](https://support.kyberswap.com/hc/en-us).