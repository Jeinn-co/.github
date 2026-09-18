# Jeinn

Full-stack TypeScript. Open source lives here; projects and collaborations are at [jeinn.co](https://www.jeinn.co).

TypeScript 全端。開源在這裡，專案與合作在 [jeinn.co](https://www.jeinn.co)。

## Open source / 開源

**[agent-skills](https://github.com/Jeinn-co/agent-skills)** — Agent skills for Claude Code, Codex CLI, and Grok Build. Currently includes:

- [`ai-usage`](https://github.com/Jeinn-co/agent-skills/tree/main/skills/ai-usage): one command to check live usage and reset times across three AI subscriptions.
- [`ai-cli-version`](https://github.com/Jeinn-co/agent-skills/tree/main/skills/ai-cli-version): one command to see whether the Claude Code, Codex and Grok Build CLIs are up to date, and when each version was installed and released. Tested on Windows only so far.

給 Claude Code、Codex CLI、Grok Build 使用的 agent skills。目前收錄 [`ai-usage`](https://github.com/Jeinn-co/agent-skills/tree/main/skills/ai-usage)：一份指令查看三家 AI 訂閱的即時用量與重置時間；以及 [`ai-cli-version`](https://github.com/Jeinn-co/agent-skills/tree/main/skills/ai-cli-version)：檢查三種 CLI 是否為最新版，以及各版本的安裝與發佈日期。目前僅在 Windows 測試。

```bash
npx skills add Jeinn-co/agent-skills@ai-usage
npx skills add Jeinn-co/agent-skills@ai-cli-version
```

---

hello@jeinn.co
