# Shashank Kontikal

**Systems & Creative Technologist** · Bengaluru, IN  
Bridging physical sensor input with local machine learning and low-latency network protocols.

[Email](mailto:shashankkontikal07@gmail.com) · [GitHub](https://github.com/Darkcoder-droid) · [LinkedIn](https://linkedin.com/in/ShashankKontikal)

---

### Engineering Focus & Active Runtimes

* **Primary Focus:** Edge AI, offline-first IoT mesh topologies, sensor-to-model inference pipelines.
* **Local Compute Nodes:**
  * **M1 Pro (10-core / 16GB):** Model quantization, PyTorch training, local LLM evaluation (Ollama/MLX).
  * **M2 Air:** Lightweight edge service orchestration, portable testing, client-side UI tooling.
* **Core Toolchain:** Python (FastAPI, PyTorch), C/C++ (Embedded, RF), TypeScript, MediaPipe, LoRa Sub-GHz.

---

### Selected Engineering Projects

#### [kelsa.ai](https://github.com/Darkcoder-droid/kelsa.ai) — Self-Hosted Career Copilot
*Self-contained productivity daemon tracking applications, resumes, and advisor telemetry.*
* Built with an **air-gapped, offline-first design pattern**; relies on isolated, zero-leak per-user JSON datastores rather than external third-party DB dependencies.
* Exposes an asynchronous FastAPI layer tailored for low-overhead cron tasks and automation scripts.
* **Stack:** Python, FastAPI, AsyncIO, Local JSON Storage Engine

#### Sign Language Translation Glove — Physical Computing & Edge ML
*Hardware-to-speech translation pipeline converting raw physical flexion into synthetic voice output.*
* Designed a 5-channel analog flex sensor array routed through microcontrollers for real-time gesture telemetry.
* Trained and deployed a low-footprint classification model mapping spatial finger configurations directly to ASL tokens with sub-100ms inference latency.
* **Stack:** Embedded C, PyTorch Edge, Signal Processing, Hardware I/O

#### [why.fi](https://github.com/Darkcoder-droid/why.fi) — Real-Time Spatial Facial Arcade
*Sub-second facial landmark matching engine running over raw video streams.*
* Uses MediaPipe mesh extraction to compute Euclidean coordinate distances against target expression vectors.
* Employs full-duplex WebSockets over FastAPI to process frame metadata with near-zero input lag.
* **Stack:** FastAPI, WebSockets, Google MediaPipe, React, Vite

#### LoRa Mesh Comm — Off-Grid Low-Power Telemetry
*Decentralized, packet-routed peer-to-peer radio communication system.*
* Implemented multi-hop mesh routing over Sub-GHz bands for communication in cellular-dead zones without central gateway dependencies.
* Tuned duty cycles and packet fragmentation to prioritize ultra-low battery consumption.
* **Stack:** C/C++, LoRa RF95, Microcontroller Firmware, Mesh Routing

---

### Technical Competencies
