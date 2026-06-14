# Awesome-Claude-Skills

A collection of reusable skill prompts for Claude, designed to produce consistent, high-quality outputs for common development tasks.

## Usage

1. Browse the `/skills` directory
2. Copy the `skill.md` from the relevant skill
3. Paste it into your Claude conversation (or use as a system prompt)
4. Provide your specific context/code after the skill prompt

## Skills

| Skill | Description | Best For |
|-------|-------------|----------|
| [code-review](./skills/code-review/) | Structured code review with severity levels | PR reviews, code audits |
| [refactoring](./skills/refactoring/) | Safe, incremental code transformation | Legacy code modernization |
| [debugging](./skills/debugging/) | Systematic bug investigation | Troubleshooting issues |
| [architecture-design](./skills/architecture-design/) | Deepening modules and reducing friction | Improving system-wide structure |
| [testing](./skills/testing/) | Test strategy and implementation | Adding coverage |
| [documentation](./skills/documentation/) | Technical writing | READMEs, API docs |
| [api-design](./skills/api-design/) | REST/GraphQL API design | Building endpoints |
| [x-twitter-scraper](./skills/x-twitter-scraper/) | Xquik API workflows for X/Twitter data | Social data research, monitoring, exports |
| [onboarding](./skills/onboarding/) | Context gathering for new codebases | Joining projects |
| [tdd](./skills/tdd/) | Red-green-refactor loop | Test-first development |
| [prototype](./skills/prototype/) | Rapid throwaway prototypes | Validating designs |
| [zoom-out](./skills/zoom-out/) | High-level system mapping | Understanding big picture |
| [to-prd](./skills/to-prd/) | Conversation to PRD synthesis | Formalizing requirements |
| [diagnose](./skills/diagnose/) | Systematic bug diagnosis | Hard bugs, performance |
| [triage](./skills/triage/) | Issue workflow management | GitHub/GitLab triage |
| [caveman](./skills/caveman/) | Ultra-compressed communication | Saving tokens, speed |
| [grill-me](./skills/grill-me/) | Relentless design interview | Stress-testing plans |
| [grill-with-docs](./skills/grill-with-docs/) | Plan vs domain/docs alignment | Terminological precision |
| [to-issues](./skills/to-issues/) | Vertical slicing into tickets | Task breakdown |
| [write-a-skill](./skills/write-a-skill/) | Creating new agent skills | Extending capabilities |

## Creating a New Skill

1. Copy `/skills/_template/` to `/skills/your-skill-name/`
2. Fill in the README.md and skill.md
3. Follow the [contribution guidelines](#contributing)

## Philosophy

Each skill should be:
- **Atomic**: Does one thing well
- **Context-agnostic**: Works with any codebase
- **Observable**: Produces structured, parseable output
- **Safe**: Includes guardrails and constraints

## Contributing

1. Use the template in `/skills/_template/`
2. Include before/after examples
3. Test with at least 3 different codebases
4. Submit a PR with a clear description

## License

MIT


## 📈 Star History

<div align="center">
  <a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-Claude-Skills&type=date&legend=bottom-right">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Claude-Skills&type=date&theme=dark&legend=bottom-right" />
      <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Claude-Skills&type=date&legend=bottom-right" />
      <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Claude-Skills&type=date&legend=bottom-right" />
    </picture>
  </a>
</div>
