# YuuMira Windows Runtime Prerequisites

[**English**](./README.md) · [简体中文](./README_CN.md)

This directory provides Microsoft Visual C++ Redistributable installers for troubleshooting cases where a missing runtime prevents YuuMira from installing, launching, or working correctly on Windows.

| File | Purpose |
| --- | --- |
| `VC_redist.x64.exe` | Runtime for 64-bit Windows applications |
| `VC_redist.x86.exe` | Runtime for 32-bit Windows applications |

YuuMira currently provides a **64-bit Windows** build, so `VC_redist.x64.exe` is normally the only package you need. Install `VC_redist.x86.exe` only when support instructions explicitly require the 32-bit runtime.

## Installation

1. Quit YuuMira.
2. Run the appropriate installer and allow administrator access if Windows requests it.
3. Follow the Microsoft installer and restart Windows if prompted.
4. Launch YuuMira again and check whether the issue is resolved.

Before running a file, check its Digital Signatures properties and confirm that the publisher is **Microsoft Corporation**. If the problem continues, use the [English bug-report template](../../../issues/new/choose) and include your YuuMira version, Windows version, error message, and reproduction steps. Never attach credentials or sensitive logs.
