

![](https://ahjustsea.github.io/BuyTheDip/bitcoindips_white.png)

BuyTheDip is a project made to help with crypto investing. It's purpose is to determine whether current prices are significantly/statistically lower (dips) or higher (peaks) than it has been in the last two weeks. Buying these dips and selling at these peaks will yield greater return on investment. Whether you sell or not is entirely up to you, but a portfolio that buys at dips will definitely outperform a scheduled-time-purchases (e.g., DCA). 

[@BitcoinDips](https://twitter.com/bitcoindips) on Twitter:

1. Current cryptocurrency prices are fetched from coinmarketcap & coingecko API every 20 minutes. Z-scores are posted every hour unless when large dips/moons are happening, z > 2 or z < -2, the results are posted immediately. 

2. 24-hour trends in z-scores are posted three times a day: 11:30am, 7:30pm and 3:30am EST.


## Mole, The Connoisseur of Flavourful Dips
Current status: **Mole** is in live beta. 
Birthdate: Oct 27th, 2021.

Going to bed? Stepping out for dinner? Kids crying their eyes out? **Mole** [@bitcoindipsMole](https://twitter.com/bitcoindipsMole) is here to help! Mole gives suggestions for limit buys based on z-scores so that you can catch large dips while you are away from the computer. For Mole to respond, you have to follow [@bitcoindips](https://twitter.com/bitcoindips).


![](https://ahjustsea.github.io/BuyTheDip/ToCallMole.png)


### Function 1: To get dip levels, 
  
- tweet ***"@bitcoindips !getdips \$SYMBOL"***. 

For example, tweet ***"@bitcoindips !getdips \$BTC"*** to get bitcoin suggestions. If you try calling more than one symbol, only the first will be used.

- **Level 1 favourless dip** = **Ketcup**. What the price (USD) would be if z-score dropped to **-1**.
- **Level 2 good dip** = **Hummus**. What the price (USD) would be if z-score dropped to **-2**.
- **Level 3 great dip** = **Tzatziki**. What the price (USD) would be if z-score dropped to **-3**.
- **Level 4 exquisite dip** = **Guacamole**. What the price (USD) would be if z-score dropped to **-4**.
- **Level 5 heavenly dip** = **Fondue**. What the price (USD) would be if z-score dropped to **-5**.
- \$SYMBOLS currently supported: **\$BTC**, **\$ETH**, **\$DOGE**, **\$SHIB**, **\$BNB**, **\$ADA**, **\$XRP**, **\$DOT**, **\$SOL**, **\$MATIC**, **\$MOON**

### Function 2: ***(WARNING, ONLY FOR RISKY/AGGRESSIVE INVESTORS)*** To get dip levels that will fill sooner,

- tweet ***"@bitcoindips !getspicy \$SYMBOL"***. 

This differs from the previous function in one aspect: Dips are calculated from current prices rather than moving day averages. These dips are risky in that *they're NOT statistically true dips*. To be used when you want to get on a coin that's trending up, but don't want to FOMO at sell order prices.  

- **Level 1 no spice dip** = **Ajvar**. What the price (USD) would be if z-score dropped to **-1** from current prices.
- **Level 2 mild spice dip** = **Cajun**. What the price (USD) would be if z-score dropped to **-1.5** from current prices.
- **Level 3 medium dip** = **Tabasco**. What the price (USD) would be if z-score dropped to **-2** from current prices.
- **Level 4 hot dip** = **Jerk**. What the price (USD) would be if z-score dropped to **-2.5** from current prices.
- **Level 5 very hot dip** = **Sambal**. What the price (USD) would be if z-score dropped to **-3** from current prices.
- \$SYMBOLS currently supported: **\$BTC**, **\$ETH**, **\$DOGE**, **\$SHIB**, **\$BNB**, **\$ADA**, **\$XRP**, **\$DOT**, **\$SOL**, **\$MATIC**, **\$MOON**

### Function 3: To get suggestions on what's dipping, 

- tweet ***"@bitcoindips !HeyMole whats good?"***. 

Mole will suggest what are currently good dips based on z-scores. Also works: "what's tasty?".


### Mole's Q&A:

- **How long does Mole take to answer?** Mole should get back to you within 2 minutes. If not, please let Mole know so errors can be tracked down and fixed!

- **Why are Mole's suggestions really low?** This happens when the crypto has pumped significantly in the last two weeks (and could be still pumping), so statistically significant dips are soooo far away. In this case, you may try \$getspicy instead of \$getdips. As stated in the warning above, it's pretty aggressive. But it's up to you. 

- **Why does one of the dips say "\$zero"?** It essential means that the price of the coin is volatile (very dramatic pumps in the last two weeks). In this case, it means that if this crypto ever reaches that level of dip, it's essentially crashed to zero. 

- **Mole cannot reply to protected tweets!**. In this case, please change your twitter settings to access Mole.

- **I did everything right and Mole still hasn't answered!** To prevent some spam attacks, Mole will only respond to accounts with at least one follower (Sorry). Or something has gone wrong. Please let me know!

- **Please be sensible towards calling Mole.** In the best case scenario, Mole will slow down and crash. In the worst case, Mole will get banned from Twitter.*


## About z-scores

Z-scores for each cryptocurrencies are calculated from trading volume-adjusted two-week moving averages and standard deviations. 

1. Z-score greater than **+2** means that the current price is significantly **HIGHER** than what's expected from the last two weeks. In this case, *you may consider ***selling*** some coins to take some profits* assuming that your average cost per coin is lower than the current price. If you're looking to buy at z-score > 2, you will be paying a premium.

2. Z-score less than **-2** means that the current price is significantly **LOWER** than what's expected from the last two weeks. In this case, *you may consider ***buying*** more coins as it is a good time to buy*, and prices may go back to norm. 

3. Z-score between +2 and -2 means that the current price is very similar to the average price of last two weeks. In other words, the price is **fair**. 


## Does it work?

Yes, buying cryptos when z-scores are less than -2 or -3 can make you 6-20% additional returns on your investment. Detailed information on how BuyTheDip makes more on your investment can be found [here](https://ahjustsea.github.io/BuyTheDip/whythisworks)

scenario |	times purchased |	bitcoin |	total ivnested (\$) |	current BTCUSD |	portfolio (\$) | profit (\$) |	profit (%)
-----: | -----: | -----: | -----: | -----: | -----: | -----: | -----:
Scheduled purchase (\$100 every two weeks; aka DCA) |	77 |	0.8605088 |	\$7,700.00 |	\$60,000.00 |	\$51,630.53 |	\$43,930.53 |	570.5%
BuyTheDip @ z-score -2 |	1000 |	0.9195261 |	\$7,700.00 |	\$60,000.00 |	\$55,171.56 |	\$47,471.56 |	616.5%
BuyTheDip @ z-score -3 |	139 |	1.0259890 |	\$7,700.00 |	\$60,000.00 |	\$61,559.34 |	\$53,859.34 |	699.5%

![](https://ahjustsea.github.io/BuyTheDip/BuyTheDip.png)


## Future development/work-in-progress

- Web Dashboard (coming soon) & Portfolio manager (coming later)
- Machine learning based short-term predictions for z-scores (who knows if it'll work)

## Reach out for suggestions

You can find me on reddit (u/Ahjustsea) or on twitter (@bitcoinDips)


### Donations

If you would like to support BuyTheDip, you can make a donation below. I have a PhD in something practically useless, so any support is greatly appreciated. Thank you!

**BTC**: <sub><sup> bc1qcay52dwm8h7qugj4tkzjcg0wrzhqf9jsh62sgn </sub></sup>

**ETH**: <sub><sup> 0xA1e608C40C88B83e3325a9f25E0523BE8bC977d2 </sub></sup>

**ADA**: <sub><sup> Ae2tdPwUPEZMc9Jp6RVE4SfCKpQCQD4LMZKiSaoyCtSzTE5JNrZNrvBiyTT </sub></sup>

**SOL**: <sub><sup> 8oETiSiMJhR1iMSPqWQDZ24qhToxfdBZHG5AP9Jfimv6 </sub></sup>

**XLM**: <sub><sup> GBC7BWLJ7LPGZGNSBOQQAGA4IQB3OINZ3WT7FHUQ3XRAWFJQC56X34XL </sub></sup>

**USDT**: <sub><sup> 0xA1e608C40C88B83e3325a9f25E0523BE8bC977d2 </sub></sup>

**DOGE**: <sub><sup> DKwBg5xx946AMYrSQL1ZecGazetWHRe7Rs </sub></sup>

**SHIB**: <sub><sup> 0xA1e608C40C88B83e3325a9f25E0523BE8bC977d2 </sub></sup>

**r/cc MOON**: <sub><sup> 0x1a5fce959e9e6574cba3893f9d3abcc127d8c82b </sub></sup>
