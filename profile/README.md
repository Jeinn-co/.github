# Jeinn

Full-stack TypeScript. Open source lives here; projects and collaborations are at [jeinn.co](https://www.jeinn.co).

TypeScript 全端。開源在這裡，專案與合作在 [jeinn.co](https://www.jeinn.co)。

## Open source / 開源

**[agent-skills](https://github.com/Jeinn-co/agent-skills)** — Agent skills for Claude Code, Codex CLI, Grok Build, and any agent that reads the `SKILL.md` convention. Currently includes:

- [`ai-usage`](https://github.com/Jeinn-co/agent-skills/tree/main/skills/ai-usage): one command to check live usage and reset times across five AI subscriptions: Claude, ChatGPT (Codex), Grok, Muse, and Gemini (Antigravity CLI).
- [`ai-cli-version`](https://github.com/Jeinn-co/agent-skills/tree/main/skills/ai-cli-version): one command to see whether five CLIs — Claude Code, Codex, Grok Build, Muse Code, and Antigravity (Gemini) — are up to date, and when each version was installed and released. Tested on Windows and macOS.

給 Claude Code、Codex CLI、Grok Build，以及任何讀 `SKILL.md` 慣例的 agent 使用的 skills。目前收錄 [`ai-usage`](https://github.com/Jeinn-co/agent-skills/tree/main/skills/ai-usage)：一份指令查看 Claude、ChatGPT（Codex）、Grok、Muse、Gemini（Antigravity CLI）五家 AI 訂閱的即時用量與重置時間；以及 [`ai-cli-version`](https://github.com/Jeinn-co/agent-skills/tree/main/skills/ai-cli-version)：檢查 Claude Code、Codex、Grok Build、Muse Code、Antigravity（Gemini）五種 CLI 是否為最新版，以及各版本的安裝與發佈日期。已在 Windows 與 macOS 測試。

```bash
npx skills add Jeinn-co/agent-skills@ai-usage
npx skills add Jeinn-co/agent-skills@ai-cli-version
```

**[ai-model-compare](https://github.com/Jeinn-co/ai-model-compare)** — An interactive chart of score against cost per task for the models behind five coding CLIs. Data comes from Artificial Analysis (default) or CursorBench and is refreshed every six hours. The Y axis can also show speed, verbosity and latency (Artificial Analysis) or tokens and steps per task (CursorBench). [Open the chart](https://jeinn-co.github.io/ai-model-compare/).

五個 coding CLI 的模型分數對每題成本互動圖表，資料可切換 Artificial Analysis（預設）與 CursorBench，每六小時更新。Y 軸也能改看速度、冗長度、延遲（Artificial Analysis），或每題 token 數與步數（CursorBench）。[開啟圖表](https://jeinn-co.github.io/ai-model-compare/) · [原始碼](https://github.com/Jeinn-co/ai-model-compare)

---

hello@jeinn.co
