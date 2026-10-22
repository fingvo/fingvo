# Sohail MN (Aka Fingvo)

<p align="center">
  <b>Full Stack & Systems Engineer | Open Source Builder</b><br/>
  Architecting high-performance systems across Telephony, Voice AI, and Software Reverse Engineering.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Author-Sohail%20MN-00f2fe?style=flat-square" alt="Author" />
  <img src="https://img.shields.io/badge/Handle-Fingvo-3178C6?style=flat-square" alt="Handle" />
  <img src="https://img.shields.io/badge/Focus-Telecom%20%7C%20Voice%20AI%20%7C%20SRE-DEA584?style=flat-square" alt="Focus" />
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=flat-square" alt="License" />
</p>

---

## Featured Open Source Systems

### 1. [Telovox](https://github.com/fingvo/telovox)
**Carrier-Grade Open-Source Real-Time AI Telephony & Calling Automation Platform**

Telovox bridges enterprise SIP trunking with ultra-low latency speech-to-speech AI workflows. It enables developers to host their own private, high-volume voice calling platform without paying per-minute SaaS markups.

* **Media & Switching Engine:** **Erlang (BEAM)** - Handles concurrent SIP signaling (RFC 3261), RTP audio packet routing, and zero-crash OTP supervision trees.
* **Agent & Automation Backend:** **Node.js (TypeScript)** - Coordinates bi-directional audio WebSocket pipelines, real-time STT (Deepgram/Whisper), streaming LLM reasoning, sub-90ms TTS (Cartesia/ElevenLabs), and mid-call dynamic webhook automations.
* **Studio Workbench:** **Next.js 14 (TypeScript)** - Full studio dashboard with live call waveform visualizers, turn-by-turn latency telemetry, outbound campaign dispatcher, and in-browser mic simulator.
* **Persistent Storage:** **MySQL 8.0** - Relational storage for agents, campaigns, leads, call logs, and turn transcripts.

```
[ Next.js Studio ] <---> [ Node.js TypeScript Agent ] <---> [ Erlang Media Engine ] <---> [ SIP Carrier ]
                                   |
                             [ MySQL 8.0 ]
```

---

### 2. [Revix](https://github.com/fingvo/revix)
**Next-Generation Software Reverse Engineering (SRE) & Binary Inspection Framework**

Revix is a modular workbench engineered for rapid binary analysis, malware forensics, firmware inspection, and decompilation assistance across Windows PE, Linux ELF, and Mach-O binaries.

* **Core Analysis Engine:** **Rust** - High-throughput binary parser for ELF and PE32+ headers, Shannon entropy calculator (0.0 to 8.0), and ASCII/UTF-16 string extractor.
* **Inspection Frontend:** **React.js (TypeScript)** - Sleek dark obsidian SRE workbench featuring an interactive hex editor, live x86_64 disassembly stream with decompiler annotations, entropy wave charts, and memory section tables.
* **Automation Suite:** **Python** - Automated signature matcher (compilers, packers like UPX/Themida) and heuristic capability threat scanner.

---

## Technical Stack & Systems Expertise

| Domain | Technologies |
| :--- | :--- |
| **Languages** | TypeScript, JavaScript, Rust, Erlang, Python, SQL, C/C++ |
| **Frontend & UI** | Next.js 14/15, React 18, Tailwind CSS, Vanilla CSS Design Systems |
| **Backend & Real-time** | Node.js, Express, Fastify, WebSockets, REST APIs, Unix Sockets |
| **Telephony & Media** | Erlang BEAM, SIP Trunking, RTP Audio Packets, WebRTC, G.711 / Opus |
| **AI & Voice Pipelines** | Streaming STT, Low-Latency TTS, Function Calling, Prompt Engineering |
| **Databases** | MySQL, MariaDB, PostgreSQL, Redis |
| **Systems & Forensics** | Binary Disassembly, ELF/PE Parsing, Shannon Entropy, SRE Workflows |

---

## Open Source Philosophy

* **Zero Mock Data:** Every system is designed production-ready, backed by real protocol streams, authentic byte buffers, and live database queries.
* **Predictable Performance:** Zero-downtime concurrency using Erlang supervision trees and memory-safe Rust native engines.
* **Developer First:** Clean modular codebases, strict typing, comprehensive architectural documentation, and permissive MIT licensing.

---

<p align="center">
  <b>Copyright (c) 2026 Fingvo. All rights reserved.</b><br/>
  <i>Engineered by Sohail MN (Aka Fingvo)</i>
</p>
