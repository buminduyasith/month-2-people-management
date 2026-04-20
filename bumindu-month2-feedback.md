# Feedback Practice — SBI + Request

All six scenarios below use the **SBI + Request** framework: Situation, Behavior, Impact, Request. SBI keeps feedback specific and grounded in what I actually saw, rather than in opinions or labels. The Request line turns the feedback into a conversation and gives the other person a clear next step.

The five short scenarios come first. The third scenario — Riley — is a difficult conversation, so I have expanded it into a full script with anticipated reactions and a clear path forward. That is where the real craft of people management shows up, and I wanted to think it through properly rather than just write four lines.

---

## Scenario 1 — Positive feedback: Jordan catching a security flaw

**Situation:**
"In yesterday's code review for the payment service pull request..."

**Behavior:**
"...you spotted a validation gap in how we handled the currency field. None of the rest of us had caught it, and it would have allowed a malformed request through to the ledger."

**Impact:**
"That single comment prevented a bug that could have hit production. More than that, it showed real growth in how you are thinking about security — a few months ago you would not have looked for that."

**Request:**
"I would love for you to walk the team through your thought process at our next team meeting. A five-minute share. It would help others learn the pattern, and honestly, it would help you see how much you have grown."

**Why this works:** specific PR, specific flaw, real impact named, and the request is both generous (recognition in front of the team) and developmental (practice sharing).

---

## Scenario 2 — Constructive feedback: Sam's comfort zone

**Situation:**
"Over the past quarter, especially when we were assigning work for the Kubernetes migration and the new observability stack..."

**Behavior:**
"...I noticed you consistently picked up familiar tasks around the legacy services, and when I floated the migration work you mentioned you were happy to stay where you were."

**Impact:**
"Your work on the legacy services is high quality, and I appreciate that. But two things worry me. One, the team needs more people who understand the new stack, and right now only Alex really does. Two, and I say this because I care — staying only with what you know makes the next career step harder, and I want that step to be available to you."

**Request:**
"For next quarter, I would like you to take the lead on one thing outside your comfort zone. Not alone — I will pair you with Alex for the first month. Can we sit down together this week and pick which project feels most interesting?"

**Why this works:** no labels ("lazy," "stuck"), honest about the team need and the personal cost, and the request is concrete and supported.

---

## Scenario 3 — Difficult feedback: Riley's missed commitments

### This one is a full script

Riley's situation needs a real, planned conversation, not a hallway comment. Below is the full script — the short SBI version up front, then the difficult conversation script that I would actually use in the meeting room.

### Short version (for reference)

**Situation:**
"Over the past month, specifically on the checkout service sprint and the auth service docs..."

**Behavior:**
"...two commitments slipped, three P2 bugs came through in the delivered code, and the documentation we agreed on did not land."

**Impact:**
"The team has been quietly covering the gaps, stakeholders are starting to ask questions, and I know this is not the work you are capable of."

**Request:**
"I want to support you through whatever is going on. Can we sit down this week — not in a 1:1 slot, in a proper meeting — and figure out what a sustainable plan looks like for you right now?"

### Full difficult conversation script

#### Situation context

**What is happening:**
Riley's delivery has been off for about two months. Missed commitments, a few more bugs than Riley's usual standard, and communication gaps with a stakeholder who has now raised it to me twice. In our 1:1s, Riley has hinted at a personal situation but has not asked for any adjustment.

**What is at stake:**
Three things. First, Riley — as a person and a teammate I care about. Second, the team, which is covering the gap without complaining but will eventually burn out if it continues. Third, Riley's standing, which will start to get damaged in the wider org if this runs much longer without a plan.

**Why I am choosing to have this conversation now, not later:**
Waiting is not kind. Waiting feels like kindness in the moment but becomes unkind later, when the gap has grown and it is harder to come back from. The earlier I have this conversation, the more options we both have.

**Setup I will use:**
- A private meeting room, not my desk
- 60 minutes on the calendar so we are not rushed
- Title the invite something neutral like "Check-in and planning" — nothing alarming
- Send a short note the day before: "I want to talk about how you are doing and how I can support you. Nothing to worry about going in — I just want us to have space to talk properly."

#### Key messages I need to deliver

I will boil this down to three clear messages, and I will not leave the room until Riley has heard them.

1. **"I have noticed a change, and I am concerned about you — not about your job."**
   This comes first. Everything else depends on Riley hearing that I am in their corner.

2. **"Here is what I am seeing, specifically, and here is the impact."**
   I will name the missed commitments, the bug rate, and the missed meetings. Specifically. No vague language. The evidence makes the conversation honest.

3. **"We need a plan together. I have some ideas, but this has to be something you agree to, not something I impose."**
   This puts Riley in the driver's seat on the solution, even though I have led us into the conversation.

#### Anticipated responses and how I will handle them

I have thought through four likely reactions. I want to be ready for any of them, not caught off guard.

**Reaction A — Defensive:** "I am doing my best. The bugs were edge cases. The missed meetings were unavoidable."

My response: I slow down. I do not argue about any single incident.
"I hear you, and I believe you are doing your best. I am not here to argue about any one bug or any one meeting. I am here because I am seeing a pattern, and patterns tell me something is harder right now than it usually is. Can we talk about what has been making things harder?"

**Reaction B — Emotional:** Riley tears up or gets very quiet.

My response: I stop pushing forward. I pass the tissues. I say nothing for a moment.
"Take your time. There is no rush here. We have as much time as you need."

If Riley wants to stop the meeting, I offer that. "If you want to pause this and come back to it tomorrow, that is fine. No consequences, no notes. Just tell me what helps."

**Reaction C — Shutdown:** Riley goes silent and will not engage.

My response: I do not fill the silence with words. I wait. If the silence goes past a minute, I try one gentle prompt:
"I am not going to push. But I do want you to know that what you tell me in this room stays in this room unless you say otherwise. And if you would rather not talk about the personal side, that is completely okay — we can focus only on the work side."

If shutdown continues, I wrap the meeting with: "I am going to take this as a signal that today is not the day. Let's meet again in two days. In the meantime, I am adjusting your sprint load to 70% so you have some air."

**Reaction D — Opens up about the personal situation:**

My response: I listen. I do not try to fix it. I do not offer advice unless asked. I thank Riley for trusting me.
"Thank you for telling me. That takes a lot. I am not going to pretend I have answers to any of this, and I do not want to. What I can do is make work one less pressure while you handle the rest. Here is what I am proposing, and I want your honest reaction..."

Then I walk into the support plan (workload reduction, flexible hours, EAP, weekly 1:1s).

#### Desired outcomes

**For Riley:**
- Feels safe, not judged
- Leaves the room with a concrete plan that has less pressure, not more
- Knows the support is real — including EAP, flexible hours, and reduced scope
- Knows I am a safe person to come back to if anything changes

**For the team:**
- Riley's workload gets formally redistributed so nobody else burns out quietly
- The team sees that when someone is struggling, the response is care, not punishment
- Stakeholders get a clear (and private) answer from me on timeline expectations

**For me as manager:**
- I have done the honest thing, early
- I have documented the plan so that if HR involvement becomes needed later, there is a paper trail that shows support came first
- I have set a clear 8-week checkpoint so this does not drift

#### Follow-up actions

Within 24 hours of the meeting:

- [ ] Send Riley a short written summary of what we agreed, in plain language, so nothing gets lost
- [ ] Update the sprint plan to reflect the 70% capacity
- [ ] Quietly redistribute the auth service on-call to Morgan for the next 8 weeks
- [ ] Message the EAP contact details to Riley directly, no pressure
- [ ] Let HR know I am running a support plan (not a PIP), so they are aware if I need advice later

Within the first week:

- [ ] First of the new weekly 1:1s
- [ ] Low-pressure check-in message mid-week: "Thinking of you. No response needed."

At week 4:
- [ ] Mid-point check: is the plan working? Does Riley need it adjusted?

At week 8:
- [ ] Formal review together, same room, same calm tone. Decide what happens next based on what we both see.

#### What I want to avoid

- I will not turn this into a lecture
- I will not compare Riley to other team members
- I will not promise things I cannot deliver
- I will not ask Riley to explain the personal situation in detail
- I will not leave the room without a clear next step

---

## Scenario 4 — Peer conflict: Morgan and Alex

**Situation:**
"In last Thursday's architecture review for the notification service..."

**Behavior:**
"...when Alex challenged the approach, I noticed both of you raised your voices, and there was a moment where you were talking over each other. The rest of the room went quiet."

**Impact:**
"Two things happened. One, we did not actually reach a decision in that meeting, which slowed the work by a week. Two, I watched Casey and Jordan visibly lean back in their chairs — they were not comfortable, and we lost their input for the rest of the meeting."

**Request:**
"I do not want to dampen the debate — strong opinions are a good thing. What I would like from both of you is a way to disagree that keeps the room open. Can the three of us sit down for 20 minutes this week, figure out what happened, and agree on how we handle the next one?"

**Why this works:** I am not taking sides, I am naming the impact on the quieter people in the room, and I am asking for a joint solution instead of issuing a rule.

---

## Scenario 5 — Growth opportunity: Casey

**Situation:**
"In your work on the notification service this sprint..."

**Behavior:**
"...you asked good questions in standups, and you paired with Morgan on two tickets, but every line of code that got merged under your name was written in a pairing session. You did not ship anything on your own."

**Impact:**
"Pairing is great for learning, and I am glad you are doing it. But you also need reps of 'figured it out on my own' — that is where confidence comes from, and it is what I will be looking for when we talk about your next role."

**Request:**
"For next sprint, I would like to give you one small ticket that is entirely yours. I will not pair you on it, but I will be available if you get stuck. Let's pick something this Friday that feels achievable but a bit of a stretch. What kind of work would you enjoy trying solo?"

**Why this works:** honest about the gap without making Casey feel bad about pairing, and the request is immediate, concrete, and gives Casey a say in what the solo ticket is.

---

## Scenario 6 — Recognition: Morgan

**Situation:**
"Throughout this quarter, especially during the March release crunch and the week after Riley's load got adjusted..."

**Behavior:**
"...you have quietly picked up extra review load, stayed late to help Jordan debug the caching issue, and took on the on-call rotation I asked you to cover without a word of complaint. You also made a point of checking in on Casey after Casey's first solo production push — I heard that from Casey directly."

**Impact:**
"You are the reason this team feels like a team right now. The individual things are small, but together they are huge. When someone is having a rough week, they look for you, and you show up. That is culture, and culture is the hardest thing in a team to build."

**Request:**
"Two things. First, I am going to name this specifically in our next team meeting, because public recognition matters and you deserve it. Second, I would like to talk with you about how we can make this kind of care visible in the performance review cycle — not as a one-off thank you, but as something that counts. Can we carve out 30 minutes in next week's 1:1 to talk about that?"

**Why this works:** specific examples, names the invisible work, and the request is not just "say thanks" — it is about making sure the work Morgan does gets real credit.
