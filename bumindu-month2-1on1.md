# 1:1 Meeting Templates and Team Context

## Author's Note

Before I wrote these 1:1 templates, I spent two weeks listening to the team and pulling together a short team health snapshot. I wanted the templates to reflect what the team actually needs right now, not a generic "manager best practice" document. The snapshot comes first, then the templates follow.

---

## Part 1 — Team Health Snapshot

### Why I did this first

When I took over this team of 6 engineers, I noticed a few things right away. Morgan kept the team glued together. Alex was hungry for more. Riley was quiet in a way that worried me. Before I started running 1:1s, I wanted a fuller picture so I could walk into those meetings with real questions, not surface ones.

### Methodology

I used three sources so the findings would not rest on one opinion:

1. **Anonymous pulse survey** — 10 short questions, sent on a Monday morning, closed Friday. 6 out of 6 responded. Questions covered workload, clarity of goals, feeling supported, psychological safety, growth, and a free-text "what would you change tomorrow?" box.
2. **1:1 notes review** — I read the last 3 months of notes from the previous tech lead and pulled the topics that came up more than twice.
3. **Retro themes** — I went through the last 2 sprint retros and listed every action item that was raised but not closed.

No single source gets the full picture, so I triangulated between the three.

### Key findings

| Metric | Result | Notes |
|---|---|---|
| eNPS | +33 | Healthy, but Riley's score was the outlier pulling the average down |
| "I feel supported" | 5/6 agreed | Riley chose "neutral" |
| "Goals are clear" | 4/6 agreed | Jordan and Casey flagged confusion on scope |
| "I have room to grow" | 3/6 agreed | Sam and Riley chose "neutral"; interesting pattern |
| On-call load | 1.8 incidents / week avg | Skewed — Alex and Morgan carry most of it |
| Deploy frequency | 4.2 / week | Above our target of 3 |
| Retro items closed | 6 of 11 | Action follow-through is the biggest gap |

### Strengths to protect

1. **Collaboration is real, not performative.** Morgan lifts the room every time, and people pair naturally. This is not something I want to push on — it is already working.
2. **Alex's mentoring of Casey.** Casey's first three PRs had detailed, patient review comments from Alex. That is why Casey is learning so fast.
3. **Deploy cadence is healthy.** 4.2 deploys per week with a low revert rate means the technical foundation is in good shape.

### Areas to improve

1. **Riley's load is not sustainable.** Riley is quietly carrying ownership of the auth service while dealing with something personal. This needs a real conversation and a workload adjustment, not a pep talk.
2. **Sam has stopped stretching.** Sam has been on the team for 5 years and has not picked up a new area in the last 6 months. The comfort-zone pattern hurts both Sam's growth and the team's resilience (only Sam knows certain legacy pieces).
3. **Jordan's confidence lags Jordan's ability.** Jordan is more capable than Jordan believes. The "goals are clear" score hints that scope ambiguity is making Jordan second-guess work.

### Action plan

| Action | Owner | By when | How we measure it |
|---|---|---|---|
| Rebalance on-call so Alex and Morgan each drop 1 week / month | Me | End of month | On-call roster updated |
| Move Riley to 70% load, weekly 1:1s, loop in EAP offer | Me | Within 1 week | Workload doc agreed with Riley |
| Give Sam the Kubernetes migration as a stretch project | Me + Sam | Start of next sprint | Sam owns project kickoff doc |
| Close 5 of the 6 open retro items | Whole team (I track) | End of sprint | Retro tracker green |
| Run a scope-clarity workshop for Jordan and Casey | Me | Within 2 weeks | Jordan and Casey rate clarity 4+/5 |

### Follow-up cadence

- Monthly 5-question pulse (same questions each time, so we can track the trend)
- Quarterly deep-dive retro with the full team
- I revisit this snapshot in 90 days and write a short "what changed" note

---

## Part 2 — Standard 1:1 Meeting Template

### Before the meeting (my prep, 10 minutes)

- [ ] Read the notes from our last 1:1
- [ ] Check which action items from last time are still open
- [ ] Note 1 or 2 specific things I have observed this week (good or bad)
- [ ] Check the person's recent PRs, tickets, or any Slack context I should know
- [ ] Remind myself: this is their time, not my status meeting

### The meeting (30 minutes)

**1. Opening (3 min)** — the human check-in
- "How are you doing this week, honestly?"
- I do not skip this. If they say "fine" with a tone that is not fine, I slow down.

**2. Their agenda (15 min)** — the biggest block
- "What is on your mind? What do you want to talk about today?"
- I take notes while they talk. I do not interrupt.
- If they have nothing, I have 2 open questions ready: "What has been frustrating this week?" and "What has felt good?"

**3. My topics (7 min)** — specific feedback and updates
- One piece of concrete feedback, good or constructive, with an example
- Any team news they need to hear from me first
- Never more than 2 or 3 items — this block is short on purpose

**4. Close (5 min)** — action items and next steps
- We say the action items out loud so we both hear them
- "Is there anything you wanted to bring up that we did not get to?"
- Confirm the next 1:1 date

### After the meeting (my follow-up, 5 minutes)

- [ ] Write up the notes while they are fresh
- [ ] Send the action items in a short message so nothing is lost
- [ ] Put anything sensitive in a private note, not the shared doc
- [ ] Schedule any follow-up I promised

---

## Part 3 — Customised Templates

Each team member needs a different focus in 1:1s. Below are three customised templates for the people where the generic version will not work.

### Template A — Alex (Aspiring Tech Lead)

**Focus:** leadership growth, stretch opportunities, visibility with stakeholders.

Alex is a strong engineer who wants more. Our 1:1s should be about finding the next stretch, not reviewing day-to-day work.

**Questions I rotate through:**
- "What is one leadership moment this week that felt good? What made it work?"
- "Where did you feel out of your depth? That is the gold — let's unpack it."
- "Which stakeholder do you want more exposure to, and how can I open that door?"
- "What feedback have you heard about yourself lately — from anyone, not just me?"

**Topics we come back to every month:**
- The Tech Lead competency map and where Alex is on it
- Mentoring progress with Casey
- A running list of stretch opportunities for Alex to choose from

**Action bias:** every 1:1 should end with Alex committing to one thing that scares them a little.

### Template B — Jordan (Developing, Low Confidence)

**Focus:** confidence, clarity, small wins, learning support.

Jordan is capable but second-guesses the work. 1:1s should feel safe and give Jordan room to name what is hard.

**Questions I rotate through:**
- "What is one thing you figured out this week that you are proud of?"
- "Where are you stuck right now? What does the stuck feel like?"
- "Is there a task you would love to try but have not volunteered for?"
- "Who on the team is a good person to learn from for this area?"

**Topics we come back to:**
- Learning goals for the quarter
- Pairing schedule with Alex or Morgan
- Scope clarity on current tickets

**Action bias:** every 1:1 should end with one small, achievable win Jordan can hit before next time. Small wins build the confidence Jordan is missing.

### Template C — Riley (Underperforming, Personal Situation)

**Focus:** care, honesty, realistic expectations, support.

Riley is going through something personal that is affecting work. My job is not to fix Riley. My job is to keep Riley safe and give Riley a path back. The templates above would feel tone-deaf here.

**Ground rules I hold for myself in these meetings:**
- Start with the person, not the work
- Ask, do not tell
- Silence is fine
- Do not push for solutions unless Riley wants them
- Never bring up performance numbers in the opening

**Questions I rotate through:**
- "How are you doing, really?"
- "What feels most manageable right now? What feels too heavy?"
- "Is there anything I can take off your plate this week?"
- "What kind of support would actually help — from me, from the team, or from outside work?"

**Topics that belong in these 1:1s:**
- Current workload and what is realistic this week (not this quarter — this week)
- Support resources, including EAP, flexible hours, and reduced scope
- A gentle check on how the agreed workload adjustments are landing

**What does NOT belong in these 1:1s:**
- Long-term performance concerns (those belong in a separate, planned conversation — see the difficult conversation script in file 3)
- Pressure to produce more
- Comparisons with other team members

**Action bias:** every 1:1 ends with Riley clear on what is expected this week and clear that I am in their corner.

---

## Part 4 — A Real 1:1 Example

### Alex — Week 1

**Date:** Monday morning, 30 minutes
**Location:** quiet corner room, not my desk

**Their topics:**
- Wants to lead the upcoming database migration project
- Frustrated that the promotion timeline is not clear
- Feels Casey is progressing well and asked if the mentoring has been formally noticed

**Discussion:**

Alex opened with the migration project. I listened for 5 minutes before saying anything. Alex laid out a clear plan for scoping the work and wanted to know if I would support them leading it. I said yes, with one condition: Alex needs to bring Jordan into the project as a paired contributor, not as a helper, so Jordan gets exposure to the architecture.

On promotion, I was honest. I said the formal decision sits with skip-level and we have a review cycle in Q3. I also said that Alex is clearly ready on the technical side, and the thing that will tip the decision is visible stakeholder-facing work. We agreed Alex would lead the next cross-team sync with Product as the first step.

On the mentoring of Casey, I thanked Alex specifically — I had read the PR comments Alex left and they were thoughtful. I told Alex I would name this contribution in the next team meeting so it is publicly recognised.

**Action items:**
- [ ] Me: Share the Tech Lead competency doc by end of Tuesday
- [ ] Me: Get Alex an intro to the Product Manager, Priya, before Friday
- [ ] Alex: Draft a 1-page plan for the database migration, including how Jordan is involved
- [ ] Alex: Lead the next cross-team sync (date: 2 weeks from now)

**Follow-up for next 1:1:**
- Check how the intro with Priya went
- Review the migration plan draft
- Revisit the promotion timeline question in 6 weeks with more concrete signals

**Private note (not shared with Alex):**
Alex's frustration on promotion is reasonable. I should talk to skip-level in the next two weeks so I am not caught off-guard if Alex pushes harder. I also want to make sure Alex's involvement with Casey is visible in the next performance cycle — right now it lives in PR comments, and that is invisible to anyone who is not looking.
