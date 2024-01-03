---
layout: default
title: Windows subsystem for Linux (WSL)
---

# Background

some introduction

## How to install wsl?
Go to cmd.exe, and run as an administrator.
 ```
$wsl.exe --install
$wsl.exe --update
```

Check: Make sure it is 2.x.x.x
```
$wsl --version
```

## How to install Linux?
Go to cmd.exe 
```
$wsl --install -d Ubuntu
```
- Set Username
- Set Password

Note: You can choose your distro (Ubuntu, kali-linux, ..)
```
NAME                                   FRIENDLY NAME
Ubuntu                                 Ubuntu
Debian                                 Debian GNU/Linux
kali-linux                             Kali Linux Rolling
Ubuntu-18.04                           Ubuntu 18.04 LTS
Ubuntu-20.04                           Ubuntu 20.04 LTS
Ubuntu-22.04                           Ubuntu 22.04 LTS
OracleLinux_7_9                        Oracle Linux 7.9
OracleLinux_8_7                        Oracle Linux 8.7
OracleLinux_9_1                        Oracle Linux 9.1
openSUSE-Leap-15.5                     openSUSE Leap 15.5
SUSE-Linux-Enterprise-Server-15-SP4    SUSE Linux Enterprise Server 15 SP4
SUSE-Linux-Enterprise-15-SP5           SUSE Linux Enterprise 15 SP5
openSUSE-Tumbleweed                    openSUSE Tumbleweed

```

Check:
```
$wsl -l -v
```
## How to use WSL within VScode?
- Go to VScode
- Connect to a remote window (connect to WSL)
- Everything sets up automatically!


