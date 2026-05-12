# Andie-Codex

> Andie for GitHub Copilot, OpenAI Custom GPT, and Claude Code.
> Built by [Giggso Inc](https://github.com/giggsoinc). MIT License.

*I don't bullshit. I help you win.*

---

## What It Is

Andie-Codex is the multi-platform version of Andie — a sharp engineering thinking partner that works across GitHub Copilot Chat, OpenAI Custom GPT, and Claude Code.

| Mode | Trigger | What You Get |
|---|---|---|
| **Deep** (default) | `deep` or just ask | World-class practitioner breaks down any technical problem — 3 levels |
| **Drama** | `drama` or `movie` | Expert panel debates your architecture decision to a conclusion |
| **Triage** | `triage` or `war zone` | War strategy applied to your engineering crisis — battle plan in minutes |
| **Kaizen** | `kaizen` or `factory` | Finds the waste in your code or process, fixes one thing at a time |

---

## Install

### GitHub Copilot Chat

Copy `.github/copilot-instructions.md` into your repository root. Copilot will follow Andie-Codex instructions automatically in VS Code Copilot Chat.

### OpenAI Custom GPT

1. Go to [chat.openai.com/create](https://chat.openai.com/create)
2. Paste the contents of `andie-codex-gpt.md` into the **Instructions** field
3. Name it **Andie-Codex**
4. Save

### Claude Code

```bash
claude plugin install andie-codex
```

---

## Example Use Cases

**Deep:** Your Postgres query plan changed after a schema migration and you don't know why — Deep mode loads the Postgres specialist and breaks it down three levels: plain English, engineering detail, and the exact fix.

**Drama:** Choosing between a monolith and microservices for your next product — Drama mode assembles a panel of architects, an Anarchist who challenges the premise, and a Saboteur who finds the 3am failure. They fight it out. You get a decision that survived scrutiny.

**Triage:** Launch is two days away and a critical dependency just broke — Triage picks the right war strategy, assigns a Commander, Red Team, and Intel Officer, and hands you a battle plan with 24-hour actions and a go/no-go decision.

**Kaizen:** Your team ships fast but the same bugs keep coming back — Kaizen maps your workflow against the 7 Lean wastes, finds the one killing you most, and locks in one improvement with a control mechanism so it never regresses.

---

## Files

| File | Purpose |
|---|---|
| `.github/copilot-instructions.md` | GitHub Copilot Chat instructions |
| `andie-codex-gpt.md` | OpenAI Custom GPT system prompt |
| `skills/andie-codex/SKILL.md` | Claude Code skill |

---

## Source

[github.com/giggsoinc/andie-codex](https://github.com/giggsoinc/andie-codex)
[github.com/giggsoinc/andie](https://github.com/giggsoinc/andie) — original Claude Code version
