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

*Telnet* is an unsecure (non-encrypted) remote network access protocol. Featuring a command-line user interface, Telnet has been utilized for such purposes as port testing and network interface (e.g., servers, switches, routers) configurations and maintenance. However, as it transmits and exposes data in plaintext (even sensitive authentication data, such as usernames and passwords), it is generally ill-advised to use it for sending confidential data or managing production environments. Eavesdropping/man-in-the-middle and interception/replay attacks remain common concerns about using Telnet.

**Telnet operates by...**

1) Establishing a connection to a remote host via TCP Port 23 (although it can be configured to operate over a different port).
2) Enabling text-based communications between clients and servers (both client-to-server and server-to-client).
3) Allowing users to log in to remote devices and run terminal commands, providing the same functionality that they would have if they were working locally. 

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
| Compatibility | Cross-platform. | Cross-platform. | Cross-platform. | *Can* be used cross-platform, but designed with Windows OSes in mind. |
| Security | Highly insecure (data is sent unencrypted, in plaintext). | Significant security advantages over Telnet, such as encrypted tunnels and support for robust authentication procedures. | Not encrypted by default, but can be easily integrated with encrypted SSH tunnels. | Not secure by default, but can be integrated with secure technologies (e.g., VPNs). |
| Port(s) | Port 23 (TCP). | Port 22 (TCP). | Port 5900 (TCP), with additional sessions using the next port up (5901, 5902, etc.). | Port 3389 (TCP). |
| Request for Comments (RFCs) | [854](https://datatracker.ietf.org/doc/html/rfc854) | [4253](https://datatracker.ietf.org/doc/html/rfc4253) | [6143](https://datatracker.ietf.org/doc/html/rfc6143) | [908](https://datatracker.ietf.org/doc/html/rfc908) (Initial), [1151](https://datatracker.ietf.org/doc/html/rfc1151) (Version 2) |

<hr />

## 6. <a name="supplemental">Supplemental Resources</a>

* *[UltraVNC Remote Access Tools Official Website](https://uvnc.com/)*
* *[Chrome Remote Desktop Official Website](https://remotedesktop.google.com/)*
* *[Microsoft Article on Telnet](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/telnet)*
