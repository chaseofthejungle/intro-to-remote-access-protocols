# Intro to Remote Access Protocols Overview Guide

**Description/Overview:** Remote access protocols are standardized sets of rules that provide users and/or devices with the ability to establish connections with or otherwise control remote devices via network connections. This guide briefly explores four of the most common remote access protocols: Telnet, Secure Shell (SSH), Virtual Networking Computing (VNC), and Remote Desktop Protocol (RDP). These protocols have similarities, but also differences concerning their intended purposes, means of interfacing, device portability, and approaches to security.

#### Table of Contents

1. [Telnet](#telnet)
2. [Secure Shell (SSH)](#ssh)
3. [Virtual Networking Computing (VNC)](#vnc)
4. [Remote Desktop Protocol (RDP](#rdp)
5. [Remote Access Protocols Comparison Table](#table)
6. [Supplemental Resources](#supplemental)

<hr />

## 1. <a name="telnet">Telnet</a>

(TODO)

<hr />

## 2. <a name="ssh">Secure Shell (SSH)</a>

(TODO)

<hr />

## 3. <a name="vnc">Virtual Networking Computing (VNC)</a>

(TODO)

<hr />

## 4. <a name="rdp">Remote Desktop Protocol (RDP)</a>

(TODO)

<hr />

## 5. <a name="table">Remote Access Protocols Comparison Table</a>

| Feature | Telnet | SSH | VNC | RDP |
| :---: | :---: | :---: | :---: | :---: |
| Popular Uses | Remote login. Often used for testing port connectivity and managing network interfaces (e.g., routers). | Securely encrypted (see 'Security Approach' below) remote desktop access. | Remote desktop access, for purposes such as file access, technical support, and server management. | High-performance remote desktop access, for purposes such as file access, technical support, and server management. |
| Interface Type | Command Line Interface (CLI). | Command Line Interface (CLI). | Graphic User Interface (GUI). | Graphic User Interface (GUI). |
| Compatibility | Cross-platform. | Cross-platform. | Cross-platform. | Intended for Windows OSes. |
| Security | Highly insecure (data is sent unencrypted, in plaintext). | Significant security advantages over Telnet, such as encrypted tunnels and support for robust authentication procedures. | Not encrypted by default, but can be easily integrated with encrypted SSH tunnels. | Not secure by default, but can be integrated with secure technologies (e.g., VPNs). |
| Port(s) | Port 23 (TCP). | Port 22 (TCP). | Port 5900 (TCP), with additional sessions using the next port up (5901, 5902, etc.). | Port 3389 (TCP). |

<hr />

## 6. <a name="supplemental">Supplemental Resources</a>

* *[UltraVNC Remote Access Tools Official Website](https://uvnc.com/)*
* *[Chrome Remote Desktop Official Website](https://remotedesktop.google.com/)*
* *[Microsoft Article on Telnet](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/telnet)*
