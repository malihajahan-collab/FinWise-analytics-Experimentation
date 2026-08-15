# The Mechanic · FinWise

> Module 3 · Retention & Engagement. The engagement mechanic that builds the habit loop, with rationale and a wireframe.

## The mechanic

*The habit loop: trigger → action → reward → investment.*

FinWise's engagement mechanic is the **Weekly Cash Clarity Check**, supported by a two-step progress bar. It reinforces the retention-predicting behavior of reviewing an updated cash-flow forecast and investigating one relevant recommendation each week.

- **Trigger:** FinWise refreshes the user's forecast after a week of new transactions or notifies the user when a material change needs attention.
- **Action:** The user reviews the updated cash position and opens the most relevant recommended action.
- **Reward:** FinWise confirms, **“This week's cash position is clear,”** giving the user confidence that the forecast is current and the material risk has been reviewed.
- **Investment:** The user's reviewed decisions and continuously connected financial data improve the context available for the next forecast, making future recommendations more relevant.

The progress bar is the interface mechanic; the Weekly Cash Clarity Check is the customer-facing experience. It rewards completion of meaningful financial work rather than logins, points, badges, or an artificial streak.

_____

## Rationale

*Why this drives retention before the paywall.*

The Weekly Cash Clarity Check uses a progress bar to reinforce the retention-predicting behavior of reviewing an updated cash-flow forecast and investigating one relevant recommendation each week. A weekly cadence matches how often meaningful transaction and obligation changes are likely to accumulate, while the clear two-step completion state gives users an authentic sense of progress toward financial clarity. The experience avoids artificial streaks, points, and social competition; instead, it earns the user's return by surfacing material changes and confirming when no further action is needed. Completing the check connects directly to FinWise's core value: helping small-business owners understand their cash position and act on emerging risks before they become problems. During the reverse trial, repeated weekly value gives users a concrete reason to retain access to FinWise before they encounter the paywall.

This is a hypothesis that should be validated by comparing weekly check completion with repeat recommendation reviews, week-over-week retention, and trial-to-paid conversion. FinWise should trigger the check only when the forecast is refreshed or a material change exists; otherwise, the mechanic could become repetitive or feel like a manufactured engagement prompt.

_____

## Wireframe

<img width="1536" height="1024" alt="finwise-weekly-cash-clarity" src="https://github.com/user-attachments/assets/a0ca3a14-8e53-418f-92d2-dc0a82a32dbe" />

![FinWise Weekly Cash Clarity Check showing the in-progress and completed states](assets/finwise-weekly-cash-clarity.png)

The wireframe shows the mechanic at 50% completion before the user reviews a recommended action and at 100% after the weekly cash position is clear. The completion state communicates the customer outcome without exposing internal design decisions.
# Engagement Weighted Scorecard, Module 3 · FinWise

**Behavior being scored:** A user reviews an updated cash-flow forecast and investigates one relevant recommendation based on their own business data.

**Mechanic being scored:** The Weekly Cash Clarity Check, shown through a two-step progress bar and completed when the user's weekly cash position is clear.

| Metric | Weight | Score (0,1,3,7,10) | Weighted |
| --- | ---: | ---: | ---: |
| Metric 1 (Depth) | 50% | 10 | 5.00 |
| Metric 2 (Breadth) | 15% | 3 | 0.45 |
| Metric 3 (Frequency) | 35% | 7 | 2.45 |
| **Total weighted KPI** | **100%** | | **7.90 / 10** |

**Result: Strong** (≥7 strong · 4–7 moderate · <4 needs improvement)

## Scoring rationale

- **Depth — 10:** The mechanic reinforces FinWise's candidate retention-predicting action rather than a proxy such as logging in. To complete the check, the user reviews their current cash position and opens a recommendation tied to a material financial change. This is the same core behavior used in the onboarding prototype's Aha moment: `personalized_cashflow_action_reviewed`.
- **Breadth — 3:** The mechanic deliberately concentrates on one high-value cash-flow workflow instead of encouraging broad feature use. This limited breadth is consistent with the hypothesis that FinWise should remove unnecessary decisions and guide users directly to personalized financial clarity. Additional accounts, team invitations, product tours, and unrelated features remain outside the critical path.
- **Frequency — 7:** Weekly use matches the expected cadence at which new transactions and obligations can produce a meaningful forecast update. The mechanic does not force daily engagement or an artificial streak. FinWise should trigger the check only after a forecast refresh or when a material change needs attention.

## Alignment with the FinWise journey

The content-driven acquisition experience brings a visitor into a pre-personalized reverse trial, the onboarding flow guides them to review their first cash-flow recommendation, and the Weekly Cash Clarity Check repeats that same value-producing behavior at a natural weekly cadence. The mechanic therefore extends the existing acquisition and activation hypothesis into retention without introducing a contradictory behavior or reward system.

The **7.90/10** score indicates a strong engagement concept. Its strength comes from depth and cadence, while its intentionally narrow breadth reflects the decision to prioritize one meaningful financial habit before expanding users into other parts of FinWise.

_____
