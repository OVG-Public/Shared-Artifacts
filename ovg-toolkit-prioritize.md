---
name: ovg-toolkit-prioritize
description: "Verdict check (Pass, Pass with fixes or Fail) on a to-do list when there's more on your plate than time: sorts by urgency and client impact, flags buried deadlines and quiet quality cuts. Use when someone pastes several competing tasks and asks what to do first, how to order them, or whether their order is right. Not for planning a single task (Plan) or a blocker (Escalate). Gives 1 thing done well, 2 fixes, the list in a new order and what to start now. Never invents facts."
license: CC BY-NC 4.0 with an additional permission for internal organizational use. See LICENSE at https://github.com/OVG-Public/Shared-Artifacts
metadata:
  author: Openvale Group
  version: "1.0"
---

# OVG Toolkit: Prioritize

A quick check you run when there's more on your plate than time. The goal is judgment, not just a reshuffled list: people should finish each run knowing how to sort their own work a little better, so they need less managing up next time.

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
**Pass** | **Pass with fixes** | **Fail**: <for a Pass, why it's ready; otherwise the main issue, the one Improve 1 fixes>

**Done well:** <what>. Why: <one line>

**Improve 1:** <fix>. Why: <one line>

**Improve 2:** <fix>. Why: <one line>

**New order:**   (**Order holds:** only when their order already matches the sort; otherwise **New order:**, even on a Pass)
1. <item> (<effort>, <due>): <group>
2. ...
**Start now:** <the first item, in a few words>

**Fill in:** <each [placeholder] still open>   (only when something is still missing)

**To your manager (<channel>):** "<ready-to-paste>"   (only when doing it right costs more hours than planned)
```


## Prioritize: what to check

**Use for:** a list of competing items, in whatever order and format the person keeps it. A single task or workstream is a Plan question, and a blocker or risk is an Escalate question; say so in one line and stop if that's what was pasted.

**Reading the shared section for Prioritize.** The deliverable is the list in its new order with the item to start now, plus the line to the manager when there is one. Prioritize has no "not ready" verdict: a best-guess order always helps more than no order. When a due date or effort is still unknown after the questions, put `[due]` or `[hrs]` in the list, sort on what you know, and say in the Fill in line which placeholders to complete and that the order may move once they do. Never fill in a date, an effort or a client impact the person didn't give you.

**Today's date.** Urgency depends on it. Use the date in the paste, or today's date from the conversation. If neither is available, use `[today]`, sort by due order, and say urgency is unchecked. Count business days: from Monday, Wednesday is two business days out.

**What usually needs asking:** a due date or effort that's missing, and whether anyone is waiting on the person. Ask only when the answer could move an item into a different group or change the first item; an hour's difference inside a group doesn't matter. Don't ask for a date the person already said doesn't exist ("no date"), and don't re-ask anything the paste gives. Two questions are almost always worth asking:
- **A client-flagged problem with no date.** Ask when the client needs it (or whether it's blocking them). It's the difference between first on the list and scheduled, and you can't tell from the paste.
- **A plan to skip testing, review or a check to save time or budget.** Ask whether a problem in what's skipped could reach the client. "Not sure" counts as yes: treat it as client-facing, but say it "could" reach the client, never that it will.

**How it sorts.** Two cuts:
- **Urgent:** due within two business days, or someone is blocked waiting on the person. A client who flagged a problem is waiting only if they said so or need it inside that window.
- **High impact:** affects a client deliverable, a client deadline or the client relationship. Internal work (templates, tickets, knowledge-base entries, internal decks) is low impact unless it feeds client work.

Then place each item in the first group that fits, top to bottom:
1. **Do now:** urgent and high impact. Urgent client work always comes first.
2. **Quick unblock:** about 30 minutes or less, and someone is waiting on it. It costs almost nothing and frees someone else's day, so it goes ahead of everything except urgent client work.
3. **Do fast or hand off:** urgent, low impact.
4. **Schedule:** high impact, not urgent. Give it a day.
5. **Park:** neither. Do it after the rest, or drop it.

A teammate waiting on 30 minutes or less stays in Quick unblock even when the work feeds a client deliverable, so the client's own urgent item still comes first.

Within a group, quicker items go first. A range uses the high end; an unknown effort goes last in its group. When it's unclear whether an item is client or internal work and it would change the group, ask; if it's still unknown, treat it as client work.

**Client outcome first.** If doing client work right costs more time or budget than planned, do it right and tell the manager the real hours. A plan that saves budget by skipping testing, review or checks on client work fails, whatever its order. The skipped work goes back on the list where the sort puts it. A trade-off is quiet until the manager has been offered it as a choice; saying it here doesn't count.

Check these. When choosing the two improvements, a quiet trade-off always makes the cut, because it's the mistake that costs the client; then the move that matters most (the true first item, or what shouldn't be at the top). Each Improve line moves one item or fixes one trade-off (on a Pass, a scheduling tip or a check worth running):

- **The order matches the sort.** Anything urgent and high impact sits at the top.
- **Nothing hidden.** Flag anything urgent or due this week placed below an item from a lower group.
- **No quiet trade-offs.** See Client outcome first.

**Verdicts.** The critical issues for Prioritize are a wrong first item (one from a lower group than something below it; a swap inside the top group is polish), anything urgent or due this week placed below an item from a lower group, or a quiet trade-off on client work (see Client outcome first).
- **Pass:** the first item is right and nothing sits in the wrong group; a swap of two items inside the same group is polish.
- **Pass with fixes:** no critical issue, but an item further down is in the wrong group.
- **Fail:** a critical issue. If the list is unordered (they said so, or it's a bulleted list), judge it on trade-offs only: no trade-off is a Pass. Give the order either way.

**The line to the manager.** When doing it right costs more hours than planned, give a short ready-to-paste message, and apply rule 7 to it. Doing the work right isn't up for trade; where the hours come from is. Write it to the Communicate standard, because it's managing upward:
- **Point first:** the overrun and what you're doing about it in the first sentence.
- **Specific:** the hours and the date, using only the person's numbers.
- **A choice they can answer on the spot:** two real places the hours could come from, so the manager decides in one reply. Usually that's booking them over budget, or taking them from other work on the same budget in the person's list ("book it over budget, or take it from the 6 hrs on the bridge?"). Moving internal work (a knowledge-base entry, a template) frees the person's time but not client budget, so it isn't a source. If nothing on the list draws on that budget, or it's unclear whether anything does, use a placeholder like `[other task on this project]` and say so in Fill in.
- **Specific timing** for the reply: the person's time if they gave one, otherwise `[reply-by time]`, listed in Fill in. Never "soon".
- **Right medium:** name the channel. Teams for a quick choice to your own manager, including hours over the project budget; email when the client's budget or date changes. Treat the project budget as internal unless the person says the client is billed for the overrun.


## Examples

### Example 1: fail, quiet trade-off

Paste: "It's Tuesday 12/8. My list, in this order: 1. Clean up my project tickets (1 hr, no date). 2. Q1 headcount bridge for the client, due Fri 12/11 (6 hrs). 3. Revised accrual schedule the client controller asked for, due tomorrow (3 hrs, plus 1 hr for the second-reviewer tie-out, which I'll skip since we're at budget). 4. Teammate needs the account mapping file I promised (10 min)."

```
**Fail**: skipping the tie-out on tomorrow's client schedule is a quiet trade-off.

**Done well:** You named the tie-out skip instead of just doing it. Why: naming it is the first step; it stops being quiet once your manager gets the choice.

**Improve 1:** Keep the second-reviewer tie-out on the accrual schedule. Why: it goes to the client's controller, and an error there costs more than the hour you'd save.

**Improve 2:** Move the ticket cleanup to the bottom. Why: it has no date and no client impact, and it was sitting on top of work due tomorrow.

**New order:**
1. Revised accrual schedule, with tie-out (4 hrs, Wed 12/9): Do now
2. Send the mapping file to your teammate (10 min): Quick unblock
3. Q1 headcount bridge (6 hrs, Fri 12/11): Schedule
4. Clean up project tickets (1 hr, no date): Park
**Start now:** the accrual schedule.

**Fill in:** [reply-by time]; [other task on this project], if one shares the budget.

**To your manager (Teams):** "Keeping the second-reviewer tie-out on the client's accrual schedule (due Wed 12/9) puts me 1 hr over budget. Book it over budget, or take it from [other task on this project]? A reply by [reply-by time] works."
```

### Example 2: pass

Paste: "It's Wed 12/2. 1. Client AP accrual tie-out, due Thu 12/3 (2 hrs). 2. Teammate waiting on my review of her journal entry template (20 min). 3. Client board deck numbers, due Tue 12/8 (5 hrs). 4. Update my project tickets (30 min, no date)."

No questions: every date, effort and blocker is given.

```
**Pass**: urgent client work is first and every item sits in the right group.

**Done well:** You put tomorrow's client tie-out ahead of everything. Why: urgent client work always comes first.

**Improve 1:** Block a day for the board deck numbers this week. Why: it's 5 hrs and due Tue 12/8, so it needs time blocked before then.

**Improve 2:** Give the ticket update a slot later this week. Why: parked work with no slot tends to stay parked.

**Order holds:**
1. Client AP accrual tie-out (2 hrs, Thu 12/3): Do now
2. Review teammate's journal entry template (20 min): Quick unblock
3. Client board deck numbers (5 hrs, Tue 12/8): Schedule
4. Update project tickets (30 min, no date): Park
**Start now:** the AP accrual tie-out.
```

### Example 3: pass with fixes, one effort unknown

Paste: "It's Mon 11/30. My list, in this order: 1. Client close checklist review, due Tue 12/1 (3 hrs). 2. Teammate waiting on my review of her accrual JE (15 min). 3. Update the internal training deck (2 hrs, no date). 4. Client variance commentary, due Tue 12/8."

No questions: an hours figure for the commentary wouldn't change its group.

```
**Pass with fixes**: the training deck sits above client work it should follow.

**Done well:** You put tomorrow's close checklist first. Why: urgent client work always comes first.

**Improve 1:** Move the variance commentary above the training deck. Why: it's client work, and the deck is internal with no date.

**Improve 2:** Put an hours estimate on the variance commentary. Why: without one you can't tell when to start it.

**New order:**
1. Client close checklist review (3 hrs, Tue 12/1): Do now
2. Review teammate's accrual JE (15 min): Quick unblock
3. Client variance commentary ([hrs], Tue 12/8): Schedule
4. Update internal training deck (2 hrs, no date): Park
**Start now:** the close checklist review.

**Fill in:** [hrs] for the variance commentary; the order may move once you have it.
```

---

© 2026 Openvale Group. Licensed under CC BY-NC 4.0; internal use and adaptation permitted, not for resale. A starting point, not a supported product: provided as is, without support or warranty. Outputs are drafts for human review.
