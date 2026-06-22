<div align="center">
  <img src="assets/banner.svg" alt="Awesome Claude Skills Banner" />

  # ✨ Awesome Claude Skills ✨
  
  <p align="center">
    <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
    <a href="https://github.com/ishandutta2007/Awesome-Claude-Skills/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Claude-Skills.svg?style=flat-square" alt="Stars" /></a>
    <a href="https://github.com/ishandutta2007/Awesome-Claude-Skills/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Claude-Skills.svg?style=flat-square" alt="Forks" /></a>
    <a href="https://github.com/ishandutta2007/Awesome-Claude-Skills/issues"><img src="https://img.shields.io/github/issues/ishandutta2007/Awesome-Claude-Skills.svg?style=flat-square" alt="Issues" /></a>
    <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
  </p>
  
  **A comprehensive, SEO-friendly collection of reusable skill prompts for Anthropic's Claude AI. Designed to produce consistent, high-quality code and text outputs for common software development tasks, prompt engineering, and AI workflows.**
</div>

## 🚀 Usage Guide

1. Browse the `/skills` directory
2. Copy the `skill.md` from the relevant skill
3. Paste it into your Claude conversation (or use as a system prompt)
4. Provide your specific context/code after the skill prompt

## 🛠️ Available Claude Skills

| Skill | Description | Best For |
|-------|-------------|----------|
| [code-review](./skills/code-review/) | Structured code review with severity levels | PR reviews, code audits |
| [refactoring](./skills/refactoring/) | Safe, incremental code transformation | Legacy code modernization |
| [debugging](./skills/debugging/) | Systematic bug investigation | Troubleshooting issues |
| [architecture-design](./skills/architecture-design/) | Deepening modules and reducing friction | Improving system-wide structure |
| [ax-extract-workflow](./skills/ax-extract-workflow/) | Reconstructs shipped-work evidence trails with ax | Retrospectives, repeatable workflows |
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
| [notfair](https://github.com/nowork-studio/NotFair) | Claude Code skills for SEO, GEO, Google Ads, and Meta Ads — connects to live data via Google Ads MCP, Meta Ads MCP, Google Search Console MCP, and Google Analytics (GA4) MCP | Marketing audits, keyword research, paid-ads optimization |
| [write-a-skill](./skills/write-a-skill/) | Creating new agent skills | Extending capabilities |
| [code-generation](./skills/code-generation/) | Rapid boilerplate and algorithm generation | Prototyping, starting new projects |
| [prompt-engineering](./skills/prompt-engineering/) | Self-improving prompts and meta-prompting | Complex reasoning tasks |
| [security-audit](./skills/security-audit/) | Vulnerability scanning and threat modeling | Securing applications |
| [performance-optimization](./skills/performance-optimization/) | Identify and fix bottlenecks | Scaling applications, refactoring |
| [code-explanation](./skills/code-explanation/) | Explain complex codebases simply | Onboarding, documentation |
| [database-design](./skills/database-design/) | Schema design and optimization | Data modeling, SQL tuning |
| [ux-ui-review](./skills/ux-ui-review/) | Heuristic evaluation of user interfaces | Frontend development, Design feedback |
| [i18n-l10n](./skills/i18n-l10n/) | Internationalization and localization strategies | Globalizing applications |
| [accessibility-audit](./skills/accessibility-audit/) | WCAG compliance checking and fixes | Web accessibility, A11y |
| [devops-pipeline](./skills/devops-pipeline/) | CI/CD pipeline generation and review | GitHub Actions, Infrastructure as Code |
| [regex-wizard](./skills/regex-wizard/) | Building and explaining complex regular expressions | Data validation, parsing |
| [data-science-eda](./skills/data-science-eda/) | Exploratory data analysis scripts and strategies | Jupyter notebooks, Pandas |
| [code-migration](./skills/code-migration/) | Migrating code between frameworks or languages | Tech stack modernization |
| [seo-optimization](./skills/seo-optimization/) | Technical SEO audits and metadata structuring | Web development, Content sites |
| [web-scraping](./skills/web-scraping/) | Building resilient scrapers and data extractors | Data mining, OSINT |
| [game-mechanics](./skills/game-mechanics/) | Designing algorithms and state machines for games | Game development |
| [cloud-architecture](./skills/cloud-architecture/) | Designing AWS/GCP/Azure infrastructure | Cloud engineering, Serverless |
| [linux-sysadmin](./skills/linux-sysadmin/) | Shell scripting and server management | System administration |
| [blockchain-smart-contracts](./skills/blockchain-smart-contracts/) | Writing and auditing Solidity/Rust contracts | Web3, DeFi |
| [graphql-schema](./skills/graphql-schema/) | Designing efficient and scalable GraphQL schemas | API development |
| [css-animations](./skills/css-animations/) | Creating complex and performant CSS/JS animations | Frontend, UI/UX |

## 💡 Creating a New Skill

1. Copy `/skills/_template/` to `/skills/your-skill-name/`
2. Fill in the README.md and skill.md
3. Follow the [contribution guidelines](#contributing)

## 🧠 Core Philosophy

Each skill should be:
- **Atomic**: Does one thing well
- **Context-agnostic**: Works with any codebase
- **Observable**: Produces structured, parseable output
- **Safe**: Includes guardrails and constraints

## 🤝 Contributing

1. Use the template in `/skills/_template/`
2. Include before/after examples
3. Test with at least 3 different codebases
4. Submit a PR with a clear description

## 📄 License

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
