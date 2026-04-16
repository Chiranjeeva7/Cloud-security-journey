# Day 11: SSH Advanced & Hardening - Completed ✅

**Date:** 10 April 2026  
**Learner:** Sai (Chiranjeeva7)

## What I Learned
- How to generate SSH key pair (`ssh-keygen`)
- How to set up key-based authentication
- Basic SSH hardening (disable password login)
- Why SSH keys are preferred over passwords in cloud environments

## Commands Practiced
- `ssh-keygen -t ed25519 -C "cloud-security-day11"`
- `cat ~/.ssh/id_ed25519.pub`
- Edited `/etc/ssh/sshd_config`
- `sudo systemctl restart ssh`
- `ssh localhost` (tested connection)

## Status
Day 11 Completed ✅

I successfully generated SSH key and practiced key-based login. This is a core skill for Cloud Security.
