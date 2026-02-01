# Build Skill Workflow

Execute these steps IN ORDER. Complete each step fully and show the required OUTPUT before moving to the next step.

**Do not skip steps. Do not jump to execution.**

---

## Step 1: Gather Skill Requirements

Ask these questions:

> **Let's build a new skill. Tell me about it:**
> 1. What should this skill do? (one sentence)
> 2. What trigger phrases should activate it? (e.g., "process inbox", "prep weekly email")
> 3. Walk me through the workflow — what happens step by step?
> 4. Does this skill need any external tools? (Gamma, Notion, Slack, etc.)

**STOP and wait for answers before proceeding.**

---

## Step 2: Confirm Understanding

**OUTPUT required before proceeding:**
```
📋 Here's what I'm building:

**Skill Name:** [kebab-case name, e.g., weekly-email]
**Purpose:** [One sentence]
**Triggers:** "[trigger 1]" / "[trigger 2]" / "[trigger 3]"
**Tools needed:** [List or "None — workflow only"]

**Workflow Steps:**
1. [Step 1]
2. [Step 2]
3. [Step 3]
[etc.]

Does this look right?
```

**STOP and wait for confirmation before proceeding.**

---

## Step 3: Write the Skill File

Create `skills/[skill-name].md` following this format:

```markdown
# [Skill Name] Workflow

Execute these steps IN ORDER. Complete each step fully and show the required OUTPUT before moving to the next step.

**Do not skip steps. Do not jump to execution.**

---

## Step 1: [First Step Name]

[Instructions for what to do]

**OUTPUT required before proceeding:**
\`\`\`
[Template for the output]
\`\`\`

---

## Step 2: [Second Step Name]

[Instructions]

**OUTPUT required before proceeding:**
\`\`\`
[Template]
\`\`\`

[Continue for all steps...]

---

## Step N: Confirm & Execute

**OUTPUT required:**
\`\`\`
✅ **[Skill Name] Complete**

[Summary of what was done/prepared]

What would you like me to do next?
\`\`\`

**STOP and wait to direct execution.**
```

**OUTPUT required before proceeding:**
```
✅ Skill file created: skills/[name].md
```

---

## Step 4: Update CLAUDE.md

Add the new skill to the Workflows table in `CLAUDE.md`:

| Trigger Phrase | Skill File | Purpose |
|----------------|------------|---------|
| "[triggers]" | `skills/[name].md` | [Purpose] |

Also update the File Locations section to include the new skill file.

**OUTPUT required before proceeding:**
```
✅ CLAUDE.md updated:
- Added to Workflows table
- Added to File Locations
```

---

## Step 5: Confirm Complete

**OUTPUT required:**
```
🎯 **Skill Built Successfully**

**New skill:** [name]
**Triggers:** [list]
**File:** skills/[name].md

Try it out by saying one of the trigger phrases!
```

---

## Conventions

- Skill files are flat: `skills/[name].md` (not nested folders)
- Use kebab-case for file names
- Every step needs an **OUTPUT required** section
- Include **STOP** points where user input is needed
- End with a confirmation step before execution
