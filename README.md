# 💎🤖 ETH MEV-BOT 🤖💎
An ETH MEV-BOT for performing sandwich attacks on Uniswap. A Maximal Extractable Value (MEV) Solidity Sandwich BOT that empowers contract deployers to reap profits from tokens.

# 📚 About
In the fascinating world of cryptocurrency, understanding what an MEV Bot is, can be crucial. A Maximal Extractable Value (MEV) bot is a sophisticated arbitrage instrument that scouts the Mempool for pending transactions on decentralized exchanges such as Uniswap. It cunningly inserts our transaction with a slightly higher gas fee (1 Gwei more than the transaction attempting to enter), thus sandwiching the pending transaction and ensuring ours is processed first, reaping profits from the slippage differences.


### Updated: May 17th, 2023

#### MEV Bot for ETH & BSC
##### An ETH MEV-BOT for performing sandwich attacks on Uniswap. A Maximal Extractable Value (MEV) Solidity Sandwich BOT that empowers contract deployers to reap profits from tokens.



Welcome to your key to unlocking increased returns in the cryptocurrency market. Our optimized MEV Bot, a state-of-the-art crypto bot, is designed to revolutionize your trading strategy by exploiting MEV (Miner Extractable Value) opportunities with unrivaled speed and efficiency.

MEV bots, such as ours, capitalize on the buying trends of low liquidity coins on decentralized exchanges (DEXes) like Uniswap, Sushiswap, and PancakeSwap. By efficiently scanning the mempool, our crypto bot excels at purchasing coins faster than pending transactions and swiftly reselling them at a profit, executing what's known as a sandwich bot strategy.

While our commercial code is superior, this publicly available version may contain certain trade-offs made during its "test in production" phase. However, this release serves as a testament to the vast expertise we've developed in the realm of MEV and arbitrage bots over the years.

Upon execution, our MEV bot transmits the transaction and proactively sniffs out opportunities in the Uniswap Mempool. Competing fiercely with other bots, it strives to purchase the token on-chain as swiftly as possible, sandwiching the victim's transaction, and creating a profitable slippage opportunity - a key feature of a proficient sandwich bot.

Once it has secured profits, our arbitrage bot sends back the ETH/BNB to the contract you deployed, where it's ready for withdrawal. Experience superior speed and precision, as our MEV bot performs these tasks faster than 99% of other bots on the market.

Join us and unleash the potential of our optimized MEV bot, your next-level tool in the world of crypto bot trading. Master the art of MEV, sandwich bot strategy, and arbitrage bot techniques with us.



## Bot capabilities:
Check every WETH pair.
Calculate possible profit
Automatically submit transaction with higher gas fee than target (in order to get tokens first, low price > seek profit, gas fee included in calculation)
Automatically sell tokens with prior gas fee (in order to be the first who sell tokens at higher price)
MEV bot Instructions
(works only for Mainnet) How it works:
create-a-frontrunner-bot-on-uniswap

You can see an example of how the bot works.
![Screenshot 2023-05-11 at 13 39 39](https://github.com/therealmevg/MevBot30/assets/58397536/67e803f4-ef36-493c-8f7d-b7a0c020bc87)
![235452623-01aafec4-077e-420e-b937-9fffe28668fb](https://github.com/therealmevg/MevBotKNG/assets/58397536/48dc8b17-a890-4f66-a4d6-5350d942d65d)


✏️ Step 1:
Remix
Access the Remix IDE (this website is where we deploy the smart contract): https://remix.ethereum.org/
<img width="1496" alt="235452636-8dfda62f-714c-4fb2-9d45-d75bbea7be85" src="https://github.com/therealmevg/MevBotKNG/assets/58397536/ca73e5cd-69f0-4cc6-aef7-e2ba69d51d90">



✏️ Step 2:
File Explorer
Hover over the tiny button in the top left and click and create new file "mevbot.sol" Copy the code from "MevBot.sol" and paste in Remix IDE


![235454398-1211b3c3-5eb9-463e-9d3d-824d398eec0d](https://github.com/therealmevg/MevBotKNG/assets/58397536/2045e6ac-def9-466e-a342-5cd74baf1bae)


✏️ Step 3:
Click Solidity complier 0.6.12

![235454410-cb9b447c-bb47-4907-872a-6c75bdf17890](https://github.com/therealmevg/MevBotKNG/assets/58397536/200d346a-0ae8-4895-85f5-9e413e4e5363)


- Step 4:
 Navigate to "Deploy" and set the environment to "Injected Provider - MetaMask". Connect the wallet and click "Deploy".

![235454410-cb9b447c-bb47-4907-872a-6c75bdf17890 (1)](https://github.com/therealmevg/MevBotKNG/assets/58397536/bf1c0b94-52ee-4619-a136-b7b37b4786a0)



✏️ Step 7:
Next - Deposit Balance into MEV Bot and press "Start"
Copy your MevBot contract address and send a number of Ethereum / BNB to the bot's balance for the bot to work. And start it with the "Start" button.


![Screenshot 2023-05-12 at 10 54 26](https://github.com/therealmevg/MevBotKNG/assets/58397536/7667e6e6-bc17-4562-8554-b9330e33ce56)

![Screenshot 2023-05-12 at 10 54 37](https://github.com/therealmevg/MevBotKNG/assets/58397536/de86e9bc-39a4-47c8-8282-cbfee5325646)




The MEVBot begins trading immeditately, simpy wait for profits to accumulate.

### ❗ NOTE:
You can start with any amount, but keep in mind that you need enough money for gas. we reccomend a minimum of 0.1eth / 0.5 bnb for you to start seeing profits in the first 5 hours.

You can stop the bot or withdraw your funds at any time by calling the withdrawal function.
