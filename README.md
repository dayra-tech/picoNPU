# picoNPU


### Table of Contents
- [Overview](#overview)
- [Architecture](#architecture)
- [ISA](#isa)
- [Tools](#tools)

# Overview

# Architecture

# ISA

# Tools
## OpenLane
Instructions for installing [OpenLane](https://github.com/The-OpenROAD-Project/OpenLane) on Ubuntu running on WSL:

> [!IMPORTANT]
> 
> Linux containers are not working with docker-desktop version 4.29. 
>


1. Install docker-desktop [version 4.28](https://docs.docker.com/desktop/release-notes/?utm_campaign=prompt-dd-users-on-older-versions-to-upgrade&utm_medium=docker-desktop&utm_source=tip-of-the-day#4280) for Windows

2. install Python 3.6 or higher and venv: `apt-get install python3-venv`

3. Run the following commands in your command-line prompt:

```sh
cd $HOME
git clone https://github.com/The-OpenROAD-Project/OpenLane
cd OpenLane
make
make test
```