# The Signals · FinWise

> Module 4 · Data & Analytics. The data pattern you found and the indicators you'll steer by.

## The data pattern

*What the funnel data revealed, the real problem behind the headline metric.*

FinWise's largest absolute funnel drop-off occurs at **Acquisition**, between Website Visits and Trials Started. Across the 13-month dataset, **94,558 website visits generated 6,424 trials**, meaning **93.21% of visitors did not start a trial** and the aggregate Visit → Trial conversion rate was **6.79%**. Monthly conversion varied substantially, from **3.41% in June 2024 to 11.21% in July 2024**.

The deeper signal is that acquisition is not the only constraint. Trial → Paid conversion remained within a narrow **1.87%–2.08% range** across all 13 months, forming a persistent ceiling around 2%. The monthly Website Visit → Trial rate and Trial → Paid rate have only a weak positive correlation of approximately **0.20**. Increasing trial starts alone therefore does not demonstrate that more users will experience value or convert to paid.

The product-usage metrics add further context:
<img width="1600" height="1420" alt="Codex Image Aug 15, 2026, 12_04_28 PM" src="https://github.com/user-attachments/assets/dafd245a-1f6c-4c42-a0e5-144e29b88c52" />

- **Financial Modeling usage shows repeated cliffs and volatility**, including drops from 31.17% to 10.78% in November 2023 and from 58.06% to 36.04% in October 2024.
- **Get Started Import usage shows a cliff followed by a temporary floor**, falling from 42.73% in December 2023 to 30.63% in January 2024 and remaining near 30%–32% through March.
- **Average Session Duration shows a cliff** from 12.11 minutes in June 2024 to 6.99 minutes in July and 5.14 minutes in August.
- **Average Sessions per User shows an early slow leak followed by recovery**, declining from 9 in October 2023 to 3 in January 2024 before later returning to 9.

The working hypothesis is therefore:

> If FinWise carries a visitor's high-intent content goal into a pre-personalized trial and guides the user to import financial data, reach a first modeling output, and review a relevant recommendation, then more users will reach activation and Trial → Paid conversion will increase because the journey connects acquisition intent directly to personalized product value.

![FinWise Website Visit-to-Trial and Trial-to-Paid conversion trends](assets/finwise-conversion-rate-comparison.png)

_____

## Leading indicators

*What predicts the outcome, early and movable.*

### North Star activation signal

**Number of trial users who import financial data and reach their first modeling output.** This is the earliest available combination of behaviors indicating that a user has progressed beyond signup and used FinWise with their own financial information.

### Acquisition leading indicators

1. **High-intent content visitor → Trial Start conversion rate**  
   This directly measures whether the content-driven experience improves the Acquisition-stage transition where the largest funnel drop-off occurs. The existing dataset does not identify content-attributed visitors, so the overall Website Visit → Trial rate can only be used as a temporary proxy.

2. **“Apply this to my business” CTA → completed trial signup rate**  
   This isolates whether the contextual CTA and lightweight signup reduce friction between demonstrated content value and trial creation. The current dataset does not contain CTA-click events, so FinWise must instrument monthly CTA impressions, clicks, and completed trial signups before calculating this metric.

### Activation and engagement leading indicators

3. **First modeling output completion rate among trial starters**  
   This shows whether newly acquired trials move beyond signup and reach the North Star rather than merely increasing trial volume.

4. **Personalized cash-flow recommendation review rate**  
   Tracked as `personalized_cashflow_action_reviewed`, this is FinWise's candidate Aha behavior: the user reviews a recommended action generated from their own financial data.

5. **Weekly Cash Clarity Check completion rate**  
   This measures whether activated users repeat the core value-producing behavior at its natural weekly cadence by reviewing an updated cash position and one relevant recommendation.

FinWise should segment these indicators by acquisition source and cohort. The first experiment should be judged on both Visit → Trial improvement and downstream North Star completion so that increased signup volume is not mistaken for improved activation quality.

![FinWise engagement and conversion trends](assets/finwise-engagement-trends.png)

_____

## Lagging indicators

*The outcome metrics themselves.*

1. **Trial → Paid Conversion Rate**  
   The immediate commercial outcome is whether the current approximately 2% ceiling increases after more users reach personalized product value.

2. **One-year paid-customer retention**  
   The existing baseline is 40%; improvement would show that converted customers continue receiving enough recurring value to remain with FinWise.

3. **Twelve-month retained ARR from content-acquired cohorts**  
   This is the scale-level proof that the strategy generated qualified trials that activated, converted, and remained customers—not merely additional website traffic or trial signups.

The strategy should be considered successful at scale only when improvements in acquisition and activation produce higher retained paid revenue. Trial volume alone is insufficient proof.

_____
