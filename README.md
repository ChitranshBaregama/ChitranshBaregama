# Chitransh Baregama

**Embedded firmware engineer · Embedded C · DLMS/COSEM · Firmware security**

I work on smart-metering firmware, where memory budgets, protocol behavior,
and reliable operation shape every design decision. My public work explores
constrained microcontrollers, testable protocol logic, and the electrical
behavior behind firmware.

[LinkedIn](https://linkedin.com/in/chitransh-baregama) · [Email](mailto:chitranshbaregama23@outlook.com) · Jaipur, India

## Selected projects

| Project | Engineering focus | What you can inspect |
| :--- | :--- | :--- |
| [ATtiny85 GSM Controller](https://github.com/ChitranshBaregama/attiny85-gsm-controller) | Missed-call and SMS control with an ATtiny85 and SIM900A | Software UART, oscillator calibration, modem parsing, host tests, and documented limitations |
| [Embedded Systems: Code and Reference](https://github.com/ChitranshBaregama/embedded-systems-resources) | Bare-metal firmware from electrical behavior to application logic | Portable C, CAN/ISO-TP, Cortex-M QEMU labs, STM32 driver examples, and peripheral handbooks |
| [Security Engineering in C](https://github.com/ChitranshBaregama/security-engineering) | Understanding cryptographic primitives through implementation | SHA-256, HMAC, known-answer tests, length-extension demonstrations, and timing measurements; educational implementations |
| [SMS P10 Notice Board](https://github.com/ChitranshBaregama/sms-p10-notice-board) | GSM-controlled display on Arduino Mega | AT transaction state machine, fixed buffers, scrolling, and EEPROM persistence in a hardware prototype |
| [DLMS/COSEM Security Reference](https://github.com/ChitranshBaregama/EncryptionAlgorithm-) | Protocol-specific security and embedded implementation decisions | Association security, AES-GCM/GMAC, key management, PKI/ECC, and Python vector calculations |

## Learn the hardware behind the firmware

Two first-principles guides connect circuit behavior to firmware decisions:

- **[GPIO: from the silicon pad to a reliable board](https://github.com/ChitranshBaregama/embedded-systems-resources/blob/main/peripherals/gpio.md)** — input receivers, push-pull and open-drain outputs, pull resistors, current paths, startup states, interrupts, and board-level debugging.
- **[ADC: from first principles to engineering practice](https://github.com/ChitranshBaregama/embedded-systems-resources/blob/main/peripherals/adc.md)** — sampling, source impedance, converter architectures, error budgets, DMA, calibration, RMS, and energy-meter acquisition.

Explore the [full reference index](https://github.com/ChitranshBaregama/embedded-systems-resources)
or go straight to the [code and build instructions](https://github.com/ChitranshBaregama/embedded-systems-resources/tree/main/code).

## Engineering background and interests

- **Metering and protocols:** Embedded C on Renesas RL78, DLMS/COSEM (IEC 62056), GSM/GPRS, and resource-constrained firmware.
- **Firmware design:** state machines, peripheral drivers, interrupt handling, protocol parsing, and real-time systems.
- **Current study:** firmware security, CAN, Cortex-M architecture, and the boundary between analog hardware and digital software.
- **Languages and tools:** C, C++, Python, IAR Embedded Workbench, GCC, GDB/OpenOCD, and QEMU.

Professional background and public portfolio evidence are distinct. Each
repository documents its own build instructions and validation limits:
host tests exercise software logic, emulator runs exercise selected target
behavior, and hardware measurements require a stated board and setup.
The handbooks contain teaching examples, not a claim of validated hardware
performance or production-ready drivers.

Open to embedded firmware opportunities and relocation.

