# Skills

Claude Code 自定义技能集合。三层目录结构：**分类 → 技能 → 内容**。

## 目录结构

```
skills/
├── README.md                 # 仓库总览（你在这里）
└── {category}/               # 一层：分类目录
    ├── README.md             # 该分类下所有 skills 摘要
    └── {skill-name}/         # 二层：单个 skill 文件夹
        └── SKILL.md          # 三层：skill 内容
```

## 分类索引

| 分类 | 说明 | 已收录 |
|------|------|--------|
| [academic/](https://github.com/sermilan/skills/tree/main/academic) | 学术研究、论文阅读、写作工具 | 1 |

## 安装方式

1. 将 `{category}/{skill-name}/SKILL.md` 复制到 `~/.claude/skills/{skill-name}/SKILL.md`
2. 重启 Claude Code 或在对话中输入对应触发词

## 贡献规范

新增 skill 时，请遵循三层结构：

1. 确定分类目录（若无合适分类则新建，同步更新本 README 的分类索引表）
2. 在分类目录下新建 `{skill-name}/` 文件夹
3. 放入 `SKILL.md` 及其他所需文件
4. 更新对应分类的 `README.md`（添加新 skill 摘要）
