# End of Day (EOD) Workflow

Execute these steps IN ORDER. Complete each step fully and show the required OUTPUT before moving to the next step.

**Do not skip steps.**

---

## Step 1: Load Context

Read these files silently:
- `second-brain/projects.md`
- `outbox/SOD/[today's date].md` (today's briefing, if it exists)
- `second-brain/decisions.md`

**OUTPUT required before proceeding:**
```
📋 Context loaded.
- Today: [Day of week, Date]
- SOD briefing found: [Yes/No]
- Tasks planned today: [List from SOD if available]
```

---

## Step 2: Review the Day

Ask:

> **Let's wrap up. Quick review:**
> 1. What got done today?
> 2. What didn't get done? (And why?)
> 3. Any decisions made that we should log?
> 4. Anything from your EA's EOD to capture? (if applicable)

**STOP and wait for answers before proceeding.**

---

## Step 3: Summarize Day

**OUTPUT required before proceeding:**
```
📝 **Day Summary**

**Completed:**
- ✅ [Item 1]
- ✅ [Item 2]

**Incomplete:**
- ⏳ [Item 1] — Reason: [why]
- ⏳ [Item 2] — Reason: [why]

**Decisions made:**
- [Decision 1]
- [Or "None to log"]

**From EA's EOD:**
- [Summary or "Not shared / N/A"]
```

---

## Step 4: Process EA's EOD (If Applicable)

If an EA's EOD was shared, extract and organize:

**OUTPUT required before proceeding:**
```
👩‍💼 **EA's EOD Summary**

**Completed today:**
- [What they finished]

**Still open:**
- [Items still in progress]

**Blockers for me:**
- [Things they need from me tomorrow]

**Handoffs/prep for tomorrow:**
- [Anything I should know]
```

If not shared, note: "EA's EOD not provided — skipping."

---

## Step 5: Update Projects

Based on today's progress, identify updates for `projects.md`:

**OUTPUT required before proceeding:**
```
📁 **Project Updates**

| Project | Update |
|---------|--------|
| [Project name] | [Task completed / status change / new blocker] |
| [etc.] | |

Should I update projects.md with these changes? (Yes/No)
```

**STOP and wait for confirmation before updating the file.**

---

## Step 6: Log Decisions

If any decisions were made today, format them for `decisions.md`:

**OUTPUT required before proceeding:**
```
📒 **Decisions to Log**

## [Date] — [Decision Title]
**Context:** [What prompted this]
**Decision:** [What was decided]
**Reasoning:** [Why]
**Owner:** [Who made the call]
**Outcome:** [TBD — to be filled later]

Should I add this to decisions.md? (Yes/No)
```

If no decisions, note: "No decisions to log today."

**STOP and wait for confirmation before updating the file.**

---

## Step 7: Prep Tomorrow

Based on incomplete items, EA's EOD, and schedule.md:

**OUTPUT required before proceeding:**
```
🔮 **Tomorrow Preview**

**Top 3 priorities:**
1. [Priority 1 — why it matters]
2. [Priority 2]
3. [Priority 3]

**Waiting on EA:** (if applicable)
- [Items they're working on that I need]

**Tomorrow's meetings:** (from schedule.md)
- [Meeting 1]
- [Meeting 2]

**Prep needed:**
- [Any meeting prep or deadlines]
```

---

## Step 8: Create EOD Log

Save to `logs/[YYYY-MM-DD].md`:

```markdown
# Daily Log — [Day of Week], [Month DD, YYYY]

## Completed
- [Item 1]
- [Item 2]

## Incomplete
- [Item 1] — [Reason]

## Decisions
- [Decision or "None"]

## Delegation Status
- [Updates from EA's EOD or "N/A"]

## Tomorrow's Top 3
1. [Priority 1]
2. [Priority 2]
3. [Priority 3]

## Notes
[Any other context]
```

**OUTPUT required before proceeding:**
```
✅ EOD log saved: [link to file]
```

---

## Step 9: Close Out

**OUTPUT required:**
```
🌙 **EOD Complete**

- Day logged ✓
- [X] project updates made
- [X] decisions logged
- Tomorrow's top 3 identified

Anything else before you sign off?
```

**STOP and wait for response.**
