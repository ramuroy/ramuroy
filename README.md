<div align="center">

<!-- Animated typing header -->
<a href="https://github.com/ramuroy">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=00E5FF&center=true&vCenter=true&width=800&height=60&lines=Embedded+Systems+Engineer;Hardware+%C2%B7+Firmware+%C2%B7+Embedded+Linux+%C2%B7+On-Device+ML;Yocto+%C2%B7+ESP-IDF+%C2%B7+STM32+%C2%B7+Rust;From+PCB+design+to+custom+Linux+distros+%E2%9A%99%EF%B8%8F" alt="Typing SVG" />
</a>

<!-- Badges -->
<img src="https://komarev.com/ghpvc/?username=ramuroy&label=Profile%20Views&color=00e5ff&style=flat-square" alt="Profile views" />
<img src="https://img.shields.io/github/followers/ramuroy?label=Followers&style=flat-square&color=00e5ff" alt="Followers" />
<img src="https://img.shields.io/badge/Open%20to-Embedded%20Roles-1f9b4e?style=flat-square" alt="Open to roles" />
<a href="https://ramuroy.github.io"><img src="https://img.shields.io/badge/Portfolio-ramuroy.github.io-00e5ff?style=flat-square&logo=astro&logoColor=white" alt="Portfolio" /></a>

</div>

---

### 🦾 About Me

```c
struct Engineer {
    char  name[]      = "Ramu Roy";
    char  role[]      = "Embedded Systems Engineer";
    char  focus[]     = "Hardware | Firmware | Embedded Linux | On-Device ML";
    char  stack[]     = "C/C++, Rust, Python, Yocto, ESP-IDF, STM32";
    char  building[]  = "eOS @ Elipse — a custom Yocto Linux distro for the RPi 5";
    char  boards[]    = "3 control PCBs designed in KiCad — 2 fabricated, 1 in the field";
    char  side[]      = "pcbrouter (KiCad autorouter in Rust) · Ember (a personal OS)";
    char  shipped[]   = "Industrial Anti-Collision System @ Tata Steel BlueScope";
    char  studies[]   = "B.Tech ECE, RGUKT Srikakulam (CGPA 8.3/10)";
    bool  ships_real_hardware = true;
};
```

- ⚙️ I work **the whole stack** — from **PCB/KiCad hardware design** and bare-metal STM32/ESP-IDF firmware, up through Yocto-based custom Linux, to on-device ML.
- 🛠️ I design the boards too: **three control PCBs in KiCad**, schematic through layout to the fabrication package. A 24 V room controller is **live in three rooms**; a 48 V, 16-channel, four-layer floor controller with on-board Ethernet is routed and packaged for fab.
- 🏭 My firmware runs in the field: an industrial **Anti-Collision System** I built is deployed at **Tata Steel BlueScope**.
- 🐧 Currently building **eOS** — a Yocto/OpenEmbedded Linux distribution for the Raspberry Pi 5 with A/B RAUC OTA, an MQTT service bus, and a Qt6/QML UI.
- 🎙️ Into **on-device voice & ML** — wake-word detection, Whisper STT, Piper TTS, and multi-mic fusion running on the edge in Rust.
- 🌐 Portfolio: **[ramuroy.github.io](https://ramuroy.github.io)**
- 📫 Reach me: **royramu694429@gmail.com**

---

### 🧑‍💻 Experience

**🐧 Embedded Systems Engineer — Elipse, Hyderabad** &nbsp;·&nbsp; *May 2026 – Present*
> Building **eOS**, Elipse's custom **Yocto/OpenEmbedded** Linux distro for the **Raspberry Pi 5** (A/B RAUC OTA rootfs, MQTT service bus, SQLite, Qt6/QML UI). Authored Yocto recipes across the `meta-eos` layer; designed `systemd` services, **D-Bus** interfaces, and a hardened Mosquitto MQTT broker. Built a generic **Rust** sensor-fusion framework and an on-device **voice subsystem** (transfer-learned wake-word → Whisper STT → Piper TTS, ONNX via `tract`). Wrote **ESP-IDF** firmware for ESP32 satellites with BLE provisioning, EC P-256 keypairs, and X.509 CSR exchange. Design the fleet's **control boards in KiCad** end to end — a 24 V room controller (v2 re-spun at −57 % board area, live in three rooms), a **48 V / 16-channel / 24 A four-layer** floor controller with 100 Ω differential Ethernet pairs, and a SELV wall keypad.

**🏗️ Embedded Systems Engineer Intern — Radiogeet** &nbsp;·&nbsp; *Sep 2025 – Mar 2026*
> Built an industrial **Anti-Collision System** for crane operations, **deployed at Tata Steel BlueScope**. Dual-core **ESP32-S3** firmware: one core for real-time **UWB** proximity ranging, the other for zone-safety logic + an embedded web UI. Used **ESP-NOW** for low-latency node-to-node links and **MODBUS RTU over RS485** to drive an 8-channel industrial relay system. Also interfaced AHT10 / ADS1115 with **STM32** and worked with LoRa and Masibus industrial I/O cards.

**🔧 R&D Engineer — Ampnics** &nbsp;·&nbsp; *Mar 2025 – Sep 2025 (Remote)*
> Contributed to **open-source hardware** — designed and reviewed PCB schematics & layouts, and supported rapid prototyping through circuit testing, debugging, and iterative design.

---

### 🧰 Tech & Tools

**Languages**
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Embedded Linux & Firmware**
![Yocto](https://img.shields.io/badge/Yocto%20Project-1f4e79?style=for-the-badge&logo=yoctoproject&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![ESP32](https://img.shields.io/badge/ESP--IDF-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-4FA94D?style=for-the-badge)

**Systems & Data**
![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![D-Bus](https://img.shields.io/badge/D--Bus-A42E2B?style=for-the-badge&logo=freedesktopdotorg&logoColor=white)

**ML, UI & EDA**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![Qt](https://img.shields.io/badge/Qt6%20%2F%20QML-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

> **Protocols:** UART · SPI · I²C · CAN · RS485 (MODBUS RTU) · BLE · ESP-NOW · LoRa · UWB

---

### 🚀 Selected Work — 2026

Most of this year's work lives in **employer or private repositories**, so the rows below say what
exists and where rather than linking to code that isn't mine to publish. Full write-ups with the
measured numbers are on the **[portfolio](https://ramuroy.github.io)**.

| Project | What it is | Where |
|---|---|---|
| 🟩 **eOS Zone Controller** | 48 V, sixteen 12-bit PWM channels at 24 A / 1,152 W, **four layers** on an impedance-controlled stackup with 100 Ω differential Ethernet pairs. Routing closed at **0 unconnected**; DC review at 19.9 mV against a 50 mV bound; fab package cut. | Elipse · private |
| 🟩 **eOS Room Controller** | 24 V per-room board — 8 dimmable PWM channels, addressable RGB, wired Ethernet, I²S mic bridge. v1 fabbed and in service; **v2 re-spun at −57 % area** and now live in three rooms. | Elipse · private |
| 🟩 **eOS Switchboard** | SELV wall control surface, 145 × 70 mm, ESP32-S3, 30 addressable indicators, CAN uplink. Fabricated; board #1 in bring-up. | Elipse · private |
| 🦀 **pcbrouter** | A **KiCad-native PCB autorouter** in Rust on exact integer geometry — no clearance decision touches floating point. Loader dump field-identical to `pcbnew` across 1,212 footprints; output judged by KiCad's own DRC. Apache-2.0. | private for now |
| 🔥 **Ember** | A personal OS: an existing Linux kernel and a Yocto userland with **systemd removed** and replaced by two programs written from scratch in Rust — `spark`, a PID 1 and service manager, and `hearth`, the login shell. Boots real hardware over UEFI with signed A/B updates. | private for now |
| 🏗️ [**Industrial Anti-Collision System**](https://github.com/ramuroy/Industrial-Anti-Collision-System) | Dual-core ESP32-S3 UWB crane safety system — **deployed at Tata Steel BlueScope**. ESP-NOW links, MODBUS RTU/RS485 to an 8-channel relay bank. | ✅ public |

<details>
<summary><b>Earlier work — 2024–25 learning projects</b></summary>

<br/>

Hardware: [Transformerless Power Supply](https://github.com/ramuroy/Transformerless-Power-Supply) ·
[LM2596 Buck Converter](https://github.com/ramuroy/LM2596-5V-Buck-Converter-PCB-Design) ·
[5V→3.3V Regulator](https://github.com/ramuroy/5V-to-3.3V-Voltage-Regulator-PCB-Design) ·
[AC-to-DC Converter](https://github.com/ramuroy/AC-to-DC-Converter-PCB) ·
[Servo Tester (NE555)](https://github.com/ramuroy/Servo-Tester-NE555)

Firmware & IoT: [RTOS Weather Logger](https://github.com/ramuroy/RTOS-Weather-Logger) ·
[FreeRTOS Multitasking LEDs](https://github.com/ramuroy/FreeRTOS-Multitasking-LEDs) ·
[Solar Track](https://github.com/ramuroy/Solar-Track) ·
[Object Detection over SPI](https://github.com/ramuroy/Real-Time-Object-Detection-using-SPI-Protocol-between-ESP32-and-Arduino) ·
[Fire Detection](https://github.com/ramuroy/Fire-Detection-System) ·
[Water Level Detector](https://github.com/ramuroy/Water-Level-Detector) ·
[Morse Caster](https://github.com/ramuroy/Morse-Caster)

</details>

---

### 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=ramuroy&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ramuroy&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" />

<img src="https://streak-stats.demolab.com/?user=ramuroy&theme=tokyonight&hide_border=true" alt="Streak" />

</div>

---

### 📈 In-Depth Metrics

<div align="center">

<img src="https://raw.githubusercontent.com/ramuroy/ramuroy/main/github-metrics.svg" alt="Detailed GitHub metrics — languages, activity, isometric calendar, habits" />

</div>

---

### 🐍 Watch the snake eat my commits

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ramuroy/ramuroy/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ramuroy/ramuroy/output/github-contribution-grid-snake.svg" />
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/ramuroy/ramuroy/output/github-contribution-grid-snake.svg" />
</picture>

</div>

---

### 🎓 Certifications & Languages

- 📜 **NPTEL** — Embedded Sensing, Actuation and Interfacing Systems *(85%)*
- 📜 **NPTEL** — Electronic Systems Design: Circuits & PCB Design with CAD *(88%)*
- 🗣️ **Languages:** English (Proficient) · Telugu (Native) · Hindi (Native)

---

<div align="center">

### 🤝 Connect

<a href="https://www.linkedin.com/in/ramu-roy-b780382b7">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="mailto:royramu694429@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>

<br/><br/>

<i>⚡ "First it blinks, then it thinks — then it ships." ⚡</i>

</div>
