---
hero_image: assets/images/heroes/hero-managing-teams.svg
hero_alt: Light blue and lavender banner for the Managing AI Teams workshop
hero_title: Managing AI Teams
hero_subtitle: Workshop 2 of 4 — Leaders Track
---

# Managing AI Teams

<span class="ws-badge ws-badge--leaders">Leaders Track · Workshop 2 of 4</span>

**Duration:** 60–90 minutes  
**Prerequisites:** [Workshop 1: Understanding AI](understanding-ai.md) is recommended

---

## What You'll Learn

- [x] Understand the key roles in an AI product team
- [x] Know what questions to ask — and what to listen for in the answers
- [x] Set realistic expectations for AI project timelines and outcomes
- [x] Create conditions for your technical team to do their best work
- [x] Spot common warning signs that an AI project is in trouble

---

## Part 1 — Who's on an AI Team?

AI product teams typically include a mix of these roles. You don't need to understand every detail of each role — but knowing *what* each person does helps you have better conversations.

| Role | What They Do | Questions to Ask Them |
|------|-------------|----------------------|
| **Product Manager (PM)** | Defines what to build and why; owns the roadmap | "What problem are we solving, and for whom?" |
| **Data Scientist** | Builds and trains models; analyses data | "What does the model do well, and where does it fail?" |
| **Machine Learning Engineer** | Turns models into working software | "How do we monitor this in production?" |
| **Data Engineer** | Builds the data pipelines that feed the model | "How clean is our data? What's missing?" |
| **UX Designer** | Designs the user experience | "How do users feel when the AI gets it wrong?" |
| **Software Engineer** | Builds the non-AI parts of the product | "How does the AI feature connect to everything else?" |

!!! tip "Not every team has every role"

    Small teams often have people wearing multiple hats. What matters is that each *concern* — data, model, product, user experience — is owned by someone.

---

## Part 2 — Setting Realistic Expectations

AI projects fail more often than traditional software projects, and often for predictable reasons. Here's what to know:

### The "It Works in the Lab" Problem

AI models are typically developed and tested on historical data. When they meet real users in the real world, performance often drops. This is normal — and manageable — if you plan for it.

> **What to do:** Ask your team: "How does performance compare between our test environment and production?" If they don't measure this, that's a risk flag.

### Timelines Are Different

Building AI products is more experimental than building traditional software. Things that seem simple can take much longer than expected because:

- Data may be messier than anticipated
- Models may not behave as hoped
- Multiple rounds of testing and iteration are normal

> **What to do:** Don't expect AI projects to have the same level of certainty in timelines as standard software. Budget time for experimentation.

### "Good Enough" Is a Valid Target

AI is rarely 100% accurate. A model that is right 90% of the time may be extremely valuable — or may be dangerous, depending on the context.

> **What to do:** Ask: "What level of accuracy do we need to create real value — and what happens when it's wrong?"

---

## Part 3 — Questions That Make a Difference

These questions will help you cut through technical complexity and understand what's really happening:

### On the Data

- "Where does our data come from, and who owns it?"
- "Does our training data reflect the people who will actually use this product?"
- "How do we handle data privacy and consent?"

### On the Model

- "What does success look like — how do we measure it?"
- "What are the failure modes? When does this go wrong?"
- "How do we know if performance degrades over time?"

### On the Product

- "How do users know they're interacting with AI?"
- "What happens when the AI is wrong — who's responsible?"
- "Can users override or correct AI decisions?"

### On the Team

- "What are the biggest blockers you're facing right now?"
- "Do you have what you need to do this work well?"
- "Where do you need my help as a leader?"

---

## Part 4 — Creating Conditions for Success

The single biggest thing you can do as a leader is remove friction and create psychological safety.

### What AI Teams Need

**Access to good data** — AI without quality data is like a car without fuel. Removing data access blockers is often the highest-value thing a leader can do.

**Time to experiment** — Iteration is not waste. If your team is afraid to try things and fail, they'll produce mediocre work.

**Clear success criteria** — "Make the AI better" is not a goal. "Increase correct predictions from 82% to 90% by Q3" is a goal.

**Protection from premature launches** — Rushing an AI product to market before it's reliable can damage user trust in ways that are very hard to recover from.

### What to Avoid

- ❌ Treating AI like a fixed software feature that "just needs to be built"
- ❌ Setting hard deadlines without accounting for data and model experimentation time
- ❌ Assuming that because AI is working today, it will keep working without monitoring
- ❌ Leaving ethical considerations as an afterthought

---

## Part 5 — Warning Signs in AI Projects

Watch for these signals that something may be going wrong:

!!! note "Red flags to watch for"

    - **"The data is fine, trust us"** — Good teams are transparent about data quality issues
    - **"It works great in demos"** — Demos can hide real-world failures
    - **"We can't measure accuracy yet"** — If a team can't measure what they're building, that's a problem
    - **"We'll fix the bias after launch"** — Bias issues are much harder to fix after deployment
    - **Constant scope changes without explanation** — May indicate the original approach isn't working

---

## Key Takeaways

- Know who's on your AI team and what each person is responsible for
- AI projects need more time for experimentation than traditional software
- The best questions focus on data quality, failure modes, and measurement
- Create safety for your team to experiment and surface problems early
- Watch for warning signs — most AI project failures are visible in advance

---

## Your Actions for This Week

1. **Have a "state of the data" conversation** with your data team — ask about completeness, quality, and bias
2. **Review your AI project metrics** — are you measuring the right things, and are targets realistic?
3. **Check in with your team**: "What's the biggest problem we haven't talked about yet?"

---

[← Workshop 1: Understanding AI](understanding-ai.md)  
[Next Workshop: AI Product Strategy →](ai-product-strategy.md){ .md-button .md-button--primary }
