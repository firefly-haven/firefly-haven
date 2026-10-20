# Jay Kochhar

**Electrical Engineering Student @ San Francisco State University** · B.S. expected **May 2029** · San Francisco Bay Area

I build and debug systems where **electronics, embedded firmware, and software meet**: sensor interfaces, PCB prototypes, edge-AI devices, and Linux-based hardware platforms. I enjoy taking projects from architecture and schematic design through bring-up, testing, and iteration.

**Seeking Summer 2027 internships** in embedded firmware, electrical/hardware engineering, hardware or silicon validation, robotics, and edge AI.

[**Email**](mailto:jay.kochhar@gmail.com) · [**Portfolio**](https://firefly-haven.github.io/) · [**GitHub projects**](https://github.com/firefly-haven?tab=repositories)

## Featured engineering work

### [60 GHz Radar Gesture Recognition — PSoC 6](https://github.com/firefly-haven/PSOC-Trigger1)
**Embedded C · Infineon XENSIV BGT60TR13C · DEEPCRAFT · GPIO/UART**

- Adapted Infineon's PSoC 6 radar/embedded-ML example into a gesture-input subsystem for a larger assistive facial-recognition project.
- Collected and labeled radar samples, **trained and deployed a custom swipe gesture**, and tested inference on physical hardware.
- Implemented **GPIO triggers and UART event output** so gesture detections could be consumed by other devices.

[My firmware and documentation](https://github.com/firefly-haven/PSOC-Trigger1) · [Full team project: Infineon-X](https://github.com/Infineon-X/infineon-x) · [Radar case study](https://firefly-haven.github.io/projects/radar-gesture.html)

### [Lantern — Interactive Projection Appliance](https://github.com/firefly-haven/lantern)
**Raspberry Pi 4 · MPU-6050 · Python/FastAPI · Svelte/TypeScript · Embedded Linux**

- Built a local-first projector application with a fullscreen display, browser-based control UI, WebSocket updates, and systemd-based startup/recovery.
- Brought up the IMU over I²C and verified **live accelerometer/gyroscope telemetry** on the Raspberry Pi and projector hardware.
- **Prototype in progress:** automatic motion-triggered blanking and calibrated desk/wall/ceiling pose switching are not yet validated on hardware.

### NVIDIA Jetson AGX Orin — Local AI & OCR
**Jetson AGX Orin 32 GB · CUDA · Ollama · llama.cpp · Python · Linux**

- Built and tested a CUDA-enabled llama.cpp setup and benchmarked local inference, investigating **long-context performance, Flash Attention, KV-cache settings, and unified-memory limits**.
- Connected local inference to an Obsidian OCR workflow with page-level transcription and visual quality checks.
- *Systems/deployment project; standalone public write-up not yet available.*

### Hardware Prototyping & PCB Fabrication
**KiCad · Circuit simulation · PCB layout · Soldering · Test instrumentation**

- Designed and prototyped instructional electronics modules, from component selection and PCB layout through fabrication, testing, and classroom materials.
- Revised a workshop synthesizer PCB, evaluated milling/laser trace-isolation options, and **fabricated, assembled, and tested working boards** using toner transfer and wet etching.
- Built a programmable peristaltic-pump prototype using an **ESP8266, stepper driver, and USB-C Power Delivery/buck-conversion hardware**.

### Raspberry Pi Compute & Storage Cluster
**Six CM4 nodes · NVMe · Ceph/CephFS · Samba · Docker · Linux networking**

- Built a six-node Raspberry Pi CM4/NVMe cluster, configured distributed storage for single-node failure tolerance, and deployed shared storage and containerized services.
- Worked through real-world Linux administration, storage, networking, and failure-recovery considerations.

## Engineering experience

**Krause Center for Innovation (KCI) — Makerspace Staff** · April 2025–present

Design and prototype electronics learning modules; troubleshoot hardware and fabrication equipment; develop and co-facilitate hands-on training for K–12 educators in circuits, soldering, CAD, and digital fabrication.

Previously held customer-facing technical and team-leadership roles at **Best Buy** and as a **Samsung Experience Consultant through 2020 Companies**.

## Technical toolkit

| Area | Tools and experience |
| --- | --- |
| **Embedded hardware** | PSoC 6, STM32 (C/ARM assembly), ESP32/ESP8266, Raspberry Pi, Jetson AGX Orin; GPIO, UART, I²C, sensor and motor interfaces |
| **Electronics & validation** | KiCad, schematic capture, PCB layout/fabrication, circuit simulation, soldering, DMM, oscilloscope, logic-analyzer debugging |
| **Programming & systems** | C, C++, Python, Linux, Git, Docker, FastAPI, Ceph, Proxmox, networking, Ollama, llama.cpp |
| **Digital design** | Combinational/sequential logic, FSMs, registers, datapaths, and Xilinx ISE simulation **(coursework in progress)** |
| **CAD & fabrication** | Parametric CAD, FDM/SLA 3D printing, CO₂/diode/fiber laser fabrication, CNC machining and CAM |

**Current focus:** microelectronics and digital design coursework, STM32 firmware, sensor-rich embedded devices, and practical validation of edge-AI systems.

I'm particularly interested in internships where I can contribute to **board bring-up, firmware, test automation, and hardware/software integration**, while continuing to learn from experienced engineers.
