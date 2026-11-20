---
name: ovg-toolkit-deliver
description: "Verdict check (Pass, Pass with fixes or Fail) before you release something a client will use: a dashboard, planning model, app or tool. Use when someone says they're about to release, hand off or go live, even if they haven't said who uses it or what they tested. Not for decks, documents or messages (Communicate) or something broken you're stuck on (Escalate). Gives 1 thing done well, 2 fixes and a short test summary to send with the release. Never invents facts or defects."
license: CC BY-NC 4.0 with an additional permission for internal organizational use. See LICENSE at https://github.com/OVG-Public/Shared-Artifacts
metadata:
  author: Openvale Group
  version: "1.0"
---

# OVG Toolkit: Deliver

A quick check you run before you release something a client will use. The goal is judgment, not just a checklist: people should finish each run knowing what "tested" means a little better, so the client finds fewer problems and nothing needs saying twice.

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
**Pass** | **Pass with fixes** | **Fail** | **Fail: not ready to release**: <for a Pass, why it's ready; otherwise the main issue, the one Improve 1 fixes>

**Done well:** <what>. Why: <one line>

**Improve 1:** <fix>. Why: <one line>

**Improve 2:** <fix>. Why: <one line>

**Test summary (send with the release):**
- <what was tested, how, and the result>
- ...
- Not tested: <anything still open, or "nothing known">
```

## Deliver: what to check

**Use for:** a dashboard, planning model, app or tool a client will use. Decks, process maps, documents and messages are Communicate. Planning the build is Plan. If something is broken and the person is stuck, that's Escalate.

**Reading the shared block for Deliver.** The deliverable is the test summary: a short list the person sends with the release so the client knows what was checked. **Fail: not ready to release** means the audience or use is still unknown after asking (in a one-shot run, not in the paste). A missing critical test is a plain Fail. If both apply, use not ready.

**Judge only what you can see.** Your evidence is the screenshots, file, link contents or log the person shares, plus what they tell you. Never claim a defect you haven't seen, and never say something passed that they didn't test. A check that matters and you can't see: ask about it when the answer could change the verdict (it can't when something visible already fails). If you don't ask, add it to the summary as a placeholder the person resolves before sending, naming the check in plain words: "[Mid-period hires and terminations: tested / not tested]". It's a Fail only if the person says it wasn't done or the evidence shows it failing. When you can't see a second issue, make the Improve line a check to run ("submit twice and confirm only one lands"), not a defect.

**What usually needs asking.** Three at most, the most decisive first, and only what the paste doesn't already say: who uses it and for what (always first when the paste doesn't say); whether they've used it end to end the way the client will, in each role; whether last round's review comments are applied everywhere they apply; whether the cases most likely to break it are tested (for a model: hires and terminations mid-period, a period roll-forward, a zero or blank input; for a dashboard or app: odd filter combinations, repeat submissions), with options like All / Some (which?) / None.

Check these. When choosing the two improvements, a critical issue always beats friction or polish:

- **Use it yourself.** Someone ran through it end to end the way the client will, in each role. Critical: nobody has used it end to end in any role.
- **Try to break it.** Odd inputs, repeated runs, the edge cases this kind of build is known for. Test more than once. Critical: a case this build is known to break on is untested and could change a number or an action the client relies on; any other untested case goes under Not tested.
- **Sanity-check the outputs.** Totals tie in full to a named source (spot-checks don't count) and make business sense. A total that ties but looks wrong next to last period (3x, a sign flip, a missing month) still needs a look. Filters and defaults are what the client will want on first open. Critical: totals don't tie in full, or a default shows selections no one would want (dates back years, a prior year, a test entity), so the first view misleads. A default that's workable but not ideal (current quarter where they'd prefer current month) is a fix to recommend, not a Fail.
- **Close the loop on feedback.** Last round's comments are fixed everywhere they apply, not only where the reviewer pointed. Critical: a comment isn't applied everywhere it applies.
- **Look for friction.** Too many clicks, confusing labels, an unclear next step, no confirmation that an action worked.
- **Show the evidence.** Screenshots or a short test log go out with the release. The test summary is the minimum.

**Verdicts.** Anything listed as Critical in the checks above is a Fail; the rest of each check is advice. Friction and missing evidence are Pass with fixes at worst.
For Fail, the two fixes say what to test or change before release. For not ready, tell them what to find out first. Rule 4 covers the rest.

**The test summary.** Always give one. List only what the person actually tested, with how and the result, in their words ("October totals tie to NetSuite"). For a Fail, write it as it will read once the two fixes are done, with `[result]` placeholders for the new tests, so they fill it in rather than rewrite it. End with a "Not tested" line: anything still open, or "nothing known". For not ready, list the tests to run once the audience is known, each with `[result]`. Keep it to about five lines, and apply rule 7.

## Examples

Terms in the examples: AR and AP are accounts receivable and payable.

### Example 1: fail, comments applied in one place

Paste: "Releasing the 13-week cash forecast workbook to the client's treasury team Friday 12/4. It rolls from the AR and AP aging. Week 1 ties to the 11/27 bank balance. Last review asked for a check row and locked input cells."

Asks: Are the check row and locked inputs on every weekly tab? (Yes / Only the summary tab / Not yet) → Only the summary tab. Have you rolled it forward a week the way treasury will? (Yes / No) → No.

```
**Fail**: last round's comments are only on the summary tab.

**Done well:** Week 1 ties to the bank balance, and you said which date. Why: treasury can check the same number themselves.

**Improve 1:** Add the check row and lock inputs on every weekly tab. Why: a comment fixed in one place gets raised again, and that costs a review round.

**Improve 2:** Roll it forward one week the way treasury will, then tie week 1 again. Why: a rolling forecast usually breaks on the roll, not on the first build.

**Test summary (send with the release):**
- Week 1 ties to the 11/27 bank balance.
- Check row and locked inputs on every weekly tab: [result]
- Rolled forward one week; new week 1 ties to [source]: [result]
- [Blank or zero inputs: tested / not tested]
- Not tested: [whatever is still open once the two fixes are done]
```

### Example 2: pass with fixes, friction only

Paste: "Releasing the headcount report to the client's HR business partners Monday 12/7. I tested it as an HRBP and as the admin, ran Sep through Nov, and totals tie to the HRIS export each month. Last round's comments are applied on every page. Log attached. Screenshot 2 shows the department slicer." (Screenshot 2: the slicer lists cost center codes like 4100-220, with no department names.)

Asks: Have you tried odd filter combinations and repeat runs? (Both / One of them / Neither) → Both.

```
**Pass with fixes**: the department slicer shows codes, not names.

**Done well:** You tested both roles across three months and kept a log. Why: that's the evidence a client needs to trust it on day one.

**Improve 1:** Show department names in the slicer (screenshot 2). Why: HR business partners know departments by name, and codes send them back to you with questions.

**Improve 2:** Attach the log to the release note. Why: it answers "was this tested?" before anyone asks.

**Test summary (send with the release):**
- Tested as an HRBP and as the admin.
- Sep, Oct and Nov totals tie to the HRIS export.
- Last round's comments applied on every page.
- Odd filter combinations and repeat runs tried.
- Not tested: nothing known.
```

---

© 2026 Openvale Group. Licensed under CC BY-NC 4.0; internal use and adaptation permitted, not for resale. A starting point, not a supported product: provided as is, without support or warranty. Outputs are drafts for human review.
