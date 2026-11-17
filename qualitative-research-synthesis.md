---
name: qualitative-research-synthesis
description: Plan stakeholder interviews and thematically code the transcripts into evidence-backed findings. Use when someone is preparing interviews (objectives, open-ended questions), uploads or pastes interview transcripts to be coded, wants a claim tested against the evidence (drill-down), a leadership readout, a findings and recommendations document, or a playback note for each interviewee. Built for FP&A business partners and internal finance teams. Trigger on "code these interviews", "prepare for stakeholder interviews", "interview guide", "thematic coding", "what did the interviews say", "does the evidence support", "findings and recommendations", "leadership readout", "synthesize interview notes", "qualitative research synthesis".
license: CC BY-NC 4.0 with an additional permission for internal organizational use. See LICENSE at https://github.com/OVG-Public/Shared-Artifacts
metadata:
  author: Openvale Group
  version: "1.0"
---

# Qualitative Research Synthesis

Helps someone plan stakeholder interviews, then turns the transcripts into findings a leadership team can act on and a follow-up for each person interviewed. The method is thematic coding: tag every passage that touches an issue, then build findings only from what was tagged, never from impression. The aim is to move the conversation with the business from transactional questions ("when will my report be ready?") to strategic ones ("how do we fix underperformance in this channel?").

Built for internal FP&A use: the person is a finance business partner interviewing the business leaders they support. The AI does the preparation and synthesis; the interview itself, and the relationship, stay person to person. Treat all coding as a draft the person reviews.

It runs in conversation. The person provides transcripts; you hold the coded corpus and produce whatever they ask for next. There is no starter codebook. The themes come from the interviews themselves.

## Before you use

This skill is a **starting point, not a supported product.** It is shared as is, without support, maintenance commitments or warranty. Adapt it to your organization, test it on sample material, and review every output before relying on or sharing it.

Interview transcripts often hold candid views about colleagues, performance, compensation and the organization. Before using this skill on real interviews:

- **Check your organization's AI and data policy.** Confirm you may process this material with your AI tool.
- **Use an approved tool.** Run it only in an AI environment cleared for confidential data, under your organization's data-handling terms.
- **Get consent.** Tell interviewees the session will be recorded or transcribed and processed with AI, and get their agreement, as your policies and local law require.
- **Treat outputs as drafts.** The skill codes and synthesizes. People decide what is true and what is shared.

When the skill first runs, remind the person of these points in one short line before starting, unless they have already confirmed them.

## Where this fits

This method is designed for the diagnostic work that comes before building anything in a finance organization: understanding what leaders actually need, where trust in the numbers breaks down, and which questions the business cannot answer today. Those findings shape the performance management design that follows.

**Words used precisely throughout.** A **passage** is one tagged quote, the unit you count. A **family** is a top-level theme; a **code** is a specific issue inside it. A **voice** is one person who spoke: not one interview, since a session can have several people in the room, and never the interviewer. A **finding** is a group of codes that share a mechanism or consequence.

## How a session goes

**0. Establish the project.** On the first request or transcript, if you don't already know, ask once, in one short message:
- which team or function is being interviewed (e.g. "the marketing leadership team")
- what decision or conversation the work should inform, in one sentence; this anchors the themes
- who the output is for, and who it is from (names or team)
- **who will read the output** (the interviewees' own team, a peer team, senior management, a wider group) and how quotes should be attributed for each: **name and role**, **role only**, or **unattributed**. Anyone who both took part and will read the output sees the version written for the widest audience. Per-person playback notes are the only place a name can appear, and they use only that person's own words. If unanswered, default to unattributed for anything leaving the person who ran the interviews, and role only for a note back to a speaker. Say plainly that with a small group a role often identifies one person, so role-only is not anonymous; only "unattributed" is. See Protecting the people who spoke.

Then get on with the work. Don't wait for the answers to start coding.

**Before the interviews (if they are still planning).** If the person says interviews are coming up, do Preparing the interviews first.

**1. Transcripts arrive.** If several arrive at once, still run the staged process below: take the first three in order as the open-coding set and say you're doing so. They may be uploaded files (.docx, .txt, .md, .vtt, .srt, PDF) or pasted text. Code each as it arrives and report back in prose: interview name, who took part and their roles, passage count, and the top three or four themes. Never show the coded table or raw JSON unless asked.

**2. Keep a running corpus.** After each interview track: documents, total passages, distinct voices, passages per family. Corroboration depends on these.

**3. They pick what's next.** Once two or more interviews are in, offer once, briefly: drill-down, leadership readout, the findings document, or a playback note for each interviewee. Don't produce any unasked, and don't re-offer every turn.

## Preparing the interviews

Do this when the person is planning interviews, before any transcripts exist. Use the Step 0 answers, and ask only for what's still missing: who will be interviewed with their roles, and how long each session is. Then produce a one-page guide:

1. **Objective.** One sentence: what we need to learn, and the decision it informs.
2. **Expectations to set at the start.** Why the conversation is happening, how long it takes, how the answers will be used, how quotes will be attributed (the Step 0 choice), and, only if it is true and you control it, that nothing is tied to performance.
3. **5 to 8 open-ended questions**, ordered broad to specific, each starting "how", "what", "tell me about", or "walk me through". Include a question about the last time something went wrong, since real events beat opinions. Close with "what haven't I asked that I should have?"
4. **Probes** for staying on the speaker's point without supplying yours: "say more about that", "what happened next", "how often", "what would you do with that?"
5. **Questions to avoid**, with rewrites. A leading or closed question narrows the answer and later costs the person corroboration, because the answer will be coded as prompted. "Do you track churn?" becomes "What do you look at to know how customers are doing?"
6. **Let the topic surface.** Don't name the project's central subject in the early questions; start from the person's own work and see whether they raise it. If it never comes up, ask about it directly near the end, and tell the person that those answers will code as prompted and count less.
7. **Tailoring.** If they gave roles, adjust two or three questions to each role's own work.

Keep it to one page; they'll use it in the room.

## Checking the questions

After each transcript, add one line to the readback (if several transcripts arrive together, give one combined summary at the end with the three most useful rewrites, not a list per interview): how many of the passages were prompted, as a count and share. If more than about a quarter were prompted, or the person asks, list up to three questions that were leading, closed or introduced a theme, each with an open rewrite. Check that the rewrite is itself open and doesn't lead. Be practical and kind; the point is the next interview, and the interviewer is the person you're talking to. A high prompted share is a finding about the interviews, not a fault: say it lowers the corroboration that can be claimed.

## Coding

Work only from the transcript. Never import outside knowledge or infer what someone "must have meant."

First establish from the transcript itself: who took part and each person's role (from how they describe their own work; leave the role blank rather than guess), a short document name (main interviewee and role, e.g. "A Morgan, Controller"; for a multi-person session add the others, "A Morgan, Controller (with B Lee)"), and the date. **If no date is stated, use the upload date and say so.** The interviewer is never a participant and never a voice. If speakers are only labeled "Speaker A/B", treat the one who mostly asks questions as the interviewer, state that assumption, and ask if it looks wrong. A person who appears in several sessions is one voice.

Then tag every passage that touches the project's questions:

| Field | Rule |
|---|---|
| `quote` | Verbatim and contiguous. **Never stitch two passages together.** Trim to the sentences carrying the point, but keep enough that a pronoun has an antecedent. |
| `speaker` | A named participant, or `unattributed` if the transcript doesn't make it unambiguous. |
| `weight` | HIGH / MEDIUM / LOW, below. |
| `family` + `code` | Exactly one of each, from the codebook as it stands. |
| `prompted` | `true` if the interviewer named this subject before the speaker did anywhere in the transcript. Critical; see Corroboration. |
| `soWhat` | One sentence on the implication for the project, not a restatement of the quote. This is where your judgment goes. If a tiebreak left a defensible alternative family, add it in a trailing clause. |

### Building the codebook from the interviews

There is no starter list. Build it in three stages so the vocabulary is stable by the time counts matter.

1. **Open coding (interviews 1–3).** Tag passages with short descriptive codes in plain lower-case phrases, written in the interviewees' own language and naming their real systems, teams and processes. Don't force them into families yet. Keep a running list of codes with the passages under each.
2. **Consolidate (after the third interview).** Group the codes into families, usually 5–12, each a theme a leader would recognize. Merge near-duplicates, split codes that hide two issues, and name each family by what it is about, not by a department. Show the person the families in a short list and say what changed. **Re-map the interviews already coded** so every passage speaks one vocabulary. Counts are only comparable after this step.
3. **Hold it steady (interview 4 onward).** Code against the codebook. Families are frozen; counts and findings are reported at family and finding level, so adding a more specific code inside an existing family is fine, but check earlier interviews for it so code-level counts stay comparable. Use `Other / Emergent` with a new code only when nothing fits. Flag a candidate family when an emergent code has three or more passages **from at least two different people**; one person's repeated point is not yet a theme. Add it only then, and re-check earlier interviews.

If the corpus is only one or two interviews, report themes as provisional and don't consolidate yet. If the first three interviews yield fewer than about 30 passages in total, hold consolidation until interview five or 40 passages, and say why. If the person supplies their own codebook, use it and skip stages 1 and 2.

### Where one passage ends

One passage carries **one point**, not one speaking turn. A long answer making three distinct complaints is three passages; a three-sentence answer circling one complaint is one. Split where the point changes, not where the sentence does, and keep each span contiguous: a split is a cut, never a reassembly. Keep a claim and the number that backs it together. A single sentence that lists several separate points may be split into fragments only if each fragment stands on its own; otherwise keep it as one passage. If splitting would leave a pronoun without its antecedent, keep the passage whole and weight it by the claim you rely on. Apply the same instinct across every interview, since counts are only comparable if segmentation is consistent.

### Picking one family when a passage spans several

Apply in order, stopping at the first that decides it:

1. **Code the mechanism, not the symptom.** "The two reports never show the same number" belongs with whatever the speaker is actually complaining about: that the sources don't reconcile, or that nobody trusts the result.
2. **Prefer the more specific family** over a general one.
3. **Prefer the family the `soWhat` is about.**
4. **Still tied?** Split only if the passage genuinely holds two separable sentences making two points. Otherwise use the family the speaker's own wording points to and name the alternative in `soWhat`. Never duplicate a quote across families to inflate counts.

### Source weight

- **HIGH**: first-hand, specific, from someone who owns the process.
- **MEDIUM**: first-hand but general; or specific but reporting what others do or say, even from a credible observer. A manager relaying what four staff told her is MEDIUM. A pure wish ("I'd want one number everyone agrees on") is MEDIUM at most and shows appetite, not the current state. A passage mixing a first-hand fact with speculation: split if separable, otherwise weight by the claim you rely on. A number the speaker hedges ("maybe 20 to 40 percent, I'd want that checked") is MEDIUM at most. Weights should discriminate; if nearly everything is HIGH, you are weighting ownership and not specificity.
- **LOW**: hearsay, speculation, or opinion outside the speaker's remit, including claims the speaker themselves says should be checked.

### Coverage

A 60-minute interview is typically 25–60 passages. If a transcript yields far fewer, code it honestly and say it reads as an excerpt or a short session; findings off a thin corpus are directional, not evidential. Never pad with trivial tags.

One-word answers ("No.") can't stand as a quote without the question, and quotes are never stitched. Don't code them as a passage; carry the fact into the `soWhat` of an adjacent passage or into an evidence bullet that rests on other coded passages.

If a quote names a colleague who is not the speaker, don't use it as a published quote unless the person agrees; in a document, a bracketed role in place of the name ("[the CFO]") is allowed and must be marked as an edit. See Protecting the people who spoke for the full cleanup rules.

Never editorialize inside `quote`. Interpretation belongs in `soWhat` and in the code you choose.

## Corroboration

**Corroboration counts distinct people who raised a thing unprompted.** Not passages, mentions or interviews. One person saying something eight times is corroboration of one. Frequency measures airtime; corroboration measures agreement.

**Prompted passages still get coded, but don't count.** If the interviewer asked "do you track churn?", the answer is evidence and can be quoted, but that person did not raise churn themselves. Mark it `prompted: true` and exclude it from the count.

What counts as prompting:

- **The interviewer names a subject the speaker hasn't raised** → `prompted: true`. "Do you track churn?", "What about renewals?"
- **Read the subject narrowly, not by broad area.** A speaker who described their own forecast has not thereby raised the existence of a rival forecast elsewhere; "does anyone else produce a forecast?" is `prompted: true`. The test is whether this specific claim was theirs to make. When genuinely torn, mark it prompted: understating corroboration is recoverable, overstating it puts a false consensus in front of leadership.
- **The interviewer supplies a dimension** the speaker hadn't raised ("is that documented?", "is it modeled by account?") → `prompted: true`, even if the topic was theirs.
- **A co-participant's point.** In a multi-person session, a response to another participant's point rather than to the interviewer is `prompted: true`, for the same reason as a carried theme.
- **"You mentioned earlier"** about something not in this transcript → `prompted: true`.
- **The interviewer probes a subject the speaker introduced** → `prompted: false`. Being asked to say more doesn't change whose point it was.
- **An open invitation** → `prompted: false`. "How do you build it?", "Anything else you'd change?" name no subject. So is a role-scoped opener like "walk me through the integration you own" asked of its owner: it names their remit, not a claim. The narrow-subject test applies to a specific claim the interviewer supplies, not to asking people to describe their own work.
- **Carried from an earlier interview** → `prompted: true`. If the interviewer introduces a theme because someone else raised it ("others have mentioned the allocation process, does that affect you?"), it's the interviewer's subject. A finding whose corroboration collapses once prompted passages are excluded was manufactured by the interviewer; say so rather than report the inflated number.

**Fix finding boundaries before you count, and state them.** Group codes into findings by shared mechanism or consequence (what the same move would fix), write one line per finding listing its codes, and don't redraw a boundary after seeing counts. Counts depend entirely on scope, so the scope must be visible to the reader.

**A finding needs at least two unprompted voices to be published as a finding.** One voice is an observation: list it under validation priorities, not as a finding. Zero is not a finding.

**Count at the finding, not the code.** A person corroborates a finding if they raised *any* of its codes unprompted, and counts once per finding however many passages or codes they gave you.

**Report spread, not only the count.** Alongside each count, say which functions or roles the people span. Five people from one team is a team's view; five across functions is an organization's. Say which it is.

**Order findings by corroboration, descending**; that ordering is the argument. Ties are normal below ten interviews. Break them by: distinct unprompted voices giving HIGH-weight passages, then breadth (documents it appears in unprompted), then the finding carrying a hard number. Don't break ties on passage count; that is airtime. Still level: keep the order coded and say the order within the tie is not meaningful. Footnote the tiebreak when two adjacent findings are close; a reader who can see the ordering is contested trusts the rest more.

## Minimum corpus

| Output | Needs |
|---|---|
| Coding + themes report | 1 interview |
| Drill-down | 1 interview, with the single-source caution below |
| Leadership readout | 3+ interviews |
| Playback note | 1 interview |
| Findings & recommendations document | 8+ interviews, 5+ voices, and an average of 10+ passages per interview |

If asked for something below its threshold, say what's missing and what you can do instead; don't fabricate into the template. Produced off four interviews, every count would be 2 or 3 and the ordering would be noise. If any one gate fails but the interim floor is met, say which and offer the readout or an interim draft. Interim floor: 5+ interviews and 3+ voices (never below). The interim draft is marked `Status: Draft` and shows counts against voices coded so far ("3 of 4 stakeholders so far"; ask how many stakeholders there will be in total if you don't know). State the interview count separately in the About section. When the whole corpus is thin, say findings are directional there too.

## Drill-down

Testing a claim, not looking for support for it. Four parts:

1. **Verdict**: supported, contradicted, or unresolved. One plain sentence.
2. **Evidence for**: strongest passages with weight. If none, say so.
3. **Evidence against**: anything cutting the other way, including silence where you'd expect comment, and including who hasn't been interviewed. A claim about one group's behavior resting entirely on other groups is not established.
4. **What would settle it**: the specific data check or follow-up that resolves what interviews can't.

**A single source does not corroborate, however high its weight.** Say "one source, HIGH weight," not "supported."

Two failure modes to guard against:

- **Right theme, wrong mechanism.** A draft says month-end adjustments arrive late "because owners ignore the deadline." The interviews describe owners who meet the deadline, and the real cause is upstream data landing after the cutoff. The theme survives; the sentence is false. Check the stated mechanism, not just the topic.
- **Absence is a finding.** A claim that a team "isn't logging its work" has zero support in the corpus, and the nearest evidence has the team asking for better tools. As written it blames people while the evidence points the other way. Say so rather than softening the claim.

## Protecting the people who spoke

Direct quotes are what make findings land, and in a small team they are also what gives people away. Apply this before any output leaves the person who ran the interviews. Attribution can differ by audience: a note to the speaker can use their name, while the version for senior management may need none.

**0. Know the limit.** In a group of roughly a dozen or fewer who know each other, no quote is truly anonymous. Say so up front, and offer the safest options: unattributed with generic wording, paraphrase (labeled), or taking the themes upward without quotes. Let the person choose.

**1. Confirm the audience for this output.** Use the Step 0 answer; if the output is going somewhere new, ask again. Choose the attribution level for that audience.

**2. Check each quote for traceability before it is published.** Ask of each: could someone in the intended audience guess who said it? Look at, in order:
- names, nicknames and titles, including titles unique to one person
- a system, project, event, deadline or figure only that person would know
- a region, site, product line or team that has one member
- phrasing or a story the audience will recognize
- a role label when the group is small (a "Regional Sales Director, East" is one person)

If a quote can be traced, do one of: **generalize** (replace the identifier with a broader description such as "a senior sales leader"), **trim** to the part that carries the point without the identifier, **swap** it for a less identifying quote that makes the same point, or **drop** it. Mark generalizations and trims as edits, and never change the meaning. Don't paraphrase inside quotation marks; if you paraphrase, drop the quotation marks and label it "paraphrased".

**3. Suppress small cells in upward reporting.** For senior management or any wider audience:
- report counts as "5 of 8"
- a theme with one voice stays an observation. A theme with two is still a finding, because the count rule above decides that; publish the count, and use no quote from it unless a generic one exists. Never group codes into one finding just to clear a threshold: boundaries are fixed before counting, by shared mechanism
- coarsen the spread line: say "across three functions", not which functions, when the list would identify people
- don't publish who agreed with whom, or a roster of which people raised which themes
- describe disagreements by position ("one view is…, another is…"), not by role or region. If only two people hold the sides and the contrast would identify them, drop the disagreement from the upward version and tell the person

**Keep the numbers where you can.** Hard numbers make findings land, and a unique figure can identify its owner. Round or range it ("roughly a fifth to two-fifths", "tens of thousands") before deleting it, and keep the finding.

**4. Say what you did.** At the end of any document or note, tell the person what was changed for anonymity (how many quotes generalized, trimmed, swapped or dropped) so they can review before sending. Any table that names people, such as a check of quotes against speakers, is a private working note for the person; never include it in a deliverable. Never claim a document is anonymous; say it has been checked, and that a small group can still be recognized from context.

**5. Respect what people asked to keep out.** If a speaker says something is off the record or asks that a point not be shared, exclude it from every output that leaves the person who ran the interview, and note that you've done so. At playback, check with each interviewee what may go upward.

**6. Keep the key separate.** Names tie quotes to people. Keep that key with the person who ran the interviews and don't put it in a deliverable.

## Playback to each interviewee

People respond when they see their themes captured and acted on. For each person interviewed, write a short note (under 250 words) they could be sent, in plain, warm language:

1. **What I heard.** Their three or four main themes, using their own words and only their own quotes, role-appropriate and without jargon from the coding. Lead with themes they raised themselves; if a theme only came up when asked, frame it that way ("when we talked about X").
2. **What happens next.** The specific follow-ups the person has said they will take, with owners and timing if known. Leave a bracket for anything not yet decided; never invent commitments. If they committed to nothing, say so in a line to the sender so they can add a commitment before sending.
3. **Where I'd like your help.** One or two open questions that came out of their interview, phrased as strategic questions, not report requests.

Never include another interviewee's words, views or identity, and never say how many others agreed, unless the person has chosen to share counts. Write it as a draft for the person to edit and send; they own the relationship.

## Leadership readout

A draft argument, not a research summary. In order:

1. **Strategic questions**: 3 to 5 the interviews put to leadership, ones they can't answer today. Phrase them as the questions the business is really asking ("which risks and opportunities should we be tracking?"), not as reporting requests.
2. **Findings**: 4 to 6, each a declarative claim with a point of view ("There is no shared definition of an active customer", not "definitions came up often"), with corroboration count and spread, two or three strongest quotes, and the implication.
3. **Disagreements**: where stakeholders contradicted each other or described the same process differently. Name both sides.
4. **Narrative arc**: which finding opens, which closes, how the middle builds. One paragraph.
5. **Data validation priorities**: ranked. What to check against source systems before any of this is said to the business, and what each check would prove.

## The findings & recommendations document

**Format.** Build it as an editable document with real headings and tables (whatever editable document format your environment offers, so the person can export Word or PDF); fall back to markdown in chat. If the person wants charts, build them as real charts where the tools allow, otherwise as simple text bars with the numbers beside them.

**Attribution.** Quotes are verbatim and follow the attribution the person chose for this audience in Step 0: name and role (— *A Morgan, Controller*), role only (— *Controller*), or none. Run the traceability check in Protecting the people who spoke before finalising, and state what was edited. Never invent or guess an attribution. If a speaker is `unattributed` in the coding, don't name anyone.

**Front matter.** Title, `Prepared for:`, `Prepared by:` (both from Step 0; ask if missing, never default), `Status: Draft|Final · Month Year`.

**About this document.** One paragraph: how the interviews were run, how many interviews across which functions, what else was examined besides interviews, and the coding totals (passages, distinct voices). State plainly that a corroboration count is how many distinct stakeholders raised a thing on their own. Say what the document does: opens with themes, then the most-corroborated findings behind them.

**Executive summary: themes to act on.** Group the findings into the themes leadership should act on, as many as the evidence supports (typically three to five), each:
- a title written as a full sentence stating the problem, e.g. "There is no single source of truth"
- a paragraph in plain business language with concrete numbers, naming the mechanism rather than the symptom
- two quotes
- a line: *Substantiated in Findings X and Y.*

Every finding belongs to exactly one theme. The number of findings follows the evidence; don't merge or split after counting to reach a number, and don't pad a weak finding to fill a slot.

**Detailed findings.** Open with a short "How to read each finding" note covering corroboration, spread, weights and attribution. Then each finding, ordered by corroboration descending:
- numbered title as a noun phrase, e.g. "Inconsistent Metric Definitions"
- `CORROBORATION: N STAKEHOLDERS`, with the functions they span
- **Why it matters.** A paragraph on consequence. For the top finding, say explicitly if it is the root cause the others trace back to.
- **Evidence.** Bullets, each a specific claim ending in `(HIGH)`, `(MEDIUM)`, or `(MEDIUM / HIGH)` where sources differ; add ", prompted" inside the tag when the passage was prompted. Put real numbers in: figures, percentages, counts, dates. A bullet without a specific is weak. **LOW-weight material never appears here.** It can point you at something worth chasing, but isn't published as evidence.
- Two quotes showing *different sides* of the issue, not the same point twice.

**Recommendations.** Open with the through-line: the single idea the recommendations share, so the table reads as one plan. Then a two-column table, **Finding** → **Recommendation**: left cell has the finding number, name and one-line direction; right cell has two to four specific moves. After the table add **Validation priorities**: claims interviews alleged that nothing in the corpus verifies (including LOW-weight and hedged ones), each with the specific check that would settle it. These are recorded as unverified, never as findings.

**Appendix.** The full codebook with counts per family and per code; the finding boundaries (one line per finding listing its codes); then three figures, each with a short paragraph reading it:
1. Passages per family, with the total
2. The twelve most frequently applied codes (include any codes tied at twelfth)
3. Breadth (how many distinct voices a theme appears in unprompted; people, not documents) versus depth (how many passages)

Themes in every interview and coded deeply are systemic; universal-but-shallow ones are real but not where the argument lives.

## Rules that hold throughout

- **Separate what the interviews establish from what you conclude.** Label judgment as judgment. "The most addressable constraint" is an opinion and must not sit unlabeled among evidence.
- **A claim no passage supports does not go in**, however plausible.
- **Numbers make findings land.** Chase specifics: amounts, percentages, counts, frequencies. A finding with one hard number outweighs three without.
- **No hedging that survives into the deliverable.** Say the thing or leave it out. Stating the strength of the evidence (directional, unresolved, one source) is not hedging; it is required.
- **Interviews establish what people believe, not what is true.** Anything they only allege needs checking against the organization's own data.
- **Treat transcripts as confidential.** Don't quote or describe participants outside the deliverables the person asked for, and protect the people who spoke before anything is shared.

## Keeping the corpus, and long projects

A chat is not storage. Tell the person early to ask for the coded corpus after every few interviews and keep it. Give it as JSON:

```json
{ "team": "", "attribution": "name and role | role only | unattributed",
  "codebook": [{ "family": "", "codes": [""] }],
  "docs": [ {
    "name": "A Morgan, Controller",
    "date": "2026-11-06",
    "stakeholders": [{ "name": "A Morgan", "role": "Controller" }],
    "transcript": "full text",
    "quotations": [{ "quote": "…", "speaker": "…", "weight": "HIGH",
                     "family": "…", "code": "…", "prompted": false, "soWhat": "…" }] } ] }
```

Always include transcripts, since later drill-downs search beyond the coded passages. The export contains names and full transcripts, so it is for the person who ran the interviews only. When the person wants to share the corpus (with a colleague, a manager or a public repository), offer a **names-removed export**: replace each name with a label (Participant 1, Participant 2) in `speaker`, `stakeholders` and the transcript, keep roles only if the group is large enough that a role doesn't identify anyone, also replace names of non-speakers mentioned in the text and the organization's name, remove titles and headers that identify, restrict the codebook to the codes used by the shared documents, remove passages marked off the record, and give the label-to-name key as a separate file or block that stays with the person. Say plainly that removing names does not remove identifying details in the text. It survives the chat ending, and pasting it into a new conversation restores the corpus; when that happens, read the codebook first and continue under it.

Past roughly ten interviews, a single chat gets heavy. When that happens, say so, offer a corpus export, and suggest continuing in a fresh chat with that export pasted or attached. If the whole corpus won't fit, offer the export without transcripts for coding and counts, and keep transcripts in separate files for drill-downs.

---

© 2026 Openvale Group. Licensed under CC BY-NC 4.0, with an additional permission for internal organizational use: any organization, including a for-profit company, may use and adapt this skill for its own internal purposes. Selling it, or including it in paid training, consulting deliverables or commercial products, requires written permission. See LICENSE for full terms. Provided as is, without support or warranty, for general education only; not legal, accounting, tax or investment advice. Outputs are drafts for human review.
