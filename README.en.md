# leoyim-skills

English | [简体中文](README.md)

A collection of personal agent skills (compatible with the SKILL spec used by WorkBuddy and other agent platforms).

## Skills

| Skill | Description | Type |
| --- | --- | --- |
| [any-subject-comic-poster](skills/any-subject-comic-poster/) | Turn any reference image (cat, animal, person, or character) into a consistent 9:16 comic-collage poster while preserving the subject's identity | Image generation |

## Layout

```
leoyim-skills/
└── skills/
    └── any-subject-comic-poster/
        ├── README.md   # Skill description (English)
        ├── README.en.md
        └── SKILL.md    # Skill definition (loaded by the agent)
```

## Install

Copy the `skills/<skill-name>/` folder into the skills directory used by your agent platform (e.g. user-level `~/.workbuddy/skills/` or project-level `.workbuddy/skills/` in WorkBuddy).

## License

MIT
