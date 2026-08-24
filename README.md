# Kaiki Quadros Ferreira

**Software engineer working where software meets machines.**
I build systems for CNC machine tools and the shop floor around them — serial protocols, embedded firmware, and AI on top of technical archives. C++, Python, and the parts of a stack that break when real hardware is on the other end.

Based in Brazil · open to remote roles worldwide

---

### The machine, end to end

These three projects are one system, taken apart. A CNC machine needs programs sent to it, needs them sent from somewhere, and needs fixing when it stops. I built all three sides at [SMI](https://github.com/dev-kaiki), and they run in production.

| | | |
|---|---|---|
| **[dnc-serial-engine](https://github.com/dev-kaiki/dnc-serial-engine)** | `C++17` `Qt` | RS-232 DNC engine. Adaptive flow control that streams G-code to controllers with kilobytes of buffer and no telemetry — fast enough to be useful, slow enough not to drop a block mid-cut. |
| **[esp32-dnc-firmware](https://github.com/dev-kaiki/esp32-dnc-firmware)** | `C++` `FreeRTOS` `ESP32` | The same job on bare metal. Six FreeRTOS tasks, lock-free ring buffers, microSD storage and an embedded web UI, so the machine gets its own Wi-Fi DNC instead of a laptop on a cart. |
| **[maia-cnc-assistant](https://github.com/dev-kaiki/maia-cnc-assistant)** | `Python` `FastAPI` `RAG` `Flutter` | RAG assistant over a company's technical archive. Multi-stage answer pipeline with safety policy, human-reviewed ingestion, three-level AI cost guards, Flutter app and WhatsApp channel. |

If you only read one thing, read the [engineering log](https://github.com/dev-kaiki/dnc-serial-engine/tree/main/docs/engineering-log) in the first repo — the flow-control debugging history on live machines, including the fix that caused the next bug.

---

### What I work with

**Systems & embedded** — C++17, Qt, FreeRTOS, ESP32, RS-232/serial protocols, CMake
**Backend & AI** — Python, FastAPI, PostgreSQL/pgvector, RAG, OpenAI & Gemini, Docker
**Apps** — Flutter, TypeScript
**Ops** — Caddy, CI, versioned migrations, backup and restore

### How I work

I ship things that run unattended in places where failure is expensive, and I document what I got wrong on the way there. The interesting part of a system is usually the constraint nobody wrote down — the controller that lies about its buffer state, the archive nobody can search, the budget that a retry loop can burn through overnight.

---

📫 [kaikiiquadros091o@gmail.com](mailto:kaikiiquadros091o@gmail.com) · [LinkedIn](https://www.linkedin.com/in/kaiki-ferreira)
