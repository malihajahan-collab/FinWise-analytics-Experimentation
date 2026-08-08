# The Solution · FinWise

> Module 2 · Acquisition & Activation. The onboarding solution and the Aha moment that makes value land.

## Aha moment

*The exact moment FinWise becomes "my money, finally clear."*

FinWise's candidate Aha moment is when a trial user **reviews a recommended cash-flow action generated from their own business data**.

In the prototype, this happens when the user clicks **“Review the $5,240”** after FinWise shows that Maple Street Bakery's projected cash balance may fall below its operating buffer within six weeks. The measurable behavioral event is:

`personalized_cashflow_action_reviewed`

This is stronger than treating account connection or dashboard viewing as the Aha moment. The user has connected real data, received a forecast tied to an actual business concern, and chosen to investigate a recommended action.

This behavior plausibly predicts retention because it completes FinWise's core value sequence:

**Connect real data → receive a relevant forecast → investigate an actionable recommendation**

Users who repeat this workflow have a reason to return as their transactions, balances, and upcoming obligations change. This remains a hypothesis until cohort data demonstrates that users who complete this action retain and convert at higher rates than those who do not.

_____

## Onboarding prototype

*Screenshots or a shareable link to the flow that gets users to the Aha faster.*

[Open the clickable FinWise onboarding prototype](https://finwise-onboarding-p-nm88.bolt.host)

The prototype uses a five-screen path:

1. **Content landing page** — demonstrates value for the visitor's cash-flow question. The single action is **“Apply this to my business.”**
2. **Lightweight sign-up** — creates the reverse trial with minimal interruption. The single action is **“Continue with Google.”**
3. **Confirm the pre-filled goal** — carries the visitor's content intent into the product. The single action is **“Use this goal.”**
4. **Connect one account** — obtains the minimum real data required for the forecast. The single action is **“Connect RBC Business Chequing.”**
5. **Personalized insight** — answers the original question and presents a recommended action. The single action is **“Review the $5,240.”**

The path is deliberately narrow:

**High-intent content → contextual trial CTA → minimal sign-up → pre-filled goal → one data connection → personalized action**

_____

## Why this activates

*The activation logic: what changes, and why it converts trial users.*

### Final hypothesis

If FinWise carries a visitor's content intent into a short, pre-personalized trial experience, then more qualified visitors will start trials and reach activation because the transition from financial guidance to applying that guidance will feel relevant and continuous.

For trial users specifically: if FinWise guides them directly to a recommended cash-flow action based on their own data, then more users will reach the candidate Aha moment because the experience removes unnecessary decisions and setup before delivering personalized value.

### What changes

- The financial goal is pre-filled from the content that generated the trial instead of being collected through a multi-question quiz.
- Sign-up is reduced to one authentication action with no credit card requirement.
- Only one primary business account is required before generating the first forecast.
- Additional accounts, team invitations, product tours, settings, and upgrade prompts are postponed until after the Aha moment.
- The first product result answers the financial question that originally brought the visitor to FinWise.

### Why it should convert

The experience preserves intent from acquisition through activation. Each screen has one job and one primary action, while pre-filled context reduces cognitive load and the single-account connection reduces setup effort. The user sees useful content before being asked to sign up and reaches an actionable result before being asked to explore the broader product or upgrade.

FinWise should test the new flow against the current onboarding experience. The primary activation metric should be the percentage of trial users who complete `personalized_cashflow_action_reviewed`. Trial-to-paid conversion and week-one retention should be downstream metrics, with onboarding abandonment, bank-connection failure, and time-to-Aha as guardrails.

_____
