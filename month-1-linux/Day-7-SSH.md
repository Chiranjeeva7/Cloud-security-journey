# Day 7: SSH Basics & Hardening - Completed ✅

**Date:** 09 April 2026  
**Learner:** Sai (Chiranjeeva7)

## What I Learned
- How to generate SSH key pair using `ssh-keygen`
- How to check SSH service status
- Basic SSH hardening (disabled password login and root login)
- Connected to localhost using SSH

## Commands Practiced
- `ssh-keygen -t ed25519`
- `sudo systemctl status ssh`
- `sudo systemctl start ssh`
- `sudo systemctl enable ssh`
- Edited `/etc/ssh/sshd_config` (PermitRootLogin no, PasswordAuthentication no)

## Status
Day 7 Completed ✅

I successfully set up SSH key-based authentication and started the SSH service on my Kali VM.
Practiced connecting to localhost.

## Next Plan
Will continue with more SSH practice and networking in upcoming days.
