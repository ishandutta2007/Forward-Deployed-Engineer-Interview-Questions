# 10. System Design / Case Studies

Open-ended, senior-level scenarios synthesizing themes across the entire repo. As with the format established across this series, these are typically extended discussions rather than questions with one correct answer — evaluate reasoning quality, whether discovery/technical/relationship considerations are integrated together rather than treated as separate silos, and whether the candidate reflexively distinguishes "technically impressive" from "actually solves the customer's real problem and will still be working in six months."

---

### 10.1 🔴 You're starting a new engagement with an enterprise logistics company that wants to reduce delivery delays. You have two weeks before your first on-site visit. Walk through how you'd prepare, what you'd prioritize during the first week on-site, and what you'd aim to have delivered by the end of your first month.

**What a strong answer covers:**
- Should propose deliberate pre-work before arriving on-site (understanding the industry and company at a general level, reviewing whatever information is already available) without over-committing to any specific technical direction before genuine discovery has occurred (category 2.8's premature solutioning warning).
- Should propose a first-week approach centered on the discovery techniques discussed throughout category 2 — multi-stakeholder engagement (2.4), shadowing/direct observation (2.3), and explicitly avoiding jumping to a specific technical solution before this discovery work is genuinely done.
- Should propose identifying and beginning to map the actual data landscape early (category 3.1's point that data integration is usually the dominant time cost) rather than treating this as a later-stage concern.
- Should propose a first-month deliverable calibrated to the time-to-value principle (category 1.6) and the vertical-slicing approach (category 4.1) — something narrow but genuinely real and demonstrable, not a comprehensive but still-abstract plan.
- A strong answer explicitly flags what it would NOT try to accomplish in the first month, showing deliberate prioritization rather than an unfocused attempt to address everything simultaneously.

---

### 10.2 🟡 A customer's engineering team wants you to build directly against their production database rather than setting up a proper staging environment, citing time pressure. How do you navigate this request?

**What a strong answer covers:**
- Should take the time pressure seriously as a legitimate concern rather than dismissing it, echoing the collaborative-not-dismissive navigation modeled throughout categories 6 and 8's case studies.
- Should clearly articulate the specific, concrete risks of working directly against production (category 5.10's sandbox discussion, in reverse — the risks of skipping this layer entirely) rather than a vague, general objection.
- Should propose a genuinely fast, low-overhead alternative (a lightweight staging setup, or a specific, tightly-scoped read-only access pattern) rather than either capitulating to the risky request or insisting on a slower, more elaborate alternative than the situation actually requires.
- Should recognize this as fundamentally a trust and risk-communication exercise (echoing category 6's framing throughout) as much as a technical one.

---

### 10.3 🔴 Eight weeks into a twelve-week engagement, your primary customer stakeholder tells you the solution you've built, while technically excellent and matching everything originally agreed upon, doesn't actually address what turns out to be their real underlying problem — which has only become fully clear to them through seeing the solution in action. There are four weeks of budgeted engagement time left. How do you handle this?

**What a strong answer covers:**
- Should directly apply the discovery-through-iteration principle discussed in category 2.10 — this is precisely the scenario that principle anticipates, and a strong answer treats it as an expected, if unwelcome, possibility rather than a shocking failure.
- Should avoid defensiveness about the original scoping — echoing the framing discussed in category 2.16's case study, this reflects normal, expected discovery evolution, not a failure to do adequate upfront discovery.
- Should propose a rigorous, honest reassessment of what's actually achievable in the remaining four weeks given this new understanding, rather than either abandoning the new insight to preserve the original plan, or over-promising a full pivot that the remaining time and budget can't realistically support.
- Should address the stakeholder and expectation-management dimension explicitly (category 9.3-9.4) — this conversation needs to happen with genuine transparency about tradeoffs, not an unrealistic promise to deliver everything.
- A strong answer proposes a specific, concrete framework for the remaining-time decision (what's the smallest, most valuable adjustment achievable in four weeks that meaningfully addresses the real problem, even if it doesn't fully solve it) rather than treating this as an unstructured, open-ended pivot.

---
