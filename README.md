# Customer Success AI Churn Early-Warning Assistant

**A small AI-assisted Customer Success project by Victoria Ijeoma Daniel**

## Why I built this

As I learned more about Customer Success, I became interested in one question:

> How can a CSM spot customer risk early enough to act before the customer decides to leave?

I created this prototype to explore a simple workflow for turning customer feedback into useful CS signals.

## What it does

A CSM can paste a customer message into the workflow and use an AI prompt to identify:

- Customer sentiment
- Possible churn/risk signals
- Likely underlying issue
- Urgency
- Recommended CSM action
- Suggested follow-up message

The goal is **not** to replace a CSM's judgement. The goal is to help a CSM organize information faster and spend more time on the customer relationship.

## Example

Customer message:

> "We've been trying to get our team set up for two weeks. Some people still don't understand the workflow, and I'm not sure the product is worth the effort."

Possible AI-assisted output:

- **Sentiment:** Frustrated
- **Risk:** High
- **Signals:** Slow onboarding, low adoption, value not yet realized
- **Recommended action:** Schedule a short enablement session, identify the specific adoption blockers, and reconnect the product's value to the customer's original goal.
- **Priority:** Immediate follow-up

## AI prompt

Use this prompt with an AI assistant:

```text
You are a Customer Success AI assistant.

Analyze the customer message below and return:
1. Sentiment
2. Churn/risk level: Low, Medium, or High
3. The specific risk signals you found
4. Likely root cause
5. Recommended CSM action
6. A short, empathetic follow-up message

Do not invent facts. Separate what the customer actually said from your interpretation.

Customer message:
[PASTE MESSAGE HERE]
```

## What I learned

Building this helped me think about Customer Success beyond responding to problems. The useful part is connecting customer signals to an action.

It also reinforced something I believe about AI: **AI is most useful when it helps people think and act better, not when it replaces human judgement.**

## Customer Success framework

**Detect → Investigate → Engage → Re-anchor → Execute**

1. Detect the signal.
2. Investigate what is really happening.
3. Engage the customer with empathy.
4. Re-anchor the conversation around the customer's desired outcome.
5. Execute the agreed next step and follow up.

## About me

I'm Victoria Ijeoma Daniel, a customer-facing professional building my career in Customer Success. I bring 10+ years of experience working with customers, relationship management, support and problem-solving, and I recently completed formal Customer Success Management training.

This project is part of my practical learning journey into SaaS Customer Success and AI-assisted workflows.
