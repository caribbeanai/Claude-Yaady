# Claude-Yaady

A Claude Code custom skill that transforms Claude into a Jamaican Patois-speaking AI assistant — reasoning wid cultural wisdom, communicating inna Patois, and saving tokens through natural conciseness.

## Project Structure

```
Claude-Yaady/
  .claude/skills/claude-yaady/
    SKILL.md                 # Core skill — persona, grammar, style, reasoning rules
  patois/
    dictionary.md            # Comprehensive Patois term repository (pronouns, verbs, adjectives, contractions)
    proverbs.md              # 20 Jamaican proverbs mapped to software engineering principles
    technical-terms.md       # Programming vocabulary in Patois-flavored equivalents
  CLAUDE.md                  # This file
  README.md                  # Project documentation
  LICENSE                    # Apache 2.0
```

## How It Works

The skill in `.claude/skills/claude-yaady/SKILL.md` instructs Claude to:
- Respond in Jamaican Patois by default
- Pull vocabulary from `patois/dictionary.md` for word choices and contractions
- Apply proverbs from `patois/proverbs.md` as reasoning heuristics
- Use technical analogies from `patois/technical-terms.md` for explanations
- Maintain full technical accuracy while using Patois as the communication style

## Skill Activation

Invoke the skill in Claude Code with `/claude-yaady`.

## Development Guidelines

- **Cultural authenticity**: Jamaican Patois (Jamaican Creole) is a full language with its own grammar system. It is not "broken English." All contributions must respect this.
- **Token efficiency**: A core design goal. Patois is naturally more concise than formal English. Additions to the dictionary should demonstrate token savings.
- **Technical accuracy**: The Patois style must never compromise correctness. Code, error messages, and technical references stay precise.
- **Proverb reasoning**: New proverbs added to `patois/proverbs.md` must map to clear software engineering principles with practical usage examples.

## Author

Adrian Dunkley ([@caribbeanai](https://github.com/caribbeanai))

## License

Apache 2.0
