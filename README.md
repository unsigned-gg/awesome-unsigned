# Awesome Unsigned [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of open GPU stacks, pooled agent runtimes, bare-metal orchestration, and deterministic plumbing across [unsigned.gg](https://unsigned.gg) and the broader open-source ecosystem.

The engine: open, forkable compute, storage, and scheduling priced like plumbing.

---

## Contents

- [Agent Substrates & Runtimes](#agent-substrates--runtimes)
- [Session Multiplexing & Control](#session-multiplexing--control)
- [Bare-Metal & Infrastructure](#bare-metal--infrastructure)
- [Deterministic Dispatch & Scheduling](#deterministic-dispatch--scheduling)
- [Sandboxing & Desktop Automation](#sandboxing--desktop-automation)
- [Terminal Interfaces](#terminal-interfaces)
- [Contributing](#contributing)

---

## Agent Substrates & Runtimes

- [uas](https://github.com/unsigned-gg/uas) — Unsigned Agent Substrate: Rust-native pooled harness runtime with strict zero-I/O domain layering.
- [substrate](https://github.com/unsigned-gg/substrate) — Execution runtime primitives for persistent agent processes.
- [ax](https://github.com/unsigned-gg/ax) — Open agentic orchestration runtime.

---

## Session Multiplexing & Control

- [herdr](https://github.com/unsigned-gg/herdr) — The runtime your coding agents live on: socket API, multi-agent pane orchestration, and session state without tmux.
- [herdr-dagr](https://github.com/unsigned-gg/herdr-dagr) — Agent swarm as a live DAG with review gates, attempts, and evidence in a split pane.
- [herdr-norn](https://github.com/unsigned-gg/herdr-norn) — Synchronized scrollback per project across multiple agent panes.

---

## Bare-Metal & Infrastructure

- [unsigned-paas](https://github.com/unsigned-gg/unsigned-paas) — Kubernetes-native AI/ML PaaS: bare-metal Talos, Helm, ArgoCD, and GPU scheduling.
- [metal-foundry](https://github.com/unsigned-gg/metal-foundry) — Talos Image Factory schematics, PXE bring-up, and bare-metal upgrade drills.
- [cadastre](https://github.com/unsigned-gg/cadastre) — Alchemy IaC control plane for cloud and edge infrastructure.

---

## Deterministic Dispatch & Scheduling

- [escapement](https://github.com/unsigned-gg/escapement) — Metered, deterministic dispatch engine for autonomous agent swarms.
- [waker](https://github.com/unsigned-gg/waker) — Accept-and-hold TCP wake proxy and idle reaper for scale-to-zero workloads.

---

## Sandboxing & Desktop Automation

- [reach](https://github.com/unsigned-gg/reach) — AI-drivable containerized desktop sandbox.
- [overflow](https://github.com/unsigned-gg/overflow) — GPU-accelerated, agent-aware terminal emulator in Rust (wgpu, ConPTY).

---

## Terminal Interfaces

- [omp](https://github.com/unsigned-gg/omp) — Terminal AI coding agent with hash-anchored edits, LSP, and subagent orchestration.
- [shell-deck](https://github.com/unsigned-gg/shell-deck) — TUI shell overlay with a clickable deck of agent messages.

---

## Contributing

Contributions are welcome. Please open an issue or pull request following the guidelines in CONTRIBUTING.md.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
