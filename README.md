# leoyim-skills

[English](README.en.md) | 简体中文

个人 Agent 技能集合（兼容 WorkBuddy 等 Agent 平台的 SKILL 规范）。

## 技能列表

| 技能 | 说明 | 类型 |
| --- | --- | --- |
| [any-subject-comic-poster](skills/any-subject-comic-poster/) | 将任意参考图（猫、动物、人物、虚构角色）转换为风格统一的 9:16 漫画拼贴海报，保持主体身份与特征一致 | 图像生成 |

## 目录结构

```
leoyim-skills/
└── skills/
    └── any-subject-comic-poster/
        ├── README.md   # 技能说明（中文）
        ├── README.en.md
        └── SKILL.md    # 技能定义（Agent 加载入口）
```

## 安装

将 `skills/<技能名>/` 整个目录复制到你所用 Agent 平台的技能目录（如 WorkBuddy 的用户级技能目录 `~/.workbuddy/skills/` 或项目级 `.workbuddy/skills/`）。

## 许可证

MIT
