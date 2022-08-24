# Pega - Activities

**Activities automate processing, and are only scripted in Dev Studio. Activities contain a sequence of steps that are performed in the instructed order.**

**!Remember** Activities are harder to maintain and not as easy to construct as other rules in Pega.

We should not use an activity for calculations or property validations that we can implement as **constraints rules** or **Declare Expression rules**. Use of a **declarative rule** (rather than an activity) eliminates the need to control how and when an activity executes. **A best practice is to use declarative processing rather than activities when feasible.**

For data manipulations, we can use a **Data Transform** instead of an activity.

**To query from an external DB, we can use Report Definition rules instead of activities.**

We may need to automate the processing of cases with a sequence of steps to be executed. Most of the time, this is possible with the steps in the case designer or multiple shapes in a flow rule or with declarative rules or data transform rules or a combination of those and other rules.
