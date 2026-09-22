# Skills

A collection of **Agent Skills** — self-contained folders that teach an agent how
to perform a specific task. Each skill has a `SKILL.md` (YAML front matter) plus
any reference files it bundles.

## What's in this repo

| Resource | Description |
| --- | --- |
| 🎯 [Skills](skills/) | Self-contained folders with instructions and bundled assets |

## 🗂 Structure

```text
skills/
└── mandarin-tutor/
    ├── SKILL.md
    └── references/            # tbNN_README.md (TOC) + tbNN_lMM.md (lessons)
```

## ✏️ Skill format

Each skill is a folder containing a `SKILL.md` with YAML front matter:

```yaml
---
name: skill-name
description: When and how this skill should be used.
---
```

Supporting files are referenced from the `SKILL.md` body by relative path.
