# agent-starter

A minimal Claude Code project skeleton: `CLAUDE.md` with working rules plus a reviewer subagent.
Public demo repo for the **Agent Shipped** channel; clone it and try the prompts from the videos.

```
CLAUDE.md                 project rules the agent reads on every session
.claude/agents/reviewer.md  read-only reviewer subagent
.claude/settings.json     hook that blocks commits containing obvious secrets
```

## Shown in

Videos on the Agent Shipped channel that use this repo:

- [My subagent stopped halfway. One missing path was why #Shorts](https://youtu.be/qoobDT2fCYE) · E007 · 2026-11-07
- [My subagent hook read an empty field. Now a bad report exits 2 #Shorts](https://youtu.be/EfsRjxtHwpc) · E004 · 2026-11-14
- [My PM agent wrote no code. My first gate blocked a legal write](https://youtu.be/-_t_ZsufwvU) · E008 · 2026-11-15 · [write-up](https://dev.to/agentshipped/scope-gate-for-subagents-3-tasks-1-blocked-write-34pa)
- [I let a 12-line hook deny risky commands before Claude Code asks #Shorts](https://youtu.be/rG6am6oF8SI) · E018 · 2026-11-19
- [I hit one .env deny rule three ways: Read, cat, grep #Shorts](https://youtu.be/Etj_FNGDxw0) · E017 · 2026-11-21
