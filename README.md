# Yan Shen

### Open Source Contributions

| Project | PR | What I Fixed |
|---|---|---|
| [Qwen Code](https://github.com/QwenLM/qwen-code) (25.6k★) | [#5935](https://github.com/QwenLM/qwen-code/pull/5935) | Updated the `/mcp` management dialog to use the same rounded full-width border style as other CLI dialogs, fixing the clipped right edge and adding a focused regression test. |
| [Qwen Code](https://github.com/QwenLM/qwen-code) (25.6k★) | [#4668](https://github.com/QwenLM/qwen-code/pull/4668) | Redesigned MiniMax setup to combine searchable recommended models with manual model ID entry, added official MiniMax-M3 support, and preserved saved credentials across compatible model switches. |
| [Qwen Code](https://github.com/QwenLM/qwen-code) (25.6k★) | [#4653](https://github.com/QwenLM/qwen-code/pull/4653) | Made Qwen Code honor `.agentignore` and `.aiignore` through the existing ignore pipeline, and added configurable custom ignore files so teams can share agent ignore rules safely. |
| [Qwen Code](https://github.com/QwenLM/qwen-code) (25.6k★) | [#4634](https://github.com/QwenLM/qwen-code/pull/4634) | Stabilized `/statusline` preset ordering so toggled items return to a fixed priority order instead of drifting to the end, which keeps saved settings, previews, and rendered output consistent. |
| [Qwen Code](https://github.com/QwenLM/qwen-code) (25.6k★) | [#4564](https://github.com/QwenLM/qwen-code/pull/4564) | Extended `/stats` with persisted daily and monthly token usage summaries, model and auth-type breakdowns, and guarded CSV or JSON export so usage and cost are easier to inspect. |
| [Qwen Code](https://github.com/QwenLM/qwen-code) (25.6k★) | [#4062](https://github.com/QwenLM/qwen-code/pull/4062) | Added a configurable `plansDirectory` for Plan Mode so approved plan files can live inside a project-specific path instead of always using the global default location. |
| [Qwen Code](https://github.com/QwenLM/qwen-code) (25.6k★) | [#3871](https://github.com/QwenLM/qwen-code/pull/3871) | Expanded core CLI i18n coverage by localizing built-in command descriptions and UI labels, adding optional dynamic command translation, and tightening locale validation. |
| [Qwen Code](https://github.com/QwenLM/qwen-code) (25.6k★) | [#3701](https://github.com/QwenLM/qwen-code/pull/3701) | Improved interactive `/export` completion so arrow-key navigation can fill and cycle export formats directly in the input, while preserving the old Enter behavior when users do not navigate suggestions. |
| [Qwen Code](https://github.com/QwenLM/qwen-code) (25.6k★) | [#3677](https://github.com/QwenLM/qwen-code/pull/3677) | Fixed MiniMax OpenAI-compatible parsing so thinking tags are handled correctly and the CLI no longer shows malformed or misleading reasoning output. |
| [Qwen Code](https://github.com/QwenLM/qwen-code) (25.6k★) | [#3668](https://github.com/QwenLM/qwen-code/pull/3668) | Added current-session billing estimates to `/stats`, including configurable pricing for input, cached input, and output tokens, so users can see approximate model cost while they work. |
| [Qwen Code](https://github.com/QwenLM/qwen-code) (25.6k★) | [#3647](https://github.com/QwenLM/qwen-code/pull/3647) | Kept the sticky todo panel compact in small terminals by truncating long items, summarizing overflow, and hiding duplicate or recently visible inline todo output to reduce Windows flicker. |
| [Qwen Code](https://github.com/QwenLM/qwen-code) (25.6k★) | [#3507](https://github.com/QwenLM/qwen-code/pull/3507) | Added a sticky todo panel to the CLI layouts so the latest task list stays visible during long conversations without forcing users to scroll back through earlier tool output. |
| [Qwen Code](https://github.com/QwenLM/qwen-code) (25.6k★) | [#3328](https://github.com/QwenLM/qwen-code/pull/3328) | Localized built-in slash command descriptions, added runtime translation support for dynamic commands, and completed built-in UI locale coverage for the officially bundled languages. |
| [Qwen Code](https://github.com/QwenLM/qwen-code) (25.6k★) | [#3270](https://github.com/QwenLM/qwen-code/pull/3270) | Stopped raw Tab keypresses from inserting literal tab characters into `BaseTextInput`, preserving Tab for completion, focus switching, and other control-key behavior. |

<!--
Paste rows like this:
| [Qwen Code](https://github.com/QwenLM/qwen-code) (25.6k★) | [#123](https://github.com/QwenLM/qwen-code/pull/123) | Describe the concrete bug you fixed, the behavior change, and why the improvement matters. |
-->
