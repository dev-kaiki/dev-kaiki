# Kaiki Quadros Ferreira

**Software engineer working where software meets machines.**
I build systems for CNC machine tools and the shop floor around them — serial protocols, the tablets and desktops that drive them, and AI on top of technical archives. C++, Python, and the parts of a stack that break when real hardware is on the other end.

Based in Brazil · open to remote roles worldwide

---

### The machine, end to end

These three projects are one system, taken apart. A CNC machine needs programs sent to it, needs them sent from somewhere, and needs fixing when it stops. I built all three sides at [SMI](https://github.com/dev-kaiki), where they are in daily use — real work on real machines, not yet sold as products.

| | | |
|---|---|---|
| **[dnc-serial-engine](https://github.com/dev-kaiki/dnc-serial-engine)**<br>[![build](https://github.com/dev-kaiki/dnc-serial-engine/actions/workflows/build.yml/badge.svg)](https://github.com/dev-kaiki/dnc-serial-engine/actions/workflows/build.yml) | `C++17` `Qt` | RS-232 DNC engine. Adaptive flow control that streams G-code to controllers with kilobytes of buffer and no telemetry — fast enough to be useful, slow enough not to drop a block mid-cut. |
| **[dnc-android](https://github.com/dev-kaiki/dnc-android)**<br>[![build](https://github.com/dev-kaiki/dnc-android/actions/workflows/build.yml/badge.svg)](https://github.com/dev-kaiki/dnc-android/actions/workflows/build.yml) | `Qt 6` `QML` `C++17` `JNI` | The same engine on a tablet bolted to the machine, reaching RS-232 through USB OTG and an FTDI chip. Ported unchanged behind an extracted `ISerialPort` — then made to actually send, through five faults that raised no error. |
| **[maia-cnc-assistant](https://github.com/dev-kaiki/maia-cnc-assistant)**<br>[![tests](https://github.com/dev-kaiki/maia-cnc-assistant/actions/workflows/tests.yml/badge.svg)](https://github.com/dev-kaiki/maia-cnc-assistant/actions/workflows/tests.yml) | `Python` `FastAPI` `RAG` `Flutter` | RAG assistant over a company's technical archive. Multi-stage answer pipeline with safety policy, human-reviewed ingestion, three-level AI cost guards, Flutter app and WhatsApp channel. |

If you only read one thing, read the [engineering log](https://github.com/dev-kaiki/dnc-serial-engine/tree/main/docs/engineering-log) in the first repo — the flow-control debugging history on live machines, including the fix that caused the next bug.

---

### What I work with

**Systems & embedded** — C++17, Qt/QML, Android (JNI, USB host), RS-232/serial protocols, FreeRTOS, CMake
**Backend & AI** — Python, FastAPI, PostgreSQL/pgvector, RAG, OpenAI & Gemini, Docker
**Apps** — Flutter, Qt Quick, TypeScript
**Ops** — Caddy, CI, versioned migrations, backup and restore

### How I work

I ship things that run unattended in places where failure is expensive, and I document what I got wrong on the way there. The interesting part of a system is usually the constraint nobody wrote down — the controller that lies about its buffer state, the archive nobody can search, the budget that a retry loop can burn through overnight.

---

### Currently

Open to **remote engineering roles worldwide** — backend, embedded and industrial systems, or applied AI. Available for contract or full-time, and comfortable working across European and American time zones from Brazil.

📫 [kaikiiquadros091o@gmail.com](mailto:kaikiiquadros091o@gmail.com) · 🌐 [dev-kaiki.github.io](https://dev-kaiki.github.io) · 💼 [LinkedIn](https://www.linkedin.com/in/kaiki-ferreira/)
