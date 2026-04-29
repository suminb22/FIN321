Stage 4 – Final Analysis, Prompt Engineering & Recommendation (10 Points)
A. Exposure Summary
The company expects to receive GBP 12,500,000 in one year, which exposes it to foreign exchange risk. As a USD-based firm, any depreciation of the British pound (GBP) against the U.S. dollar will reduce the USD value of the receivable and negatively impact reported revenue.
The primary objective of this analysis is to evaluate hedging strategies that can protect the firm’s USD cash flows while balancing cost, flexibility, and risk exposure.

B. Summary of Hedge Outcomes
Each hedging strategy provides a different trade-off between certainty and potential upside.
Forward Hedge
 The forward contract locks in a fixed exchange rate of 1.35, guaranteeing USD proceeds of $16,875,000 regardless of future market conditions. This provides full certainty but eliminates any upside potential.
Money Market Hedge
 The money market hedge generates approximately $16,785,971, closely matching the forward hedge due to interest rate parity. However, it requires borrowing and investing, making it operationally more complex and potentially impacting liquidity.
Put Option Hedge
 The put option hedge establishes a minimum USD value of approximately $17,990,750 after accounting for the premium. It provides downside protection while allowing participation in favorable exchange rate movements.
No Hedge
 Without hedging, USD proceeds vary directly with the future spot rate. While this allows full upside if GBP appreciates, it exposes the firm to significant downside risk if GBP depreciates.
Overall, the key distinction is that forward and money market hedges prioritize certainty, while the put option provides both protection and flexibility.

C. Sensitivity Analysis
The sensitivity analysis evaluates outcomes across exchange rate scenarios ranging from 1.40 to 1.52.
When GBP depreciates below the strike level of 1.46, the put option hedge provides superior protection, ensuring a higher minimum USD value than all other strategies. In contrast, the unhedged position results in significantly lower proceeds.
When GBP appreciates above 1.46, the option expires, and the firm benefits from higher spot rates. In these cases, the unhedged strategy can generate the highest returns, but it comes with full exposure to downside risk.
Forward and money market hedges remain constant across all scenarios, offering stability but no participation in favorable movements.
A key insight from the model is that the put option hedge dominates all other hedging strategies across the tested range, except in high appreciation scenarios where no hedge yields the highest absolute return.

D. Strategic Recommendation
Based on the analysis, the put option hedge is the recommended strategy.
This approach provides a strong balance between downside protection and upside participation. It ensures that the firm maintains a minimum level of USD proceeds while still benefiting from favorable exchange rate movements.
Compared to forward and money market hedges, the put option offers greater flexibility, making it more aligned with a firm that seeks both risk management and potential value creation.

E. Executive Justification
From a management perspective, the put option hedge offers several key advantages.
First, it ensures cash flow stability by establishing a minimum USD value, which supports budgeting and financial planning. Second, it preserves upside potential, allowing the firm to benefit if GBP appreciates. Third, while the option premium represents an upfront cost, it can be justified as the price of flexibility and risk protection.
In contrast, forward and money market hedges eliminate uncertainty but also remove any opportunity for gain. Given the firm’s exposure and the results of the sensitivity analysis, the put option provides the most balanced and strategically sound solution.


# GOAL
Create an Excel-based FX hedging model for a GBP-denominated receivable. The model must compare forward hedge, money market hedge, put option hedge, and no hedge outcomes, including a sensitivity analysis.

# INPUT VARIABLES
Use the following named ranges:
FC_AMT = 12,500,000
S0_in = 1.35
F0_in = 1.35
R_USD = 3.70%
R_FC = 4.25%
K_PUT = 1.46
PREM_PUT = 0.02
T_DAYS = 1

# MODEL STRUCTURE
Create the following sections:
Input Section
Highlight all inputs in yellow
Use named ranges exactly as specified
Assumptions Section
Highlight in blue
Include interest rate assumptions and timing
Calculation Section
Highlight formulas in green
Forward Hedge
USD_forward = FC_AMT × F0_in
Money Market Hedge
Borrow PV of FC: FC_AMT / (1 + R_FC)
Convert to USD: × S0_in
Invest in USD: × (1 + R_USD)
Put Option Hedge
Premium = FC_AMT × PREM_PUT
FV of premium = Premium × (1 + R_USD)
If S_T < K_PUT → exercise
If S_T ≥ K_PUT → expire

# SENSITIVITY ANALYSIS
Vary S_T from 1.40 to 1.52 in increments of 0.01
Calculate USD proceeds for all strategies
Display results in a table and chart

# OUTPUT SECTION
Highlight outputs in gray
Include:
USD proceeds for each strategy
Comparison table
Winner column
Sensitivity chart

# VERIFICATION
Confirm forward ≈ money market hedge
Check option payoff logic at strike price
Validate all named ranges
