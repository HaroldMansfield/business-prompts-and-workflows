# Turn a Workflow Into a Skill

A workflow becomes a skill when it is packaged as repeatable instructions an AI assistant can load and follow.

## Basic structure

```text
my-skill/
  SKILL.md
  references/
  templates/
  scripts/
```

## Steps

1. Create a folder with a clear skill name.
2. Add a `SKILL.md` file.
3. Write a short description that explains when the skill should be used.
4. Move the workflow instructions into the body of `SKILL.md`.
5. Put long examples, checklists, or background materials in `references/`.
6. Put reusable forms, prompt shells, or document formats in `templates/`.
7. Add scripts only when the workflow needs repeatable automation.
8. Test the skill on a real task and revise anything unclear.

## Simple `SKILL.md` pattern

```markdown
---
name: example-skill
description: Use when you need to complete this specific workflow.
---

# Example Skill

## When to use this

Use this skill when...

## Workflow

Step-by-step instructions go here.

## Output format

Define what a good result should look like.
```
