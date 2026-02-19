# SOC 2 Quality Guild — s2guild.org

This is the website and rubric repository for the SOC 2 Quality Guild.

## Project Structure

- `index.html` — Main website (s2guild.org), single-page static site
- `rubric/` — Versioned rubric documents and changelog
- `llms.txt` — Short LLM-readable summary of the Guild and rubric
- `llms-full.txt` — Complete rubric with all 11 signals and tactical response guide
- `.claude/commands/soc2-review.md` — Claude Code skill for analyzing SOC 2 reports
- `.claude-plugin/` — Plugin manifest for Claude Code marketplace distribution

## SOC 2 Review Skill

The `/soc2-review` slash command analyzes a SOC 2 report PDF against the Reliability Rubric v1.0. Usage:

```
/soc2-review /path/to/report.pdf
```

The skill evaluates 11 signals across 3 pillars (Structure, Substance, Source) and produces a structured assessment with ratings, evidence, and recommended actions.

## Principles

- **Education, not accusation** — We evaluate report reliability, not vendor trustworthiness
- **Practitioner-driven** — Built for people making real vendor trust decisions
- **Open and transparent** — CC BY-SA 4.0 license

## License

CC BY-SA 4.0
