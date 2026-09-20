# Grok Personalities

12 switchable response personalities for **Grok chat** (Custom Agents) and **Grok Build** (personas).

## Modes

| Mode | Vibe |
|------|------|
| **Direct** | Answer-first, plain, no fluff |
| **Structured** | Headings, bullets, clean layout |
| **Deep** | Thorough reasoning & trade-offs |
| **Builder** | Concrete engineering partner |
| **Concise** | Maximum compression |
| **Tutor** | Patient teaching |
| **Critic** | Hard evaluation first |
| **Strategist** | Decisions & second-order effects |
| **Creative** | Fresh angles & options |
| **Empath** | Human situation first |
| **Analyst** | Evidence, logic, quantification |
| **Irreverent** | Sharp, dry, anti-corporate |

## Chat Grok — Custom Agents

Go to **Settings → Customize → Create Agent** and paste one of the instruction blocks from [`custom-agents.md`](custom-agents.md).

You get up to 4 active slots. Rotate the ones you use most.

## Grok Build — Personas

Copy the `.toml` files from [`personas/`](personas/) into:

- `.grok/personas/` (project), or
- `~/.grok/personas/` (user)

Or add them under `[subagents.personas]` in `config.toml`.

## Skill

[`skills/personality-switcher/SKILL.md`](skills/personality-switcher/SKILL.md) lets you switch by saying e.g. “be direct”, “critic mode”, “personality: strategist”.

Install by copying the folder into `/home/workdir/.grok/skills/` or your skills path.

## Quick switch prompt

Paste at the start of a chat:

```
Personality mode: [Direct | Structured | Deep | Builder | Concise | Tutor | Critic | Strategist | Creative | Empath | Analyst | Irreverent]

Apply the matching rules strictly for this conversation.
```

## License

MIT — use freely.
