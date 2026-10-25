# agent-skills

Agent skills in the open [Agent Skills](https://agentskills.io) format. Each skill is a directory containing a `SKILL.md` (YAML frontmatter plus instructions) and optional `references/`, `scripts/`, or `assets/`.

Skills live in `.agents/skills/` so any compatible agent can discover them.

## Skills

| Skill | Description |
| --- | --- |
| [data-system-design-review](.agents/skills/data-system-design-review/SKILL.md) | Review and design data-heavy backend systems: storage, replication, partitioning, transactions, batch and stream pipelines. |
| [microservices-design-review](.agents/skills/microservices-design-review/SKILL.md) | Review and design microservice architectures: service boundaries, communication, data and workflows, resilience, security, delivery, and migration. |

## Usage

Point your agent at `.agents/skills/`, or copy a skill directory into your agent's skills location.

## License

[MIT](LICENSE)
