# FLC Skunk Works - Session Prompts
**Copy-paste these prompts to start/end sessions with any AI assistant**

---

## STARTING A SESSION

### Option 1: Quick Start
```
continue
```
*Use when the AI already has context from files*

### Option 2: Full Context Start (Recommended for new AI sessions)
```
I'm continuing work on the FLC Skunk Works program.

Please read these files first:
1. @Program_Charter.md - Program mission and principles
2. @Active_State.md - Current state and active task

Then check the "For Next Session" section in @Active_State.md and continue from the Active Task.

Acknowledge what you've read and what you'll work on.
```

### Option 3: Initiative-Specific Start
```
I'm working on the [Initiative Name] initiative.

Please read:
1. @Program_Charter.md - Program context
2. @Active_State.md - Program state
3. initiatives/[initiative-slug]/Manifest.md - Initiative details
4. initiatives/[initiative-slug]/Active_State.md - Initiative state

Continue from the active task for this initiative.
```

---

## DURING A SESSION

### Get Status Report (SITREP)
```
SITREP

Generate a VP-ready status report including:
- Executive summary (2-3 sentences)
- Initiative status table (all initiatives)
- Value delivered to date (from @Value_Ledger.md)
- Blockers/risks (if any)
- Next 3 priorities

Keep it to one page equivalent. Make it audit-ready.
```

### Create New Initiative
```
new initiative: [Name]

Sponsor: [Who requested or who benefits]
Problem: [What problem this solves]
Value: [Expected ROI or benefit]

Please:
1. Create the initiative folder structure in /initiatives/[slug]/
2. Generate the Manifest.md using our template
3. Initialize the Active_State.md
4. Score against our selection criteria
5. Add to program @Active_State.md initiative board
```

### Value Check
```
value check

Review @Value_Ledger.md and:
1. Summarize current value delivered
2. Update projections if new information available
3. Identify gaps in value tracking
4. Suggest evidence we should gather
```

### Stakeholder Brief
```
stakeholder brief: [Stakeholder Name]

Generate a communication artifact for [Stakeholder Name] including:
- Relevant initiative updates
- Value delivered that matters to them
- Any asks or decisions needed
- Format per their preferences (from @Stakeholder_Map.md)
```

---

## ENDING A SESSION

### Standard End Session
```
end session

Please:
1. Summarize what we accomplished this session
2. Output the FULL updated @Active_State.md in a code block
3. If we worked on a specific initiative, also output its updated Active_State.md
4. Suggest a git commit message
5. Note what the next session should start with
```

### End Session + Value Update
```
end session

Also update @Value_Ledger.md if we delivered or discovered any new value this session.

Output:
1. Session summary
2. Updated @Active_State.md (full file, code block)
3. Updated @Value_Ledger.md sections if changed
4. Git commit message
5. Next session starting point
```

---

## SPECIAL COMMANDS

### Archive Initiative
```
archive initiative: [Name]

Please:
1. Move initiative folder to /archive/
2. Update @Value_Ledger.md with final value delivered
3. Remove from active tracking in @Active_State.md
4. Generate lessons learned summary
```

### Prepare for Stakeholder Meeting
```
prepare for meeting with [Stakeholder]

Using @Stakeholder_Map.md, prepare:
1. Key talking points
2. Data/metrics they care about
3. Any asks or decisions to make
4. Potential questions and answers
5. One-page leave-behind summary
```

### Weekly VP Update
```
weekly VP update

Generate a brief weekly update for VP including:
- Top 3 accomplishments this week
- Initiative status board
- Value delivered/projected
- Any blockers or decisions needed
- Next week's priorities

Format: Brief email or one-slider
```

---

## TIPS FOR EFFECTIVE SESSIONS

1. **Start focused:** Have a clear goal for each session
2. **Stay in scope:** One coherent chunk of work per session
3. **End cleanly:** Always run `end session` to save state
4. **Commit often:** Git commit after each session
5. **Track value:** Update @Value_Ledger.md whenever value is delivered

---

## TROUBLESHOOTING

### AI doesn't have context
Use the "Full Context Start" prompt above.

### State got out of sync
```
Please read @Active_State.md and @Program_Charter.md to resync.
Tell me the current state as you understand it.
```

### Need to reset an initiative
```
reset initiative: [Name]

Reread the Manifest.md and create a fresh Active_State.md
```

---

*Keep this file handy - copy-paste prompts to maintain session continuity across AI conversations.*
