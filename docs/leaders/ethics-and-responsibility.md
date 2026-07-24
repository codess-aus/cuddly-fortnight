---
hero_image: assets/images/heroes/hero-ethics.svg
hero_alt: Pink and blue banner for Ethics and Responsibility workshop
hero_title: Ethics & Responsibility
hero_subtitle: Workshop 4 of 4 — Leaders Track
---

# Ethics & Responsibility

<span class="ws-badge ws-badge--leaders">Leaders Track · Workshop 4 of 4</span>

**Duration:** 60–90 minutes  
**Prerequisites:** [Workshop 1: Understanding AI](understanding-ai.md) recommended

---

## What You'll Learn

- [x] Understand the core ethical challenges in AI
- [x] Recognise bias and how it appears in AI systems
- [x] Know what your responsibilities are as an AI leader
- [x] Apply basic frameworks for ethical AI decision-making
- [x] Prepare your team for responsible AI practices

---

## Why Ethics Is a Leadership Issue

Ethical AI is not just a technical problem. Engineers can build safeguards into models, but the decisions about what to build, who it affects, and what tradeoffs are acceptable — those are leadership decisions.

> "The people most harmed by poorly designed AI systems are often the least visible to the teams that build them."

If you're leading an AI product team, you own the ethical implications of what your team ships. This workshop helps you understand what that means in practice.

---

## Part 1 — What Is Bias in AI?

Bias in AI happens when a system consistently produces outcomes that unfairly favour or disadvantage certain groups of people.

### How Bias Gets Into AI Systems

**Historical data bias** — If your training data reflects past discrimination (e.g. historical hiring data that favoured one gender), the model will learn to replicate it.

**Representation bias** — If your training data doesn't include enough examples from certain groups (e.g. images mostly from one ethnicity), the model will perform worse for underrepresented groups.

**Measurement bias** — If the labels or outcomes in your training data were applied inconsistently or unfairly, the model inherits those inconsistencies.

**Feedback loop bias** — Once a model is deployed, its outputs can influence future data (e.g. a model that recommends fewer job ads to one group → that group applies less → future data has fewer applicants from that group).

### Real-World Examples

- Facial recognition systems with significantly lower accuracy for darker-skinned faces
- Résumé screening tools that downranked applications from women
- Healthcare risk scores that underestimated severity of illness for Black patients
- Bail risk assessment tools that predicted higher recidivism for certain ethnic groups

!!! note "Bias is often invisible until you look for it"

    These systems weren't built by people who intended harm. The harm came from not asking the right questions during design and testing.

---

## Part 2 — Fairness, Transparency, and Accountability

Three concepts that every AI leader needs to understand:

### Fairness

Fairness means the AI produces equitable outcomes across different groups of users. There are actually multiple definitions of fairness that can conflict with each other — your team needs to decide which one matters most for your context.

> **Leader's question:** "Does our AI perform equally well for all the people it affects?"

### Transparency

Transparency means users, stakeholders, and regulators can understand how and why the AI makes its decisions. "Black box" AI — where even the developers can't explain specific decisions — is a growing legal and ethical risk.

> **Leader's question:** "Can we explain this AI's decisions in plain language to a user who's been affected by them?"

### Accountability

Accountability means there's a clear answer to: "When this AI causes harm, who is responsible?" This is often blurrier than people expect.

> **Leader's question:** "If this AI causes harm, what is our process for addressing it — and who owns that process?"

---

## Part 3 — Legal and Regulatory Context

AI regulation is evolving rapidly around the world. As a leader, you need to stay broadly informed:

| Regulation | Where | What It Covers |
|------------|-------|----------------|
| **EU AI Act** | European Union | Risk-based framework; high-risk AI requires strict controls |
| **GDPR** | EU/UK | Data privacy; affects training data collection and use |
| **Australia's AI Ethics Framework** | Australia | Voluntary principles for responsible AI |
| **US Executive Order on AI** | USA | Safety, security, and trust in AI |

!!! tip "You don't need to be a legal expert"

    You do need to have legal and compliance people in the room when making decisions about AI products that affect users. Make this a habit, not an afterthought.

---

## Part 4 — An Ethical Decision Framework

When your team is facing a decision about an AI product, use this simple framework:

### The FAIR Check

**F — Who is Affected?**  
Who will be impacted by this AI system? Include people who aren't your direct customers — employees, communities, people who are excluded.

**A — What Could Go Wrong?**  
What are the realistic ways this could cause harm? List them. The act of listing them makes them manageable.

**I — Is There Informed Consent?**  
Do the people affected know they're interacting with AI? Do they have a meaningful choice?

**R — Who Is Responsible?**  
Is there a named owner for each category of risk? If no one is accountable, no one will act.

### Worked Example

> *Your company wants to use AI to automatically screen incoming customer service requests and assign urgency levels.*

| FAIR Check | Consideration |
|------------|---------------|
| **F** | All customers who submit requests; staff whose workload will change |
| **A** | Urgent requests might be mislabelled as low priority; bias against certain writing styles |
| **I** | Should customers know their request is being prioritised by AI? |
| **R** | Customer service manager owns complaint outcomes; data team owns model performance |

---

## Part 5 — Building a Responsible AI Culture

Individual decisions matter, but culture is what creates consistently responsible AI.

### Practices to Embed

- **Ethics reviews as standard process** — not optional, not only for "controversial" projects
- **Diverse teams** — people from different backgrounds catch blindspots others don't see
- **User research with underrepresented groups** — go to them; don't assume
- **Red teaming** — deliberately try to find ways the AI could be misused or could fail
- **Incident response** — have a plan for what you'll do when something goes wrong

### What Leaders Can Do Right Now

1. **Add "who is affected?" to every AI project brief**
2. **Require bias testing before any AI product goes live**
3. **Make it safe to raise ethics concerns** — people need to know they won't be penalised for flagging problems
4. **Appoint someone responsible** for responsible AI in your organisation

---

## Key Takeaways

- Bias in AI is common, usually unintentional, and often invisible until you look
- Fairness, transparency, and accountability are leadership responsibilities, not technical problems
- The FAIR Check (Affected, Could Go Wrong, Informed Consent, Responsible) is a practical starting point
- Culture and process are what make responsible AI sustainable

---

## Your Actions for This Week

1. **Pick one current AI product or project** and run a quick FAIR Check
2. **Identify who owns responsible AI** in your team or organisation — if no one does, that's your action
3. **Read one article** on an AI ethics failure in an industry similar to yours

---

[← Workshop 3: AI Product Strategy](ai-product-strategy.md)  
[← Back to Leaders Track](../index.md){ .md-button .md-button--primary }
