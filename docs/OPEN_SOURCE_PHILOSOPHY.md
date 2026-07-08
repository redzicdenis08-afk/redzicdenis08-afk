# Open Source Philosophy

## The problem with most AI repos

Most AI GitHub repos are either tutorial notebooks that do not run in production,
monoliths where you cannot extract the useful part, or vague templates with zero
real signal detection.

## What I do instead

I extract the reusable core of each production system and open-source it as a
standalone reference engine. Fictional data protects real customers.
Real patterns come from systems that talk to real people.

## What stays private

- API keys, secrets, customer data
- Proprietary prompt text used in live VAPI agents
- EC2 deployment configs and account credentials

## What I publish

- The scoring, routing, and ranking logic
- The compliance and audit trail patterns
- The signal detection and classification rules
- Working CLI with zero runtime dependencies where possible

## Why this matters

If you are building AI voice automation, you do not need another tutorial.
You need to see how someone solved the real problems:

- What do you do when the call drops mid-booking?
- How do you handle DNC opt-outs in real time?
- How do you score a lead batch when your data is messy CSV?

These repos answer those questions with runnable code.
