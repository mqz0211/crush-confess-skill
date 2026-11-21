# Crush Confess Agent Skill (`crush-confess`)

An open [AgentSkills.io](https://agentskills.io)-compatible skill that helps AI assistants assess relationship readiness, choose safe timing and delivery mediums, and draft clear, low-pressure romantic confessions or date invitations tailored to cultural context.

## What This Skill Does

- **Context Intake:** Asks only missing essentials (relationship baseline, cultural context, reciprocity signals, and logistics).
- **Readiness Check:** Evaluates whether to recommend a light date ask, a formal exclusivity check, warming rapport first, or pausing for boundary/power-dynamic risks.
- **Channel & Setting Guidance:** Prioritizes calm 1-on-1 in-person conversations, with situational rules for calls, texts, and handwritten notes.
- **Low-Pressure Scripts:** Drafts concise, proportionate options with explicit room to decline—never guilt-tripping, public ambushes, or heavy "feelings dumps."
- **Rejection Playbook:** Always includes respectful, calm fallback responses if she declines or needs time to think.

## Repository Structure

```text
crush-confess/
├── SKILL.md      # Core skill instructions & YAML metadata
├── README.md     # Documentation & installation guide
├── LICENSE       # MIT License
└── .gitignore    # Standard ignore rules
```

## Installation

### Using the `skills` CLI (Recommended)

Works across Claude Code, Cursor, Codex, GitHub Copilot, Gemini CLI, Windsurf, and other compatible agents:

```bash
# Install into the current project
npx skills add mqz0211/crush-confess-skill

# Or install globally across all projects
npx skills add mqz0211/crush-confess-skill -g
```

*(If using a multi-skill repository layout under `skills/`, target the skill directly:)*

```bash
npx skills add mqz0211/crush-confess-skill --skill crush-confess
```

### Manual Installation

Clone or copy the `crush-confess/` folder into your agent's skills directory (for example, `.agents/skills/crush-confess/` in your project or `~/.agents/skills/crush-confess/` globally).

## Usage Examples

Once installed, your agent discovers the skill automatically when relevant, or you can invoke it directly (e.g., `/crush-confess`):

- *"I've been close friends with someone at university for a year and we text daily. Should I confess my feelings?"*
- *"I've gone on 3 great dinner dates with a girl in Penang. How do I ask to make things official without making it awkward?"*
- *"She said she just wants to stay friends—how do I reply respectfully?"*

## Validation & Maintenance

To verify `SKILL.md` formatting and frontmatter constraints locally:

```bash
npx skills-ref validate .
```

To update an installed skill later, re-run `npx skills add <your-username>/<your-repo>`. To remove it, delete the `crush-confess` folder from your agent's skills directory or run `npx skills remove crush-confess`.

## Safety & Scope

This skill is designed strictly for drafting, evaluating, and coaching—it instructs agents never to send messages autonomously. If you wire your agent to external messaging MCP tools, add `disable-model-invocation: true` to `SKILL.md` frontmatter so the skill only runs on explicit `/crush-confess` invocation.

## License

MIT — see [LICENSE](LICENSE) for details.
