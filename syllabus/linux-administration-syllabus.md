# Complete Linux Administration Syllabus

Roadmap for System & Network Engineers · Beginner to Advanced

Based on your uploaded Linux topic list and the additional infrastructure administration modules, here is the complete 28-topic Linux roadmap. It covers Linux fundamentals, system administration, networking, security, automation, server management, and troubleshooting.

## Phase 1 — Linux Fundamentals

01–05 · Foundation

1. Introduction to Linux

* Linux architecture and distributions

* Linux kernel, shell, GNU utilities

* Ubuntu, Debian, Red Hat, Rocky Linux

* Linux use cases and server environments

2. Linux Installation and Configuration

* Installation and partitioning basics

* Virtual machines and Linux installation

* Initial configuration and hostname

* User creation and system setup

3. Linux Command Line

* Basic commands and command syntax

* Navigation: `pwd`, `cd`, `ls`

* File operations: `cp`, `mv`, `rm`, `touch`

* Text viewing: `cat`, `less`, `head`, `tail`

* Help: `man`, `--help`, `info`

4. Linux Filesystem and Directory Structure

* Filesystem hierarchy

* `/etc`, `/var`, `/home`, `/tmp`, `/usr`

* Absolute and relative paths

* File types, links, inodes

* `find`, `locate`, `file`, `stat`

5. Linux Users, Groups, Permissions and Ownership

* User and group management

* `useradd`, `usermod`, `passwd`

* `chmod`, `chown`, `chgrp`

* `umask`, ACLs, SUID, SGID, sticky bit

* `sudo` and privilege management

## Phase 2 — Processes and System Administration

06–10 · Core administration

6. Shells and Processes

* Bash and other shells

* Process states and process IDs

* `ps`, `top`, `htop`, `pgrep`

* `kill`, `pkill`, signals

* Foreground/background jobs

7. Multitasking at the Command Line

* Pipes and redirection

* Command chaining

* `grep`, `sort`, `uniq`, `cut`, `awk`, `sed`

* `xargs`, pipelines and exit codes

* `nohup`, `jobs`, `fg`, `bg`

8. systemd and Service Administration

* `systemctl` and service lifecycle

* Starting, stopping and enabling services

* Unit files and service dependencies

* Targets and boot services

* Service failure diagnosis

9. System Information and Resource Monitoring

* CPU, memory and disk information

* `uname`, `uptime`, `free`, `vmstat`

* `lscpu`, `lsmem`, `lsof`

* System resource utilization

* Hardware and OS inventory

10. Kernel and Boot Management

* Kernel architecture and modules

* `lsmod`, `modprobe`, `uname`

* Boot sequence and bootloader basics

* Kernel parameters

* Boot failures and recovery

## Phase 3 — Package Management and Software

11–13 · Software administration

11. Package Managers and Repositories

* APT and DPKG

* DNF/YUM and RPM

* Repository configuration

* Package installation and removal

* Dependencies and repository troubleshooting

12. Building, Managing and Distributing RPM Packages

* RPM package structure

* RPM queries and verification

* SPEC files

* Building RPM packages

* Package signing and distribution basics

13. System Upgrade and Patch Management

* Security updates

* Kernel upgrades

* Package updates and rollback planning

* Repository maintenance

* Patch verification and maintenance windows

## Phase 4 — Linux Networking and Remote Access

14–18 · Essential for System & Network Engineers

14. Linux Network Configuration

* IP addressing and subnetting

* Network interfaces and NetworkManager

* `ip`, `nmcli`, `ip route`

* Default gateways and routing tables

* DNS client configuration

* Network troubleshooting

15. SSH and Remote Administration

* SSH client and server

* SSH key authentication

* `sshd_config` hardening

* SCP and SFTP

* SSH tunnels and jump hosts

* Remote-access troubleshooting

16. Desktop and Remote Access

* Linux desktop environments

* Remote desktop concepts

* VNC and RDP-compatible solutions

* Remote access security

* GUI versus terminal administration

17. Linux Firewall and Security

* UFW, firewalld and nftables

* Firewall rules and zones

* Ports, protocols and network access

* SELinux fundamentals

* SSH hardening and sudo security

* Security auditing basics

18. DNS and DHCP Server Administration

* DNS resolution and record types

* Forward and reverse lookup

* BIND DNS configuration

* DHCP scopes and reservations

* DHCP server configuration

* DNS/DHCP troubleshooting

## Phase 5 — Bash and Automation

19–20 · Operational automation

19. Bash Scripting

* Variables and data types

* Conditions and loops

* Functions and arguments

* Exit codes and error handling

* Arrays, input and output

* Text processing and command substitution

20. Bash Scripting for System Administration

* Automated backups

* User and account administration

* Disk-space monitoring

* Service health checks

* Log analysis and alerts

* Cron and scheduled jobs

* Idempotent scripts and logging

## Phase 6 — Storage, Services and Databases

21–24 · Server operations

21. Linux Storage and Filesystem Administration

* Disk and partition management

* `lsblk`, `fdisk`, `parted`

* Filesystem creation and checking

* Mounting and `/etc/fstab`

* LVM and logical volumes

* Swap, disk quotas and storage troubleshooting

22. Web Server and Application Services

* Apache and Nginx

* Virtual hosts and server blocks

* Reverse proxies

* TLS certificates and HTTPS

* Application service configuration

* Web-server logs and troubleshooting

23. Database Server Administration Using MariaDB

* Database installation and configuration

* Users, roles and permissions

* Database backup and restore

* Service and connection troubleshooting

* Database logs and basic performance checks

24. Backup, Recovery and Disaster Recovery

* `tar`, `rsync` and file synchronization

* Full and incremental backup concepts

* Automated backup scheduling

* Configuration and database backups

* Restore testing and recovery procedures

* Backup retention and recovery planning

## Phase 7 — Performance, Logging and Troubleshooting

25–27 · Advanced operations

25. Linux Performance Tuning

* CPU and memory bottlenecks

* Disk I/O analysis

* Network performance

* `top`, `vmstat`, `iostat`, `sar`

* Process and resource optimization

* Capacity planning fundamentals

26. Kernel and System Logging

* `journalctl` and systemd journal

* `/var/log` and application logs

* `rsyslog` and log rotation

* Boot and kernel messages

* Log filtering and incident investigation

* Centralized logging concepts

27. Linux Troubleshooting and Incident Response

* Boot and service failures

* DNS and connectivity failures

* Permission and ownership problems

* Disk-full and memory-exhaustion incidents

* Package and dependency failures

* Log-based root cause analysis

* Evidence collection and incident documentation

## Phase 8 — Containers and Production Readiness

28 · Modern infrastructure

28. Docker and Linux Container Administration

* Container fundamentals

* Images and registries

* Containers, volumes and networks

* Docker Compose

* Container logs and troubleshooting

* Container security basics

* Linux namespaces and cgroups fundamentals

## Recommended learning order

Stage 1 — Linux Administrator

Topics 1–13

Learn the CLI, filesystem, users, permissions, processes, services, packages and patching.

Stage 2 — Linux System & Network Engineer

Topics 14–24

Configure networking, secure SSH, manage firewalls, operate servers, administer storage and automate tasks.

Stage 3 — Production Operations

Topics 25–28

Diagnose incidents, analyze performance, manage logs and operate containers.

My recommendation: Use Ubuntu Server for your primary hands-on labs, then learn the RPM ecosystem using Rocky Linux or another compatible distribution. Practice each topic in your existing VMware environment and document the objective, commands, expected output, troubleshooting steps and verification evidence.

You do not need to master all 28 topics at once. Focus first on Linux administration, SSH, networking, systemd, storage, Bash and troubleshooting; these establish the practical foundation for your target role.
