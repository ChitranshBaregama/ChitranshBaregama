# Chitransh Baregama

**Senior Embedded Firmware Engineer** — utility-grade smart metering firmware at
Genus Power Infrastructure, Jaipur. Bare-metal Embedded C on Renesas RL78,
DLMS/COSEM (IEC 62056), FreeRTOS. 3.5+ years, all of it on firmware that has to
run unattended in the field for a decade.

Currently going deeper on automotive and Linux-side embedded: CAN, AUTOSAR,
BSP work, and firmware security.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/chitransh-baregama)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=microsoftoutlook&logoColor=white)](mailto:chitranshbaregama23@outlook.com)

---

## What I've published here

I learn by writing the reference I wish existed, then making it hold up. Both
of these are open, and both state plainly which claims are verified and which
are not.

### 📘 [DLMS/COSEM Security — Engineering Reference](https://github.com/ChitranshBaregama/EncryptionAlgorithm-)

Seven volumes, ~60,000 words, on the security stack behind most of the world's
smart meters. Built from the Green Book 8th edition as the sole normative
source, with every statement labelled by how much weight it can bear —
specification requirement, cryptographic theory, implementation
recommendation, vendor behaviour, or inference.

Every official Green Book test vector is reproduced independently in Python.
While doing that I found **nine errors in a widely-circulated secondary
security guide**, each documented with the clause that settles it — including
a Security Control bit-layout error that decodes correctly for the three
commonly-quoted values and silently sends you to the wrong key the moment you
touch broadcast or Suite 1.

### 🔧 [Embedded Systems Reference](https://github.com/ChitranshBaregama/embedded-systems-resources)

~240,000 words on bare-metal firmware — UART, I²C, SPI, interrupts and the
NVIC, memory systems, flash engineering, state machines, the physical layer —
plus **code that builds and runs on a laptop with no board attached**:

- Six bare-metal Cortex-M3 programs under QEMU: startup and memory map,
  SysTick, NVIC preemption, a lock-free SPSC ring buffer driven by a real ISR,
  a HardFault decoder that turns a hang into a line number, a framed-protocol
  parser
- Hardware-independent logic compiled *unmodified* by both the target build and
  a host test suite — 19 tests, 605k assertions, under AddressSanitizer
- Register-accurate STM32F4 I²C and SPI drivers, labelled compile-verified
  rather than hardware-verified, because they are

### 📟 [SMS P10 Notice Board](https://github.com/ChitranshBaregama/sms-p10-notice-board)

GSM-controlled scrolling LED notice board — ATmega2560 + SIM800 + P10 matrix.
Sender authentication, message queueing, power-cut persistence, and a
notification-independent SMS engine for unattended 24/7 operation.

---

## What I actually work on

| | |
| :--- | :--- |
| **Metering firmware** | Single-phase metrology firmware on Renesas RL78. Bare metal, no RTOS, hard constraints on flash and RAM |
| **Protocol stacks** | DLMS/COSEM (IEC 62056), IS 16444, GSM/GPRS. Association setup, ciphered APDUs, HLS authentication |
| **RTOS** | FreeRTOS multi-tasking runtimes — a telemetry gateway on ESP32 balancing extraction, processing and transmission |
| **Embedded Linux** | Buildroot BSP for Raspberry Pi 4; a character device driver handling virtual interrupts and concurrency |
| **Deterministic bare metal** | FSM-structured single-core frameworks where asynchronous polling loops must not interfere |

**Tools:** IAR Embedded Workbench, arm-none-eabi-gcc, GDB + OpenOCD, QEMU,
logic analyzers, MISRA C.

**Languages:** Embedded C (C11), C++, Python.

---

## What I'm working toward

Firmware security as a specialisation — secure boot, update integrity, debug
port lockdown, fault injection and side channels. The DLMS security manual was
the first step; the next ones are a responsible disclosure and upstream
contributions to U-Boot or Zephyr.

Open to relocating.

---

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=ChitranshBaregama&show_icons=true&theme=tokyonight&count_private=true&hide_border=true" height="165" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ChitranshBaregama&layout=compact&theme=tokyonight&hide_border=true" height="165" alt="Top languages" />
</p>

📍 Jaipur, Rajasthan, India · 📧 [chitranshbaregama23@outlook.com](mailto:chitranshbaregama23@outlook.com) · 💼 [LinkedIn](https://linkedin.com/in/chitransh-baregama)
