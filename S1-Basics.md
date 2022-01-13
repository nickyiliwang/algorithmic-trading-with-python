# Section 1

## Terminologies
![alt text](https://www.oanda.com/wandacache/2017_quote-3a80ae8ef4de572e54599ed375620a35323754f7.png)

The Exchange Rate is the price for which foreign currencies are traded. The Quote List and Quote Panel show different views of the current OANDA exchange (buy/sell) rates in real time. When there is movement in the exchange rate for a currency pair, the green and red up/down indicators alert traders to momentary changes in direction.

### CURRENCY PAIRS
Currency pairs are always listed in the same order. For example, the most commonly-traded currency pair consists of the Euro and the U.S. dollar. This pair is always listed as EUR/USD and never the reverse order. In this example EUR is is the BASE currency, and USD is the QUOTE currency. When published with an exchange rate, the currency pair indicates how much of the quote currency is required to purchase one unit of the base currency.

### SPREAD
The SPREAD is the difference between the two prices. The bid price is always less than the ask price because brokers pay less than they receive for the same currency pair. This difference – known as the spread – is how your broker is compensated for their services in executing your trade. Some brokers, including OANDA, also offer pricing options that include a commission combined with lower spreads. A spread is commonly measured in pips. The pip is the value of the 4th decimal place for pairs other than for JPY, where it is 2nd decimal place. OANDA, however, offers increased pricing transparency by displaying 5 decimal places for currency pairs, other than JPY in which 3 decimal places are shown. This is called a pipette.

### BID PRICE
The BID price is the rate that your broker is willing to pay for the currency pair; in other words, this is the rate you receive if selling to the market. For example in the rate panel shown, the bid price is 1.05761. You could sell one Euro for 1.05761 US dollars.

### ASK PRICE
The ASK price is the rate at which your broker is willing to sell and represents the rate you must pay to buy the base currency. In the example 1 Euro will cost you 1.05775 US dollars.

## Spread and Pips
The spread of an Exchange rate is the profit OANDA makes, in Pips, usually the price difference in the 4th decimal from the base Currency and Quote currency. 

*The lower the spread the higher the trading efficiency

Foreign exchange is liquid (spot trading) and so they have low spreads and boosts efficiency of a trade.

## Hypothetical Mid Price and Spread
In a full Transaction (open & close) Traders lose the average spread.
*average spread is the Trading/Transaction Cost for the Trader
ie. a Spread of 1.4 Pips has an hypothetical Mid Price of 0.7 Pips ((0.00874 - 0.00860) / 2)

If we make 100 transaction in a day, we might pay 2000 in trading costs alone

Trader lose half spread in each Trader (aka. Half Spread Costs)

Spread sheet: 
https://docs.google.com/spreadsheets/d/1M5MamEEsMda152TbjgXWG85qf7h8Wr-7ohW_vam9juc/edit#gid=991877962

## Margin and Leverage
Margin is the amount of money required to open a position, while leverage is the multiple of exposure to account equity. 

The amount of margin depends on the margin rate requirements. This differs between each trading instrument, depending on market volatility and liquidity in the underlying market.

Higher the Leverage higher the risk.

OANDA recommends 20:1 or lower, your broker lends you money to use for trading based on your leverage ratio. the minimum margin of cash required in your account represents the collateral for the loan.

Calculations:
<!-- https://www1.oanda.com/resources/legal/canada/legal/margin-rates -->
1. EUR/USD margin rate is 4.9%
2. at Leverage of 50 : 1
3. Margin Required: to do an initial purchase will be $4900
4. Margin Available: assuming we have $100,000 we will be able to make a trade

Setting a maximum leverage in the account may prevent some risks

## Margin Closeout
The Margin Closeout Value is equal to your balance plus your unrealized P/L from all open positions, converted into the currency of the account, all calculated using the current midpoint rates. 

If your Margin Closeout Value falls to less than half of your Margin Used, all open positions will be automatically closed using the current fxTrade rates at the time of closing. If trading is unavailable for certain open positions at the time of the margin closeout, those positions will remain open and the fxTrade platform will continue to monitor your margin requirements. When the markets reopen for the remaining open positions, another margin closeout may occur if your account remains under-margined.

### Margin Used Calculation Example:
USD account with maximum leverage set to 20:1 and a long 10,000 EUR/GBP open position. 
The current rate for EUR/USD is 1.1320/1.1321 => midpoint rate of EUR/USD is 1.13205.

For the leverage calculation, the lower of the maximum regulated leverage and your selected leverage is used.
20:1 leverage = 5% margin requirement is used

Your margin used is position size x Margin Requirement = 10,000 EUR x 5% = 500 EUR. The Margin Used in your account currency = 500 x 1.13205 = 566.025 USD.

### Margin Closeout Value Calculation Example (cont. from above example):
You have a USD account with balance of 1,000 USD

Your unrealized P/L calculated by the current midpoint rate is (current midpoint rate – open rate) x position size = (1.13205 – 1.1200) x 10,000 = 120.50 USD.
Your Margin Closeout Value is 1,000 + 120.50 = 1,120.50 USD.

*In conclusion, margin closeout is a broker's way of protecting their money, the less the closeout value, the less time you have to react before a warning

## Netting vs. Hedging 
netting example:
I'm buying long position of 100k of a trade and selling 50k of the same instrument, thus netting the 100k
but we made 3 transactions and only needed to pay for 1 spread cost

Hedging:
We hold both the Long and short position at the same time: ie. 100k EUR/USD LONG and 50k SHORT EUR/USD, if I SHORT 50k EUR/USD, we would hold 100k LONG and SHORT of the same instrument 
While we have these 2 positions open, it seems like we are not at risk of losing money

The difference:
1. While hedging we are trading almost the same ammount in transaction while paying the spread twice

Conclusion:
Opening a Netting account will yield less trading costs

## Market, Limit and Stop Orders
1. Limit order allows an investor to set the minimum or maximum price at which they would like to buy or sell
2. Stop order allows an investor to specify the particular price at which they would like to buy or sell.

## Take-Profit and Stop-Loss Order
1. A take profit (TP) works automatically closes a position once a profit target is reached to lock in profits.
2. Stop loss (SL) is a price limit entered by a trader. 
3. When the price limit is reached the open position will close to prevent further losses.

