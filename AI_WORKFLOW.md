# AI Workflow Write-up

## Project
Customer Success AI Churn Early-Warning Assistant

## Problem
Customer feedback often contains early warning signs before a customer openly says they want to leave. A CSM needs a practical way to recognize those signals and decide what to do next.

## Input
A customer email, chat message, survey response, meeting note, or feedback comment.

## AI analysis
The AI is asked to classify:
- sentiment
- risk level
- observable risk signals
- likely root cause
- recommended action
- follow-up message

## Human-in-the-loop
The CSM reviews the AI output before taking action. The AI should never make the final customer decision.

## Example
Input:
"We've been trying to get our team set up for two weeks. Some people still don't understand the workflow, and I'm not sure the product is worth the effort."

Output:
Risk: High
Signals: onboarding delay, adoption difficulty, unclear value
Action: proactive enablement + discovery conversation + value re-alignment

## Why this matters
The project demonstrates how I am learning to combine Customer Success thinking with AI rather than treating AI as a replacement for customer relationships.
