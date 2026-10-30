# unilever-3-statement-dcf-model
Integrated 3-statement and DCF model for Unilever PLC in Excel, with Worst / Base / Best scenarios, FY26E–FY30E forecast and valuation.
# Unilever PLC: Integrated 3-Statement & DCF Model

An Excel financial model for Unilever PLC: historical statements (FY23–FY25),
a five-year forecast (FY26E–FY30E), a three-statement build, and a DCF valuation
with Worst / Base / Best scenarios.

![Summary sheet](docs/summary.png)

## Headline (as built, 30 Oct 2026)
| Scenario | Value per share | vs €53.90 price |
|---|---|---|
| Worst | €50.71 | -6% |
| Base | €67.93 | +26% |
| Best | €80.13 | +49% |

Best case is a ceiling, not a forecast. Terminal value is ~81% of enterprise value,
so the result is highly sensitive to WACC.

## What's inside
- `Cover`: contents, colour code, live integrity checks
- `Summary`: executive summary, scenario comparison, chart
- `DATA_INPUT`: historical statements and forecast income statement and balance sheet
- `ASSUMPTIONS`: all drivers and the scenario selector (cell C4)
- `CASH_FLOW`: indirect cash flow, dividends, buybacks, net debt
- `DCF`: WACC, FCFF, valuation bridge, sensitivity grid

## How to use
Download `model/Unilever_PLC_3S_DCF_Model_v1_1.xlsx`. Change the scenario in
`ASSUMPTIONS!C4` (1 = Worst, 2 = Base, 3 = Best). Edit blue cells only.

## Sources
Unilever Q4 & Full Year 2025 results (12 Feb 2026); Unilever H1 2026 results;
Euronext Amsterdam delayed quote; 10-yr Bund yield; TradingView beta.

## Limitations
- FY23/FY24 balance sheets include Ice Cream while the income statement excludes it;
  forecasts are anchored on FY25.
- A possible Foods separation is not modelled.
- The scenario comparison table on the DCF sheet is a static snapshot.
- Share price, risk-free rate and beta are point-in-time and need refreshing.

## Author
Jhanvee Kamal Parikh | https://www.linkedin.com/in/jhanveekparikh/

*Illustrative analysis only; not investment advice.*
