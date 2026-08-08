# cleydroid

> A free, open-source mobile operating system powered by Linux

---

## About

**[Cleydroid]** is an independent operating system built for mobile devices. Designed to offer a lightweight, smooth,and privacy-focused alternative to mainstream mobile plateforms, it is built entirely on open technologies.

### Key Features
* **Linux Kernel:** Driven by a Linux kernel tailored for mobile hardware.
* **Touch-First UI:** Responsive user interfacedesigned specifically for handled use.
* **Privacy by Default:** Zero telemetry, zero trackers, full ownership of you data.
* **Open Ecosystem:** Native support for standard Linux softwareand custom packages.

---

## Hardware Support & Project Status

Current state of hardware support accross target architectures:
### Target Devices
* **Emulator:** QEMU (x86_64 / ARM64)
* **Smartphones:** [e.g., PinePhone, Librem 5 or Mainline Linux devices]

---

## Quickstart (Testing)

### Prerequisties

* A 64-bit Linux destribution (Fedora, Debian, Arch, Ubuntu, Kova etc.)
* `qemu-system-x86_64` (for emulation) or `fastboot` (for flashing real devices).

### Run in QEMU Emulator
```bash
# Download the latest system image
wget [https://github.com/Darul123-bit/cleydroid/releases/download/v0.1/os-image.img](https://github.com/Darul123-bit/cleydroid/releases/download/v0.1/os-image.img)

# Launch the image
qemu-system-x86_64 -m 2048 -anable-kvm -drive file=os-image.img,format=raw
```
