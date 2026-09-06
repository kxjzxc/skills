# My Skills

A personal collection of AI agent skills I want to use, study, and maintain.

## Skills

### Product & Design

- [to-prd](skills/to-prd/SKILL.md) — Turn a product idea into a PRD. Compatibility entry for the former workflow.
- [to-spec](skills/to-spec/SKILL.md) — Turn an existing conversation and codebase understanding into a technical spec.
- [grill-me](skills/grill-me/SKILL.md) — Stress-test a plan or design through relentless questioning.
- [grill-with-docs](skills/grill-with-docs/SKILL.md) — Stress-test a design while maintaining domain documentation.
- [grilling](skills/grilling/SKILL.md) — Core interview skill used by `grill-me` and `grill-with-docs`.
- [domain-modeling](skills/domain-modeling/SKILL.md) — Build and sharpen domain terminology, CONTEXT.md, and ADRs.

### Engineering

- [code-review](skills/code-review/SKILL.md) — Review changes independently against repository standards and the originating spec.

## Install

Install any skill directly from this repository:

```bash
npx skills add https://github.com/kxjzxc/skills --skill <skill-name>
```

Examples:

```bash
npx skills add https://github.com/kxjzxc/skills --skill grill-with-docs
npx skills add https://github.com/kxjzxc/skills --skill code-review
```

## Structure

Each skill is independently installable:

```text
skills/
├── <skill-name>/
│   └── SKILL.md
└── ...
```

Some skills have supporting files in their own directory.
