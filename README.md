# RebuiltPSX

## Overview

RebuiltPSX is a reimplementation of the PlayStation BIOS behavior and system interface.

The goal is to provide a compatible firmware layer for PlayStation software by recreating expected system behavior through independent implementation.

It is intended for use in emulators, research projects, and experimental PS1-compatible systems.

# Clean-room statement

This project does not include:

Any original Sony code
Decompiled BIOS binaries
Reverse-engineered proprietary source code
Copied implementation from Sony firmware

All code is written independently using:

Observed system behavior
Emulator testing outputs
Public documentation and technical references
Independently designed interface implementations

# Goals

Recreate PS1 BIOS-level behavior through independent implementation
Provide a compatible system interface for PS1 software
Model BIOS system calls and hardware interaction behavior
Support multiple BIOS behavior profiles (revisions)
Serve as a platform for research and experimentation in PS1 system design

# Why this exists

This project started from curiosity and interest in how systems like the PlayStation actually work.

I like building things that turn ideas into something real, and this project is one of those experiments. It is meant to explore how a system behaves and recreate that experience in an open way.
