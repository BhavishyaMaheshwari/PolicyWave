# Policy Wave

Policy Wave is an interactive policy simulation platform designed to help governments, researchers, and citizens understand how policy decisions affect people in the real world before they are finalized.

---

## Problem Statement

Government policymakers often spend **2–4 weeks** working with static policy reports that arrive too late to be useful. In reality, many policy decisions are finalized within days, leaving little room to explore alternatives, identify trade-offs, or address issues early.

This gap results in guesswork, limited transparency, and unintended consequences, particularly for vulnerable groups. The challenge is compounded by a few key realities:
- Only about **27% of Indians have strong financial literacy**, even as policies grow increasingly complex  
- Small policy changes (1–5%) can lead to **non-linear effects** that static reports fail to capture  
- Lower-income households spend **2–3× more** of their income on essentials and are impacted first  

---

## Solution

Policy Wave replaces static reports with an **interactive policy simulation experience**.

Instead of relying on lengthy documents and assumptions, decision-makers can directly interact with a policy by adjusting inputs, observing immediate effects, and understanding trade-offs in real time. This shifts policymaking from a delayed, abstract exercise to a more concrete and practical process.

### Example

If fuel tax is increased to **30%** and transport investment to **₹600 Cr**, Policy Wave can immediately highlight:
- A potential **~12.5% reduction in pollution**
- An increase in commute costs  
- Greater affordability pressure on lower-income commuters  

By showing both benefits and risks upfront, the platform allows policymakers to adjust decisions before policies affect real people.

---

## How on-demand.io Is Utilized

Policy Wave uses **AIREEV’s on-demand.io** as the reasoning layer behind its simulations.

- Policy Wave defines the baseline policy state, constraints, assumptions, and user context  
- Policy changes are represented as structured deltas  
- This information is passed to the AI agent for analysis  

The AI agent then:
- Compares changes against the baseline  
- Reasons through interactions across multiple factors  
- Estimates directional impact and ranges rather than fixed predictions  
- Identifies key drivers, trade-offs, and affected groups  
- Returns structured explanations that are rendered in the UI  

---

## Impact

Using the same simulation example:
- Policymakers can see impact **before** decisions are finalized  
- Trade-offs between benefits and risks become visible early  
- Human outcomes such as costs, access, and exposure are clearly surfaced  
- Decisions are easier to communicate, improving transparency and trust  

---

## Our USP

- Governments can **test and compare policy scenarios** before implementation instead of reacting after rollout  
- Individuals can see how policies translate into **clear, everyday outcomes**, not just high-level aggregates  
- Simulation, expert insight, and informed discussion are brought together in one platform  

---

## Target Audience

- **Primary:** Government policymakers  
- **Secondary:** Research institutions and policy consultants  
- **Tertiary:** Citizens and civil society groups seeking to understand policy impact  

The long-term beneficiaries are the groups most affected by policy decisions but least visible in traditional reports.

---

## Tech Stack

- **Frontend:** Next.js, React, TypeScript, Tailwind CSS  
- **Backend:** Node.js, Express, TypeScript, PostgreSQL, Prisma  
- **AI Layer:** AIREEV’s on-demand.io for policy reasoning and impact analysis  

---

## License

MIT License
