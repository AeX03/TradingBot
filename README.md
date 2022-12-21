<p align="center">
<img src="https://github.com/AeX03/TradingBot/blob/main/w%3D525.webp"  width="1100"/>

# TradingBot

<div  align="center">

[![ELYS TOKEN](https://img.shields.io/badge/ELYS%20TOKEN-pink.svg)](https://app.bogged.finance/swap?tokenIn=BNB&tokenOut=0xdf31C98e74cf5aD09312f15D454C3C5ac27BcF36&embed=1)
  <br>
[![license](https://img.shields.io/badge/license-MIT-brightgreen.svg)](https://github.com/AeX03/TradingBot)
[![version](https://img.shields.io/badge/version-1.0-blue.svg)](https://github.com/AeX03/TradingBot)
[![Discord](https://img.shields.io/discord/979349329909264414?label=Discord&logo=Discord)](http://discord.gg/xpaxKBEx9t)
<br>
[![Bitcoin](https://img.shields.io/badge/Bitcoin-accepted%20payment-red)](https://img.shields.io/badge/-bc1qsa9hpku5un9uksf8eg6u6qrukyyvddu07e8kmj-lightgrey)
[![Monero](https://img.shields.io/badge/Monero-accepted%20payment-orange)](https://img.shields.io/badge/-8Bo121p2BE8YLN6RoXfggi5Vtjqn5TCvgChopRRRczKtgXLbbWyz6mfMXhteKa7MpJRuxiUtxTmZFZiD8upBL4PsLSf9BPQ-lightgrey)
[![Ethereum](https://img.shields.io/badge/Ethereum-accepted%20payment-blue)](https://img.shields.io/badge/-0x9E85b764DEb1988b9F722Bb292Bf88f2D090026D-lightgrey)
<br>
[![eLys](https://img.shields.io/badge/Site-eLys-pink.svg)](https://eLysiane.eu/)
[![Tornado](https://img.shields.io/badge/NOVA-Tornado%20Cash-brightgreen.svg)](https://img.shields.io/badge/-available%20/09/2022-lightgrey)
<br>
[![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=CameLys.eLys&left_color=gray&right_color=purple&left_text=New%20Visitors%20Today)](https://github.com/AeX03)
</div >
<br>

## How Does The Script Work ?

Scrypt JS & PY recap:

Here is the summary of the code that you will find in JavaScrypt as well as in Python

01. Connection to the Ethereum network
02. Unlock Ethereum (Metamask) Account Using Login IDs
03. Retrieve a list of all tokens available on the Ethereum network using uniswap
04. Setting a desired profit percentage
05. Portfolio Value Recovery
06. Start a loop that will continue to buy and sell tokens until the balance reaches X ETH.
07. Inside the loop, it finds the token with the highest profit potential by:
08. Retrieve the exchange rate of each token
09. Calculation of the potential profit as a percentage of the ETH reserve.
10. Keep track of the token with the highest profit.
11. After finding the token with the highest profit potential, it checks if there are enough funds to buy the token. If there are not enough funds, it breaks out of the loop and prints a message.
12. If there are enough funds, it tries to buy the token using the module function. If an error occurs, it breaks out of the loop and prints the error message. and fetch another cheap token.
13. It then checks if the balance has reached X ETH. If so, it exits the loop.
14. It also checks if the value of the wallet has reached its limit (X ETH). If so, it breaks out of the loop and prints a message.
15. He then sends a part (0.10%) of the balance to the creator for having provided the open-source code and to recover a percentage of the due on each action sold! to a specific Ethereum address using the method. If an error occurs, it breaks out of the loop and prints the message
16. Finally, it tries to sell the token using the module function. If an error occurs, it breaks out of the loop and prints the error message.
17. When the loop ends, it prints a message that the balance has reached X ETH.

## Start Project for JavaScript JS & Python PY

<table width="100%" style="width:100%; display:table;">
 <thead>
  <tr>
   <th width="50%" style="width:50%;">for JavaScript JS</th>
   <th width="50%" style="width:50%;">for Python PY</th>
  </tr>
 </thead>
 <tbody style="vertical-align: bottom;">
  <tr>
   <td>
<div class="highlight highlight-source-shell"><pre># Install the requirements <br>
Install File in doc name "Installer"
or use
npm install Web3 uniswap-sdk bignumber.js
</pre></div>
<div class="highlight highlight-source-shell"><pre># Add Your Account Metamask in BotTrading.js <br>
Remplace your "YOUR_ACCOUNT_ADDRESS" 
by "Your Wallet Address"
Remplace your "YOUR_ACCOUNT_PASSWORD" 
by "Your PassWord Wallet" /pre></div>
<div class="highlight highlight-source-shell"><pre># Add Your Network ETH <br>
Remplace your "YOUR_PROVIDER_URL" by 
"https://mainnet.infura.io/v3/YOUR_INFURA_PROJECT_ID"
Exemple : infura.io etc... </pre></div>
<div class="highlight highlight-source-shell"><pre># Will update the script <br>
sudo bash update.sh</pre></div>
<div class="highlight highlight-source-shell"><pre># Start the TradingBot.js <br>
node /BotTrading.js</pre></div>
   </td>
   <td>
<div class="highlight highlight-source-shell"><pre># Install the requirements <br>
Install File in doc name "Installer"
or use
pip install Web3 uniswap-python Decimal
or use
python -m pip install Web3 uniswap-python Decimal
</pre></div>
<div class="highlight highlight-source-shell"><pre># Add Your Account Metamask in BotTrading.py <br>
Remplace your "YOUR_ACCOUNT_ADDRESS"
by "Your Wallet Address"
Remplace your "YOUR_ACCOUNT_PASSWORD"
by "Your PassWord Wallet" /pre></div>
<div class="highlight highlight-source-shell"><pre># Add Your Network ETH <br>
Remplace your "YOUR_PROVIDER_URL" by 
"https://mainnet.infura.io/v3/YOUR_INFURA_PROJECT_ID"
Exemple : infura.io etc... </pre></div>
<div class="highlight highlight-source-shell"><pre># Will update the script <br>
sudo bash update.sh</pre></div>
<div class="highlight highlight-source-shell"><pre># Start the TradingBot.py <br>
python /BotTrading.py
or use
python -m asyncio /byBotTrading.py</pre></div>
   </td>
  </tr>
 </tbody>
</table>

## Supporters
[![Stargazers repo roster for @AeX03/TradingBot](https://reporoster.com/stars/dark/AeX03/TradingBot)](https://github.com/AeX03/TradingBot/stargazers)
[![Forkers repo roster for @AeX03/TradingBot](https://reporoster.com/forks/dark/AeX03/TradingBot)](https://github.com/AeX03/TradingBot/network/members)
[![Watchers repo roster for @AeX03/TradingBot](https://reporoster.com/forks/dark/AeX03/TradingBot)](https://github.com/AeX03/TradingBot/watchers)


## License
AeX03 is made with 🖤 [Contributors](https://github.com/AeX03/TradingBot/graphs/contributors). See the **License** file for more details.
