---
description: Capital Efficient Pools With Auto-Compounding Yields
---

# Add Liquidity To An Existing Elastic Pool

## Introduction

In order to participate in a **KyberSwap Elastic** pool and earn fees, you first need to add liquidity to the pool. Adding liquidity to a pool opens a new position. You can add liquidity either to an existing pool, or as part of creating a new pool. This guide describes the steps required to **add liquidity to an existing pool**.

Note: “Adding Liquidity” should not be confused with “Increasing Liquidity.” Adding Liquidity means creating a new position, whereas Increasing Liquidity pertains to increasing the size of a position you currently hold. Please refer to [Increasing Liquidity On Elastic](increasing-liquidity-on-elastic.md) if you have an existing position that you would like to add more liquidity to.

<details>

<summary>Liquidity Provider Flow</summary>

Still deciding on which solution suits you best?&#x20;

* **Overview**: [Earn Yield By Contributing Liquidity](../../../kyberswap-solutions/kyberswap-interface/user-guides/earn-yield-by-contributing-liquidity.md)
* **Detailed comparison**:  [Classic vs Elastic](../../classic-vs-elastic/)&#x20;

#### Next steps

1. [Connect Your Wallet](../../../kyberswap-solutions/kyberswap-interface/user-guides/connect-your-wallet.md)
2. [Switching Networks](../../../kyberswap-solutions/kyberswap-interface/user-guides/selecting-preferred-network.md)
3. [Elastic Pool Creation ](elastic-pool-creation.md)****
4. **Add Liquidity To An Existing Elastic Pool <-**
5. [Increasing Liquidity On Elastic](increasing-liquidity-on-elastic.md)
6. [Elastic Fee Collection](elastic-fee-collection.md)
7. [Yield Farming On Elastic](yield-farming-on-elastic.md)
8. [Removing Liquidity On Elastic](removing-liquidity-on-elastic.md)

</details>

## Adding liquidity to an existing pool

Here are the steps for opening a new position using an existing liquidity pool.

### **Step 1**: View available pools

Ensure you are on the correct network, and then choose the tokens to provide as liquidity. You can do this through the token selectors at the top of the Elastic Pools interface. Once you’ve selected your pair of tokens, a filtered list of pools that use that pair will be displayed on the interface.

![View available pools](https://support.kyberswap.com/hc/article\_attachments/14197115708185)

Note: If you know the contract address of the pool you want, you can also filter the list for the pool you want by inputting the address in the search bar.

### **Step 2**: Select pool

Select the pool you’d like to participate in by clicking on the appropriate “Add Liquidity” button. This will open the Add Liquidity screen.

![Add liquidity pop-up](https://support.kyberswap.com/hc/article\_attachments/14197098964249)

### **Step 3**: Select fee tier&#x20;

For a list of fee tiers and their recommended applications, please refer to [this article](https://support.kyberswap.com/hc/en-us/articles/13954867874329).

![Select fee tier](https://support.kyberswap.com/hc/article\_attachments/14197115918873)

### **Step 4**: Set your price range

This is the range at which your capital will be used in the pool. If the market price moves outside the range your capital will not be used and will not earn any fees.

You can set your price range either using the sliders or by typing in prices manually.

![Select price range](https://support.kyberswap.com/hc/article\_attachments/14197115971993)

Note: You can also choose to click on the “Full Price Range” option, but that will set your range to be between 0 and infinity, and your liquidity will be very thinly spread out, greatly impairing its fee-earning potential.

### **Step 5**: Configure token amounts

Specify the deposit amounts, or how much liquidity you would like to add to open this position. You can either manually type in amounts or use the “Max” and “Half” buttons. Once you specify the deposit amount for one leg of the pair, the corresponding leg’s amount will be automatically calculated and populated for you.

Note: The proportion of liquidity deposited for each leg of the pair is determined by your price range, so it is helpful to set the price range before specifying your deposit amounts.

![Deposit amounts](https://support.kyberswap.com/hc/article\_attachments/14197116099097)

### **Step 6**: Authorize contract

If you haven’t already done so, you will need to need to authorize the KyberSwap smart contract to transact using your tokens on this network. Click the “Approve \[Token]” button to do so. This will open the approval dialog window on your wallet.

![Approve USDC](https://support.kyberswap.com/hc/article\_attachments/14197099433625)

Once the approval is confirmed, the previously-greyed-out “Preview” button will be clickable.

### **Step 7**: Review liquidity provision

Click on the “Preview” button to bring up the preview screen. Once you have reviewed the information on this screen, click on the “Supply” button to proceed.

![Preview pop-up](https://support.kyberswap.com/hc/article\_attachments/14197099595545)

You will need to confirm this transaction in your wallet.

![Metamask confirmation](https://support.kyberswap.com/hc/article\_attachments/14197099648409)

Once you’ve confirmed the transaction you will see a screen informing you that the transaction has been submitted. You can click on “View Transaction” to view your transaction on the appropriate blockchain explorer.

![Transaction submitted](https://support.kyberswap.com/hc/article\_attachments/14197099789209)

Your new position should now be visible on the My Pools page on KyberSwap.

![Elastic pool positions](https://support.kyberswap.com/hc/article\_attachments/14197099857049)