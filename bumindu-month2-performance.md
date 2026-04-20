# Performance Reviews

This file contains two full performance reviews for H1 2025. The first is for Alex Chen, who is tracking at Exceeds Expectations and is close to being ready for a Tech Lead role. The second is for Riley Park, who is going through a difficult personal period and is not delivering at their usual level. Both reviews aim to be honest, specific, balanced, and focused on what happens next.

---

## Performance Review 1 — Alex Chen

**Review period:** H1 2025 (January – June)
**Role:** Senior Software Engineer
**Manager:** Bumindu
**Overall rating:** Exceeds Expectations

### Summary

Alex has had a standout six months. The work has been high quality, the mentoring of Casey has visibly lifted a more junior team member, and Alex has started acting like a Tech Lead in small but important ways — owning scope, pulling in stakeholders, and giving thoughtful feedback to others. There are a small number of growth areas, and they are exactly the areas you would expect from someone one step away from a formal Tech Lead role. I am recommending Alex for Tech Lead consideration in Q3, and this review lays out what still needs to be in place before that conversation.

### Results (what Alex accomplished)

**Key accomplishments:**

1. **Led the API redesign project, delivered 2 weeks early.**
   - Reduced p95 response time from 420ms to 250ms (a 40% improvement).
   - Mentored Casey and Jordan on the new patterns during the project, which made the rollout smoother.
   - Wrote a clear migration guide that the Insights team also picked up.

2. **Built and landed the new automated testing framework.**
   - Test coverage moved from 62% to 85% on the services Alex owns.
   - Regression bugs caught in CI went up by 50% — which means they did not reach production.
   - Saved roughly 4 engineer-hours per week on manual regression checks.

3. **Incident response leadership on 3 P1 events.**
   - Took ownership during the February payment outage, kept stakeholders informed every 15 minutes, and co-wrote a clean post-mortem.
   - Wrote two runbooks that the whole team now uses for similar incidents.

**Metrics summary:**

| Metric | Target | Actual | Notes |
|---|---|---|---|
| Projects delivered | 2 | 3 | API redesign, testing framework, and the caching refactor |
| Code review turnaround | 24h | 16h | Consistent across the period |
| Test coverage (Alex's services) | 80% | 85% | Pulled the rest of the team up with the framework |
| P1 incidents led | — | 3 | All resolved within SLA |

### How (behaviors and ways of working)

**Strengths, with concrete examples:**

- **Technical clarity.** In the 5 March architecture review for the caching refactor, Alex explained the trade-off between TTL and invalidation so clearly that Product agreed the direction in a single meeting. That is a rare skill.
- **Mentorship that actually teaches.** Casey's first three PRs had patient, detailed comments from Alex — not "change this to that," but "here is why this matters." Casey has grown faster because of it.
- **Proactive with stakeholders.** Alex started sending a weekly update to Priya from Product about the API redesign without being asked. This kind of thing is what separates a strong senior from a Tech Lead.

**Growth areas, also with examples:**

- **Perfectionism slows some deliveries.** The caching refactor went through 6 review rounds before Alex felt it was ready to merge. The code was already good after round 3. The extra polish cost a week. I want Alex to practise "good enough to ship, then iterate."
- **Delegation is still hard.** On the API redesign, Alex took the hardest pieces personally instead of handing them to Jordan as a stretch assignment. That is a missed mentoring opportunity. Tech Leads delegate to grow others, not only to save time.
- **Meeting facilitation has room.** Alex is a strong one-on-one communicator but can be quiet in larger meetings where the energy is loud. I would like Alex to practise holding space in team meetings.

### Growth assessment

**Progress on last period's goals:**

| Previous goal | Status | Evidence |
|---|---|---|
| Lead a cross-team project | Done | API redesign, delivered early |
| Improve documentation practices | Done | Migration guide adopted by Insights team |
| Develop public speaking / talks | Partial | Gave one internal tech talk, needs more reps |

**Skills demonstrated, mapped to the Tech Lead competency framework:**

- Architecture: Advanced
- Mentorship: Proficient, trending to Advanced
- Project leadership: Proficient
- Stakeholder management: Developing (the biggest gap for Tech Lead readiness)
- Meeting facilitation: Developing

### Future focus

**Goals for H2 2025 (SMART):**

1. **Lead the system design for the B2B platform rollout, end-to-end.**
   Specific: Alex owns the design doc, the review cycle, and the delivery plan.
   Measurable: design doc approved by architecture council, delivery on schedule.
   Timeline: design done by end of August, delivery by end of November.

2. **Formally mentor Jordan through one cross-service project.**
   Specific: Alex pairs with Jordan on the notification service refactor.
   Measurable: Jordan delivers the refactor with Alex in a support role, not a doing role.
   Timeline: start in July, complete by end of September.

3. **Facilitate two team meetings per month starting July.**
   Specific: Alex runs either the sprint planning or the architecture review.
   Measurable: I give Alex direct feedback after each, and Alex improves against the last one.
   Timeline: ongoing from July.

**Development plan:**

- Attend the "Leading through Influence" workshop in July
- Shadow a Tech Lead from the platform team for 2 sessions this quarter
- Deliver 2 internal tech talks, one on the API redesign and one on the testing framework
- Read "The Manager's Path" chapters 3–5 with me, and we discuss in a skip-level

### Promotion readiness

**Tech Lead readiness:** around 80%.
**Recommended timeline:** formal conversation in Q3, role change by end of Q4 if H2 goals are met.
**Main blocker:** stakeholder management experience. The H2 goals above are specifically designed to close this gap.

### What I appreciate about working with Alex

Alex makes the team better. People copy how Alex reviews code, how Alex writes docs, and how Alex handles pressure during incidents. That is the kind of invisible contribution that does not show up in a ticket count but shows up everywhere else. I want to thank Alex for that publicly, not just in this review.

---

## Performance Review 2 — Riley Park

**Review period:** H1 2025 (January – June)
**Role:** Senior Software Engineer
**Manager:** Bumindu
**Overall rating:** Needs Improvement

A quick note before the review. Riley has shared with me that there is a difficult personal situation affecting work right now. That is real, and it matters. This review is honest about the performance gap because it has to be, but it is also honest about the context and the support plan. The goal is not to judge Riley — it is to give Riley a fair, accurate picture and a clear way back.

### Summary

Riley's technical skills are as strong as they have ever been. The challenge this period has been consistency, delivery pace, and communication — all of which have been affected by circumstances outside work. I am rating this period as Needs Improvement because the outputs do not match Riley's usual standard, but I want to be clear that this is not a commentary on Riley as an engineer. With the support plan below, I am confident Riley can return to good standing within 8 weeks.

### Results (what Riley accomplished)

**Accomplishments:**

1. **Completed the user authentication service upgrade.** Shipped on time, and the security review was clean. The technical depth on this was exactly what we needed.
2. **Fixed 3 critical security vulnerabilities** found during the April audit. Riley spotted a related fourth issue nobody else caught.
3. **Kept the payment service stable** through the Q1 traffic spike — no incidents on Riley's owned services during that period.

**Areas of concern:**

1. **Missed 3 sprint commitments** in the April–May window. Two slipped into the following sprint, one was reassigned to Morgan.
2. **Higher than usual bug rate on delivered code.** Escape rate was 15% this period, against a team target of under 5%. This is well above Riley's own historical average.
3. **Documentation gaps** on two projects, including the auth upgrade, where we had to fill in the gaps after the fact.

**Metrics summary:**

| Metric | Target | Actual | Notes |
|---|---|---|---|
| Sprint commitment | 80% | 55% | Strong first 6 weeks, then a clear drop |
| Code review turnaround | 24h | 72h | Slower response times from April onwards |
| Bug escape rate | <5% | 15% | Not Riley's usual standard |
| Security issues caught | — | 4 | Still the strongest on the team here |

### How (behaviors and ways of working)

**Strengths that have held steady:**

- **Deep technical expertise.** When Riley is engaged, the quality is still there. The auth service upgrade is proof.
- **Positive relationships on the team.** Riley has not been difficult to work with. Morgan and Alex have both told me unprompted that they value Riley.
- **Responsive when looped in.** When I or another teammate brings Riley into a problem directly, Riley engages and helps.

**Areas of concern:**

- **Missed meetings without notice.** This has happened 4 or 5 times in the last two months. The team has covered without complaint, but it is a signal.
- **Communication gaps with stakeholders.** A product manager asked me twice for an update Riley was supposed to send. I filled the gap, but Riley should have been the one.
- **Code quality below Riley's usual line.** This is the one that tells me something is off. Riley does not usually ship code with 3 P2 bugs in it.

### Context

I want to name this openly. Riley shared with me that there is a personal situation that has been ongoing since roughly February. I am not going to describe it in this document — that is Riley's to share, not mine. What I will say is that it is real, it is hard, and it explains the pattern. This review is not a disciplinary document. It is an honest snapshot paired with a support plan.

### Support plan

This is the part of the review that matters most.

**Immediate adjustments (already in place):**

- Workload reduced to 70% of normal capacity, with Morgan picking up the auth service on-call rotation temporarily
- Weekly 1:1s instead of bi-weekly, so I can stay close without being intrusive
- EAP (Employee Assistance Program) contact shared, no pressure to use
- Flexible hours — Riley can shift start and end times as needed, no questions
- Riley's name removed from the new project assignments for this sprint

**Medium-term plan (next 8 weeks):**

| Week | What we are aiming for | How we measure it |
|---|---|---|
| Week 1–2 | Stabilise at 70% load, no new scope | Sprint commitment met at 70% |
| Week 3–4 | Maintain 70%, re-engage on one documentation piece | Docs back up to Riley's standard |
| Week 5–6 | Gradual lift to 80% if Riley feels ready | Weekly check-in, Riley decides |
| Week 7–8 | Full capacity if sustained | Joint review at the end of week 8 |

**Clear expectations during the plan:**

1. Meet the adjusted 70% sprint commitment
2. Attend all required meetings, or let me know in advance if you cannot
3. Deliver code at the quality level we both know Riley is capable of

These are lower than the team baseline on purpose. This is not a performance improvement plan in the formal sense. It is a support plan, and I will document it that way with HR.

### Path forward

**Review checkpoint:** 8 weeks from today. At that point we sit down and look at the data together. If the pattern has stabilised, we move Riley back to normal load and the rating resets in H2. If things are still difficult, we talk about longer-term options together — including extended leave if that is what is needed.

### What I want Riley to hear

Riley, if this document gets read cold, I want the last thing to be this: I am not writing this review to punish you. I am writing it because it is my job to be honest, and because I believe you can come back from this period stronger. You have my full support, and this plan is here to take pressure off, not add it. We will get through this together.
