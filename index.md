
BuyTheDip is a project made to help with crypto investing. It's purpose is to determine whether current prices are significantly/statistically lower (dips) or higher (peaks) than it has been in the last two weeks. Buying these dips and selling at these peaks will yield greater return on investment. Whether you sell or not is entirely up to you, but a portfolio that buys at dips will definitely outperform a scheduled-time-purchases (e.g., DCA). 

Current cryptocurrency prices are fetched from coingecko API every 20 minutes. Z-scores are posted every hour, and trends in z-scores are posted every other hour. However, when large dips/moons are happening, z > 2 or z < -2, the results are posted immediately. More coins/tokens can be added on demand. 


## about z-scores

Z-scores for each cryptocurrencies are calculated from trading volume-adjusted two-week moving averages and standard deviations. 

1. Z-score greater than **+2** means that the current price is significantly **HIGHER** than what's expected from the last two weeks. In this case, *you may consider ***selling*** some coins to take some profits* assuming that your average cost per coin is lower than the current price. If you're looking to buy at z-score > 2, you will be paying a premium.

2. Z-score less than **-2** means that the current price is significantly **LOWER** than what's expected from the last two weeks. In this case, *you may consider ***buying*** more coins as it is a good time to buy*, and prices may go back to norm. 

3. Z-score between +2 and -2 means that the current price is very similar to the average price of last two weeks. In other words, the price is **fair**. 


## does it work?

Yes, buying cryptos when z-scores are less than -2 or -3 can make you 6-20% additional returns on your investment. Detailed information on how BuyTheDip makes more returns on your investment can be found [here](https://ahjustsea.github.io/BuyTheDip/whythisworks)

![alt text](https://ahjustsea.github.io/BuyTheDip/BuyTheDip.png)

scenario |	n |	total_bitcoin |	total_fiat |	latest_price |	total_worth	gain |	gain_per
-----: | -----: | -----: | -----: | -----: | -----: | -----: 
S1: |	Scheduled purchase ($100 every two weeks) |	77 |	0.8605088 |	$7,700.00 |	$60,000.00 |	$51,630.53 |	$43,930.53 |	570.5%
S2: |	BuyTheDip @ z-score -2 |	1000 |	0.9195261 |	$7,700.00 |	$60,000.00 |	$55,171.56 |	$47,471.56 |	616.5%
S3: |	BuyTheDip @ z-score -3 |	139 |	1.0259890 |	$7,700.00 |	$60,000.00 |	$61,559.34 |	$53,859.34 |	699.5%

## future development/work-in-progress

Machine learning based short-term predictions for z-scores


### donations

If you would like to support BuyTheDip, you can make a donation below. I have a PhD in something practically useless, so any support is greatly appreciated. Thank you!

**BTC**: bc1qcay52dwm8h7qugj4tkzjcg0wrzhqf9jsh62sgn

**ETH**: 0xA1e608C40C88B83e3325a9f25E0523BE8bC977d2

**ADA**: Ae2tdPwUPEZMc9Jp6RVE4SfCKpQCQD4LMZKiSaoyCtSzTE5JNrZNrvBiyTT

**SOL**: 8oETiSiMJhR1iMSPqWQDZ24qhToxfdBZHG5AP9Jfimv6

**XLM**: GBC7BWLJ7LPGZGNSBOQQAGA4IQB3OINZ3WT7FHUQ3XRAWFJQC56X34XL

**USDT**: 0xA1e608C40C88B83e3325a9f25E0523BE8bC977d2

**DOGE**: DKwBg5xx946AMYrSQL1ZecGazetWHRe7Rs

**SHIB**: 0xA1e608C40C88B83e3325a9f25E0523BE8bC977d2

**r/cc MOON**: 0x1a5fce959e9e6574cba3893f9d3abcc127d8c82b
