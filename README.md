# CAN-SLIM-screener
Automated screener for William J O'Neil's winning CAN SLIM system. From the book: [How to Make Money in Stocks](https://www.amazon.com/How-Make-Money-Stocks-Winning/dp/0071614133)

### Acronyms
IBD: Investor's Business Daily, a weekly newspaper offering much of the data to conduct the CAN SLIM analysis.

# TOC
1. [Quick Start](#Quick-Start)
2. [Control Flow](#Control-Flow)
3. [Inputs](#Inputs)
4. [Data Sources](#Data-Sources)
5. [Pre CANSLIM Chapter Notes](#Pre-CANSLIM-Chapter-Notes)
6. [CAN SLIM](#CAN-SLIM)
7. [Output](#Output)
8. [Contributing](#Contributing)

## Quick Start
```
TBD
```

## Control Flow
Diagram TBD

## Inputs
User inputs, likely a ticker, maybe some dates

## Data Sources
likely alpha vantage for charting
unknown for quarterly & annual reports

## Pre CANSLIM Chapter Notes
* Find and focus on tight prices
* Find pivot and observe volume % delta
* Look to volume dry ups near lows
* High n tight flag is very rare
* Ascending bases can be confusing

## CAN SLIM
These are my notes as I read the book

1. [C](#c---current-big-or-accelerating-quarterly-earnings-and-sales-per-share)
2. [A](#a---annual-earnings-increases-look-for-big-growth)
3. [N](#n---newer-companies-new-products-new-management-new-highs-off-properly-formed-chart-bases)
4. [S](#s---supply-and-demand-big-volume-demand-at-key-points)
5. [L](#l---leader-or-laggard-which-is-your-stock)
6. [I](#i---institutional-sponsorship)
7. [M](#m---market-direction-how-you-can-determine-it)

### C - Current Big or Accelerating Quarterly Earnings and Sales per Share
Stock must show a major increase in current quarterly EPS for the most recent quarter when compared to the same Q of the prior year. There are 3 levels to look for: light, medium, and strict. If you're new, use strict.

| level | light | med | strict | ideal |
|-------|-------|-----|--------|-------|
| % Δ   | 20    | 30  | 50     | 70+   |

Check for sales growth of 25%.

Sell if earnings decelerate over 2Q by 66% (e.g., 100% to 30% or 50% to 15%).

Manual checks:
* No old companies that are in maintainer mode
* Check other stocks in industry group
* Anticipate (use consensus EPS estimates) next Q by looking back 3Q to see if there will be another hefty EPS gain
* No major non-recurring sale (like real estate) that can pump a single Q earnings

### A - Annual Earnings Increases: Look for Big Growth
Automated Screening:
* Annual increase of earnings for the last 3Y; min 25% usually 50%.
  * One of last 5Y can be down if new high immediately reached
  * Estimates should be up, but can be ignored
* Look for ROE because it shows efficiency in cash spend. ROE = net income / shareholder equity
  * ROE 17% minimum
* Cash flow = net income + deprecation + amortization
  * Cash flow can be 20% greater than actual EPS
* Stability from 1-99, lower is better. 25 or less is desireable.
  * Calculated by taking last 3-5Y of Q earnings
  * Typically plotted on a log chart to see accuracy of the trendline
  * Can use daily graphs or daily graphs online as a source (https://marketsmith.investors.com/)
  * Can also use investors business daily (https://www.investors.com/)
* Observe EPS rating: calculated off most recent 2Q over last year's respective 2Q and the most recent 3Y of earnings
  * Also a 1-99 rating scale, 99 is better and is percentile ranking within sector.

### N - Newer Companies, New Products, New Management, New Highs Off Properly Formed Chart Bases
* Need to find stocks that break out of proper bases that typically last 8 weeks to 15 months.
* If the stock is more than 5-10% above the exact buy point off the base, then it should be avoided.
* Look for important new products or services, or that have benefitted from new management or materially improved industry conditions. Buy their stock when they are emerging from sound, correctly analyzed price consolidation patterns and are close to, or making new price highs on increased volume.

### S - Supply and Demand: Big Volume Demand at Key Points
* Smaller volume stocks tend to be better performers, if all other factors are equal.
* Executives hold > 1-3% in large companies and +3% in smaller companies is a good sign.
* Small to mid size companies performing a buy back (of 10%) is considered a good sign if they qualify for the other CAN SLIM criteria.
* Low Debt to Equity, even paying it down is considered good because the cost dedicated to interest will fall and earnings will rise.
* Watch for convertible bonds, equity can be diluted when bonds expire.
* Price down and volume down is positive; Price up and volume up is positive.
* IBD provides: daily trading volume and percentage volume is above or below average 3M trailing volume
* When a stock breaks out of a consolidation, trading volumes should rise 50% in many cases 100%
* Analyze base pattern week by week, beginning first week a stock closes down in a new base and continuing each week until the current week, where you think it'll break out of the base
  * judge price progress each week and whether it was on increased or decreased volume from the prior week
  * also ensure the stock closed within spread
  * do a both week by week check adn evaluate the pattern's overall shape to see if it is sound

### L - Leader or Laggard: Which is Your Stock?
* Buy top 3, To qualify for top 3
  * Best QE
  * Best ROE
  * Best sales growth
  * Best margin
  * Most dynamic stock-price action
* Be wary of sympathy plays
* Use Relative Price Strength (RS) from IBD
  * To calculate RS, measure price performance for the given stock for the last 52 weeks. Every stock in the market is assigned a percentile from 1 to 99
  * RS must be over 70, eliminate 69 and below -- identify as a laggard
  * Ideally 80+
  * Best are 90+ just before they break out of their first or second base structure
* In short term corrections (eg 10%) look for stocks that correct 1.5x-2x (eg 15-20%), not greater
  

### I - Institutional Sponsorship
* Have at least 5 institutional investors

### M - Market Direction: How You Can Determine It

## Output
* A rating to indicate stock's strength when compared to screening criteria
* Reminder of qualitiative factors to investigate

## Contributing
TBD
