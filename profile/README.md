<p align="center">
  <img src="https://memcastle.github.io/images/logo.svg" alt="MemCastle">
</p>

<p align="center"><strong>Local-first, always-on memory server for AI coding agents over MCP/HTTP</strong></p>

<p align="center">
  <img src="https://img.shields.io/github/v/release/memcastle/memcastle" alt="Release">
  <a href="https://memcastle.github.io/">
    <img src="https://img.shields.io/badge/docs-memcastle.github.io-blue" alt="Documentation">
  </a>
  <img src="https://img.shields.io/github/license/memcastle/memcastle" alt="License">
</p>

---

Running several AI coding agents (OpenCode, Claude Code, Cursor, ...) side by side
usually means each one gets its own, disconnected memory — or none at all.
MemCastle is a single daemon per palace (the memory store that one or more of your projects share)
that all of them talk to over MCP or HTTP,
so a mining run, a search, or a saved decision from one agent
is immediately visible to every other agent and to the CLI.
Everything lives in one SurrealDB store, embedded by default, so there is no external service to run.

