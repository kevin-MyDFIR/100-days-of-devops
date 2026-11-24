# Day 01 - Linux User Management

## Objective
Create a Linux user with a non-interactive shell.

## Commands Used

```bash
sudo useradd -s /usr/sbin/nologin anita
id anita
grep anita /etc/passwd
