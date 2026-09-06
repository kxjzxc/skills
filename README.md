# My Skills

A personal collection of AI agent skills I want to use, study, and maintain.

## Skills

- [grill-me](skills/grill-me/SKILL.md) — Stateless design grilling; delegates to `grilling`.
- [grill-with-docs](skills/grill-with-docs/SKILL.md) — Design grilling with glossary and ADR updates.
- [grilling](skills/grilling/SKILL.md) — Shared questioning primitive for stress-testing plans and designs.
- [domain-modeling](skills/domain-modeling/SKILL.md) — Build and sharpen domain language, `CONTEXT.md`, and ADRs.
- [to-spec](skills/to-spec/SKILL.md) — Synthesize the current conversation into an engineering spec.
- [code-review](skills/code-review/SKILL.md) — Review a diff against repository standards and the originating spec.
- [to-prd](skills/to-prd/SKILL.md) — Local compatibility entry retained for the older PRD workflow.

## Install

Install a skill directly from this repository:

```bash
npx skills add https://github.com/kxjzxc/skills --skill <skill-name>
```

For Codex:

```bash
npx skills add https://github.com/kxjzxc/skills --skill grill-with-docs -a codex -y
```

## Structure

Each skill is independently installable and carries its Codex metadata when the upstream skill provides it:

```text
skills/
├── grill-me/
│   ├── SKILL.md
│   └── agents/
│       └── openai.yaml
├── grill-with-docs/
│   ├── SKILL.md
│   └── agents/
│       └── openai.yaml
├── grilling/
│   ├── SKILL.md
│   └── agents/
│       └── openai.yaml
├── domain-modeling/
│   ├── SKILL.md
│   ├── CONTEXT-FORMAT.md
│   ├── ADR-FORMAT.md
│   └── agents/
│       └── openai.yaml
├── to-spec/
│   ├── SKILL.md
│   └── agents/
│       └── openai.yaml
└── code-review/
    ├── SKILL.md
    └── agents/
        └── openai.yaml
```
