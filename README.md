# CAN-SLIM-screener
Automated screener for William J O'Neil's winning CAN SLIM system. From the book: [How to Make Money in Stocks](https://www.amazon.com/How-Make-Money-Stocks-Winning/dp/0071614133)

# TOC
1. [Quick Start](#Quick-Start)
2. [Control Flow](#Control-Flow)
3. [Inputs](#Inputs)
4. [Data Sources](#Data-Sources)
5. [CAN SLIM](#CAN-SLIM)
6. [Output](#Output)
7. [Contributing](#Contributing)

## Quick Start
```
TBD
```

## Control Flow
Diagram TBD

## Inputs
User inputs, likely a ticker, maybe some dates

## Data Sources
likely alpha vantage

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
### S - Supply and Demand: Big Volume Demand at Key Points
### L - Leader or Laggard: Which is Your Stock?
### I - Institutional Sponsorship
### M - Market Direction: How You Can Determine It

## Output

## Contributing
TBD
