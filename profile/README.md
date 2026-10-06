# Jeinn

Full-stack TypeScript. Open source lives here; projects and collaborations are at [jeinn.co](https://www.jeinn.co).

## Open source

**[agent-skills](https://github.com/Jeinn-co/agent-skills)** — Agent skills for Claude Code, Codex CLI, Grok Build, and any agent that reads the `SKILL.md` convention. Currently includes:

- [`ai-usage`](https://github.com/Jeinn-co/agent-skills/tree/main/skills/ai-usage): one command to check live usage and reset times across five AI subscriptions: Claude, ChatGPT (Codex), Grok, Muse, and Gemini (Antigravity CLI).
- [`ai-cli-version`](https://github.com/Jeinn-co/agent-skills/tree/main/skills/ai-cli-version): one command to see whether five CLIs — Claude Code, Codex, Grok Build, Muse Code, and Antigravity (Gemini) — are up to date, and when each version was installed and released. Tested on Windows and macOS.

```bash
npx skills add Jeinn-co/agent-skills@ai-usage
npx skills add Jeinn-co/agent-skills@ai-cli-version
```

**[ai-model-compare](https://github.com/Jeinn-co/ai-model-compare)** — An interactive chart of score against cost per task for the models behind five coding CLIs. Data comes from Artificial Analysis (default) or CursorBench and is refreshed every six hours. The Y axis can also show speed, verbosity and latency (Artificial Analysis) or tokens and steps per task (CursorBench). [Open the chart](https://jeinn-co.github.io/ai-model-compare/) · [Source code](https://github.com/Jeinn-co/ai-model-compare)

---

hello@jeinn.co
