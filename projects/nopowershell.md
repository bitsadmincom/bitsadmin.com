---
title: NoPowerShell
caption: PowerShell rebuilt in C# for Red Teaming purposes
permalink: /projects/nopowershell
order: 2
---

NoPowerShell is a tool implemented in C# which supports executing PowerShell-like commands while remaining invisible to any PowerShell logging mechanisms. This .NET Framework 2 compatible binary can be loaded in Cobalt Strike to execute commands in-memory. No `System.Management.Automation.dll` is used; only native .NET libraries. An alternative usecase for NoPowerShell is to launch it as a DLL via `rundll32.exe`: `rundll32 NoPowerShell.dll,main` in restricted environments.

![Rundll32 feature of NoPowerShell used to bypass application whitelisting](/assets/images/NoPowerShellDll.png "Rundll32 feature of NoPowerShell used to bypass application whitelisting"){:class="img-fluid"}

Url: [https://github.com/bitsadmin/nopowershell/](https://github.com/bitsadmin/nopowershell/){:target="_blank"}