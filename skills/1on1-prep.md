# 1:1 Meeting Prep Workflow

Execute these steps IN ORDER. Complete each step fully and show the required OUTPUT before moving to the next step.

**Do not skip steps.**

---

## Step 1: Identify Direct Report

If not specified in the trigger, ask: **"Which 1:1 are you prepping for?"**

Present options from `second-brain/team.md` under "Direct Reports" section.

**Common triggers:**
- "prep my 1:1 with [Name]" → That person
- "[Name] 1:1 prep" → That person
- "prep for Thursday" → Check who has Thursday 1:1s in team.md

**STOP and wait for answer if not specified.**

---

## Step 2: Get 1:1 Doc Link

Read `second-brain/team.md` and find the `1on1_doc` field for the identified person.

If no doc link exists, ask user to provide it.

**Note:** This workflow assumes a rolling 1:1 document with dated sections or tabs. If using a different format, adapt accordingly.

---

## Step 3: Fetch Doc Content

Fetch the 1:1 document content.

**Expected doc structure:** Rolling document with dated sections (tabs, headers, or pages). Each section is a separate meeting agenda.

To access:
1. Fetch the document
2. Identify dated sections — look for date patterns
3. Read the **most recent section** for current week's agenda
4. Read the **previous section** for last week's action items

**OUTPUT required before proceeding:**
```
📋 1:1 doc loaded for [Name]

**Current week section:** [Date found or "Not yet created"]
**Previous week section:** [Date]
```

---

## Step 4: Extract Current Week

From the current week's section, extract:

**Their Updates:**
- What they're reporting on
- Progress on their goals/metrics
- Wins they're sharing

**Blockers & Asks:**
- Where they need help
- Decisions they need from you
- Resources or support requested

**Discussion Topics:**
- Items they want to discuss
- Questions they're raising
- Issues flagged for attention

---

## Step 5: Review Previous Week

From the prior week's section, extract:

**Action Items from Last 1:1:**
- Items assigned to them — did they complete?
- Items assigned to you — did you complete?
- Commitments made — were they kept?

**Unresolved Items:**
- Topics that were parked or tabled
- Issues that may need follow-up

---

## Step 6: Cross-Reference Context

Pull additional context from Second Brain:

```
second-brain/team.md     # Their role, metrics, responsibilities
second-brain/company.md  # Key objectives, company goals
second-brain/projects.md # Active projects they own
```

Note connections:
- How their updates relate to company objectives
- Whether their blockers impact other projects
- If their asks align with their responsibilities

---

## Step 7: Generate Prep Summary

**OUTPUT required before proceeding:**

```markdown
# 1:1 Prep: [Name] — [Date]

## At a Glance
- **Role**: [from team.md]
- **Responsibilities**: [from team.md]
- **Meeting Cadence**: [day]

---

## What They're Bringing

### Updates & Wins
[Summarize their reported progress]

### Blockers & Asks
[What they need from you — prioritized]

### Discussion Topics
[What they want to talk about]

---

## Follow-Up from Last 1:1

### Their Action Items
- [ ] [Item] — Status: [Done/Open/Unknown]

### Your Action Items
- [ ] [Item] — Status: [Done/Open]

### Unresolved Topics
[Anything parked that should be revisited]

---

## Your Prep Notes

### Decisions Needed
[Decisions they're asking for — be ready to make them]

### Questions to Ask
[Suggested questions based on their updates]

### Context to Share
[Relevant info from company.md or projects.md they should know]
```

---

## Step 8: Save & Confirm

Save to: `outbox/drafts/1on1-prep-[name]-[YYYY-MM-DD].md`

**OUTPUT required:**
```
✅ 1:1 prep saved: [link to file]

Ready for your 1:1 with [Name]. Anything you want me to adjust or add?
```

**STOP and wait for response.**

---

## Adaptive Behavior

**If current week's section doesn't exist yet:** Note "No current week section found" and focus on prior action items + context from team.md.

**If you're running late:** Offer a 60-second verbal summary instead of full doc.

**If multiple 1:1s same day:** Offer to prep all of them in sequence.

**If a blocker is urgent:** Flag it prominently and suggest addressing first.

---

## Setup Notes

To use this skill effectively, make sure your `second-brain/team.md` includes for each direct report:
- `1on1_doc`: Link to your shared 1:1 document
- `1on1 Cadence`: Which day you meet
- `Responsibilities`: What they own
- `Current Focus`: Their key priorities

The 1:1 document works best as a rolling doc where each meeting has its own dated section, making it easy to review history and track action items over time.
