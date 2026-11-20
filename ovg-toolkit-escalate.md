---
name: ovg-toolkit-escalate
description: "Verdict check on whether to escalate when you're stuck, blocked, see a risk or are about to ping someone for help: Pass (escalate now, with a ready-to-send message) or Fail (not yet: what to try first, or what to collect). Use when someone describes a blocker, an error, a slipping date or a non-responsive stakeholder and asks whether to escalate or who to go to. Searches the documentation first for technical errors. Not for checking a message about something they've already decided to send (Communicate) or ordering a to-do list (Prioritize). Never invents facts."
license: CC BY-NC 4.0 with an additional permission for internal organizational use. See LICENSE at https://github.com/OVG-Public/Shared-Artifacts
metadata:
  author: Openvale Group
  version: "1.0"
---

# OVG Toolkit: Escalate

A quick check you run when you're stuck, see a risk, or are about to ping someone for help. The goal is judgment, not just a drafted message: people should finish each run knowing when to escalate, to whom, and what a good escalation looks like, so they need the skill less over time. Escalating too late costs more than escalating a little early.

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
**Pass: escalate** | **Pass with fixes: escalate** | **Fail: not yet** | **Fail: not ready to escalate**: <the main reason, the same one Improve 1 addresses>

**Done well:** <what>. Why: <one line>

**Improve 1:** <fix>. Why: <one line>

**Improve 2:** <fix>. Why: <one line>

**Try first:** <one or two steps, with a link to any doc you found>   (Fail: not yet)

**Collect first:** <the exact error, what you tried, what changed>   (Fail: not ready)

**Meanwhile:** <one step to try in parallel>   (Pass and Pass with fixes, when there's a fix worth trying)

**Tell your EM today:** "<one line>"   (any verdict, when the client can see the impact; skip it when the Message already goes to the EM)

**Message (<channel>, to <who>):**   (Pass and Pass with fixes)
<ready-to-send text>
```

## Escalate: what to check

**Use for:** a blocker, an error you can't clear, a date at risk, a stakeholder who isn't responding, or a risk someone above you should know about. Routine updates and non-urgent asks are Communicate. Once the issue is fixed and the person is informing others, it's Communicate again.

**Reading the shared block for Escalate.** Pass and Fail grade the timing call, not the person: "Fail: not yet" means it isn't time yet. On a Pass the Improve lines can carry the main action. Improve lines hold the judgment (timing, level, context); Try first holds the concrete steps and the doc link. The deliverable is the "Try first" steps (not yet), the "Collect first" list (not ready) or the escalation message (escalate). **Pass with fixes: escalate** means it's time to escalate and the draft they pasted needs the two fixes; the rewritten message includes them.

**Check the documentation first.** For a technical error, search before you judge: the vendor's official documentation first (Microsoft Learn for Microsoft products; use a docs tool if you have one), then a web search. Name and link what you found, and say plainly if you found nothing that fits. Never say a doc says something you haven't read. If you can't search, give the search terms to try and don't claim what the docs say.

**What usually needs asking.** What exactly is failing, first, when the paste doesn't say. Then: (1) whether a deadline is at risk, and which date; (2) how long they've been stuck, or how many times they've followed up; (3) what they've already tried. Ask who owns the relationship or the decision only when it changes who to go to.

**When it's time.** Escalate when any of these is true: a date is at risk; they've been stuck more than about half a day; or someone hasn't replied after two follow-ups. Anything the client can see (a date, a deliverable, data they use, the budget) gets a same-day heads-up to the engagement manager, even when it isn't time to escalate yet: that's the **Tell your EM today** line, and the slot says when it applies. A date is at risk when something someone relies on (the client, your manager, a teammate) will be late or wrong before the fix can land. If they can't say: when there's a one-sitting fix to try, it isn't at risk yet (try it first); otherwise production or client-facing work counts as at risk.

Check these. When choosing the two improvements, the timing call (escalate now, or try one thing first) always makes the cut:

- **Low-hanging fruit.** Is there an obvious or documented fix they haven't tried? Name it and link the source.
- **Context.** Where things stand, what they tried and what exactly is blocked. The reader shouldn't need a follow-up question.
- **Options and a recommendation.** Two or three real options, with the one they'd pick. A decision is easier to give than a problem is to solve.
- **Right level.** Go one level up from where it's stuck:
  - A technical blocker inside the build: the project team (a teammate or tech lead).
  - A date, scope, budget or client-relationship risk: the engagement manager.
  - Something the engagement manager can't solve (staffing, cross-client, a commercial call): firm leadership, with or through the engagement manager.
  - A client-side dependency (access, data, a decision): the client, usually through whoever owns the relationship. Routine follow-ups can go to the client directly.
  Don't skip the engagement manager to reach leadership or the client. If more than one route fits, the EM heads-up comes first and the technical or client route runs alongside it.

**Verdicts, in this order.** (1) They can't say what's failing (an unknown cause alone doesn't count): **Fail: not ready to escalate**, with the Collect first list, plus the Tell your EM line when the slot applies. (2) A date is at risk: **Pass: escalate**, with the fix as Meanwhile. (3) There's an obvious or documented fix they can try in one sitting (re-sign a connection, rerun smaller, a documented setting), they've been stuck less than about half a day (if they can't say, treat it as less), and no date is at risk before then: **Fail: not yet**. Switching channel counts as that kind of fix only before two follow-ups; after two, escalate. (4) Otherwise: **Pass: escalate**; asking a teammate early is cheap.

**The message.** Write it to the Communicate standard: point first, then background, where it stands, the options, the recommendation, and the ask with a day and date. Use only facts from the paste and the answers; options are suggestions, so mark any specific you don't have with a placeholder. If they didn't say which option they'd pick, add one line above the message: "The recommendation is my suggestion; change it if you'd pick differently." Pick the channel the Communicate way: Teams for a quick yes/no to your own manager or team, email for the client, leadership, or anything that needs a record. Keep it short, and apply rule 7.

## Examples

### Example 1: not yet

Paste: "It's Mon 12/7. The Fabric notebook that loads GL detail times out on the full year. One month runs fine. I've rerun it twice. The data is due to the client's FP&A team Wed 12/9."

Asks: How long have you been stuck on this? (Under an hour / Half a day / More than a day) → Under an hour.

```
**Fail: not yet**: a quick test is untried, and Wednesday isn't at risk today.

**Done well:** You showed one month runs fine. Why: it points at volume, and it's the first thing anyone helping would ask.

**Improve 1:** Test the volume theory yourself before pulling anyone in. Why: one month already works, so a quick test will likely tell you more than a conversation.

**Improve 2:** Set a cutoff (say, end of day Tue 12/8): if it's still failing then, escalate to your tech lead. Why: Wednesday is safe today, not after another lost day.

**Try first:** Run the load in monthly batches. [Link to any doc found on notebook timeouts, or "no doc found; search: Fabric notebook timeout large table"]

**Tell your EM today:** "Heads-up: the GL load for FP&A's Wed 12/9 data is timing out on the full year. I'm testing a fix and will confirm by [time, day]."
```

### Example 2: escalate

Paste: "Client IT still hasn't given our service account access to the production lakehouse. I asked 11/30 and followed up by email 12/2 and 12/4. Go-live is Fri 12/11 and we need two days of testing in production. My EM owns the client relationship."

No questions: the date at risk, the follow-ups and the relationship owner are all given.

```
**Pass: escalate**: go-live is at risk after two follow-ups.

**Done well:** You followed up by email and kept the dates. Why: it shows you used the right channel before going up.

**Improve 1:** Escalate to your EM today rather than sending a third follow-up. Why: two days of testing before Fri 12/11 means access has to land by Wed 12/9.

**Improve 2:** Bring a recommendation along with the problem. Why: your EM can say yes in one reply.

The recommendation is my suggestion; change it if you'd pick differently.

**Message (Teams, to your EM):**
Heads-up on Fri 12/11 go-live: client IT still hasn't given our service account access to the production lakehouse. I asked on 11/30 and followed up by email on 12/2 and 12/4, and access still isn't in place. We need two days of testing, so access has to land by Wed 12/9.
Options: (1) you raise it with [client sponsor] today, (2) we start testing in [non-production workspace] and move only the final run to production, (3) we move go-live to [date].
I'd go with 1, and switch to 2 if there's no access by [date]. OK to go ahead? A yes by [time] [day, date] works.
```

### Example 3: not ready

Paste: "Stuck on our internal forecast model, not sure what to do."

Asks: What's going wrong? (An error message / Numbers look wrong / Not sure how to build the next part) → Not sure. Is a date at risk? (Yes, this week / No / Not sure) → Not sure.

```
**Fail: not ready to escalate**: there's nothing specific to raise yet.

**Done well:** You flagged it instead of sitting on it. Why: saying you're stuck early is how small problems stay small.

**Improve 1:** Write down exactly what you tried and what happened. Why: it's the first thing anyone helping will ask.

**Improve 2:** Find out the next date the model is due. Why: it decides whether this waits or goes to your EM today.

**Collect first:** the exact error or the number that looks wrong, the steps you took, and what changed since it last worked.
```

---

© 2026 Openvale Group. Licensed under CC BY-NC 4.0; internal use and adaptation permitted, not for resale. A starting point, not a supported product: provided as is, without support or warranty. Outputs are drafts for human review.
