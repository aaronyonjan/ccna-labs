# Secure Passwords and SSH Configuration Lab

## Objective

This lab focuses on securing remote access to a Cisco switch by encrypting plaintext passwords and replacing Telnet with SSH.

Telnet sends data in plaintext, which makes it insecure. SSH provides encrypted remote access and is the preferred method for managing network devices.

## What This Lab Covers

- Accessing a switch remotely using Telnet
- Saving the current running configuration
- Viewing plaintext passwords in the running configuration
- Encrypting plaintext passwords
- Configuring an IP domain name
- Generating RSA encryption keys
- Creating a local SSH user account
- Configuring VTY lines to use local login
- Restricting remote access to SSH only
- Removing the old VTY line password
- Verifying that Telnet is blocked
- Verifying SSH remote access
- Saving the final configuration
