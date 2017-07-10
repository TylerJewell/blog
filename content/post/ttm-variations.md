+++
date = "2017-07-09T05:36:35-07:00"
draft = false
title = "TTM Variations"
+++

Over the years of trading TTM, I have made adjustments to increase returns or mitigate perceived risks. The flavors include:  

1. Risk Adjustments
2. IRA Adjustments 
3. At-the-Money Exploitation
4. Underlying Diversification
5. Small Account Adjustments

##### Risk Adjustments
It's possible to change the strategy to reduce or increase risk. My historical rate of return has been close to 21% CAGR, which is .35% CWGR. This includes times where I hvae made great aggressive rolls during a week and also times where I have made severe mistakes. I guess that my losses from mistakes cancel out the gains from being aggressive over time.

Mistakes and unnatural gains haev a tendency to happen when I trade closer to the money. When I set an aggressive weekly target, the strikes are closer to at-the-money, and the likelihood of having to adjust early or more frequently is higher. Once you get into a cycle of rolling and adjusting, it's a continual process. If you are aggressive like I am, you frequently have either calls or puts ITM, and so certain sides of the trade are showing lossses or gains, sometimes dramatically so. So, this leads week over week oscillations that are higher as the market is bouncing around.

I can moderate my risk by closing all open positions and beginning again from a new starting position where the strangle is appropriately spaced away from where the market currently sits. I do this by always opening the same number of puts and calls, but lowering the weekly income expectation. By reducing the weekly income expectation, you lower the amount of premium that is targeted for a single week. And this lets you find strikes that are further OTM from where the stock is currently at. 

For example, if I wanted to target a .2% weekly gain, which would lead to a 11% yearly gain, I would open the same number of contracts at different locations. With the market closing at $2425 on July 7th, 2017, I would open puts closing on July 17th at $2350, more than 3% margin of safety. A 3% move in a single week is around a 4% probability, so in a bull market this may be a once a year phenomenon. The call side would have a similar protection, opened at $2470, about 2% OTM. This would be threatened seriously 2-3 times / year. In either case, if the position was threatened, I could adjust early giving myself ample room to move out in time and further away from ATM. In a low IV scenario, this likely means that the market would lose momentum quickly and exhaustion would keep my options OTM or perhaps a reversal would increase the margin of safety. 

Reducing the risk does not mean no risk, however. No matter how small your weekly expectation is, there is always risk. Reducing the weekly expectation just reduces the number of weeks where you are threatened and you have to use adjustments to dig out of the hole that is created. There are some traders that use the reduced risk to create a mental mindset that they must not be as skilled in adjusting threatened sides. When threatening happens infrequently, then the trader is less skilled (emotionally and tactically) in how to trade through the threatening periods. I always trade with a mindset where I will always be threatened. This keeps the risk in perspective and transforms it into a number, but prevents risk complacency from setting in.

##### IRA Adjustments
I first started trading TTM at eTrade [in a TREG margin account](http://www.investopedia.com/terms/r/regulationt.asp). I left my 401K and IRA accounts untouched invested in index funds.

After I became comfortable with the principles of TTM, I wanted to get the same benefits for trading in an IRA account. IRA accounts are cash margin, requiring risk to be bounded. The presumption is that IRA accounts can never have a margin call. 

TTM calls for using margin safely. The upside and downside scenarios have been mapped out and understood. Given this understanding, why would IRA brokers not allow for trading a similar philosophy in that account? If the trader has mapped out the various outcomes and willing to assume the risk, could they pursue the higher risk strategy?

IRA accounts can be converted to behave similarly to TREG or [Portofolio Margin](https://en.wikipedia.org/wiki/Portfolio_margin) where the extra leverage is exploited. This is where I remind readers that the risk associated with leverage is immense, and please do not trade anything with leverage without a clear understanding of the risks you are taking. And my lawyer would be telling me that I must tell you that trading is inherently risky and that you are trading at your own risk. 

Many brokers will let you trade options in IRA accounts as long as the risk is bounded. You can do this with long options at the same expiration in the same contract size as the short options. 

Let's assume you are targeting .3% return / week on a $500,000 IRA account. On July 7th, the market closed at $2425. If you are accepting a 50% drop before adjustments can be made, this would allow you to open 5 puts. 50% survival means the market can move $1210 before you can make a move, allowing you $121,000 / contract. $500K / $121K = 4.1. (I use a ceiling function in my calculations to round up as I do not mind accepting the additional risk). The ceiling of 4.1 is 5 puts. The target is $1500 for the week and $750 from the put side of the strangle. You will need $1.50 / contract @ 5 contracts to generate the put side. As of July 7th, you could open puts that expire on July 17th (9 days to expiration) for $1.50 at a $2365 strike price, which is just a little under 3% margin of safety.

For this to work in an IRA account, I would also open 5 long dated puts, purchasing them for $.05. I would seek the highest strike price where options are selling for $.05. This is around $1850. This would make the IRA have 5 vertical put spreads, each with a spread of close to $600. Your IRA broker would calculate tihs as $300,000 in risk, which is below the $500,000 maximum they would allow. The long dated options are effectively worthless and have given the account the behaviors of a portfolio margin account.

The call side is similar. Saving you the calculations, I would look to open 15 call contracts generating $.50 each. I would look to open $2465 calls that generate $.50 credit. This gives a little less than 2% margin of safety. The long dated calls would be around $2520, or about $6000 / contract, or $90,000 in total risk allocation by your broker. Some brokers will treat the put and calls as offsets against each other as long as they are on the same expiration. Other brokers do not so the combined risk of the call spread and hte put spread must be below the total account value.

Adjusting positions in an IRA account requires extra management. 

First, it's generally quite difficult to adjust both the call and put position at the same time. So you will need to adjust one position at a time. If margin is offset between the call and the put, then adjusting one side to a different expiration wipes out this offsetting calculation and your broker will require that the margin allocated to puts and calls are combined below the total account margin value. If I am adjusting options out a week, there is usually a non-threatened short side that is at $.05 or close to it. You can close this side first, leaving the long position in the IRA account and removin the short side. IRA brokers treat any margin required for that spread as released. You can then adjust the threatened side using the full margin available to you.

Second, you will need to decide how to roll threatened positions. You can either do it in two transactions or a single transaction. If you perform it in two transactions, you will close the short option on the threatened side, and then open a new spread at the new expiration further out. The challenge with two transactions is that if the market is moving, then you will experience slippage where the premium you collect after the adjustment could be higher or lower than if you had done it as a single clean transaction. Market makers are tricky and usually a double transaction leads to slippage that benefits the counter party more than myself. In a single adjustment, you need to do a three legged order. You are both buying back the short position that is threatened and opening a new spread at the further expiration. This guarantees that you will not get any slippage, but makes the transaction harder to complete for the market maker. You may have to give up $.05-$.10 in additional premium to get a good price so that the trnansaction can complete.

Third, if you have a fast moving downward market, the risk gets harder to manage. As the market moves downward, implied volatility spikes. In order to purchase $.05 options at a new expiration, you will have to move further away in strikes. While in our example, $60K was the spread for a single week, as IV moves up, it could easily be $200K to get the same $.05 spread. This will force you to reduce the number of contracts that you are trading to fit within the margin requirements or perhaps you will purchase more expensive put options at $.20 to keep the spread manageable. Chances are that if IV has increased dramatically, then you are also collecting a lot more premium. If you have gotten inverted where your short option is ITM, then you may be collecting great premiums, but have to look at pushing your short option out much further than one week to get out of trouble. And the further out in time you must push, the further down the stack your long options will be to find. So, please be careful trading within an IRA account, some of the adjustment philsophies available to PM accounts are less flexible in an IRA account.

##### At-the-Money Exploitation
There is more premium ATM than OTM. Subsequently, you can open fewer contracts to obtain the same amount of premium vs. the contracts that must be opened further OTM. How would the strategy adjust if there were fewer contracts opened, but ATM?

The original strategy assumes that the number of call contracts opened is based upon avoiding a margin call if the market rises 10%, though this was later revised to 15%. And the number of put contracts opened is based upon a downsize protection of 50%. The algorithm calls for at least 3x the number of put contracts opened. In early versions of the algorith, I often had 5x the calls vs. puts opened. It was not unusual to see 10 puts and 50 call contracts opened for every million dollars invested.

The downside of heavy call contract volume is the cost of digging out of losses when the position is over-threatened or potentially even breached, usually due to a v-shaped rally. If the call position is caught ITM, even after pre-mature roll out adjustments, the volume of contracts that are ITM is rather large given the total position. Subsequently, the time needed to unravel and adjust is longer than normal, unless you get an immediate reversal. Immediate reversals are uncommon with v-shaped rallies or long term bull markets. The buying resilience of buyers limits the severity and frequency of adjustments. For example, my records from 2014 after QE3 showed that the market jumped 10% quickly, and multiple adjustments to month out in time did not prevent options from going ITM. I was using ATM puts to generate as much income as possible and closing ITM calls with that extra premium. But there were so many calls that went ITM that it was 9 months before that position was managed to be OTM. 

During a strong trending market, it could be possible to unwind an ITM position faster if the starting number of contracts was smaller.

Strategy modifications:   

1. Call contract position size should match the put contract position size.
2. Open pull and call contracts slightly OTM, usually generating 1-2% of cash.
3. This guarantess that at expiration, one side is likely ITM. There is almost always options ITM.
4. Use spread of extra cash generated beyond the weekly target to close ITM options or move them to OTM.
5. Reopen the OTM position to be ATM or slightly OTM for the next expiration once it expires.

I began this strategy at the beginning of 2017. The objective was to increase the rate of return instead of avoiding the risks of over leverage. When opening contracts ATM, the amount of cash generated is generous, so would ensure that cash generated since the beginning of the year is equivalent to .4% / week, so that if that rate of cash can be maintained over time, then the NLV will follow suit eventually, even if NLV oscillates from underlying price movement.

The results of this variation are indeterminate. My first live test opened options where the market began a strong and lasting upward movement with a historically low IV period. This caused some of the call contracts to go deep ITM and it was taking extensive time to use cash generated from OTM and ATM puts to dig call contracts to OTM. On an expectation of an imminent reversal, my put contracts were opened .5%-1% OTM. This is in violation to the strategy adjustment rules, which is to open ATM contracts when a threatened side goes ITM. There were a couple months of this violation, and had the rules been followed, my 2017 results mid-year would likely be 2% higher than where they were at.

##### Underlying Diversification
I only trade TTM against SPX, or sometimes against /ES, SPY or similar vehicle tied to the S&P 500. Early in the strategy, I blended the strategy across options on a variety of futures tied to oil, USD, cattle, gold, silver, wheat, soybeans, bonds, NDX, and RUT. I never executed the strategy against individual stocks.

Diversification across different asset classes would open up different kinds of implied volatility. And it would be likely the case that some asset classes would not be trending (great for option sellers) while others were trending (generally showing losses). This could smooth out the returns. 

The strategy was independently executed against each asset class. This requires splitting your cash reserves into multiple pools of independently managed money. I had different return expectations for each asset class given the risk factors that were anticipated.

I ultimately stopped trading this diversification and go exclusively SPX because:   

1. The time required to trade spiked. It takes me 30 minutes each week to trade a set of positions againts a single asset class. My efforts were nearly 8 hours / week with the additional asset classes.

2. The asset classes were usually correlated in unexpected ways. Most asset classes were trending simultaneously due to unintended correlations that underlie the market. The premise of safety from diversification was not observable in the early results.

3. The S&P 500 has numerous and strong earnings projections. The price of the SPX can be forward projected based upon reasonable PE ratios, giving a higher confidence on a future price range to trade within. This work is done by dozens, if not 100s of analysts, so can have a high degree of reliability. The same analysis for the fundamentals affecting the price of other assets is not as freely available, making future price range predictions harder. The effort to study other asset classes caused research time to jump to 20 hours / week.

4. Other asset classes do not have the "no-crash-up" concept that is the foundation of my particular strangle strategy. The downward or upward risk assumption, bounded by 50% and 15% with SPX was adjusted to 75% and 75% with other asset classes.

5. Liquidity of contracts was not always present in other asset classes. Mixed with high fees associated with trading options on futures, you absorb high costs from rolling threatened positions regularly.

6. It is harder to dig out of a hole when one side is threatened when you have a smaller pool of funds. If following diversification, then avaialble working capital has been allocated to other asset classes, offering a smaller number of contracts to be opened in the strangle. When one side is threatened in a strangle, the opposite side is moved to ATM and the funds are used to move the ITM side to OTM. The larger number of contracts that can be opened ATM means that more ITM contracts can be more quickly moved OTM. Fund diversification weakens the accounts ability to dig out of any single threatened position.

##### Small Account Adjustments
I trade my primary account using Portolio Margin. Most PM brokers require $100,000 in starting capital, which may be out of reach for some traders. Before going into PM, I started off with a TREG margin account. The basic principles with the right amount of leverage should be available in a TREG account.

One issue is trading SPX. It's great given it's large size requiring fewer contracts to be opened and its tax advantaged status. Also, the European contract expiration is essential to avoid stress from early exercise.

However, SPX contracts with the market hovering around $2400 require $100,000 of available capital in any type of margin so that you can open up a single put contract with a reasonable margin of safety. Also, if one side of the strangle is threatened and I must move the non-threatened side to ATM, having a small amount of funds does not allow me to move many contracts to ATM. 

In these scenarios, it may be advisable to switch over to an ETF equivalent, like SPY, that trades at one tenth the size of SPX. This gives a higher volume of contracts offering finer grained management during periods of adjustment.

One positive benefit to trading this way is that your volume of contracts traded will be nearly 10x higher, giving some additional bargaining power with the broker to press down the cost / option contract.