# myskills

A collection of my custom skills for Claude Code.

## Skills

| Skill | What it does |
|---|---|
| [enterprise-team](enterprise-team/SKILL.md) | Simulates a full enterprise software team (16 roles you can switch on or off) that works a task through the software development lifecycle, one role at a time, with handoffs, rework loops and minimal prompting. Run with `/enterprise-team <task>`. |

## Installing a skill

Link the skill's folder into `~/.claude/skills` so edits here take effect right away. On Windows (PowerShell):

```powershell
New-Item -ItemType Junction -Path "$env:USERPROFILE\.claude\skills\<skill>" -Target "<path to this repo>\<skill>"
```

On macOS or Linux:

```sh
ln -s "<path to this repo>/<skill>" ~/.claude/skills/<skill>
```
