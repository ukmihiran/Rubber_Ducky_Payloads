# Simple Payload Example for the USB Rubber Ducky

This repository contains payload examples for the Hak5 USB Rubber Ducky. 

## Files

### 01. Domain User’s Credential Dump
This attack focuses on the domain user’s credential dump using the Mimikatz tool.

### 02. Linux RevShell
This attack shows Linux dirty pipe exploitation (CVE-2022-0847) that hijacks a SetUID binary to spawn a root shell. This exploit needs a Linux kernel version 5.8 or later.

### 03. Windows RevShell
This attack demonstrate the windows stager payload to use to get the reverse shell of the windows machine. The attacker deploys malicious payload into the windows startup folder to execute upon user login to gain persistence access.
