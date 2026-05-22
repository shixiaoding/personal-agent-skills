# Research Summary Skills（资料收集总结 Skill 套件）

## 包含内容

```text
research-summary-orchestrator/
research-collector/
research-document-writer/
notion-publisher/
research-version-manager/
references/
```

## 推荐安装位置

Codex：

```bash
mkdir -p ~/.codex/skills
cp -R research-summary-orchestrator ~/.codex/skills/
cp -R research-collector ~/.codex/skills/
cp -R research-document-writer ~/.codex/skills/
cp -R notion-publisher ~/.codex/skills/
cp -R research-version-manager ~/.codex/skills/
```

Claude Code：

```bash
mkdir -p ~/.claude/skills
cp -R research-summary-orchestrator ~/.claude/skills/
cp -R research-collector ~/.claude/skills/
cp -R research-document-writer ~/.claude/skills/
cp -R notion-publisher ~/.claude/skills/
cp -R research-version-manager ~/.claude/skills/
```

## 使用方式

直接对 AI 说：

```text
使用资料收集总结 Skill，帮我收集 OpenSpec 大厂实践资料，生成 md 并同步到 Notion。
```

或：

```text
基于上一版生成 v3，不要覆盖旧文档。
```

或：

```text
这版确认了，后续只做资料库更新。
```
