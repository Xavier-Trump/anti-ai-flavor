# anti-ai-flavor · 中文去 AI 味

一个 Claude Code skill，用来从中文小说/散文里去掉「AI 腔」——套路化措辞、空泛总结、公式化结构。

## 安装

把整个 `anti-ai-flavor/` 文件夹放进 Claude Code 的 skills 目录：

- 用户级（全局）：`~/.claude/skills/`
- 项目级：`.claude/skills/`

## 使用

- 敲 `/anti-ai-flavor` 直接调用
- 或写/改中文正文时，按描述自动触发

## 结构

```
anti-ai-flavor/
├── SKILL.md                 # 核心规则 + 快速检查 + 评分
└── references/
    └── ai-tells.md          # 14 类中文 AI 腔的「病 → 改」对照
```

## License

MIT，见 [LICENSE](LICENSE)。
