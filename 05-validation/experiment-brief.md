# The Validation · FinWise

> Module 5 · Experimentation Methods. The experiment brief that tests the bet.

## Method

**Method:** Multi-Armed Bandit

**Why:** FinWise has a persistent trial-to-paid conversion ceiling of approximately 2%. The hypothesis is that onboarding friction prevents some users from experiencing meaningful financial value early enough. A Multi-armed Bandit approach allows FinWise to explore different onboarding experiences while progressively directing more users towards better-performing variants.

_____

## Hypothesis + primary metric

IF WE test different personalised onboarding experiences that simplify banking data import and provide clear reconciliation progress for FinWise Trial Users, WE EXPECT a 15% relative increase in users achieving meaningful activation within 14 days, AS MEASURED BY the percentage of trial users successfully importing banking data and completing their first financial reconciliation within fourteen days of signup.

**Primary metric:** 14-day Activation Rate: Percentage of new trial users completing a meaningful reconciliation within fourteen days of signup., target: A 15% relative uplift in activation versus the existing onboarding experience, subject to sufficient evidence that the improvement is real

_Experiment: Finwise - Accelerating First Value, Increase the proportion of trial users who successfully complete their first meaningful financial reconciliation within 14 days of signing up._

_Testing Three onboarding experiences: A: Existing onboarding (control); B: Guided three-step onboarding with simplified banking data import; C: Guided onboarding with a personalised reconciliation progress tracker. A MAB will progressively allocate more traffic towards better-performing experiences. on Three onboarding experiences: A: Existing onboarding (control); B: Guided three-step onboarding with simplified banking data import; C: Guided onboarding with a personalised reconciliation progress tracker. A MAB will progressively allocate more traffic towards better-performing experiences.. Current experience: New trial users can access FinWise's financial management features, but the existing onboarding journey does not consistently guide them towards their first meaningful reconciliation. Users may need to independently identify the next action required to realise value. This is an assumption to validate.._

_Predicted outcome: Personalised, progress-led onboarding will increase the proportion of users completing their first meaningful reconciliation within fourteen days, while reducing time to first key action.. If successful: At least 15% relative uplift in fourteen-day activation versus the control.. If unsuccessful: Activation remains at or below the control, or any uplift is too small or uncertain to justify rollout.  Reconciliation accuracy deteriorates.._

_____

## Guardrail + read date

- **Guardrail:** Reconciliation Accuracy: Percentage of reconciled transactions confirmed as correct. Must not deteriorate materially compared with the control experience.
- **Read date:** 14 working days from the launch date.

_____


