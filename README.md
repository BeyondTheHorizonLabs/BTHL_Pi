# BTHL_Pi

SkinwalkerPi is a comprehensive toolkit designed to bootstrap and manage the installation of **BTHL_OS** on a variety of devices, including Raspberry Pi, Orange Pi, and mini ITX systems. With a focus on paranormal and scientific field testing, SkinwalkerPi ensures seamless setup for advanced sensor monitoring and data analysis.

---

## Features

- Supports ARM and x64 architectures.
- Compatible with Raspberry Pi, Orange Pi, and mini ITX systems.
- Automates the installation of **BTHL_OS**, a Linux OS fork.
- Includes configuration tools for sensor monitoring devices, drones, and SDR-based applications.
- Provides a modular design for adding new device support and configurations.

---

## Prerequisites

- A compatible device (Raspberry Pi, Orange Pi, or mini ITX).
- USB or SD card for OS installation.
- Access to a terminal or SSH client.
- Basic understanding of Linux commands.

---

## Installation

1. Clone the SkinwalkerPi repository:

   ```bash
   git clone git@github.com:BeyondTheHorizonLabs/SkinwalkerPi.git
   cd SkinwalkerPi
   ```

2. Run the bootstrap script:

   ```bash
   sudo ./bootstrap.sh
   ```

   This script will:
   - Format and prepare your USB/SD card.
   - Download the latest **BTHL_OS** image.
   - Install the OS and required dependencies.

3. Follow the on-screen prompts to configure your device.

---

## Usage

### Bootstrapping SBTHL_OS

After running the bootstrap script, your device will boot into **BTHL_OS**, ready for further configuration and use with:

- Environmental sensors
- GPS and SDR tools
- Drone-based monitoring systems

### Updating the Toolkit

To update SkinwalkerPi, run:

```bash
git pull origin main
sudo ./update.sh
```

This will ensure you have the latest features and bug fixes.

---

## Relation to BTHL_OS

SkinwalkerPi is the primary tool for bootstrapping and configuring **BTHL_OS**. While SkinwalkerOS provides the core operating system, SkinwalkerPi simplifies the installation process and ensures compatibility with supported devices.

For more information about **BTHL_OS**, visit the [BTHL_OS repository](https://github.com/BeyondTheHorizonLabs/BTHL_OS).

---

## Contribution

We welcome contributions! Please see the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines.

---

## License

This project is licensed under the [MIT License](LICENSE).
