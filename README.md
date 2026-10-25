<div align="center">

# 📊 social-analytics-reporter

**Social media analytics exports into a clear report with KPIs, reasons and next actions. An Agent Skill for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![License: MIT](https://img.shields.io/github/license/milad-ahmd/social-analytics-reporter)](LICENSE)
[![Stars](https://img.shields.io/github/stars/milad-ahmd/social-analytics-reporter?style=social)](https://github.com/milad-ahmd/social-analytics-reporter)
![Category](https://img.shields.io/badge/category-Marketing-blue)
![Works with](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Cline%20%7C%20Cursor%20%7C%20Codex-8A2BE2)

[Install](#-install) · [Usage](#-usage) · [How it works](skills/social-analytics-reporter/SKILL.md) · [All skills](https://github.com/milad-ahmd/agent-skills)

</div>

> Part of **[agent-skills](https://github.com/milad-ahmd/agent-skills)**, a growing collection of practical skills for AI coding agents.

## 📦 Install

**One command (installs the whole collection):**

```bash
curl -fsSL https://raw.githubusercontent.com/milad-ahmd/agent-skills/main/install.sh | bash -s -- social-analytics-reporter
```

**Manually (Claude Code):**

```bash
git clone https://github.com/milad-ahmd/social-analytics-reporter /tmp/social-analytics-reporter
mkdir -p ~/.claude/skills && cp -r /tmp/social-analytics-reporter/skills/social-analytics-reporter ~/.claude/skills/
```

**Per project:** copy `skills/social-analytics-reporter` into `<project>/.claude/skills/`.
**Any other agent:** paste [`SKILL.md`](skills/social-analytics-reporter/SKILL.md) into your rules or system prompt.

## 💬 Usage

Just ask your agent:

```text
Analyze this Instagram Insights export
Write my monthly social media report
```

The full workflow, rules and output format are in [`SKILL.md`](skills/social-analytics-reporter/SKILL.md).

## 🧩 More skills

See the full collection: **[milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills)**.

## 🤝 Contributing

Issues and PRs are welcome, especially real-world before/after examples.

## 📄 License

[MIT](LICENSE) © Milad Ahmadi

<div align="center">

**If this skill saved you time, a ⭐ helps others find it.**

</div>
