# unsure-caveman

Agent skill for terse, uncertainty-aware responses.

## Install

After publishing this repository to GitHub:

```bash
npx skills add <owner>/unsure-caveman
```

To install only this skill from a multi-skill repository:

```bash
npx skills add <owner>/unsure-caveman --skill unsure-caveman
```

## Skill

`unsure-caveman` makes the agent start every response with:

- `CONFIDENCE`
- `FUZZY WHY`
- `FIX BRAIN`

Then it answers in compact caveman style while preserving technical exactness.

## Publish Notes

The `skills` CLI discovers skills in `skills/<skill-name>/SKILL.md`, as used here. The skill name must match the parent directory name.
