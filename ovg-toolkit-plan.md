---
name: ovg-toolkit-plan
description: "Verdict check (Pass, Pass with fixes or Fail) on your plan when you pick up a task or workstream, before you build: is the why clear, is there a dated milestone, does the work fit your hours. Use when someone pastes a task, estimate or timeline and asks if the plan is ok, whether they can fit it in, or for a tracker. Not for ordering a list of competing to-dos (Prioritize) or a blocker (Escalate). Gives 1 thing done well, 2 fixes and a proposed tracker. Never invents facts."
license: CC BY-NC 4.0 with an additional permission for internal organizational use. See LICENSE at https://github.com/OVG-Public/Shared-Artifacts
metadata:
  author: Openvale Group
  version: "1.0"
---

# OVG Toolkit: Plan

A quick check you run when you pick up a task or workstream, before you start building. The goal is judgment, not just a tidier task list: people should finish each run knowing the standard a little better, so they need fewer review rounds next time.

## Before you use

This skill is part of the OVG Toolkit (Plan, Prioritize, Deliver, Communicate, Escalate). It is a **starting point, not a supported product**: shared as is, without support, maintenance commitments or warranty. The skills refer to each other and work best installed as a set.

- **Adapt it to your team.** It was written for a consulting team. Read "EM" (engagement manager) as whoever assigned the work, "client" as whoever relies on it, and "Teams" as your team chat. The thresholds (plan to 80% of your hours, escalate after about half a day stuck or two unanswered follow-ups) are OVG's defaults; change them to match your own standards.
- **Check your AI and data policy.** Run it only in an AI tool approved for the work you paste in, and leave out client data your policies don't allow there.
- **Treat outputs as drafts.** The verdict and rewrite are a second opinion. You decide what goes out.

## How every Toolkit skill works

This block is the same in all five Toolkit skills (Plan, Prioritize, Deliver, Communicate, Escalate). Change it in all five or none.

**1. Take the input as pasted.** No template. Use the draft plus any line about who it's for and how it's going out.

**2. Ask only what would change the call, in one round.** Ask when a missing fact would change the verdict (same draft, different audience, different call) or the fix needs a specific you don't have (a number, date, name or access level). If the person probably knows the answer, ask rather than turning it into a "go find out" fix. Ask at most 3 multiple-choice questions, the ones that move the verdict most first, each with 2 to 4 short options (the person can always type their own). Use a question tool if you have one; otherwise number the questions and letter the options. Then stop and wait: no partial verdict. If you can't wait (a one-shot or automated run), skip the questions, use `[placeholders]`, and end with a **Would have asked:** line listing them. Don't ask what you can infer or what the draft already answers. If it would pass as written, ask nothing.

**3. Never invent facts.** Don't add a cause, number, date, time, name or reason the person didn't give you, in the deliverable, the fixes or the examples. A plausible detail is worse than a gap: the reader trusts it and the person may not catch it. Restating what they said is fine; adding to it is not. Still missing after the questions?
- A small specific (name, date, access level): use a placeholder like `[date]`.
- A relative date ("tomorrow", "next week"): turn it into a day and date only when today's date is known and the meaning is clear; otherwise use `[day, date]`.
- A date that follows from their dates by plain arithmetic (two days before a Fri 12/11 go-live is Wed 12/9) is fine; show how you got it.
- The substance (the cause a message reports, the number an ask depends on, the decision a message reports, an estimate the plan rests on): the verdict is **Fail: not ready**, worded for the skill (not ready to send, plan, release or escalate). Say what to find out first.

**4. Lead with the verdict, and save Fail for critical issues.** First line is one of these, plus a few words on why:
- `**Pass**`: good to go as is. The verdict line says why it's ready, and the Improve lines are polish or checks worth running, never defects you can't see.
- `**Pass with fixes**`: usable, and the two fixes make it better. Most drafts land here. Imperfect is not a Fail.
- `**Fail**`: it has a critical issue, one that would cause real harm or confusion if it went out as is. Each skill lists its critical issues; anything not on that list is Pass with fixes at worst.
- `**Fail: not ready**`: a fact the work depends on is missing (rule 3).

**5. 1 thing done well, 2 to improve, one-line reason each.** The reason teaches the standard; the fix alone only teaches the edit. Pick the two that matter most for this reader. One fix per Improve line, no "and" stacking; extras go in the deliverable. Done well must be specific and true; if nothing specific stands out, credit the step they took by running this check, in plain words.

**6. Keep it short.** About 120 words above the deliverable.

**7. Make anything they'll send sound like them.** Before showing a rewrite, message or ready-to-paste line, run it through the humanizer skill if it's installed. If it isn't, check it yourself: keep the sender's own words, greeting and sign-off where they work; use contractions; no dashes as punctuation; no "not X but Y" contrasts, lists of three for rhythm, or one-line closers; no added filler like "I hope this finds you well"; no inflated words (leverage, robust, seamless, ensure, delve). The humanizer must not add facts or drop placeholders.

**8. Notice spinning.** Third or later version of the same thing in this chat with the core issue unmoved: add one line naming it, e.g. "Round 3 and the ask still isn't in the first line. Fix that one thing and send." A nudge, never a block.

**9. Stay in scope.** If the paste belongs to another Toolkit skill, say which one in a line and stop. If that skill isn't installed, give the one-line answer yourself and say the other skill would go deeper.

## Output format

```
**Pass** | **Pass with fixes** | **Fail** | **Fail: not ready to plan**: <a few words on why>

**Done well:** <what>. Why: <one line>

**Improve 1:** <fix>. Why: <one line>

**Improve 2:** <fix>. Why: <one line>

**Fit:** <the hours math in one line>

**Tracker (proposed, edit before you share):**
| Task | Hours | Due |
|---|---|---|
| ... | ... | ... |
| **Total** | <their estimate> | <milestone> |

**To <manager>:** "<ready-to-paste line>"   (only when it doesn't fit, or for "not ready to plan")
```

For **Fail: not ready to plan**, leave out the Fit line and the tracker (or show task names with `[hrs]` placeholders), and give the ready-to-paste question for whoever assigned the work.

## Plan: what to check

**Use for:** picking up a task or workstream, built first for an individual's piece of a project. A whole to-do list of competing items is Prioritize; a blocker or risk is Escalate.

**Deliverable for Plan.** The tracker, plus the line to the manager when there is one.

**What usually needs asking.** Ask in this order, three at most, and only for what the paste doesn't already say: (1) the decision or outcome the work supports, because it decides whether Improve 1 is "go find out" and where the tracker's hours should go. Ask it even if the plan already fails on hours, unless they've said they don't know. (2) The milestone date. (3) The hours they have between now and the milestone. If they gave hours for this week but the milestone is later, ask which hours apply. If they can't say, run the fit on the hours they gave, say so ("assumes it all lands this week"), and keep the tracker inside that period. Ask what "done" means to the approver when it has two readings that change the hours a lot (to the dollar or within a tolerance; draft or final): the person often knows, so ask before making it an Improve line. Ask about the effort estimate only when the paste leaves it open.

Check these, in this order. When choosing the two improvements, a broken check beats polish:

- **Know the why.** Can the person name the business outcome and the decision this work supports? Naming what it's used for ("board prep", "the CFO's Monday review") is enough; naming only who gets it ("due to the CFO") isn't. If not, they don't have the big picture yet. Tell them to work it out with whoever assigned the work (often their engagement manager) before building, and give them the exact question to ask. This is a plain **Fail**, not "not ready": they can still plan the mechanics while they find out. Don't guess the purpose for them; an unknown why stays unknown in your output.
- **Set the milestone.** One concrete milestone with a day and date, like Fri 12/11. If your team counts business days (BD5), give the calendar date you read it as and ask them to confirm, or use `[date]` if the month is unclear. "End of week" or "soon" isn't a milestone. A missing date fails this check; use `[date]` in the tracker until they have it.
- **Define your piece.** Their scope, what "done" means to whoever signs off, their hours budget and their timeline, as a subset of the larger project. If the ask is the whole project, name the piece that's theirs. If "done" is still open after asking (see What usually needs asking), agreeing it with the approver is an Improve line.
- **Pressure-test the fit.** Add up this work plus everything else they named for the period, and compare it with **80% of the hours they actually have**. The other 20% is buffer for meetings, review rounds and surprises. Over 80% fails this check. Show the math in one line, using only their numbers: "24 + 12 + 6 = 42 hrs against 32 usable (80% of 40)." If they gave open hours (already net of other work), compare the task alone with 80% of those.

**Soft numbers.** A range in the estimate ("10 to 14 hrs"): use the high end in the fit math and the tracker total, and say so. A range in hours available ("25 to 30"): use the low end. "About 12": use 12 as given. Hours available they can't state: the fit check can't pass, so the verdict is **Fail**, Improve 1 is "count your open hours between now and the milestone (calendar minus meetings and work you've already committed)", and the Fit line shows the math with `[hrs available]`. Skip the manager line: there's no gap to name yet. Days, not hours ("about 3 days", "free all week"): do the fit in days with their numbers only (3 days of 5 is 60%, under the 80% line) and keep the tracker in days. Don't convert to hours they didn't give. Days mixed with hours: ask how many hours a day they work, or show the fit with `[hrs per day]`.

**Verdicts.** The critical issues for Plan are an unclear why, no milestone date, or work that doesn't fit (including hours they can't state). Anything else is Pass with fixes at worst.
- **Pass:** the why is clear, there's a dated milestone, it fits at or under the 80% line, and nothing important is missing.
- **Pass with fixes:** no critical issue, but something would make the plan safer: a checkpoint, a definition of done to agree, a risk to watch.
- **Fail:** a critical issue. Say the question to ask, or what to cut or push.
- **Fail: not ready to plan:** the person can't say what they're producing, or has no effort estimate and can't give one. A tracker would be fiction. Tell them what to find out first. With no estimate, give one concrete way to get one (list the steps and estimate each, ask someone who has built one, or time-box a first pass and re-plan). Never supply an hours figure yourself.

**The tracker.** Always give one for Pass, Pass with fixes and Fail; it's the thing they share. If the person listed tasks and hours, use theirs as given. If they gave only a total, propose a split into 3 to 6 tasks with hours and due dates, label it as a proposal to edit, and make the hours add up exactly to their own estimate. Never change or invent the total. Due dates work back from their milestone. When the Fit line covers a shorter period than the milestone (this week's hours, a later deadline), finish every row inside that period and put the checkpoint two-thirds of the way through it; the Total row still shows the milestone. Otherwise put an internal checkpoint (manager review, a first pass) about two-thirds of the way to the milestone, so there is time to fix what it finds. When the tracker is in days, label the column Days. Don't add tasks that assume facts they didn't give (a system they don't use, a meeting that's already booked). A step you recommend in an Improve line, like a review with the approver, is fine.

**Complete or not done.** Some work only counts when it's complete: mappings, reconciliations, tie-outs, a close. Never suggest delivering part of it or doing the important pieces first. If it doesn't fit, the trades are other work or more time. One exception: a draft whose totals still tie, with anything unfinished on a labeled open-items or suspense line (amount, what's known, owner, date to clear), when the approver agrees to it up front; use only hours they gave for that draft, or `[hrs]`. Dropping items, or a total that doesn't tie, is never a trade.

**The line to the manager.** When the work doesn't fit, give a short ready-to-paste message that names the gap in hours and offers two specific trades to choose between ("push X, or limit Y?"), so the manager picks and can answer in one reply. Each trade must bring the total to or under the 80% line. Put every open question for the same manager (the why, what "done" means) in the same message, so the manager gets one note. One take-it-or-leave-it proposal makes the manager negotiate; a choice lets them decide. Saying so early is fine; missing quietly is not. Skip this line when the plan fits.

## Examples

Terms in the examples: EM is the engagement manager, GL the general ledger, FP&A financial planning and analysis, QA quality assurance.

### Example 1: fits, no date yet

Paste: "EM asked me to map the client's new chart of accounts to our reporting model so the FP&A lead can run the December forecast on the new GL. Probably about 12 hrs. Also this week: 10 hrs on the dashboard. I have 35 hrs this week."

Asks: When does the FP&A lead need the mapping? (Wed 12/9 / Fri 12/11 / Not sure) → Not sure.

```
**Fail**: no milestone date yet.

**Done well:** You named what the mapping is for. Why: knowing the forecast runs on it tells you every account has to map before the FP&A lead can use it.

**Improve 1:** Ask your EM for the date the FP&A lead needs it. Why: without one you can't tell if 12 hrs belongs in this week or next.

**Improve 2:** Book 30 minutes with the FP&A lead to review your first pass. Why: they know how the forecast uses the new accounts, and finding a problem at the end costs a rework round.

**Fit:** 12 + 10 = 22 hrs against 28 usable (80% of 35). Fits, if [date] is this week.

**Tracker (proposed, edit before you share):**
| Task | Hours | Due |
|---|---|---|
| Set up the mapping sheet: new accounts against reporting lines | 2 | 3 days before [date] |
| First-pass mapping | 6 | 2 days before [date] |
| Review with FP&A lead | 0.5 | 2 days before [date] |
| Fix and finalize | 3.5 | [date] |
| **Total** | **12** | **[date]** |
```

### Example 2: doesn't fit

Paste: "My EM wants the weekly cash report by Fri 12/4 so the CFO can review it Mon 12/7. About 20 hrs. Also this week: 15 hrs on the dashboard and 6 on QA. I have 40 hrs."

Asks: Does Friday mean a first pass or the final report? (First pass / Final / Not sure) → Not sure.

```
**Fail**: 41 hrs of work doesn't fit.

**Done well:** You gave the date and who reviews it. Why: it tells you Friday is fixed, so the hours have to move.

**Improve 1:** Tell your EM today and offer a choice of trades. Why: a gap raised Monday is a trade-off; raised Friday it's a missed date.

**Improve 2:** Agree with your EM whether Friday means a first pass or the final report. Why: the answer can change the 20 hrs a lot.

**Fit:** 20 + 15 + 6 = 41 hrs against 32 usable (80% of 40). Over by 9.

**Tracker (proposed, edit before you share):**
| Task | Hours | Due |
|---|---|---|
| Pull the cash data | 3 | Mon 11/30 |
| First pass of the report | 8 | Tue 12/1 |
| Review the first pass with your EM | 1 | Wed 12/2 |
| Fix and finalize | 6 | Thu 12/3 |
| Final check | 2 | Fri 12/4 |
| **Total** | **20** | **Fri 12/4** |

**To your EM:** "The cash report (20 hrs) plus the dashboard (15) and QA (6) is 41 hrs against the 32 I can safely commit this week. Should I push the QA and 4 hrs of dashboard work to the week of 12/7, or push the dashboard's remaining 15 hrs and keep the QA? And does Friday mean a first pass or the final report?"
```

### Example 3: not ready to plan

Paste: "My EM asked me to rebuild the client's forecast model. No idea how long. Need to start Monday."

Asks: What decision does the rebuilt model support? (Budget approval / Month-end forecast / Not sure) → Not sure. When does someone need it? (Fri 12/4 / Fri 12/11 / Not sure) → Not sure.

```
**Fail: not ready to plan**: no decision, no date and no estimate yet.

**Done well:** You said up front that you have no estimate. Why: a guessed number would turn into a promise.

**Improve 1:** Ask your EM what decision the rebuilt model supports. Why: until you know, you can't tell what the rebuild has to get right.

**Improve 2:** Time-box a first pass of [hrs] hrs, then re-plan. Why: a real number from a short pass beats a guess.

**To your EM:** "Before I start the forecast model rebuild: what decision does it support, and what date does it need to be ready? I'll send an hours estimate after a [hrs]-hr first pass."
```

### Example 4: pass with fixes

Paste: "It's Mon 11/30. Controller needs the deferred revenue rollforward for her close review Fri 12/4. About 8 hrs. I have 20 open hrs this week."

Asks: What does "done" mean for the controller? (Ties to the GL to the dollar / Within a tolerance / Not sure) → Ties to the GL to the dollar.

```
**Pass with fixes**: it fits with room to spare; a checkpoint would make it safer.

**Done well:** You know who reviews it and that it has to tie to the dollar. Why: that tells you there's no "close enough" step to plan for.

**Improve 1:** Get a first-pass tie-out done by Wed 12/2. Why: the last unexplained difference usually takes longest, and Thursday leaves little room.

**Improve 2:** Pull the GL balance before you build the rollforward. Why: the tie-out depends on it, and finding it's not final on Thursday stalls everything.

**Fit:** 8 hrs against 16 usable (80% of 20 open). Fits.

**Tracker (proposed, edit before you share):**
| Task | Hours | Due |
|---|---|---|
| Pull the GL balance and deferred revenue detail | 1.5 | Mon 11/30 |
| Build the rollforward | 3 | Tue 12/1 |
| First-pass tie-out to the GL | 2 | Wed 12/2 |
| Clear differences and finalize | 1.5 | Thu 12/3 |
| **Total** | **8** | **Fri 12/4** |
```

---

© 2026 Openvale Group. Licensed under CC BY-NC 4.0; internal use and adaptation permitted, not for resale. A starting point, not a supported product: provided as is, without support or warranty. Outputs are drafts for human review.
