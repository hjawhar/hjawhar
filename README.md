# Hassan Jawhar

Retired DeFi researcher and protocol developer. Spent years building high-frequency trading infrastructure, MEV systems, and DEX tooling across Solana and EVM chains.

Now focused on what sits underneath: **reverse engineering**, **embedded systems**, and **distributed systems**. Taking apart binaries, writing firmware, building things that talk to each other at the edge.

---

### Current Work

**Reverse Engineering** — Binary analysis, firmware extraction, protocol dissection. Spending time inside disassemblers and debuggers understanding how things actually work under the hood.

**Embedded Systems** — Real-time computer vision pipelines for edge hardware, vehicle telemetry over OBD-II, sensor integration. Rust on bare metal and constrained targets.

**Distributed Systems** — Event-driven architectures, service discovery, consensus patterns. Building systems that scale horizontally and degrade gracefully.

---

### Stack

```
Languages       Rust · C · ARM/x86 Assembly · Python
RE Tooling      Ghidra · radare2 · GDB/LLDB · Frida · objdump · Wireshark
Embedded        ARM Cortex-M · ESP32 · STM32 · Raspberry Pi · JTAG · UART/SPI/I2C
Distributed     NATS · gRPC · Protocol Buffers · Raft · CRDTs
CV / ML         ONNX Runtime · YOLO · ArcFace · PaddleOCR · OpenCV
Infra           Docker · Kubernetes · Prometheus · Grafana · Jaeger
Cloud           AWS · Hetzner · Cloudflare · Tailscale
Database        PostgreSQL · Redis · SQLite
OS              Linux · FreeRTOS · Zephyr
```

---

### Selected Projects

[**perception**](https://github.com/hjawhar/perception) — High-throughput real-time computer vision pipeline — object detection (YOLO), face recognition (SCRFD + ArcFace), and OCR (PaddleOCR) in Rust via ONNX Runtime. Designed for edge deployment on drones, surveillance units, and roadside hardware.

[**makana**](https://github.com/hjawhar/makana) — Live OBD-II vehicle telemetry. Read, record, replay, and visualize real-time car data. Rust backend with a single-file HTML dashboard.

[**irc**](https://github.com/hjawhar/irc) — A modern IRC stack built from scratch in Rust: server, mIRC-style GUI client, and bouncer — all sharing a common protocol crate.

[**distributed-system**](https://github.com/hjawhar/distributed-system) — Distributed system exercising real patterns: service discovery, pub/sub, request-reply, horizontal scaling. Four services over NATS, deployed via Docker Compose or Kubernetes, with full Prometheus/Grafana/Jaeger observability.

---

<sub>hassanjawhar@protonmail.com</sub>
