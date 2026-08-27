# The Mechanic · FinWise

> Module 3 · Retention & Engagement

## Chosen gamification mechanic: Cash Plan Freshness

**Cash Plan Freshness** is a weekly status mechanism that makes the user’s forecast freshness visible. After a user has reviewed a personalized cash-flow action, FinWise marks their 30-day cash plan as **Current**. When a material change affects the forecast—for example, a projected cash-buffer breach, a material invoice change, or a meaningful change in upcoming outgoings—the status becomes **Needs review** and shows one recommended action. Reviewing that action restores the Current status for the week.

Cash Plan Freshness mockup

<img width="1200" height="800" alt="cash-plan-freshness" src="https://github.com/user-attachments/assets/ca017352-db1a-4a7d-8017-0772f114335f" />
<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="800" viewBox="0 0 1200 800" role="img" aria-labelledby="title desc">
  <title id="title">FinWise Cash Plan Freshness mechanic mockup</title>
  <desc id="desc">A FinWise screen showing a cash plan that needs a review after a material forecast change, with one recommended action to review invoices.</desc>
  <style>
    .bg { fill: #f5f7fb; }
    .surface { fill: #fff; stroke: #dce4ef; stroke-width: 1; }
    .soft { fill: #f3f6fa; }
    .ink { fill: #14213d; font-family: Arial, Helvetica, sans-serif; }
    .muted { fill: #64748b; font-family: Arial, Helvetica, sans-serif; }
    .navy { fill: #163361; }
    .white { fill: #fff; font-family: Arial, Helvetica, sans-serif; }
    .alert-surface { fill: #fff8e6; stroke: #d19024; stroke-width: 1; }
    .alert { fill: #9a5b00; font-family: Arial, Helvetica, sans-serif; }
    .line { stroke: #dce4ef; stroke-width: 1; }
  </style>
  <rect class="bg" width="1200" height="800"/>
  <rect class="surface" x="0" y="0" width="1200" height="78"/>
  <rect class="navy" x="72" y="23" rx="9" width="32" height="32"/>
  <text class="white" x="88" y="45" text-anchor="middle" font-size="18">▦</text>
  <text class="ink" x="116" y="46" font-size="22" font-weight="700">FinWise</text>
  <text class="muted" x="1080" y="46" font-size="16" text-anchor="end">Cash plan</text>

  <text class="ink" x="160" y="156" font-size="37" font-weight="700">Your cash plan needs a review.</text>
  <text class="muted" x="160" y="190" font-size="19">A meaningful change affects your 30-day forecast. Review one action to keep your plan current.</text>

  <rect class="alert-surface" x="160" y="226" rx="14" width="880" height="92"/>
  <circle fill="#d19024" cx="197" cy="272" r="18"/>
  <text class="white" x="197" y="279" text-anchor="middle" font-size="19" font-weight="700">!</text>
  <text class="alert" x="232" y="264" font-size="17" font-weight="700">Plan updated since your last review</text>
  <text class="muted" x="232" y="290" font-size="15">A cash-buffer risk is now projected in 18 days.</text>

  <rect class="surface" x="160" y="342" rx="14" width="580" height="272"/>
  <text class="muted" x="188" y="378" font-size="13" font-weight="700">30-DAY CASH PLAN</text>
  <text class="ink" x="188" y="414" font-size="27" font-weight="700">$9,400 projected low</text>
  <text class="muted" x="188" y="440" font-size="15">Day 18 · preferred buffer $15,000</text>
  <line x1="190" y1="537" x2="712" y2="537" stroke="#d19024" stroke-width="2" stroke-dasharray="6 6"/>
  <text class="alert" x="710" y="529" text-anchor="end" font-size="13">Buffer $15k</text>
  <polyline fill="none" stroke="#163361" stroke-width="4" points="190,472 250,482 315,495 380,515 440,542 510,582 557,562 622,518 712,467"/>
  <circle fill="#d19024" cx="510" cy="582" r="7"/>
  <text class="muted" x="190" y="590" font-size="12">Today</text>
  <text class="muted" x="448" y="590" font-size="12">+15 days</text>
  <text class="muted" x="712" y="590" text-anchor="end" font-size="12">+30 days</text>

  <rect class="surface" x="760" y="342" rx="14" width="280" height="272"/>
  <text class="muted" x="788" y="378" font-size="13" font-weight="700">WHAT CHANGED</text>
  <text class="ink" x="788" y="430" font-size="34" font-weight="700">$5,240</text>
  <text class="muted" x="788" y="462" font-size="15">in invoices due this week</text>
  <text class="muted" x="788" y="486" font-size="15">are now at risk of</text>
  <text class="muted" x="788" y="510" font-size="15">being delayed.</text>

  <rect class="surface" x="160" y="638" rx="14" width="880" height="118" stroke="#163361" stroke-width="1.5"/>
  <rect class="soft" x="188" y="665" rx="8" width="42" height="42"/>
  <text class="navy" x="209" y="693" text-anchor="middle" font-size="22">↗</text>
  <text class="muted" x="246" y="674" font-size="12" font-weight="700">ONE ACTION TO REVIEW</text>
  <text class="ink" x="246" y="702" font-size="20" font-weight="700">Review invoices due this week</text>
  <text class="muted" x="246" y="728" font-size="15">Reviewing these invoices can help keep your balance above buffer through the month.</text>
  <rect class="navy" x="784" y="674" rx="9" width="228" height="54"/>
  <text class="white" x="898" y="707" text-anchor="middle" font-size="16" font-weight="700">Review action</text>
</svg>


### What the user sees and when

| Moment | Experience |
| --- | --- |
| After first Aha | A simple status: **“Your cash plan is current.”** The user sees the forecast horizon and the action they just reviewed. |
| Weekly operating cycle | A quiet in-product reminder appears only if the plan has new, material information to review. |
| Material forecast change | The status changes to **“Your cash plan needs review”** and names the single relevant action, such as reviewing invoices that affect the projected buffer. |
| After review | FinWise confirms that the plan is current again and shows what changed in the forecast. |

### Intrinsic motivation and cadence

The primary motivation is **loss aversion**, grounded in a real loss: allowing a cash plan to become stale can mean discovering a buffer risk or delayed invoice too late. This is deliberately **not a streak**. Small-business cash management has a natural **weekly** cadence, so FinWise earns a return when the forecast has changed materially instead of demanding a daily check-in or penalizing a missed app open.

### Rationale

Cash Plan Freshness reinforces the same behavior that defines FinWise’s candidate Aha moment—reviewing a personalized cash-flow recommendation—rather than rewarding arbitrary clicks, points, or time in the product. The mechanism gives users a practical reason to return each week: keep their financial plan current when conditions change. It supports Module 1 and Module 2 by creating more repeat occasions for users to experience personalized value; it does not replace the post-Aha paid-plan experiment. If FinWise’s recommendations are generic, inaccurate, or do not lead to useful decisions, the status alone will not prevent churn, so each review must show the specific forecast change and the outcome of the recommended action.

---

## Engagement Weighted Scorecard

The original scorecard used average session duration as a depth proxy. For this mechanic, that is too indirect: longer sessions can reflect friction rather than value. This mechanic-specific scorecard tracks the user behaviors that Cash Plan Freshness is designed to move.

| Dimension | Mechanic-specific metric | Weight | Baseline proxy from available data | Current score | Weighted |
| --- | --- | ---: | --- | ---: | ---: |
| **Depth** | Share of eligible users who review a personalized cash-flow action after a material forecast change. | 50% | Financial-modeling usage: **36.73%** (until action-review tracking exists). | 3 | 1.50 |
| **Breadth** | Share of users completing the core workflow: account import → first financial model → recommended-action review. | 30% | Average of data import (39.04%) and modeling (36.73%): **37.89%**. This is a proxy, not a user-level completion rate. | 3 | 0.90 |
| **Frequency** | Average weekly cash-plan reviews per eligible user. | 20% | Sessions per user: **6.62** (until weekly review events are tracked). | 7 | 1.40 |
| **Cash Plan Engagement KPI** | `0.50 × depth score + 0.30 × breadth score + 0.20 × frequency score` | **100%** |  |  | **3.80 / 10** |

**Baseline interpretation: Needs improvement.** The strongest observable signal is return frequency, but fewer than 40% of users reach either core workflow action. The mechanic should improve meaningful action completion and repeat review—not simply create longer sessions or more notification opens.

### What each metric must move

- **Depth:** More eligible users should review the action tied to a material forecast change. This is the direct repeat of `personalized_cashflow_action_reviewed`.
- **Breadth:** More users should progress through the complete value chain: account data → financial model → recommended action. This protects against “engagement” that never reaches core product value.
- **Frequency:** More eligible users should return on a weekly cadence when their cash plan changes materially, rather than being prompted to open FinWise every day.

### Measurement plan

| Item | Definition |
| --- | --- |
| Unit of analysis | Eligible trial and paid users with a connected primary business account. |
| Treatment | Cash Plan Freshness status plus a single material-change review prompt. |
| Control | Existing forecast experience without the Freshness status or weekly material-change prompt. |
| Evaluation window | Four weeks after the first personalized cash-flow action review. |
| Primary engagement readout | Change in the Cash Plan Engagement KPI versus control. |
| Product outcomes | Trial-to-paid conversion for trial users; four-week return rate and later retention for paid users. |
| Guardrails | Notification opt-outs, dismissed prompts, bank-connection failure, and evidence that recommendations were not material or useful. |

### Instrumentation required

```text
material_forecast_change_detected
cash_plan_freshness_status_viewed
cash_plan_review_started
personalized_cashflow_action_reviewed
cash_plan_action_completed_or_dismissed
cash_plan_freshness_restored
```

Replace the baseline proxies with these event-level cohorts once instrumentation is live. In particular, measure the intersection of account import, modeling, and action review at the user level; do not infer it from separate aggregate feature-adoption rates.

---

## Design stress test

| Principle | How Cash Plan Freshness meets it |
| --- | --- |
| Meaningful behavior | It rewards reviewing a personalized cash-flow action, the candidate behavior that predicts retention. |
| Natural cadence | It appears weekly or when a material forecast change occurs, not daily by default. |
| Real motivation | The plan becoming stale represents a genuine loss of financial visibility, not a fake lost streak. |
| Earned return | A prompt is tied to a concrete forecast change and one relevant action. |
| Core value | The mechanism brings users back to an updated financial model and recommended action, not to points or badges. |
