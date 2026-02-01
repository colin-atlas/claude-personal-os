# Start of Day (SOD) Workflow

Execute these steps IN ORDER. Complete each step fully and show the required OUTPUT before moving to the next step.

**Do not skip steps. Do not jump to execution.**

---

## Step 1: Load Context

Read these files silently:
- `second-brain/profile.md`
- `second-brain/company.md`
- `second-brain/projects.md`
- `schedule.md`
- Check `inbox/` for any files

**OUTPUT required before proceeding:**
```
📋 Context loaded.
- Today: [Day of week, Date]
- Key Objectives: [List top 3 objectives]
- Active Projects: [Count] projects, [Count] open tasks
- Inbox: [Count] items (or "empty")
- Today's scheduled meetings: [List from schedule.md based on day of week]
```

---

## Step 2: Ask the 4 Questions

Ask these questions exactly:

> **Let's kick off the day. Quick answers:**
> 1. What's the #1 thing that would make today a win?
> 2. What's on your todo list today?
> 3. Any issues or urgent items I should know about?
> 4. Anything from your EA's SOD to capture? (if applicable — paste it)

**STOP and wait for answers before proceeding.**

---

## Step 3: Summarize Inputs

After receiving answers, summarize what you heard.

**OUTPUT required before proceeding:**
```
📝 Got it. Here's what I heard:

**Today's Win:** [Summarize #1 priority]

**Todo List:**
- [Item 1]
- [Item 2]
- [etc.]

**Issues/Urgent:** [Summarize or "None flagged"]

**EA's SOD:** [Confirm received or "Not shared / N/A"]
```

Ask: "Did I capture that right?"

**STOP and wait for confirmation before proceeding.**

---

## Step 4: Process EA's SOD (If Applicable)

If an EA's SOD was shared, extract and organize:

**OUTPUT required before proceeding:**
```
👩‍💼 **EA's SOD Summary**

**Their priorities today:**
- [What they're focused on]

**Waiting on me:**
- [Items needing my input/approval/decision]
- ⚠️ [Flag any that are blocking or time-sensitive]

**Delegation updates:**
- [Status on previously delegated items]

**Coordination notes:**
- [Where their work connects to my priorities]
```

If no EA SOD was shared, note: "EA SOD not provided — skipping this section."

---

## Step 5: Analyze Tasks & Recommend

Review the todo list and recommend how to handle each item.

**Use this prioritization lens:**
- Does this move a key objective forward?
- Is this in my Zone of Genius or should it be delegated?
- What's the cost of delay?
- Can Claude or an EA do 80% of this?

**OUTPUT required before proceeding:**

```
📊 **Task Analysis & Recommendations**

| Task | Recommendation | Reasoning |
|------|----------------|-----------|
| [Task 1] | **Claude does it** | [Why] |
| [Task 2] | **Claude starts, you finish** | [Why] |
| [Task 3] | **Delegate to EA** | [Why] |
| [Task 4] | **You handle** | [Why — Zone of Genius] |
| [etc.] | | |

**My top recommendation:** [Which task should be the focus, and which should Claude start immediately]
```

---

## Step 6: Build Delegation Queue (If Applicable)

Based on the task analysis, create a list of items to delegate.

**OUTPUT required before proceeding:**
```
📤 **Delegation Queue**

| Task | Context | Deadline | Expected Outcome |
|------|---------|----------|------------------|
| [Task] | [What they need to know] | [When] | [What done looks like] |
| [etc.] | | | |
```

If no items to delegate, note: "No delegation items today."

---

## Step 7: Create Daily Briefing

Save the daily briefing to `outbox/SOD/[YYYY-MM-DD].md` using this format:

```markdown
# Daily Briefing — [Day of Week], [Month DD, YYYY]

## Today's Focus
[#1 priority from conversation]

## EA Sync (if applicable)
**Their priorities:** [From their SOD]
**Waiting on me:** [Items needing my input]
**Delegation updates:** [Status on open items]

## Task Plan

### Claude's Tasks
- [ ] [Tasks Claude is handling]

### Delegation Queue
- [ ] [Task] — [Context] — [Deadline]

### My Tasks
- [ ] [Tasks I'm handling personally]

## Today's Schedule
[Meetings from schedule.md for this day of week]

## Inbox Items
[Files processed or "No items"]

## Notes
[Any other context for the day]
```

**OUTPUT required before proceeding:**
```
✅ Daily briefing saved: [link to file]
```

---

## Step 8: Confirm Before Execution

**OUTPUT required:**
```
🎯 **SOD Complete**

Your briefing is ready. Here's the plan:

**Claude will start on:**
- [Task 1]
- [Task 2]

**Delegation queue:**
- [Count] items ready for handoff

**For you:**
- [Your focus tasks]

What would you like me to start on first?
```

**STOP and wait for direction.**

---

## Reminders

- Today is [check current day] — adapt questions for Monday (weekly kickoff) or Friday (weekly planning)
- If Monday: Add "What are your priorities for this week?" to the questions
- If Friday: Add "Anything to prep for weekly review later?"
- Reference active projects from `projects.md` when analyzing tasks
- Flag anything that conflicts with key objectives
