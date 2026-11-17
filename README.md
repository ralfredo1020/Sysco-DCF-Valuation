# Sysco (SYY): Three-Statement Model and DCF Valuation

**Rating: Hold | DCF fair value: $73.47 | Share price: $82.52 (Oct 29, 2026) | Downside: 11.0%**

An Excel model that projects Sysco's financial statements through fiscal 2031 and values the company with a discounted cash flow (DCF). This is an educational portfolio project, not investment advice.

## The question

Is Sysco's stock fairly priced today? I chose Sysco as it is a company that runs a business that is easily explainable. Sysco has steady multi-year financials that make it a good test for this model. 

## Recommendation

My base case values Sysco at about **$73 per share**, roughly 11% below the $82.52 share price. That falls inside my ±15% band, so the call is **Hold**. In order for the stock to be today's price, I believe that we need to see a WACC closer to about 7.60% or long-term growth around 3% instead of 2.5%. This is not unreasonable and out of the question, that is why it is a hold. 

## The business

Sysco is the largest foodservice distributor in the United States. They deliver to locations such as restaurants, schools, and hospitals. Even with an 18.5% gross margin, small changes in areas such as volume or working capital impact the company's operating margin which is at about 3.7%. 

## What's in the workbook

| Tab | What it does |
|---|---|
| Assumptions | Historical ratios (FY2024 to FY2026) and my forecast inputs with the reasoning for each |
| IS, BS, CF | Income statement, balance sheet, and cash flow, linked together. The balance sheet balances in every year |
| DCF | WACC, unlevered free cash flow, terminal value, and value per share |
| Sensitivity | Value per share across WACC and terminal growth |
| Sources | Every filing, page number, and data link behind the inputs |

## Key assumptions

| Assumption | Forecast | Why |
|---|---|---|
| Sales growth | 6.0% in FY2027, 2.2% in FY2028, then 4.0% | Lower end of Sysco's 6% to 7% guidance for fiscal 2027 which is a 53-week year. Fiscal 2028 does not repeat this because the extra week does not exist so it drops down to 2.2%, this ends up being 4% with the recent growth of 3% to 4%.|
| Gross margin | 18.5% | The gross margin would remain stable as it has been between 18.4% and 18.5% in each of the last three years.|
| Operating margin | 3.7% rising to 4.0% | Announced cost savings take place.|
| Net capex | 0.8% of sales rising to 1.0% | Starts near Sysco's $720 million for fiscal 2027, then we see it rise toward 1% of sales, so depreciation is covered by the final year. |
| WACC | 8.1% | Risk free rate of 4.99%, equity risk premium of 4.5%, and a beta of about 1.0 (Industry beta is adjusted for debt)  |
| Terminal growth | 2.5% | Below long run economic growth. |

## Results

- **Enterprise value:** about $47.0 billion, of which 76% is terminal value
- **Implied multiple:** 11.6x FY2026 EBITDA
- **Net debt:** 2.9x FY2026 EBITDA
- **Sensitivity range:** $46 to $145 per share across WACC of 6.65% to 9.65% and terminal growth of 1.5% to 3.5%


Half a point of WACC moves the value by about $8 to $9 per share, and the full range starts at about $46 and ends at about $145. The share price is in the middle of the range so that model does not tell us if the signal is a strong buy or a strong sell. The model tells us that the stock is priced reasonably according to the assumptions made. 

## Key risks

Sysco has debt about 2.9 times EBITDA, and the interest expense went up from $607 million in 2024 to $717 million in 2026. If there were to be higher interest rates implemented, then we could see the discount rate being raised and the interest bill being raised. Sysco has thin margins and higher labor costs, and fuel costs could cut into those earnings quickly. 

## Limitations

- Figures are GAAP as reported, not the adjusted numbers Sysco uses in its guidance
- Statements are condensed, and share count and debt are held flat
- Cash flows are discounted from the FY2026 balance sheet date (June 27, 2026) using year-end discounting
- Projections are my own judgment, not company forecasts

## Data sources

- Sysco Form 10-K, fiscal 2026 and fiscal 2025 (SEC EDGAR)
- Sysco Q1 fiscal 2027 results and FY2027 guidance (Nov 3, 2026)
- 10-year Treasury yield: FRED (DGS10)
- Industry beta and equity risk premium: Aswath Damodaran, NYU Stern
- Share price: From Market Chameleon, closing price on October 29,2026. 

Full detail with page numbers is in the workbook's Sources tab.

## Using the model

Download the workbook and open it in Excel. Blue cells are inputs, black cells are formulas, and green cells link to other tabs. Change any forecast input on the Assumptions tab and everything flows through to the valuation.

## About

|Raul Ramirez| I am an MBA candidate in Business Analytics looking to graduate December 2026. I have experience with Excel, SQL, Power BI, Tableau, and I am currently learning how to work with Microsoft Power Apps. I am building a portfolio to showcase my knowledge and break into an entry level analyst role. 
