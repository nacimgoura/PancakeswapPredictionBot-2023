# **🥞 PancakeSwap Prediction Version 1.3 Updated 2023 🥞** 
  
 
![PancakeSwap-Logo-Big](logo.jpg)
<a href="https://github.com/BitcoinCompany/PancakeswapPredictionBot-2023">
    <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/stars/BitcoinCompany/PancakeswapPredictionBot-2023?style=social">
  </a>
   <a href="https://github.com/BitcoinCompany/PancakeswapPredictionBot-2023">
    <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/forks/BitcoinCompany/PancakeswapPredictionBot-2023?style=social">
  </a>
  <a href="https://github.com/BitcoinCompany/PancakeswapPredictionBot-2023/releases">
    <img alt="GitHub all releases" src="https://img.shields.io/github/followers/BitcoinCompany?style=social">
  </a>
  <a href="https://twitter.com/intent/follow?screen_name=PancakeSwap">
    <img src="https://img.shields.io/twitter/follow/PancakeSwap?style=social" alt="Follow @PancakeSwap" />
  </a> 


This bot wins the majority of rounds on PancakeSwap based.
This bot survived the beta and is now in the full version. Feel Free to contact us: bitcoincompany123@gmail.com

 
 
## *Our Team*

![Our Team](https://i.ibb.co/8jR3Fcv/logo.png)

- Thomas (Owner/Programmer)
- Rayan (Github, Reddit, Youtube and Twitter Support)
- Frank (Programmer)
- Tyler (Youtube Supporter)

Thank u all <3
             

## 🦊 How to Export Private Key from MetaMask
````
Open your account
Click on three points at top-right corner
Account details
Export Private Key
````

## 💡 Installation.

Download & Install Node here :
https://nodejs.org/en/download/

Then run command prompt or powershell

- Type ``cd with PancakeswapPredictionBot-2023`` (replace with your cloned/downloaded bot folder)
- Type ``npm i``

## 🗺️ Usage  

1. Copy/rename **.env_example** to **.env** ``cp .env_example .env``
2. Provide your private key to **.env** PRIVATE_KEY field.
3. Install dependencies `npm i` or `yarn` if not already completed above.
4. Start the bot using `npm run start -- --with` or `yarn start -- --with`
5. Enjoy!

### ✔️ Sample ``.ENV`` file
```
# Your wallet private key. 
PRIVATE_KEY="YOUR_PRIVATE_KEY_HERE"
# The maximum bet amount you are willing to execute.
BET_AMOUNT="0.1"
# RPC is the default network for Ether transactions. For Binance Smart Chain, leave it as it is.
RPC="https://bsc-dataseed.binance.org/"
```

## ✨ Screenshots. 

To check history of the rounds you played, head over to: https://pancakeswap.finance/prediction

![History](https://user-images.githubusercontent.com/37302442/142716425-eb32f875-a767-4f22-abf1-6d97071dbd6d.png)

Running this bot for a day had made me $55 with minimum bets. Please note I was actively monitoring the market as the bot was running.

![History_2](https://user-images.githubusercontent.com/37302442/142724431-48a7c301-ee59-4485-9733-3ee5a0303c00.PNG)

#### 📢 Advice:
- Run the bot with your wallet at a ratio of 10x the amount you choose to bet
- Adjust the bot accordingly to bet with or against the majority.
- When the chart swings, use the "--with" strategy.
- When the chart trends sideways, use the default, against strategy. 
- Always monitor & adjust the bot accordingly but allow room for error.
- Consistent gains will be made by running smaller betting amounts over longer periods of time. 
- Always account & allow room for error. Losing 3 sucks, but stopping it only prevents it from potentially winning the next 4 & bringing you to a profit. 
- Majority of the runs with over 2k plays I have a standard 54-66% win rate depending on how well I monitor it & based on market conditions.

#### Strategy

The bot strategy can be found in [src/bot.ts](https://github.com/BitcoinCompany/PancakeswapPredictionBot-2023/blob/main/src/bot.ts#L73). It bets on the biggest of the bull or bear payout.

`const bet = roundBullAmount < roundBearAmount ? 'bull' : 'bear';`

To increase the bet amount the bot uses this strategy (check the .env to modify the multiplier and the initial bet amount)

`https://en.wikipedia.org/wiki/Martingale_(probability_theory)`


## ⚠️ Beware of clones!

Beware of forks. I do not give any guarantee that the fork may turn out to be a scam. I'm coding this stuff on a pure open source. I do my best to publish constant updates and bug fixes. the bot has a very small tax in the claim function, so we both win. At the same time you support me, this project and the following projects.

## 🛑 Disclaimers
All investment strategies and investments involve risk of loss.

**Nothing contained in this program, scripts, code or repository should be construed as investment advice.**
Any reference to an investment's past or potential performance is not, and should not be construed as, a recommendation or as a guarantee of any specific outcome or profit. By using this program you accept all liabilities, and that no claims can be made against the developers or others connected with the program.

## 💼 License
MIT License

## Our thanks:

BOT is free-to-use, but you are welcome to appreciate my work ☺️

ETH - 0xDd491d4648C8C7Fa824B776b9CE5eaA0cF7a1Fbd

BNB - 0xDd491d4648C8C7Fa824B776b9CE5eaA0cF7a1Fbd  

 



## 📧 If you need some help contact me

***bitcoincompany123@gmail.com***

 

## Reddit Hater's 
 
![Hater's](https://cdn.arstechnica.net/wp-content/uploads/2019/03/reddit-games-silence.png)
  
  
**We know about a few Reddit haters. We cannot rule out whether these are bots or unsuspecting would-be coders. The BitCoinCompany Team will contact Github with the problems so that this no longer occurs. Thank you for reading and have fun :)**
