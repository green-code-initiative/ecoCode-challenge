# Hello! Welcome to the checkers team 👋

Choose the "The Right Tool for the Job" in the list below. The methodology you follow and the relevance of the results you obtain are an integral part of the challenge you have accepted. Good luck.

## [vJoule](https://github.com/davidson-consulting/vjoule) & ETSdiff by [Davidson Consulting](https://www.davidson.fr/)

### [vJoule](https://github.com/davidson-consulting/vjoule)

A tool to estimate the energy consumption of processes running on your computer, based on hardware measurements.

- vjoule exec - used to estimate the energy consumption of a given command
- vjoule profile - used to create a profile of the energy consumption of your computer
- vjoule top - used to visualize the energy consumption of your computer and the cgroups monitored by vjoule service

[See **full documentation**](https://davidson-consulting.github.io/vjoule/v1.0/)

*Works on **Linux** on PC/servers (x86/64)*

## Fruggr by digital4better

## [Scaphandre](https://github.com/hubblo-org/scaphandre/) by [Hubblo](https://hubblo.org/fr/)

[Scaphandre](https://github.com/hubblo-org/scaphandre/) monitors power and energy metrics of a server, desktop or laptop, and of each program (through PIDs and commandline of the processes) running on this machine.

[See **full documentation**](https://hubblo-org.github.io/scaphandre-documentation/) for details, including [reference of metrics available](https://hubblo-org.github.io/scaphandre-documentation/references/metrics.html).

### Features

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

### Requirements

- CPU architecture supported : only **x86** CPUs, either Intel or AMD
- Operating Systems supported : **GNU/Linux** or **Windows** (from server 2016 to 2022, desktop 8, 10 and 11)
- Based on [RAPL (Running Average Power Limit)](https://hubblo-org.github.io/scaphandre-documentation/explanations/rapl-domains.html) : only available on **CPUs built in 2011 and later**

## [Joular Project](https://github.com/joular/) by [UPPA](https://www.univ-pau.fr/)

- [PowerJoular](https://github.com/joular/powerjoular): monitors the power consumption for a process (PID) or an application (multi-pid). Works on **Linux** on PC/servers (x86/64) and ARM SBC (Raspberry Pi, TinkerBoard).
- [JoularJX](https://github.com/joular/joularjx): monitors the power consumption for each method and each execution branch in a Java application (in real time). Works on **Windows** (x86/64), **macOS** (Intel and Apple M chips), and **Linux** (PC/servers x86/64 and ARM SBC like Raspberry Pi).
- [PowDroid](https://github.com/joular/powdroid): monitors the power consumption of **Android** smartphones (system-wide). Works on any Android smartphone. Requires a USB cable and a computer to run the analysis (**Windows**, **macOS** or **Linux**).
