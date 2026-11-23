# Asian Paints: DCF Valuation Model (Excel)

## Objective
Value Asian Paints Ltd using a 5-year free cash flow to firm (FCFF) DCF, and test what the current market price implies.

## Data
- Consolidated financials FY22 to FY26 from Screener.in (screenshots of 23 Nov 2026), in Rs crore
- Peer table (paints sector) from Screener.in
- Risk-free rate based on recent India 10-year G-sec yields (about 7.2%)

## Method
- Historical analysis: margins, ROE, ROCE, working-capital days, DuPont
- Projections FY27E-FY31E: revenue growth fading from 10% to 8%, EBITDA margin rising from 19% to 20%
- WACC from CAPM (about 11.5%), terminal growth 6%
- Sensitivity grid (WACC vs terminal growth) and a reverse DCF
- Tools: Excel (all formulas live; blue cells are inputs)

## Key findings
1. The base-case model gives about Rs 877 per share against a market price of Rs 2,579 on 23 Nov 2026.
2. The market price implies a terminal growth rate of about 9.9%, versus 6% assumed, so the market is pricing a much longer high-growth runway than a 5-year forecast captures.
3. Asian Paints trades at about 36x EV/EBITDA, against about 12x implied by the model, and at a P/E about 52% above the peer median.

## Limitations
- Beta (0.8) and equity risk premium (5.5%) are my assumptions.
- Investments are treated as cash-like; the balance sheet is as at March 2026.
- Terminal value is about 80% of enterprise value.

This is an educational exercise, not investment advice.
