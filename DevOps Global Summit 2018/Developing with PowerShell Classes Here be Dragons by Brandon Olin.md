﻿#### Developing with PowerShell Classes: Here be Dragons by Brandon Olin

[![Developing with PowerShell Classes: Here be Dragons by Brandon Olin](https://i2.ytimg.com/vi/i1DpPU_xxBc/hqdefault.jpg "Developing with PowerShell Classes: Here be Dragons by Brandon Olin")](https://www.youtube.com/watch?v=i1DpPU_xxBc)

Classes are a powerful capability in PowerShell and are meant to provide a more familiar developing experience to more traditional programmers. You will not experience calm skies and quiet seas though. This talk will show you where the dragons lurk and help you navigate the stormy seas.
    Classes were introduced in PowerShell 5 and mainly to aid in writing DSC resources but can be used with non-DSC modules as well. This talk will go over some of the hidden gotchas when developing with classes including:

* Importing issues

* Verbose / Debug oddities

* Sharing classes between modules

     I've developed and released a large PowerShell project (PoshBot) that primarily consists of PowerShell classes. While I could have written the module using traditional functions and cmdlets, I wanted an excuse to try classes out on a new project. Using classes was not a smooth experience and I want to share some of my challenges.


