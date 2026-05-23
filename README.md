# MAVProxy – Team Rakshak Fork

[![MAVProxy Status](https://ci.appveyor.com/api/projects/status/github/Ardupilot/MAVProxy?branch=master\&svg=true)](https://ci.appveyor.com/project/tridge/MAVProxy/history)

## Overview

MAVProxy is a lightweight MAVLink Ground Control Station (GCS) written in Python. It is designed for communication, monitoring, and control of MAVLink-compatible vehicles.

This repository is a custom fork maintained and adapted by Team Rakshak for Raspberry Pi based onboard communication systems, telemetry bridges, and UAV deployment workflows.

---

## About the Fork

This fork extends the original MAVProxy project with additional helper modules intended for:

* Raspberry Pi telemetry bridges
* Network management utilities
* Ground station communication support
* UAV field deployment workflows

The goal of this fork is to simplify communication between onboard systems and the Ground Control Station during autonomous operations.

---

## Added Modules

### 1. mavproxy_hostapd.py

Utility module for configuring and managing HostAPD based wireless access points on Raspberry Pi systems.

Wiki:
[https://github.com/Matchstic/MAVProxy/wiki/mavproxy_hostapd.py](https://github.com/Matchstic/MAVProxy/wiki/mavproxy_hostapd.py)

---

### 2. mavproxy_fping.py

Network monitoring helper module using `fping` for connection diagnostics and link health monitoring.

Wiki:
[https://github.com/Matchstic/MAVProxy/wiki/mavproxy_fping.py](https://github.com/Matchstic/MAVProxy/wiki/mavproxy_fping.py)

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/MAVProxy.git
cd MAVProxy
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Documentation

Official MAVProxy documentation:

[https://ardupilot.org/mavproxy/index.html](https://ardupilot.org/mavproxy/index.html)

ArduPilot Discord:

[https://ardupilot.org/discord](https://ardupilot.org/discord)

---

## License

MAVProxy is released under the GNU General Public License v3.0 or later.

---

## Maintainers

### Original MAVProxy Developers

* Andrew Tridgell
* Peter Barker

### Platform Maintainers

* Windows: Stephen Dade
* macOS: Rhys Mainwaring

---

## Team Rakshak Integration

This fork is actively used and adapted within Team Rakshak for UAV communication infrastructure, onboard networking utilities, and autonomous mission support systems.

The repository serves as part of the software stack used in Team Rakshak robotics and aerial systems development workflows.

---

## Acknowledgements

Original MAVProxy project by the ArduPilot community.

This fork builds upon the open-source work contributed by the MAVLink and ArduPilot ecosystem.
