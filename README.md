# HL7 EU Skills and Plugins

A community repository for sharing skills and related tools with HL7 Europe and
the wider HL7 community. It starts with reusable assistant skills; additional
resource types can be documented here as they are contributed.

## Skills

Each skill lives in its own directory under `skills/` and has a `SKILL.md` file
with YAML frontmatter containing a name and a short description:

```text
skills/
└── your-skill-name/
    └── SKILL.md
```

See [`skills/explain-hl7-v2-message/SKILL.md`](skills/explain-hl7-v2-message/SKILL.md)
for an example.

## Contributing a skill

1. Create a descriptively named directory under `skills/`.
2. Add a `SKILL.md` with `name` and `description` frontmatter and clear,
   task-focused instructions.
3. Keep the skill scoped, state any assumptions, and avoid presenting
   unverified output as authoritative.
4. Open a pull request describing what the skill does and when it should be
   used.
