# Claude-Yaady

**Claude Skills turns your AI into a Real Jamaican Yaady — passionate, focused, and efficient.**

> "Wi likkle but wi tallawah." — Small but mighty.

---

## Wha Dis?

Claude-Yaady is a custom skill for [Claude Code](https://claude.ai/code) that transforms Claude into a Jamaican Patois-speaking AI assistant. It doesn't just translate words — it changes how Claude **thinks, reasons, and communicates**, drawing on Jamaican cultural wisdom, proverbs, and the natural efficiency of Patois.

When yuh activate dis skill, Claude will:
- **Respond inna Jamaican Patois** — authentic grammar, vocabulary, and expression
- **Reason wid Jamaican proverbs** — cultural logic applied to software engineering decisions
- **Save tokens** — Patois is naturally more concise than formal English
- **Bring creative vibes** — cultural expression that makes AI interaction more human and engaging

---

## Why Patois?

Jamaican Patois (also called Jamaican Creole) is a full language spoken by over 3 million people. It has its own grammar, tense system, and expressive power.

### Token Efficiency

Patois is naturally concise. Same meaning, fewer tokens:

| English | Patois | Savings |
|---------|--------|---------|
| "I have completed the task" | "Mi done" | ~60% |
| "Everything is working correctly" | "Everyting irie" | ~60% |
| "Let me investigate the issue" | "Mek mi dig" | ~50% |
| "I would like to suggest" | "Mi a seh" | ~60% |
| "Could you please check" | "Check it nuh" | ~50% |

### Cultural Reasoning

Jamaican proverbs become software engineering heuristics:

- **"Cockroach nuh bizniz inna fowl fight"** — Separation of concerns
- **"Chicken merry, hawk deh near"** — Check edge cases when things look easy
- **"One one coco full basket"** — Ship incrementally
- **"Bush have ears, wall have eyes"** — Security mindset
- **"If yuh cyaan hear, yuh wi feel"** — Read the error messages

---

## Wha Inside

```
Claude-Yaady/
  .claude/skills/claude-yaady/
    SKILL.md                 # The core skill definition
  patois/
    dictionary.md            # 100+ Patois terms organized by category
    proverbs.md              # 20 proverbs mapped to engineering principles
    technical-terms.md       # Tech vocabulary in Patois
```

### The Patois Repository

The `patois/` directory is a comprehensive term bank:

- **`dictionary.md`** — Full vocabulary: pronouns, verbs, tense markers, adjectives, greetings, Rasta-influenced terms, contractions, and a token-saving reference table
- **`proverbs.md`** — 20 Jamaican proverbs, each with: the original Patois, English translation, engineering principle, and usage example
- **`technical-terms.md`** — Programming concepts expressed in Patois: APIs as "cook shop windows", databases as "di vault", debugging as "trace di jumbie"

---

## Installation

### Option 1: Clone into your project

```bash
# Clone the repo
git clone https://github.com/caribbeanai/Claude-Yaady.git

# Copy the skill and patois files into your project
cp -r Claude-Yaady/.claude your-project/
cp -r Claude-Yaady/patois your-project/
```

### Option 2: Use directly

```bash
# Clone and work inside the repo
git clone https://github.com/caribbeanai/Claude-Yaady.git
cd Claude-Yaady

# Start Claude Code — the skill is available via /claude-yaady
```

---

## Usage

Once installed, activate the skill in Claude Code:

```
/claude-yaady
```

### Example: Before and After

**Without Claude-Yaady (standard Claude):**
> I've analyzed the error and it appears that the issue is caused by a null reference exception in the authentication middleware. The variable `user` is undefined when the session has expired. I would recommend adding a null check before accessing the user properties.

**With Claude-Yaady:**
> Di buss come from di auth middleware — `user` a ghost when di session expire. Add a null check before yuh touch di user properties. Sorted.

**Without Claude-Yaady:**
> I'll review your pull request. I notice that this function is handling both authentication and logging simultaneously, which violates the single responsibility principle. I'd suggest separating these concerns into distinct modules.

**With Claude-Yaady:**
> Look ova yuh PR. Dis function a handle auth AND logging same time — cockroach nuh bizniz inna fowl fight. Separate dem concerns into dem own module. Seen?

---

## How It Reasons

Claude-Yaady doesn't just speak differently — it **thinks** differently. Jamaican proverbs guide its reasoning:

```
User: "Should we rewrite the whole auth system with the new framework?"

Claude-Yaady: "New broom sweep clean, but old broom know di corner.
Di current auth system work. Before wi dash weh everyting, ask:
wha specifically bruk? If a just di token handling, fix dat one ting.
Nuh dash weh yuh stick before yuh done cross river.
Every mickle mek a muckle — start small, prove it work, den expand."
```

Three proverbs, clear reasoning, practical advice.

---

## Cultural Note

Jamaican Patois is a legitimate, rich language — not "broken English" or a joke accent. This project treats it with the respect it deserves. The goal is authentic representation of how Jamaicans actually speak and think, bringing that warmth, directness, and creativity into AI interaction.

This skill was built with love for Jamaica, its language, and its culture.

---

## License

Apache 2.0 — see [LICENSE](LICENSE).

## Author

**Adrian Dunkley** ([@caribbeanai](https://github.com/caribbeanai))

---

*One love.*
