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

## Habilidad / Skill

`unsure-caveman` hace que el agente comience cada respuesta con (Spanish format):

- `CONFIANZA`
- `POR QUÉ DUDA`
- `CORREGIR CEREBRO`

O su equivalente en inglés (English format):

- `CONFIDENCE`
- `FUZZY WHY`
- `FIX BRAIN`

Luego responde en un estilo cavernícola compacto y técnico. / Then it answers in a compact and technical caveman style.

Soporta comandos como `/cavernicola`, `/caveman`, `modo cavernícola`, entre otros. / Supports commands like `/cavernicola`, `/caveman`, `modo cavernícola`, and more.

## Publish Notes

The `skills` CLI discovers skills in `skills/<skill-name>/SKILL.md`, as used here. The skill name must match the parent directory name.
