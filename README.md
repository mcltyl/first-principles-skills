# First-Principles Thinking

**Cut through complexity by reasoning from fundamental truths.**

Tired of following "best practices" that don't fit your situation? Or getting stuck in analysis paralysis when facing new problems?

This Agent Skill teaches your AI to think from first principles:
- **Break down** problems to their most basic facts
- **Question** hidden assumptions everyone else accepts
- **Re-derive** solutions from scratch instead of copying patterns
- **Validate** reasoning by finding the weakest link

Works with Claude Code, Codex CLI, OpenClaw, and any Agent Skills-compatible tool.

---

## Installation

### npx skills

```bash
npx skills add git@github.com:mcltyl/first-principles-skills.git
```

### Manually

#### Claude Code

Add the contents of this repo to a `/.claude` folder in the root of your project.

#### OpenCode

```bash
git clone https://github.com/mcltyl/first-principles-skills.git ~/.opencode/skills/first-principles-skills
```

#### OpenClaw

```bash
git clone https://github.com/mcltyl/first-principles-skills.git ~/.openclaw/skills/first-principles
```

## Skills

| Skill | Description |
|-------|-------------|
| [first-principles](skills/first-principles) | First-principles thinking framework. Break down problems to basic facts and re-derive solutions from there. |

## The Five-Step Process

```
1. Identify Purpose    → What is this ultimately trying to achieve?
2. Break Down to Facts → What is verifiably true?
3. Find Assumptions    → What unexamined assumptions am I accepting?
4. Re-derive           → Given only these facts, what would I do?
5. Validate            → Which step is weakest?
```

## Example

**Question**: "Do *The Pathless Path* and *The Surrender Experiment* contradict each other?"

**Without first principles**: "Yes, one says choose your path, the other says surrender"

**With first principles**:
1. **Purpose**: Understand if two frameworks can coexist
2. **Facts**: Book A = choosing direction; Book B = letting go of attachment
3. **Assumption challenged**: "Choosing" and "letting go" are NOT mutually exclusive
4. **Re-derive**: They address different layers (what vs. how)
5. **Conclusion**: Direction without attachment = synthesis of both

## Common Pitfalls

| Pitfall | Symptom | Solution |
|---------|---------|----------|
| Fake first principles | "Industry wisdom" treated as facts | Ask: "Where did this come from?" |
| Analysis paralysis | Endless decomposition | Set depth limit, then decide |
| Ignoring practicality | Theoretical optimum, can't execute | Include feasibility as a fact |

## License

MIT

---

## Support

If you find this useful, consider buying me a coffee ☕

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support-yellow?style=flat&logo=buy-me-a-coffee)](https://buymeacoffee.com/mclty)
