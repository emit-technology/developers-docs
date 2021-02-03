## 4.1 Sub-accounts

EMIT Wallet is a multi-chain wallet and supports cross-chain functionality. After the account is created, sub-accounts for multiple blockchain systems supporting EMIT CROSS are created at the same time, and these addresses can be used as transfer targets for the corresponding blockchain. It is also possible to transfer assets to other addresses of the same type as the transfer initiator. In the same account, different blockchain system sub-accounts can transfer assets between each other. For example, if Ethereum and Super ZERO (SERO) blockchain systems are currently supported, USDT assets can be transferred between the two sub-accounts in the EMIT account "ETH Acc for EMIT" as shown below.

![img](https://blog.emit.technology/content/images/2021/01/Bitmap6.png)

> Note that if a transaction is executed in Ethereum, it is necessary to have ETH assets in the Ethereum account as GAS fees in order to send the transaction correctly.

## 4.2 Transfer Targets

Click on the QR code icon on the right side of the sub-account to see the public key address of the corresponding sub-account, which is different for each sub-account.

![img](https://blog.emit.technology/content/images/2021/01/Bitmap5.png)

> Using "copy" button or QR code scanning, you can get the text of the public key address of the corresponding sub-account.

## 4.3 Asset Storage and In-chain Transfers

Since EMIT Wallet is a multi-chain wallet and supports cross-chain functionality, an asset may be stored on multiple blockchain systems. EMIT Wallet provides a very convenient way to view the asset storage status.

![img](https://blog.emit.technology/content/images/2021/01/Bitmap7.png)

> By clicking on the "Transfer" button to the right of each chain, you can initiate an in-chain transfer, i.e., transfer to other accounts on that chain. This functionality is no different from the transaction functionality of the dedicated wallets of the corresponding blockchain systems.

## 4.4 Transaction List and Transaction Details

By clicking on a sub-chain under an asset, you can view the list of transactions for the corresponding asset under that sub-chain.

![img](https://blog.emit.technology/content/images/2021/01/Bitmap2.png)

Further, by clicking on a transaction, you can view the transaction details.

![img](https://blog.emit.technology/content/images/2021/01/Bitmap1.png)

## 4.5 Cross-chain Transactions

There is a "Cross" button on the right side of each asset, click on it to transfer assets between sub-accounts of several different blockchain systems.

![img](https://blog.emit.technology/content/images/2021/01/Bitmap4-1.png)



For security reasons, EMIT Wallet currently only allows transfers between sub-accounts, and cannot directly transfer to external accounts across blockchain systems. If you want to transfer to an external account, please do it in a sub-account first and then use the initiate transaction function to transfer to the external account.