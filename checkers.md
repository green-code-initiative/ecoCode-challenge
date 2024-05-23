# Hello! Welcome to the checkers team 👋

Choose the "Right Tool for the Job" in the list below. The methodology you follow and the relevance of the results you obtain are an integral part of the challenge you have accepted. Good luck.

## 📋 Prerequisites
Here are the things you need to succeed in this challenge:

- Your experience and your brain 😤
- A computer with an internet connection to download or interact with measurement tools.
- A GitHub account to test some code / share your hard work with the community

## 🔧 Tool suggestion

### [vJoule](https://github.com/davidson-consulting/vjoule/tree/v1.3.0) & [ETSdiff](https://github.com/davidson-consulting/ETSdiff) by [Davidson Consulting](https://www.davidson.fr/)

#### [vJoule](https://github.com/davidson-consulting/vjoule/tree/v1.3.0)

A tool that interfaces multiple sources of energy consumption and centralizes all energy readings in one place to provide a higher abstraction for developers and to help measure energy consumption.

- vjoule exec - used to estimate the energy consumption of a given command
- vjoule top - used to visualize the energy consumption of your computer and the cgroups monitored by vjoule service

[See **full documentation**](https://davidson-consulting.github.io/vjoule/v1.3/)

*Works on **Linux** on PC/servers (x86/64)*

#### [ETSdiff](https://github.com/davidson-consulting/ETSdiff)

An experimental tools that aims at the **differential analysis** of solutions producing an identical result within the framework of a **complete chain** of web applications.

To cover the whole chain and spots transfer impacts, ETSdiff uses 3 distinct indicators: Energy, Transfer and Storage. 

To insure good installation and understand how it work use this 2 projects:
- [ETSdiff-Test-Snippets](https://github.com/davidson-consulting/ETSdiff-Test-Snippets)
- [OpenDataBDD](https://github.com/davidson-consulting/OpenDataBDD)

*Works on **Linux** on PC/servers (x86/64)*

### Fruggr by Digital4better

[Fruggr](https://www.fruggr.io), developed by [Digital4better](https://digital4better.com), is a SaaS platform that enables companies to drive their sustainable digital transition.
It assesses the environmental and social impact of their overall IT ecosystem in a simple and automated way, providing recommendations for improvement.

#### Features

With Fruggr, you benefit from a comprehensive evaluation at all levels of your digital ecosystem.
From assessing sustainable digital maturity to analyzing the impact on your IT infrastructure, Fruggr examines all digital aspects in a simple and automated manner:

- Dynamic analysis of the environmental and social impact of your digital applications
- Evaluation of the accessibility of your websites and web applications
- GHG assessment of your IT infrastructure and compliance audits
- Measurement of the impact of your infrastructure through GreenOps analysis
- Evaluation of your sustainable digital maturity and support in your transition roadmap
- Analysis of your digital workplace footprint

#### Requirements

By default, Fruggr doesn't require many elements to operate.
For example, it may need access to your digital services or analytics accounts, cloud billing, and digital workplace billing.

### [Scaphandre](https://github.com/hubblo-org/scaphandre/) by [Hubblo](https://hubblo.org/fr/)

[Scaphandre](https://github.com/hubblo-org/scaphandre/) monitors power and energy metrics of a server, desktop or laptop, and of each program (through PIDs and commandline of the processes) running on this machine.

[See **full documentation**](https://hubblo-org.github.io/scaphandre-documentation/) for details, including [reference of metrics available](https://hubblo-org.github.io/scaphandre-documentation/references/metrics.html).

#### Features

- measuring on **bare metal hosts**
- measuring on **qemu/kvm hypervisor** to get power usage and energy consumption of each virtual machine
- measuring and exposing power/energy metrics of a Qemu/KVM **virtual machine**, to allow manipulating those metrics in the VM as if it was a bare metal machine (relies on hypervisor features)
- **exposing** metrics as a **prometheus (HTTP) exporter**, see an [example of a grafana + prometheus setup](https://metrics.hubblo.org)
- sending metrics in **push mode** to a **prometheus Push Gateway**I
- sending metrics to **riemann**
- sending metrics to **Warp10**
- works on **kubernetes**, as a daemonset
- outputing power consumption metrics in a **JSON file**
- showing basic power consumption metrics **in the terminal**
- **packages** available for **RHEL** 8 and 9, **Debian** 11 and 12, **Windows**, and **NixOS** (community based)
- gets hosts's power from **RAPL PSYS** domain (full SoC / motherboard + attached components power) when available, or RAPL DPKG and DRAM (limited coverage : power consumed by CPU, memory and integrated graphic chipset)
- once in a timeseries database, metrics are easily searchable thanks to **labels**

#### Requirements

- CPU architecture supported : only **x86** CPUs, either Intel or AMD
- Operating Systems supported : **GNU/Linux** or **Windows** (from server 2016 to 2022, desktop 8, 10 and 11)
- Based on [RAPL (Running Average Power Limit)](https://hubblo-org.github.io/scaphandre-documentation/explanations/rapl-domains.html) : only available on **CPUs built in 2011 and later**

### [Joular Project](https://github.com/joular/) by [UPPA](https://www.univ-pau.fr/)

- [PowerJoular](https://github.com/joular/powerjoular): monitors the power consumption for a process (PID) or an application (multi-pid). Works on **Linux** on PC/servers (x86/64) and ARM SBC (Raspberry Pi, TinkerBoard).
- [JoularJX](https://github.com/joular/joularjx): monitors the power consumption for each method and each execution branch in a Java application (in real time). Works on **Windows** (x86/64), **macOS** (Intel and Apple M chips), and **Linux** (PC/servers x86/64 and ARM SBC like Raspberry Pi).
- [PowDroid](https://github.com/joular/powdroid): monitors the power consumption of **Android** smartphones (system-wide). Works on any Android smartphone. Requires a USB cable and a computer to run the analysis (**Windows**, **macOS** or **Linux**).

### ❓ Questions ❓

If you have any questions, coaches are here to help you or use the dedicated channel on Slack:

- [ecoCode public Slack]([https://ecocode-workspace.slack.com/](https://join.slack.com/t/ecocode-workspace/shared_invite/zt-1soofawn4-Jos03e03VEQPWrw6yhgz7g))
  - Main channel: `challenge24-general`
  - Checkers channel: `challenge24-checkers`

You can also create private discussions with all members of your team using the direct messages Slack feature.
