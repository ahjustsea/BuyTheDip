# BuyTheDip

BuyTheDip is a project made to help with crypto investing. It's purpose is to determine whether current prices are significantly/statistically lower (dips) or higher (peaks) than it has been in the last two weeks. Buying these dips and selling at these peaks will yield greater return on investment, though this algorithm cannot tell you if the price has stopped dipping or peaking. Whether you sell or not is entirely up to you, but a portfolio that buys at dips will definitely outperform a scheduled-time-purchases (e.g., DCA). 

Current cryptocurrency prices are fetched from coingecko API every 20 minutes. Z-scores are posted every hour, and trends in z-scores are posted every other hour. However, when large dips/moons are happening, z > 2 or z < -2, the results are posted immediately. More coins/tokens can be added on demand. 


## about z-scores

Z-scores for each cryptocurrencies are calculated from trading volume-adjusted two-week moving averages and standard deviations. 

1. Z-score greater than +2 means that the current price is significantly **HIGHER** than what's expected from the last two weeks. In this case, *you may consider ***selling*** some coins to take some profits*. If you're looking to buy at z-score > 2, you will be paying a premium.

2. Z-score less than -2 means that the current price is significantly **LOWER** than what's expected from the last two weeks. In this case, *you may consider ***buying*** more coins as it is a good time to buy*, and prices may go back to norm. 

3. Z-score between +2 and -2 means that the current price is very similar to the average price of last two weeks. In other words, the price is **fair**. 


## donations
If you would like to support BuyTheDip, you can make a donation below. Any support is greatly appreciated. Especially becuase I have a PhD in something practically useless and I really need all the help I can get. Thank you!

BTC: bc1qcay52dwm8h7qugj4tkzjcg0wrzhqf9jsh62sgn

ETH: 0xA1e608C40C88B83e3325a9f25E0523BE8bC977d2

ADA: Ae2tdPwUPEZMc9Jp6RVE4SfCKpQCQD4LMZKiSaoyCtSzTE5JNrZNrvBiyTT

XLM: GBC7BWLJ7LPGZGNSBOQQAGA4IQB3OINZ3WT7FHUQ3XRAWFJQC56X34XL

USDT: 0xA1e608C40C88B83e3325a9f25E0523BE8bC977d2

XRP: rDkw7qyugKu6oBxe4B1HnUF39WpKRC59uT

DOGE: DKwBg5xx946AMYrSQL1ZecGazetWHRe7Rs

SHIB: 0xA1e608C40C88B83e3325a9f25E0523BE8bC977d2

r/cc MOON: 0x1a5fce959e9e6574cba3893f9d3abcc127d8c82b
