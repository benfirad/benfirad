<p align="center">
  <img src="./assets/header.svg?v=ascii-giraffe-1" width="100%" alt="daak terminal profili ve ASCII zürafa">
</p>

<p align="center">
  <code>agentic-ai</code> · <code>smart-home-iot</code> · <code>macos-native</code> · <code>local-first</code> · <code>sub-5ms-fts5</code> · <code>autonomous-workflows</code>
</p>

> Quiet, fast, local-first tools, smart-home hardware telemetry & autonomous multi-agent workflows. Built for macOS, Linux, Android TV, and private Tailscale meshes—with reversible automation and zero cloud bloat.

---

## `~/featured-systems`

| Project | Architecture & Impact | Stack |
| :--- | :--- | :--- |
| [🦆 **hermes-plugin-antigravity-duet**](https://github.com/benfirad/hermes-plugin-antigravity-duet) | **Claude Duet-style 24/7 autonomous background task queue** with isolated workspaces, a **Human-in-the-Loop (HITL) approval gate**, and a 6-tier multi-model CLI quota fallback engine ([Upstream PR #144514](https://github.com/NousResearch/hermes-agent/pull/144514)). | `Python` `SQLite-WAL` `Multi-Agent` |
| [⚡ **Remote Spotlight**](https://github.com/benfirad/remote-spotlight) | **Sub-5ms cross-device Spotlight search bar for macOS.** Queries remote Windows workstations, Linux servers, and NAS drives over SSH/Tailscale using local BM25 SQLite FTS5 indexing and on-demand SCP streaming—eliminating SMB/NFS Finder freezes. | `Swift` `SQLite-FTS5` `Tailscale` |
| [📺 **tv-vibehack**](https://github.com/benfirad/tv-vibehack) *(23★)* | **Your TV, minus the ads.** Privacy-first, tvOS-inspired Android TV launcher with a pure-Python ADB toolchain, dynamic Stremio media shelf, day/night solar wallpaper cycles, frosted glass settings, and ultra-low dock peek physics. | `Java` `Python-ADB` `Android-TV` |
| [🏝️ **Atoll (Ruflo Swarm Edition)**](https://github.com/benfirad/Atoll) | **Dynamic Island for macOS** enhanced with a live **Multi-Agent Swarm telemetry dashboard (`NotchRufloView`)**, Arc & Zen browser real-time audio waveform tapping, and DisplayServices hardware brightness fixes ([Upstream PR #893](https://github.com/Ebullioscopic/Atoll/pull/893)). | `Swift` `AppKit` `CoreAudio` |
| [🎙️ **daakDİKTE-macos**](https://github.com/benfirad/daakDIKTE-macos) | **Offline-first voice dictation for macOS & Linux** powered by local `whisper.cpp`, Carbon global hotkeys, and AVFoundation capture ([Co-authored Upstream PR #8](https://github.com/yusufipk/dikte/pull/8)). | `Python` `PyQt6` `whisper.cpp` |
| [💡 **daakREMEMBER**](https://github.com/benfirad/daakREMEMBER) | **Zero-friction macOS menu bar thought & task capture** that syncs privately across nodes over Tailscale and bridges directly into autonomous background queues. | `Swift` `AppKit` `Tailscale` |
| [🛡️ **daakLOLILE**](https://github.com/benfirad/daakLOLILE) | **Privacy-first Tor relay, Snowflake proxy & hardware telemetry** utility with pressure-gated memory maintenance and frosted-glass macOS menu bar controls. | `Swift` `PowerShell` `Tor` |
| [🧠 **daakRAM**](https://github.com/benfirad/daakRAM) | **Native macOS memory pressure monitor** and safe application lifecycle manager. | `Swift` `macOS` |
| [🕰️ **ClockScrambler**](https://github.com/benfirad/ClockScrambler) | **macOS menu-bar clock customizer** featuring written time, emoji modes, and live background-aware color adaptation. | `Swift` `AppKit` |

---

## `~/smart-home-and-edge-hardware`

Beyond desktop software, I architect **zero-cloud ambient home & hardware automation** across repurposed ARM/Android nodes, Zigbee bridges, and macOS control planes:

* **🎬 Autonomous Cinema & Philips Hue Engine (`daak-hue-automator v2.9`):** Repurposed a Samsung Galaxy S9+ (`star2lte`) into a 24/7 headless Linux/Termux edge controller that polls an Android TV over OpenSSL-signed ADB every 2 seconds. Inspects real-time media playback states and active TCP sockets (filtering out false-positive Bluetooth loopback sockets on port 7000) with **4s/6s anti-flicker hysteresis debouncing**, solar sunset brightness curves, and self-healing zombie/SIGTSTP watchdog recovery to orchestrate Philips Hue living-room scenes automatically.
* **🎛️ Unified Hardware Telemetry & D-Pad Control Plane (`DAAK Node Hub v2.23`):** Native macOS frosted-glass menu bar hub & OLED-black Android launcher displaying real-time power draw (Watts) across 4 machines, interactive Philips Hue zone sliders, Android TV D-Pad remote controls, and a Thunderbolt-first 1440p60 multi-camera OBS broadcast studio.

---

## `~/showcase`

<p align="center">
  <a href="https://github.com/benfirad/daakREMEMBER"><img src="https://raw.githubusercontent.com/benfirad/daakREMEMBER/main/docs/hero.svg" width="49%" alt="daakREMEMBER"></a>
  <a href="https://github.com/benfirad/daakDIKTE-macos"><img src="https://raw.githubusercontent.com/benfirad/daakDIKTE-macos/macos-support/docs/hero.svg" width="49%" alt="daakDİKTE"></a>
</p>
<p align="center">
  <a href="https://github.com/benfirad/daakLOLILE"><img src="https://raw.githubusercontent.com/benfirad/daakLOLILE/main/docs/hero.svg" width="49%" alt="daakLOLILE"></a>
  <a href="https://github.com/benfirad/daakRAM"><img src="https://raw.githubusercontent.com/benfirad/daakRAM/main/docs/hero.svg" width="49%" alt="daakRAM"></a>
</p>

---

## `~/upstream-contributions`

* **[NousResearch/hermes-agent #144514](https://github.com/NousResearch/hermes-agent/pull/144514)** — Authored `antigravity-duet` plugin (Autonomous background task queue, Human-in-the-Loop approval gate, and multi-model CLI bridge).
* **[Ebullioscopic/Atoll #893](https://github.com/Ebullioscopic/Atoll/pull/893)** — Fixed core animation bouncing loop, wildcard notification CPU spikes, and multi-monitor jitter in macOS Dynamic Island.
* **[yusufipk/dikte #8](https://github.com/yusufipk/dikte/pull/8) & [#44](https://github.com/yusufipk/dikte/pull/44)** — Co-authored the native macOS backend (`AVFoundation` audio capture, Carbon global hotkeys, and Apple key-code mapping).
* **[Gathin23/cleanyourtv #155](https://github.com/Gathin23/cleanyourtv/pull/155) & [#51](https://github.com/Gathin23/cleanyourtv/pull/51)** — Featured `tv-vibehack` (Stremio shelf, frosted glass settings, and dock peek physics) in the upstream showcase.

---

## `~/toolbox`

```text
ai-agents  : Model Context Protocol (MCP), Multi-Agent Swarms, HITL Queues, whisper.cpp
smart-iot  : Philips Hue REST/Zigbee, Pure-Python ADB, Headless Termux/ARM Edge Nodes
languages  : Python (Asyncio/FastAPI), Swift (AppKit/SwiftUI), TypeScript (React 19), Java, Bash
storage    : SQLite FTS5 (<5ms BM25 search), WAL concurrency, SHA-256 delta sync
infra      : Tailscale Mesh, Docker, Cloudflare Zero-Trust Tunnels, Stalwart Mail, launchd
principles : local-first, privacy-aware, deterministic gates, reversible automation
```

## `~/activity`

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/benfirad/benfirad/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/benfirad/benfirad/output/github-contribution-grid-snake.svg">
    <img alt="Hareketli GitHub katkı grafiği" src="https://raw.githubusercontent.com/benfirad/benfirad/output/github-contribution-grid-snake.svg">
  </picture>
</p>

```console
daak@github:~$ echo "build small; verify the real thing; share what survives"
```
