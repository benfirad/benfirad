<p align="center">
  <img src="./assets/header.svg?v=ascii-giraffe-1" width="100%" alt="daak terminal profile with an ASCII giraffe">
</p>

<p align="center">
  <a href="https://github.com/benfirad?tab=repositories"><img src="https://img.shields.io/badge/macOS-native-111?style=flat-square&logo=apple&logoColor=white" alt="macOS native"></a>
  <img src="https://img.shields.io/badge/local--first-privacy--aware-0e4429?style=flat-square" alt="local-first">
  <img src="https://img.shields.io/badge/AI%20agents-human--in--the--loop-FA7314?style=flat-square" alt="AI agents with approval gates">
  <img src="https://img.shields.io/badge/home%20lab-Tailscale%20mesh-242424?style=flat-square&logo=tailscale&logoColor=white" alt="Tailscale home lab">
</p>

> Small, quiet tools for macOS, Android TV and a self-hosted home lab. Everything runs locally, asks before it does anything risky, and can be undone.

---

## `~/now`

<table>
<tr>
<td width="50%" valign="top">

### 🦆 [DAAK Duffy](https://github.com/benfirad/daak-duffy) <a href="https://github.com/NousResearch/hermes-agent/pull/144514"><img src="https://img.shields.io/badge/NousResearch%20Hermes-Official%20Plugin-7c3aed?style=flat-square" alt="Hermes Plugin"></a>

Self-hosted background AI worker and official [Nous Research Hermes Agent](https://github.com/NousResearch/hermes-agent/pull/144514) catalog plugin. Queue a task, it runs it with Claude Code, Antigravity or Ollama, falls back between models when one hits its quota, and **stops to show you the exact command** before anything risky. Zero-dependency Python server plus a native SwiftUI menu bar app.

<a href="https://benfirad.github.io/daak-duffy/">Website</a> · <a href="https://github.com/benfirad/daak-duffy/blob/main/CHANGELOG.md">Changelog</a> · <a href="https://github.com/NousResearch/hermes-agent/pull/144514">PR #144514</a>

`Python` `SwiftUI` `SQLite` `Claude Code` `Hermes Agent`

</td>
<td width="50%" valign="top">

### 📺 [tv-vibehack](https://github.com/benfirad/tv-vibehack) <img src="https://img.shields.io/github/stars/benfirad/tv-vibehack?style=flat-square&label=%E2%98%85&color=FA7314" alt="stars" align="right">

Your TV, minus the ads. Debloats any Android TV over ADB and gives it a clean, tvOS-inspired launcher with a Stremio shelf, day/night wallpapers and a frosted-glass settings panel.

`Java` `Python ADB` `Android TV`

</td>
</tr>
</table>

## `~/macos-utilities`

| | Project | What it does | Stack |
| :-: | :--- | :--- | :--- |
| ⚡ | [**Remote Spotlight**](https://github.com/benfirad/remote-spotlight) | Spotlight-style bar that searches other machines (Windows, Linux, NAS) over SSH from a local SQLite FTS5 index, in a few milliseconds and without mounting anything. | `Swift` `FTS5` |
| 💡 | [**daakREMEMBER**](https://github.com/benfirad/daakREMEMBER) | Menu bar capture for thoughts and tasks, synced privately between your own devices over Tailscale. | `Swift` `AppKit` |
| 🧠 | [**daakRAM**](https://github.com/benfirad/daakRAM) | Memory pressure monitor that tells you which app is the problem and closes it safely. | `Swift` |
| 🕰️ | [**ClockScrambler**](https://github.com/benfirad/ClockScrambler) | Menu bar clock in words, emoji or colours that match your wallpaper. | `Swift` `AppKit` |
| 🛡️ | [**daakLOLILE**](https://github.com/benfirad/daakLOLILE) | Tor relay, Snowflake proxy and hardware telemetry for a spare PC, with safe power modes and a menu bar remote. | `PowerShell` `Swift` |
| 🎙️ | [**daakDİKTE**](https://github.com/benfirad/daakDIKTE-macos) | Offline voice typing for macOS and Linux with local whisper.cpp and global hotkeys. | `Python` `whisper.cpp` |
| 🏝️ | [**Atoll** (fork)](https://github.com/benfirad/Atoll) | Dynamic Island for macOS, with a live agent dashboard in the notch. | `Swift` `CoreAudio` |

## `~/upstream`

- **[NousResearch/hermes-agent #144514](https://github.com/NousResearch/hermes-agent/pull/144514)**: **Official plugin catalog admission** for DAAK Duffy (`daak-duffy` / `antigravity-duet`) — background task queue with human-in-the-loop approval gates, multi-agent Ruflo swarms and multi-model Antigravity fallback. Code-reviewed and merged by **@teknium1**.
- **[Ebullioscopic/Atoll #893](https://github.com/Ebullioscopic/Atoll/pull/893)**: fixed an animation bounce loop, notification CPU spikes and multi-monitor jitter.
- **[yusufipk/dikte #8](https://github.com/yusufipk/dikte/pull/8), [#44](https://github.com/yusufipk/dikte/pull/44)**: native macOS backend (AVFoundation capture, Carbon hotkeys, key-code mapping).
- **[Gathin23/cleanyourtv #155](https://github.com/Gathin23/cleanyourtv/pull/155), [#51](https://github.com/Gathin23/cleanyourtv/pull/51)**: tv-vibehack featured in the upstream showcase.

## `~/home-lab`

A repurposed phone runs headless as a 24/7 edge controller: it watches what the TV is playing and dims the Philips Hue lights for films, with debouncing so a paused trailer does not flicker the room. A broken-screen laptop runs the AI worker and backups; everything talks over a private Tailscale mesh and nothing needs a cloud account.

## `~/toolbox`

```text
languages  : Swift (SwiftUI, AppKit), Python, Java, TypeScript, PowerShell, Bash
ai         : Claude Code, MCP, multi-agent queues, approval gates, whisper.cpp, Ollama
data       : SQLite FTS5, WAL, delta sync
infra      : Tailscale, launchd, Docker, Cloudflare Tunnels, GitHub Actions
principles : local-first · ask before acting · verify the real thing · reversible
```

## `~/activity`

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/benfirad/benfirad/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/benfirad/benfirad/output/github-contribution-grid-snake.svg">
    <img alt="Animated contribution graph" src="https://raw.githubusercontent.com/benfirad/benfirad/output/github-contribution-grid-snake.svg">
  </picture>
</p>

```console
daak@github:~$ echo "build small; verify the real thing; share what survives"
```
