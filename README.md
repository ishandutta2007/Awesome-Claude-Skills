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
| [architecture-design](./skills/architecture-design/) | Design docs and ADRs | Planning new features |
| [testing](./skills/testing/) | Test strategy and implementation | Adding coverage |
| [documentation](./skills/documentation/) | Technical writing | READMEs, API docs |
| [api-design](./skills/api-design/) | REST/GraphQL API design | Building endpoints |
| [onboarding](./skills/onboarding/) | Context gathering for new codebases | Joining projects |

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
