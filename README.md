# Linux-SSH-Hardening-lab

## Objective
SSH Hardening of linux server

## Tools Used
- Ubuntu server
- UFW
- Fail2Ban

## Initial Security Vulnerabilities
- No brute-force protection
- root login enabled
- Passwords authentification enabled
- default port for ssh (22)
- unlimited login attempts

## Hardening Steps Taken
1. Update system
2. Disable login with password and require public key
3. Disable Root login
4. Change the default SSH port to 2222
5. Configure sshd to listen on port 2222
6. Configure UFW to allow ssh traffic on port 2222 only
7. Install brute-force protection (Fail2Ban)

## Security Improvements
- Prevent direct root attacks by disabling root login
- Eliminate password brute-force by enabling SSH keys
- Customize SSH port to reduce automated scans
- Limit network exposure by setting firewall rules
- Block brute-force attempts by enablin Fail2Ban

## Skills Used
- Linux system administration
- SSH configuration
- Firewall configuration
- Security Hardening
- Brute-force mitigation
- Access control implementation



