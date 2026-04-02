# Linux Hardening Guide

## Description
A practical guide to securing Linux servers using standard hardening techniques to reduce vulnerabilities.

## Steps Taken
1. Disabled root login over SSH
2. Configured SSH key authentication
3. Installed and configured firewall (ufw)
4. Enabled fail2ban to block repeated login attempts
5. Regularly updated system packages

## Commands Used
sudo ufw enable
sudo ufw allow ssh
sudo systemctl enable fail2ban

## Skills Learned
- System hardening best practices
- SSH and firewall configuration
- Basic intrusion prevention
