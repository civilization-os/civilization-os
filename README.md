# civilization-os 🏛️

> **Server operations runtime for AI agents.**
>
> We build MCP (Model Context Protocol) servers that turn AI coding agents into full-fledged server operations platforms.

---

## Projects

### [🔌 ssh-mcp](https://github.com/civilization-os/ssh-mcp)

Stateful remote server management for AI agents — persistent SSH sessions, interactive PTY terminals, SFTP file operations, Kubernetes management, system monitoring, and Java diagnostics via Arthas.

Use it with Claude Code, Reasonix, Cursor, Codex, or any MCP-compatible AI agent.

```
ssh_connect → ssh_exec → ssh_file_read → ssh_sysinfo
     ↓
ssh_shell (interactive PTY with real-time output streaming)
     ↓
ssh_k8s_list_pods → ssh_k8s_pod_logs → ssh_k8s_arthas_attach
```

| Feature | Description |
|---------|-------------|
| 🖥️ **Interactive Shell** | Full PTY with real-time output, `expect` pattern matching, ANSI stripping |
| 📁 **SFTP** | Read, write, list, delete, rename, mkdir, chmod, stat — full file ops |
| 📊 **Monitoring** | System info, processes, disk usage, log tail & search |
| ☸️ **Kubernetes** | Pod management, exec, logs, cp, and Arthas Java diagnostics |
| 🔐 **Security** | Credentials stay in process memory only — never persisted to disk |

---

## Why civilization-os?

AI agents are great at *writing* code. But deploying, monitoring, and operating servers requires a different kind of tool — one that maintains state, streams real-time output, and lets humans observe and intervene.

We build that bridge.

---

## Get Involved

- 🌐 **[ssh-mcp](https://github.com/civilization-os/ssh-mcp)** — Star us, open issues, send PRs
- 💬 **Discussions** — Share your use cases and ideas
- 🤝 **Contributions welcome** — Check out our good first issues

---

<p align="center">
  <sub>Built with ❤️ for the AI operations era</sub>
</p>
