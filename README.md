<div align="center">
<pre>
██╗  ██╗██╗    ████████╗██╗  ██╗███████╗██████╗ ███████╗
██║  ██║██║    ╚══██╔══╝██║  ██║██╔════╝██╔══██╗██╔════╝
███████║██║       ██║   ███████║█████╗  ██████╔╝█████╗
██╔══██║██║       ██║   ██╔══██║██╔══╝  ██╔══██╗██╔══╝
██║  ██║██║       ██║   ██║  ██║███████╗██║  ██║███████╗
╚═╝  ╚═╝╚═╝       ╚═╝   ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚══════╝
</pre>
</div>

---

## (Some) Open Source Contributions

<details>
  <summary>Symmetria</summary>

  - **Description:**  An intuitive and comprehensive framework for interacting with the symmetric group and its elements, built on a Rust backend for optimal performance.

  - **Repository:**  [VascoSch92/symmetria](https://github.com/VascoSch92/symmetria) · [VascoSch92/symmetria-core](https://github.com/VascoSch92/symmetria-core)

  - **Contributions:**  Creator & Maintainer

</details>

<details>
  <summary>OpenHands</summary>

  - **Description:**  An open-source platform for AI software-engineering agents.

  - **Repository:**  [OpenHands](https://github.com/OpenHands)

  - **Contributions:**  Core contributor - 180+ merged pull requests on the [agent SDK](https://github.com/OpenHands/software-agent-sdk), 40+ on [agent-canvas](https://github.com/OpenHands/agent-canvas)
      - **Parallel tool calls** - the execution engine, a resource-lock manager to make concurrent tools safe, per-tool resource declarations, and the concurrency limit surfaced end-to-end in agent settings
      - **Subagents** - file-based agent definitions in markdown + YAML frontmatter, built-in specialized agents, and the task tool set that replaced the delegate tool
      - **LLM profiles** - a persisted profile store, the management API, cipher-encrypted secrets, and per-conversation model switching from the chat UI
      - **Conversation history tree** - parent/child lineage, fork-from-event and navigation, exposed over HTTP and surfaced as branching a conversation from any message
      - **Prompt registry** - typed prompt sections replacing the Jinja templates, guarded by a golden-snapshot test of the rendered system prompt
      - **Token-level streaming** - over the agent-server WebSocket and rendered live in the chat

</details>

<details>
  <summary>Ruff</summary>

  - **Description:**  An extremely fast Python linter and code formatter, written in Rust.

  - **Repository:**  [astral-sh/ruff](https://github.com/astral-sh/ruff)

  - **Contributions:**  34 merged pull requests, in three areas
      - **Fix-safety auditing** — documenting and re-classifying when an autofix can silently change behaviour: `RUF005`, `RUF007`, `RUF013`, `RUF017`, `RUF027`, `RUF028`, `RUF033`, `SIM103`, `SIM110`, `SIM112`, `SIM210`, `FLY002`, `D200`
      - **Correctness fixes** — [#16080](https://github.com/astral-sh/ruff/pull/16080) argument ordering in `PLR1730`'s fix, [#16550](https://github.com/astral-sh/ruff/pull/16550) starred expressions in `FURB161`, [#16552](https://github.com/astral-sh/ruff/pull/16552) mixed-case hash names in `S324`
      - **Fewer false positives** — [#15980](https://github.com/astral-sh/ruff/pull/15980) exempt `sys.path += ...` from `E402`, [#15988](https://github.com/astral-sh/ruff/pull/15988) leading underscores in `N801`, [#16454](https://github.com/astral-sh/ruff/pull/16454) module-attribute names in `A001`

</details>

<details>
  <summary>Feature Engine</summary>

  - **Description:**  Feature engineering package with sklearn like functionality.

  - **Repository:**  [feature-engine/feature_engine](https://github.com/feature-engine/feature_engine)

  - **Contributions:**
      - https://github.com/feature-engine/feature_engine/pull/806 - Implementation of a mean normalization scaling transformer

</details>

---

<div align="center">
<sub>🦊</sub>
</div>
