# Skills

Claude Code 自定义技能集合。

## 已收录 Skills

### paper-reading — 论文研读笔记

基于 S. Keshav 三遍阅读法（Three-Pass Method）的结构化论文研读 Skill。

- **触发方式**：`/paper-reading`、`/读论文`、`/论文笔记`、「帮我读这篇论文」
- **输出**：Pass 0 阅读前校准 → Pass 1 五 C 鸟瞰 → Pass 2 精读笔记（论证链 + 灵魂图解读 + 跨领域桥接）→ Pass 3 深潜批判
- **来源**：Keshav, S. (2007). How to Read a Paper. *ACM SIGCOMM CCR*, 37(3), 83–84.
- **课程参考**：Stanford EE384m [Handout](https://web.stanford.edu/class/ee384m/Handouts/HowtoReadPaper.pdf)

### 安装方式

1. 将 `paper-reading/SKILL.md` 复制到 `~/.claude/skills/paper-reading/SKILL.md`
2. 重启 Claude Code 或在对话中输入 `/paper-reading` 触发

---

## 目录结构

```
skills/
├── README.md
└── paper-reading/
    └── SKILL.md
```
