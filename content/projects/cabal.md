+++
title = "Cabal"
description = "Going beyond off-the-shelf tooling by engineering a custom C2 platform"
weight = 1
date = 2025-10-22

[extra]
codeberg = "https://codeberg.org/abrumsen/Cabal"
tags = ["go", "python"]
+++

{% align(to="justify") %}

# Abstract

Command and Control (C2) frameworks are the standard tools used for simulating post-exploitation in a red team engagement as 
they allow operators to establish the persistent, covert, and organized remote access necessary to accurately mimic a sophisticated adversary.

However, modern security defenses are highly effective at detecting signatures from over-used C2 agents such as Metasploit's meterpreter or Sliver's implants.
Consequently, relying on these established frameworks during red team engagements presents two limitations:
firstly, it fails to accurately test a target environment against a novel attacker.
Secondly, it hinders operator development, removing the need and the opportunity to truly understand the underlying persistence and evasion techniques.

Therefore, to overcome these limitations and ensure realistic threat emulation, we must move beyond established standards. 
This is why I decided to develop Cabal, my very own C2 framework.
Cabal serves as a personal deep dive into the capabilities a modern C2 should have, 
allowing me to put my theoretical knowledge of threat actor techniques to the test using a hands-on approach.

{% end %}