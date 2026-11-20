---
name: ovg-toolkit-communicate
description: "Verdict check (Pass, Pass with fixes or Fail) on a message before it goes out: a status update, an ask, a decision request, a deck cover note or an incident follow-up. Use when someone pastes a draft and asks you to check it, how to word it, or whether it should be email or Teams, especially before it goes to a client or manager. Not for deciding whether to escalate a blocker or risk at all (Escalate) or a style-only rewrite with no verdict (humanizer). Gives 1 thing done well, 2 fixes and a rewrite that sounds like the sender. Never invents facts."
license: CC BY-NC 4.0 with an additional permission for internal organizational use. See LICENSE at https://github.com/OVG-Public/Shared-Artifacts
metadata:
  author: Openvale Group
  version: "1.0"
---

# OVG Toolkit: Communicate

A quick check you run before you hit send. The goal is judgment, not just a cleaner draft: people should finish each run knowing the standard a little better, so they need fewer review rounds next time.

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
**Pass** | **Pass with fixes** | **Fail** | **Fail: not ready to send**: <for a Pass, why it's ready; otherwise the main issue, the one Improve 1 fixes>

**Done well:** <what>. Why: <one line>

**Improve 1:** <fix>. Why: <one line>

**Improve 2:** <fix>. Why: <one line>

**Call first:** <one line>   (only when the right first step is a call)

**Rewrite (<channel>):**
<ready-to-paste text, and nothing that isn't meant to be sent>
```

## Communicate: what to check

**Use for:** any drafted message, however urgent: status updates, asks, decision requests, and the cover message for decks, process maps or business cases (review only the cover message and flag that the content needs its own review). Deciding whether to escalate a blocker or risk at all is Escalate; once there's a draft to check, it's here. Once an issue is fixed and the person is informing others (an incident follow-up, a "resolved" note), it's back here.

**Incident follow-ups** are where invented facts do the most damage. The reader's real questions are what actually happened, whether it's fixed, and whether their data or work is right today. A vague cause ("multiple jobs ran at once") doesn't answer the first; a plain one builds more trust and lets them judge the risk. When you ask about the cause, ask one level below what the draft says: if the draft says "jobs ran at the same time", ask why they ran at the same time (our test runs overlapped production / two scheduled jobs collided / not sure yet). How the overlap broke things is a detail; why it happened is what tells the client whether it will happen again.

The line is between claiming and reporting. An update that says plainly what's known, what isn't, and how the team will find out is complete and can pass, even with the cause still open; that is the standard to teach. When the cause is still open, the rewrite says so plainly ("we're still confirming the cause") rather than leaning on a vague label. A message that claims more than the person knows fails. If the overreach is one line you can cut or reword ("we're not worried" or "won't happen again" while the cause is unknown; good runs since the failure don't show it won't recur), it's a plain **Fail**. If the whole point of the message is the thing they don't know yet (answering "why did it fail?" with a guess like "looks like a transient issue", or announcing a root cause that isn't confirmed), it's **Fail: not ready to send**, with a holding note: only what's known and when the next update comes (`[time]` if unknown). Internal next steps to a manager don't each need a date unless someone is waiting on one.

**What usually needs asking:** who it's going to, the channel, what the reader needs to do, and by when. If you can't tell whether the message needs anything back (an intro or FYI reads that way), ask that first. A one-line draft with no audience is the classic case: fine as a Teams note to your manager, a fail as an email to a client CFO.

Check these. When choosing the two improvements, a broken check beats polish, and a wrong channel always makes the cut, because it's the habit that most often stalls a timeline:

- **Point first.** The ask or headline lands in the first one or two sentences, especially for executives. "Let me know what you think" at the end makes the reader do the work.
- **Enough context.** The reader can act without a follow-up question: which file, which workspace, what's blocked.
- **Right medium.** Pick the channel and format:
  - A question asking only for information or an opinion, answerable on the spot (yes/no, one fact): Teams.
  - An update or hand-off in a team thread already working the issue: Teams, same thread.
  - Asks someone to do something, decide something that needs thought, or approve: email, even when it's phrased as a question. It's easier to follow up and keeps a record.
  - Bad news, pushback or feedback about a person: a call or conversation first, then an email that confirms what was agreed. Bad news here means a client date or deliverable moves, or their work is affected today; an incident note about something already fixed can go by email.
  - Long content (more than a screen): a deck, one-pager or memo, with a short cover message. Flag it; rewrite only the cover message.

  Clients follow the same rules. An information question on Teams that can't be answered on the spot is a broken check (Pass with fixes): make it answerable rather than moving it. When the right first step is a call, the rewrite is the follow-up email, with `[what we agreed]` and `[new date]` placeholders, plus the **Call first** line.
- **Specific timing.** "By Friday", "tomorrow", "at your earliest convenience" mean different things to different people, and vague timing is a main reason timelines drag. Name the day and date. EOD means before you sign off; COB means within the other person's working hours. Add a time zone when people are in different zones.
- **Safe to send.** Nothing is stated as fact that the sender hasn't confirmed (see claiming vs reporting above), the right people are on To and Cc, and nothing confidential goes to someone who shouldn't see it.

**Critical issues for Communicate:** no clear ask when the message needs one (the reader can't tell what you need from them); a promise to the reader with no time at all ("we'll get it to you"); a fact stated with more certainty than the sender has (see claiming vs reporting); the wrong people on To or Cc; or something confidential going to someone who shouldn't see it. A promise with any time, even a vague one, is vague timing, not a critical issue.
- **Pass with fixes:** no critical issue, but the two fixes would save the reader a follow-up, a delay or a misread. A buried ask, vague or relative timing ("next week", "tomorrow", "end of week"), or the wrong channel lands here. When the message needs a decision or action, "let me know what you think" with no question anywhere is a missing ask, and a question that's there but late is a buried one. In an intro or FYI that needs nothing back, "let me know what you think" or "happy to discuss" is a friendly close: leave it, and don't count it against a Pass. Don't suggest adding an ask or a follow-up call either, and don't add one in the rewrite (bad news still gets its **Call first** line); whether to ask for something is the sender's choice.
- **Fail:** a critical issue above. The list wins: a missing ask or a claim beyond what they know is a Fail even when the fix is one line. Anything not on the list is Pass with fixes at worst, however much the rewrite changes.

Rule 4 covers Pass and Fail: not ready.

**The rewrite:** match the channel the message should go out on (if you're moving it from Teams to email, write the email with a subject line). Keep the person's voice and keep it as short as the content allows, then apply rule 7 so it doesn't read like it was written by AI. For a pass, still give a lightly tightened version.

## Examples

### Example 1: pass with fixes, decision buried

Draft (email to the engagement manager): "Hi Sam, wanted to give a quick update on the headcount model. Finished mapping the payroll file, ran into some issues with department codes that don't match the GL, worked around most of them. Also cost centers 410 and 415 look like they were merged in September. Should we treat them as one going forward? Model should be ready end of week."

Asks: When do you need Sam's answer on 410/415? (Wed 11/18 / Thu 11/19 noon / Before the model is done) → Thu 11/19 noon. When is the model ready? (Thu 11/19 / Fri 11/20 morning / Fri 11/20 EOD) → Fri 11/20 by noon.

```
**Pass with fixes**: the decision you need is buried.

**Done well:** Email for a question that needs a decision. Why: it keeps a record of what Sam agreed to.

**Improve 1:** Put the 410/415 question first. Why: Sam can answer in one line without reading the update.

**Improve 2:** Replace "end of week" with "Fri 11/20 by noon". Why: "end of week" is Thursday to some people and Friday night to others.

**Rewrite (email):**
Subject: Decision by Thu 11/19 noon: treat cost centers 410 and 415 as one?
Hi Sam, cost centers 410 and 415 look merged as of September. Should we treat them as one going forward? I need your answer by Thu 11/19 at noon.
Status: payroll mapping is done; I've worked around most department codes that don't match the GL. The model will be ready Fri 11/20 by noon.
```

### Example 2: not ready to send

Draft (email to the client CFO, replying to her question about why this morning's refresh failed): "Hi Dana, the refresh failed because several jobs ran at the same time. It's fixed and this won't happen again."

Ask: Why did the jobs run at the same time? (Our test runs overlapped production / Two scheduled jobs collided / Not sure yet) → Not sure yet.

```
**Fail: not ready to send**: Dana asked why, and the cause isn't confirmed yet.

**Done well:** You answered her the same morning and said it's fixed. Why: the part you know reaches her first.

**Improve 1:** Replace the cause with "we're still confirming the cause". Why: a guessed cause that turns out wrong costs more trust than saying you don't know yet.

**Improve 2:** Say when she'll hear next. Why: a next-update time gives her something to plan around.

**Rewrite (email), as a holding note:**
Subject: Re: this morning's refresh
Hi Dana, on your question about this morning's refresh: it's fixed, and we're still confirming the cause. [One line on whether today's numbers are right, once you've checked.] I'll update you by [time].
```

---

© 2026 Openvale Group. Licensed under CC BY-NC 4.0; internal use and adaptation permitted, not for resale. A starting point, not a supported product: provided as is, without support or warranty. Outputs are drafts for human review.
