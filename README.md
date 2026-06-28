# Yan Shen

### Open Source Contributions

<table>
  <thead>
    <tr>
      <th>Project</th>
      <th>PR</th>
      <th>What I Fixed</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="12" valign="top">
        <a href="https://github.com/QwenLM/qwen-code">Qwen Code</a><br>
        (25.6k★)
      </td>
      <td><a href="https://github.com/QwenLM/qwen-code/pull/5935">#5935</a></td>
      <td>Updated the <code>/mcp</code> management dialog to use the same rounded full-width border style as other CLI dialogs, fixing the clipped right edge and adding a focused regression test.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/QwenLM/qwen-code/pull/4668">#4668</a></td>
      <td>Redesigned MiniMax setup to combine searchable recommended models with manual model ID entry, added official MiniMax-M3 support, and preserved saved credentials across compatible model switches.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/QwenLM/qwen-code/pull/4653">#4653</a></td>
      <td>Made Qwen Code honor <code>.agentignore</code> and <code>.aiignore</code> through the existing ignore pipeline, and added configurable custom ignore files so teams can share agent ignore rules safely.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/QwenLM/qwen-code/pull/4634">#4634</a></td>
      <td>Stabilized <code>/statusline</code> preset ordering so toggled items return to a fixed priority order instead of drifting to the end, which keeps saved settings, previews, and rendered output consistent.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/QwenLM/qwen-code/pull/4564">#4564</a></td>
      <td>Extended <code>/stats</code> with persisted daily and monthly token usage summaries, model and auth-type breakdowns, and guarded CSV or JSON export so usage and cost are easier to inspect.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/QwenLM/qwen-code/pull/4062">#4062</a></td>
      <td>Added a configurable <code>plansDirectory</code> for Plan Mode so approved plan files can live inside a project-specific path instead of always using the global default location.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/QwenLM/qwen-code/pull/3871">#3871</a></td>
      <td>Expanded core CLI i18n coverage by localizing built-in command descriptions and UI labels, adding optional dynamic command translation, and tightening locale validation.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/QwenLM/qwen-code/pull/3701">#3701</a></td>
      <td>Improved interactive <code>/export</code> completion so arrow-key navigation can fill and cycle export formats directly in the input, while preserving the old Enter behavior when users do not navigate suggestions.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/QwenLM/qwen-code/pull/3677">#3677</a></td>
      <td>Fixed MiniMax OpenAI-compatible parsing so thinking tags are handled correctly and the CLI no longer shows malformed or misleading reasoning output.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/QwenLM/qwen-code/pull/3647">#3647</a></td>
      <td>Kept the sticky todo panel compact in small terminals by truncating long items, summarizing overflow, and hiding duplicate or recently visible inline todo output to reduce Windows flicker.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/QwenLM/qwen-code/pull/3507">#3507</a></td>
      <td>Added a sticky todo panel to the CLI layouts so the latest task list stays visible during long conversations without forcing users to scroll back through earlier tool output.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/QwenLM/qwen-code/pull/3270">#3270</a></td>
      <td>Stopped raw Tab keypresses from inserting literal tab characters into <code>BaseTextInput</code>, preserving Tab for completion, focus switching, and other control-key behavior.</td>
    </tr>
  </tbody>
</table>

<!--
Use an HTML table with rowspan when consecutive PRs belong to the same project.
-->
