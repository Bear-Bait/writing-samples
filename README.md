# Broadcast Infrastructure Incident Reports

This repository contains a collection of real-world Incident Reports (Post-Mortems) and Root Cause Analyses (RCA) for a macOS-based broadcast automation system. 

The documents demonstrate systematic debugging of complex hardware and software failures in a 24/7 production environment.

## 🛠 Skills Demonstrated
- **Log Analysis:** Deep inspection of unified system logs (`log show`), kernel buffers (`dmesg`), and application-specific error logs.
- **Network Troubleshooting:** Diagnosing socket exhaustion (`ADDRINUSE`), throughput bottlenecks (USB vs. Native Gigabit), and DNS resolution hangs.
- **Hardware Auditing:** Verification of hardware link speeds and bus topology using `system_profiler` and `ioreg`.
- **Automation & Scripting:** Development of AppleScript failsafes to handle stream stalls and silent failures.
- **Disaster Recovery:** Coordination of manual and automated recovery procedures to minimize air-time loss.

## 📁 Incident Collection
- **2026-03-06:** Network Socket Exhaustion (ASIX USB Chipset Bottleneck)
- **2026-03-02:** Stream Reconnect Failures & VLC DNS Hangs
- **2026-02-27:** Audio Driver Hijacking (LogMeIn Kernel Conflicts)
- **2026-02-24:** CoreAudio Process Deadlocks
- **2026-02-22:** Missing Asset Cascading Failures

## 📄 Note on Anonymization
All reports have been scrubbed to remove sensitive information, including internal IP addresses, machine serial numbers, and specific organizational names.
