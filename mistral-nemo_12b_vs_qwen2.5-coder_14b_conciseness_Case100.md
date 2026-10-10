**Quantitative Systems-Engineering and Macroeconomic Critique of State Pension Funds' Equity Allocation Mandates**

**1. Actuarial Discount Rate Constraint Loop**

State pension funds are statutorily mandated to use an actuarial discount rate (ADR) to calculate their liabilities. This ADR is typically set between 6.5% to 7.5% (e.g., California Public Employees' Retirement System uses 7.0%). The fund's assets must grow at this rate to meet future liabilities. If the fund's assets grow at a lower rate, it will face a shortfall, potentially leading to insolvency.

Let's denote:
- ADR as `r`
- Fund's assets as `A`
- Liabilities as `L`
- Time horizon as `t`

The constraint loop is:

`A(t) * (1 + r)^t ≥ L(t)`

**2. Risk-Asset Allocation and Overbought Markets**

To meet the ADR, funds often increase their allocation to risk assets like equities, even when markets are overbought. Let's denote:
- Equity allocation as `E`
- Equity market price as `P`
- Equity market saturation index as `S` (e.g., Shiller P/E ratio)

The risk-asset allocation constraint is:

`E * P ≥ A * (1 + r)^t / L`

If `S` is high, indicating an overbought market, the fund may still increase `E` to meet the ADR constraint.

**3. Regulatory and Liquidity Boundaries**

- **Fiduciary Duty**: Funds must act in the best interests of beneficiaries. This can limit cash-holding agency, as holding cash may not maximize returns.
- **Liquidity Constraints**: Funds may have redemption requirements, limiting their ability to hold illiquid assets. Let's denote:
  - Redemption rate as `R`
  - Illiquid assets as `I`

  The liquidity constraint is:

  `I ≤ R * A`

- **Fiat Currency Degradation**: Inflation erodes the purchasing power of funds' assets. Let's denote:
  - Inflation rate as `i`
  - Real asset growth rate as `g_r`

  The real asset growth constraint is:

  `g_r ≥ r + i`

**4. Institutional Compounding Squeeze**

State funds face a compounding squeeze due to their large size and long-term liabilities. Let's denote:
- Fund's assets under management (AUM) as `AU`
- Market capitalization of investable assets as `MC`

If `AU / MC` is high, the fund may struggle to deploy capital without moving markets, leading to lower returns. This compounds over time, exacerbating the ADR constraint.

**5. Public-Sector Asset Allocation Capture**

State funds' large size and long-term liabilities can lead to capture by public-sector asset allocation. Let's denote:
- Public-sector assets as `PA`
- Total investable assets as `TA`

If `PA / TA` is high, the fund may face political pressure to invest in local or state projects, even if these investments do not maximize returns.

In conclusion, state pension funds face a complex set of quantitative and macroeconomic constraints that can force them to deploy capital into visibly overbought markets, even when real-time asset inflation indicators signify terminal over-saturation. These constraints are driven by statutory actuarial discount rates, regulatory and liquidity boundaries, and institutional size.