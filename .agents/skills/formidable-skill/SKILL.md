---
name: formidable-skill
description: Use when the user wants to create a PR and share their personal skills.
disable-model-invocation: true
---

The user wants to share their personal skill with the Formidable OSS GitHub organization.

Before anything, the user must be made aware that the skill will be public through the [`vercel-labs/skills` cli](https://github.com/vercel-labs/skills)

Only then, skills can start being copied to the discovery `skills` folder, i.e. `skills/gabimoncha/formidable-skills`.

The copy process should be:
- user shares the skills location and their names, i.e. "i want to share my `op-seo-skill` from project `X`"
- skills are then copied from that location to `skills/<username>/op-seo-skills`
- user can then freely edit the skill and commit and open PR at it's own pace

Never commit, push, or open the PR yourself