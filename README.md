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
<br>
<img align width="1800" src="https://github.com/AeX03/AeX03/blob/main/picture/gif-line.gif"/>
<br>
01. Requests a connection to the Metamask account on the Ethereum network.
02. Asks for a desired profit percentage.
03. Requests the number of ethereum wallet balances to reach.
03. Retrieve a list of all the tokens available on the Ethereum network using the coincapmarket site for real-time prices.
04. Portfolio Value Recovery.
05. Start a loop that will buy chips with the desired percentage value.
06. Inside the loop, it finds the token with the highest profit potential by :
- Retrieve the exchange rate of each token.
- Calculation of the potential profit as a percentage of the ETH reserve.
- Keep track of the token with the highest profit in a specifc folder to see which tokens are buying.
07. After finding the token with the highest profit potential, he checks if there are enough funds in the Metamask account to buy the token while signing the   transaction. If there are not enough funds, he will go to the next token and will write a message next to the token in the specifc folder with the NAME, ADDRESS and quantity he could not buy.
08. It then checks if one of the tokens with the token sell percentage rate has been reached if so it will start a loop to sell it.
09. Inside the loop, if it finds the token with the percentage to reach it will :
- Sell the token and keep track in the specific folder with the NAME, ADDRESS it sold.
- Show win percentage win.
10. It also checks if the value of the wallet has reached its limit (X ETH). If not, it will start the buying and selling loop again.
If so, it exits the loop and displays a BALANCES REACHED X ETH message.
11. He then donates a portion (0.10%) of the balance to the creator for providing the open-source code and recovering a percentage of the due on each share sold !
12. When the loop completes, it prints a message that the balance has reached X ETH.

<br>
<img align width="1800" src="https://github.com/AeX03/AeX03/blob/main/picture/gif-line.gif"/>
<br>

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
Install File in doc name "Installer.sh"
use sudo chmod +x install.sh
and sudo ./install.sh
or sudo bash install.sh
</pre></div>
<div class="highlight highlight-source-shell"><pre># Will update the script <br>
sudo bash update.sh</pre></div>
<div class="highlight highlight-source-shell"><pre># Start the TradingBot.js <br>
node /BotTrading.js</pre></div>
   </td>
   <td>
<div class="highlight highlight-source-shell"><pre># Install the requirements <br>
Install File in doc name "Installer"
use sudo chmod +x install.sh
and sudo ./install.sh
or sudo bash install.sh
</pre></div>
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
<br>
Luca364 is made with 🖤 [Contributors](https://github.com/luca364). See the **License** file for more details.
