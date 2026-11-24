# Repository skill configuration

This repository uses the Qifei Proposal Skill V2 suite from [`skills/qifei-proposal-skill`](https://github.com/HavenBanya/qifei-proposal-skill).

## Load the skills

Initialize the source submodule after cloning this repository:

```bash
git submodule update --init --recursive
```

For proposal planning, strategy, workflow, and project governance, follow:

- `skills/qifei-proposal-skill/skills/qifei-proposal-v2/SKILL.md`

The V2 suite also includes these companion skills:

- `skills/qifei-proposal-skill/skills/grill-me-lite/SKILL.md`
- `skills/qifei-proposal-skill/skills/proposal-ppt-production/SKILL.md`
- `skills/qifei-proposal-skill/skills/ppt-html-calibration-editor/SKILL.md` (optional HTML calibration)

When installing the suite into the local Codex skills directory, run from the initialized submodule:

```bash
python scripts/install_skills.py --suite v2
```

Use the upstream repository's `README.md` for setup and runtime requirements. The upstream `LICENSE` governs use of the skill materials.
