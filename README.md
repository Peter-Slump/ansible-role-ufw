# Ansible role UFW (Uncomplicated Firewall)

Version: 0.0.2

Supported OS: Ubuntu

Ansible role UFW (Uncomplicated Firewall)

- Make SSH accessible
- Enables Firewall

## Role variables
```
ufw_ssh_port: 22  # Port to open for SSH
```

## Example
```
- hosts: all
  roles:
    role: ufw
```
