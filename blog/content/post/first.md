+++
date = "2017-06-12T05:36:35-07:00"
draft = false
title = "The Tyler Trading Method"

+++

**Revisions**  
2/1/12 – First Draft   
2/19/13 – Updates: Hedging precautions, rolling strategies.  
3/24/13 – Updates: Added some examples.  
6/23/17 - Refresh.

**Overview**  
In 2011 I became sick and recovered 9 months later. I became obsessed with finding ways to yield 10% in the market regardless of market direction. A consistent 10% return on invested capital in public markets with liquidity gave me confidence in long term financial security.

The obsession evolved into a hobby. I've shared this strategy on various popular trading forums to collect feedback and to help others seeking similar outcomes. This strategy was discussed for a period of many quarters on the Karen Super Trader Yahoo group and later dubbed by active participants on that group the "Tyler Trading Method (TTM)".

**Results**  
This investment approach has been pursued since 11/1/11 and has generated a 49% cumulative return in approximately 15 months of operation while spy would have returned around 20% over the same period.  This is averaging about .6% compounded weekly, though in the later quarters of this strategy have reduced the risk to target only a .4% weekly return. The largest drawdown has been -3% compared to SPY’s -8%.
 
The strategy assumes:  
- Volatility is a friend  
- Markets never crash to the upside  
- You do not have to pick a market direction to make money  
- Use leverage, safely, to get scale  
- Time is infinite, and therefore theta burn is a friend  

The game plan is to sell weekly strangles on broad-based indexes.  


This document outlines a strangle selling strategy and an investment fund organization structure to optimize around tax considerations.  This document is technical for audiences that wish to have a deeper understanding of the strategy the investment fund is using.  Individuals will need to understand concepts relating to derivatives, stock options, margining, and broker market making.


Components of the strategy:
1)	Underlying selection.
2)	Structure of the sale.
3)	Timing of the sale.
4)	Strike price of puts and calls to open.
5)	Sizing the positions.
6)	Adjusting positions as time moves.
7)	Adjusting positions as markets move.
8)	Making selective hedges to guard against black swan events.

UNDERLYING SELECTION
This strategy calls for options against broad-based indexes such as SPX, RUT, NDX.  This is because:
1)	Diversification.  Coverage across the equities markets means lower volatility, but lower upside or downside sudden risks.
2)	Tax Advantages.  Options against indexes in the US are taxed as 1256 contracts, which means 60% of all profits are treated as long term gains.  The same option on an equivalent ETF, such as SPY, is treated as short term capital gain for all profits in this strategy.  Options trading on ETFs or individual equities that are not treated as 1256 contracts need to have ~13% better gross returns to net the same funds as returns on vehicles that support 1256 contracts.
3)	European Contracts.  Index options are generally European style, which means that there is no risk of early assignment if you accidentally got caught ITM.  One less thing to worry about in risk mitigation.
4)	Option Liquidity.  Generally, you want to see at least 50K options being traded on the underlying each week to have enough liquidity in order to get the best possible price and to have liquidity when options need to be adjusted in times of market momentum.
5)	Strike Variety.  The underlying should have a wide range of strikes available each week.  As a rule of thumb, you want to see strikes at least 8% and 20% lower than the underlying.  Underlyings with limited strike selection, such as RUT, can create problems in situations where certain rolls are occurring or may not offer enough margin of safety in momentum markets.
6)	Reasonable Volatility.  We are generally seeking a daily implied volatility of at least 1.1%, though SPX rarely trades at that level except in periods of high VIX.  Lower volatility forces the seller to either give up weekly premium to maintain a reasonable margin of safety or to give up their safety.  
7)	Better Commissions.  Generally, indexes have large underlying values. A seller of contracts has to open fewer contracts to generate premium given a starting base of capital.  Fewer contracts to open (and to adjust in tough times) equates to lower overall commissions, which is a contribution to the bottom line.
8)	Number of Expiration Weeks Available.   Having many near term week expirations available gives the manager more adjustment options to pursue in a situation where an adjustment is necessary at all.   In particular, SPX has weekly expirations that go for the near term 8 weeks.  When an adjustment does need to occur, it is preferable to only go out a single week, but if the adjustment happens early, having the room to go further out in time is helpful.   Recently, the RUT has also added in this capability, making it a possibly attractive target.

STRUCTURE OF THE SALE
In its purest form, this strategy is selling an out of the money call and put with expirations in a couple of days.  The intent is to let the options sit until expiration, and there may be some situations where you close out the options early.  

This leaves the seller naked on both sides of the sale.  This approach will not work in IRAs as they are cash-based margin and subsequently require a significant amount of reserve to open a single contract.  IE, a $1350 put requires $135K in margin reserve, which is a lot to hold for what is usually a $100 weekly profit.  For TREG & portfolio margin (PM) accounts, brokers are smart enough to recognize that a put and call that expire at the same time against the same underlying are perfectly hedged against you, so the margin reserves required to open both contracts is the higher of the individual margin reserve of each individual component.  

In some situations, it makes more sense to open up a bull put spread or a bear call spread instead of going naked with the puts and calls.  These situations include:
1)	IRA accounts where spreads are the only way to get leverage.
2)	PM accounts where a spread with a distant long leg lowers the margin reserve significantly, giving the seller more leverage. 
3)	As a hedge against rising vega for black swan events.

TIMING OF THE SALE
The opening trades are made some time through Monday – Thursday of the week with options that will expire in the same week.  We are seeking a day where the market has a strong move in either direction (up / down), with an increase in implied volatility.  Dates that are closer to Thursday are preferred over earlier in the week, though I have found myself opening positions on Monday or Tuesday most frequently.   If any of trade with options expiring in the current week needs adjustment, the adjustment will be made to the following week if on Thursday or Friday, but may have to be pushed out to further weeks if you need to adjust Monday-Wednesday.  This creates an incentive to open contracts later in the week to avoid having to adjust too early and push out a long distance in time.

This means a couple things:
1)	If the market moves strongly on Monday, say more than .8% in either direction, this is a candidate for opening up puts or calls in the direction that the market is moving. If the market moved up strongly on Monday, then the target is to open calls further out of the money.  The reverse is true for puts.
2)	In some situations, it makes sense to open up trades on the Friday before the week begins.  This would be ideal when there is a long weekend where the investment gets 3 free days of theta burn.  If this path is pursued, strikes with sufficient must be selected.

STRIKE SELECTION
To determine the strike price of the calls and puts to open, we use a small amount of fundamental and technical analysis to find strike prices that are distant and with support / resistance.   Additionally, for SPX at 1500 we seek $.8 - $1.5 of premium on the calls, and $1 - $3 premium on the puts.  With a VIX at 23, this gives 2-3% protection on the upside and 3-6% downside protection, depending upon the strike selected.  With a VIX at 13, you get about 1% protection on the upside and 2% on the downside.   To reduce risk, and lower the overall returns, you can go further out of the money on either side.   I generally target 3 calls for every 1 put (reasons below).  On a $1M portfolio with VIX trading at 13 and SPX at 1500, would open up around 70 calls at $1520-$1525 for $.35 credit, and look for 25-30 puts at $1440 for $.60 credit.  This would be done with 3-5 days remaining to expiration.  At maximum opening, this would generate $2450 in premium from the calls and $1800 from the puts.  A total of $4250, or just over .42%. 

Monitoring and adjustment of the positions is key.  If at any time SPX gets within .5% of the put or call strike, buy back the strike and roll out 1 week to a strike that is further out of the money.  Experience shows that a call can be rolled up and out to a strike that is about 1.4% - 2.0% further out of the money while collecting another $.35 - $.7 of additional premium.  For puts, you can tend to roll out and down for anywhere from 1.5% - 3.0%.  It partly depends upon how close to expiration the adjustment is made.   The equity value at the moment the adjustment is made shows negative, but the position lives on another week with additional premium buying time for the market to reverse course.  For calls, given this indefinite adjustment technique of 1% / week, the adjustments will eventually move ahead of even the most bull markets.  There will be a week that flat lines or reverses course, and the investor keeps the entire premium collected. 

Additionally, over time, have found that it is a good idea to reduce risk when rolling out. Even though you are giving yourself price protection by moving further OOTM, I find that it’s healthy to take 10-20% of the contracts off the table.   If I have to adjust because the market is surging up, I’d move from 100 call contracts to 80 call contracts one week out.  To compensate, the further week out puts will be tighter.  Instead of 4% OOTM, maybe only 2.5%.  When markets move in a certain trend direction, they tend to continue in that path, and reversals that come all the way down are not that common.  But even if this does occur, you are quite pleased because your large batch of call options are now safely OOTM, and you are working to adjust your puts down and out.  With this model, an investor keeps riding the wave up and down until there is a week where all contracts expire profitable & safe.  At which point, you start over the following week at the beginning.

CONTRACT COUNTS  
We are the most aggressive with the number of calls opened.  We use the maximum number of possible calls to open each week based upon margin allowances & assuming the market has a 10% rise.  This means that the account is highly leveraged and could show significant losses if there was a significant crash to the upside.  There have been few instances in history where markets move more than 5% up in a single day, and most of those instances are after significant crashes.  What we do avoids any issues from whiplash in the market, so we are in a position that even if the market moves up with momentum, we have enough time and space to keep adjusting outward.  In a Portfolio Margin trading account, the number of calls to open is determined by figuring out the allocation array for the underlying and then forecast a 10% rise in the underlying.  For RUT trading at $800, a 10% rise would be $880, and the maximum margin required for a call with RUT at $880 is $8800 (10% * 100).  An $880K investment account would be able to open 100 RUT call contracts.  

The put side is different.  Markets can crater.  Flash crashes can wipe 10% out in an instant.  30% Black Monday’s are no longer a concern as the market has circuit breakers to halt trading now.  Our nightmare scenario is a flash crash that occurs at 12:45PM.  The markets close before the crash rebounds.  This triggers massive global sell offs overnight, and the US markets continue their downward movement the next day.  Overnight brokerages would probably liquidate many options positions or change their margin requirements with little notice for adjustment.   To account for this, we use less leverage on puts than on calls.  We only open up enough puts to survive a 50% drop in the underlying value, still offering time and premium through adjustments.  For every 100 calls that are opened, approximately 30 puts can be opened at the same time.  By doing this, if there is a flash crash or deeper dive, such as in 2008, the account value overall will drop precipitously, but through adjustments, premium collection, and time, the value of the investments will rebound quickly.  Following this model on RUT in 2008 would have had the account break even in around 3 months from the date Lehman Brothers collapsed.  

HEDGING
Based upon some guidance given by colleagues and for my own peace of mind, I have found that it’s good to create hedges to protect against black swan events.  My most fearful event is a major terrorist attack with the use of nuclear weapons.  It would happen over night with no chance to adjust before the markets have cratered downward.

A gap down of 10% + another drop of 20% would quickly wipe out a portfolio even if your put contracts are a fraction of your call contracts.  Also, if you have a significant crash, IV would be spiking and even though your calls are significantly out of the money, they would have also increased in value.   Check it out with models – a 1000% climb in vega with a 30% drop in price would cause the calls to increase in value as fast as the puts.

So, for protection, have found myself doing two very cheap things:
1)	I buy $.05 puts against my short puts each week.  It effectively makes it a put credit spread.  On a week where I sell my puts at $1450, I can buy $1300 puts for $.05.   For a $1M account, I would have opened 70 calls and 25 puts.   My maximum loss is $15K / contract, which places my maximum loss at $375K in case of a black swan.  And if the black swan occurs, I will not take that loss, but I will begin the process of rolling out and down, collecting even more premium to get ready for the eventual market correction.

2)	I buy $.05 calls 4 weeks away from expiration.  If I open my $1550 calls for this week, I’d be looking to open $1700 calls 4 weeks out.  One long batch of calls will last for 4 weeks.  If vega does spike, both the short calls and long calls will increase in value, and I can sell my long leg (for a nice profit) right as my short calls are expiring.

All told, these hedging strategies reduce my profit each week by around .03%, which is not a bad price to pay for peace of mind.

EXAMPLE
This example is as of 3/22.  Let’s say you have a $1M account at IB and you want to follow this strategy.   These prices are being checked on Friday afternoon for expiration on 3/29.  SPX closed at 1556.  While I don’t generally open contracts on a Friday, this is the prices that are available for the week.

1)	Target: .4% return for the week.  .4% * 1M = $4000 premium target.
2)	Bias: Market is trending upwards, though the market has surged in recent weeks, and Cyprus issues could cause a dramatic drop at any moment.  The feel is that we should get 50% of premium from calls and 50% from puts because the market is generally going up.  $2K from each.
3)	# of Calls:  Target strike is around $1585.  Given an 8% leverage, this means that we can open 68 call contracts and avoid a margin call if a spike upward.
4)	Call Premium: .2941 needed.  On Friday, 3/22, $1590 strike can be opened up for $.30.  This is more than 2% OTM, which is fairly safe.
5)	# of Puts:  Given a 35% allocation of puts vs. calls, this means 25-26 put contracts can be opened.
6)	Put Premium: .77 needed.  On Friday, 3/22, the $1470 put strike would generate $.80.  This is nearly a 6% OTM, a great margin of safety for a single week, especially with the fed pumping money in and the market in an uptrend.

If at any time in the week, the SPX were to touch $1580, it would be time to think about rolling the calls one week out.  I’d look to buy back the calls at whatever price and sell new calls one week later.  I would probably reduce the calls by 8-10 contracts, so we’d go from 68 to 60 or so.  Also, we would collect more premium, and would look to be gaining about $.50 for the effort.  At the same time, the puts should be getting tightened to better strikes to help compensate for the pressure on the calls.   I would not reduce the number of puts until the puts are under pressure themselves.   If my calls came under pressure early in the week, I would move the puts aggressively from $1470 to $1520, and probably collect a good $1-$2 in additional premium.  The rationale is that your calls are going to be showing some nice near term losses and if the market reverses, you will be gaining money even if your puts start to get in trouble.  If your calls stay under pressure, you are dramatically reducing the near term losses and setting yourself up for an even bigger gain if the market steadies or reverses.   If your puts suddenly come under pressure, then you apply the same adjustment techniques in the opposite direction.   You keep repeating adjustments until all of your contracts have been reduced to zero, or the market expires in between your puts and calls.
