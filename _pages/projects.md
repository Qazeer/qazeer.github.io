---
layout: single
classes:
  - wide
  - smallfont
title:  "Projects"
permalink: /projects/
---

--------------------------------------------------------------------------------

### FarsightAD

FarsightAD is a PowerShell script that implements multiple cmdlets to
help detect and investigate Active Directory persistence, following a forest or
domain compromise. It rely on a mix of reviewing the current domain state and
getting historical information / timestamps (notably from replication meta
data) whenever possible.​
<br><br> Areas of persistence covered: fully or partially hidden objects
(detected using replication data queried through `DRS`), SIDHistory &
primaryGroupID persistence, ACL / GPO / AD CS / Kerberos based persistence, ...
<br> More information on the project will be shared following the
[SANS DFIR 2022 Summit](https://www.sans.org/cyber-security-training-events/digital-forensics-summit-2022/).
<br><br>
<i class="fab fa-fw fa-github" aria-hidden="true"></i> [Qazeer/FarsightAD](https://github.com/Qazeer/FarsightAD)

--------------------------------------------------------------------------------

### EDRSandblast

EDRSandBlast is a tool written in C that weaponize a vulnerable signed driver
to bypass EDR detections (Kernel callbacks and ETW TI provider) and LSASS
protections. <br>
Multiple userland unhooking techniques are also implemented to evade userland
monitoring.
<br><br> *Developed with [Maxime Meignan](https://twitter.com/th3m4ks)*
<br><br>
<i class="fab fa-fw fa-github" aria-hidden="true"></i> [wavestone-cdt/EDRSandblast](https://github.com/wavestone-cdt/EDRSandblast)

--------------------------------------------------------------------------------

### OffensivePythonPipeline

Static standalone binaries for Linux and Windows (x64) of Python offensive
tools. <br>
Compiled using Docker for Windows, WSL2, and Make.
<br><br>
<i class="fab fa-fw fa-github" aria-hidden="true"></i> [Qazeer/OffensivePythonPipeline](https://github.com/Qazeer/OffensivePythonPipeline)

--------------------------------------------------------------------------------

### Other contributions

Occasional contributions to open-source security projects, such as Metasploit,
Priv2Admin, KapeFiles, PingCastle, Velociraptor's Artifact Exchange, etc.
