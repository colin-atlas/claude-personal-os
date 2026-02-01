# Personal Operating System for Claude Cowork

A system for running structured daily workflows with Claude as your AI executive assistant.

## What This Is

This is a "second brain" and personal operating system that helps you:
- Start each day with a structured morning routine
- Prep for and debrief meetings
- Track projects, decisions, and delegations
- Run weekly reviews and planning sessions
- Draft communications in your voice
- **Build custom skills to automate your own workflows**

## Requirements

**Claude Cowork requires a paid Claude account** (Pro, Team, or Enterprise). Cowork is not available on the free tier.

## Quick Start

**Step 1:** In Claude Cowork, select a folder for your workspace (or create a new one called `claude-cowork`).

**Step 2:** Copy this entire prompt and send it to Claude:

---

```
I want to set up the Personal Operating System from this GitHub repo: https://github.com/colin-atlas/personal-os-cowork

Please:
1. Create the folder structure (inbox, outbox, outbox/SOD, outbox/weekly, outbox/drafts, logs, skills, second-brain)
2. Fetch and save all the template files from the repo:
   - CLAUDE.md (root)
   - schedule.md (root)
   - skills/sod.md
   - skills/eod.md
   - skills/meeting-prep.md
   - skills/debrief.md
   - skills/weekly-review.md
   - skills/draft-message.md
   - skills/build-skill.md
   - second-brain/profile.md
   - second-brain/company.md
   - second-brain/team.md
   - second-brain/projects.md
   - second-brain/decisions.md

3. After creating the files, ask me questions to personalize:
   - Profile.md — my goals, work style, zone of genius
   - Company.md — mission, values, objectives
   - Team.md — who I work with (EA, direct reports, advisors)
   - Projects.md — what I'm working on
   - Schedule.md — my weekly meeting rhythms

4. Show me the folder structure when done and explain how to use it.
```

---

**Step 3:** Answer Claude's personalization questions to fill in your second brain.

**Step 4:** You're set! Attach `CLAUDE.md` to start any new session.

## How to Use It

| Say This | What Happens |
|----------|--------------|
| "let's start our day" | Morning routine — context load, priorities, task planning |
| "prep me for [meeting]" | Meeting preparation with talking points and agenda |
| "debrief" | Post-meeting capture — decisions, action items, follow-ups |
| "draft a message to [person]" | Communication drafting in your voice |
| "weekly review" | Friday planning — wins, patterns, next week priorities |
| "wrap up" | End of day — log progress, prep tomorrow |
| "build a skill" | Create a new custom workflow for any repeating task |

## File Structure

```
claude-cowork/
├── CLAUDE.md              ← Attach this to start sessions
├── schedule.md            ← Your weekly rhythms
├── second-brain/
│   ├── profile.md         ← Your goals and preferences
│   ├── company.md         ← Mission, values, objectives
│   ├── team.md            ← People you work with
│   ├── projects.md        ← Active projects and tasks
│   └── decisions.md       ← Decision log
├── skills/                ← Workflow scripts
│   ├── sod.md             ← Start of Day
│   ├── eod.md             ← End of Day
│   ├── meeting-prep.md
│   ├── debrief.md
│   ├── weekly-review.md
│   ├── draft-message.md
│   └── build-skill.md     ← Create new skills
├── inbox/                 ← Drop files for processing
├── outbox/
│   ├── SOD/               ← Daily briefings
│   ├── weekly/            ← Weekly reviews
│   └── drafts/            ← Message drafts
└── logs/                  ← Session logs
```

## Building Custom Skills

The real power of this system is that **you can create your own skills** for any workflow you repeat.

Say **"build a skill"** and Claude will walk you through:
1. Defining what the skill does
2. Setting trigger phrases
3. Mapping out the step-by-step workflow
4. Creating the skill file
5. Updating CLAUDE.md to recognize the new triggers

**Example skills you might build:**
- "process inbox" — Triage and organize files dropped in inbox/
- "prep weekly email" — Draft your weekly team update
- "client onboarding" — Run through your new client checklist
- "content review" — Review and give feedback on drafts
- "quarterly planning" — Structure your quarterly goal-setting

## Customization

- **Build new skills:** Say "build a skill" to create workflows for your repeating tasks
- **Modify existing skills:** Edit any skill file in `skills/` to change the steps
- **Update your context:** Keep `second-brain/` files current for better Claude responses
- **Add trigger phrases:** Edit `CLAUDE.md` to add new ways to activate skills

## Sharing with Your EA (Optional)

Claude Cowork works from a local folder on your computer. If you want to share your workspace with an EA or team member, you can sync your local folder to a cloud platform.

**How to set it up:**
1. Create your `claude-cowork` folder locally (this is where Cowork will read/write files)
2. Sync that folder to a cloud platform like Google Drive, Dropbox, or OneDrive
3. Share the synced folder with your EA

**What this enables:**
- Your EA can see your daily briefings in `outbox/SOD/`
- Your EA can drop files into `inbox/` for you to process
- You can share delegation queues and project updates in real-time
- Your second brain stays in sync across your workflow

**Example with Google Drive:**
1. Install Google Drive for Desktop
2. Move your `claude-cowork` folder into your Google Drive folder (or create it there)
3. In Google Drive, right-click the folder → Share → Add your EA's email
4. Select the synced folder when starting Claude Cowork
