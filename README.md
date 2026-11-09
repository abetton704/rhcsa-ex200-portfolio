# rhcsa-ex200-portfolio
Hands-on RHCSA (EX200, RHEL 10) labs: real-world sysadmin scenarios, runbooks, scripts, and verification evidence. 

# RHCSA (EX200) Hands-On Portfolio — RHEL 10

Antonio Betton | USMC Veteran | Help Desk Lead transitioning to Linux Systems Administration
www.linkedin.com/in/antonio-betton

## What this is
Evidence of hands-on Red Hat Enterprise Linux 10 administration. Every module is a
change ticket I executed as the Linux admin for a fictional Fortune 500 bank
(Meridian Global Financial) on a two-node lab, with runbooks, scripts, and
verification output captured from the real systems.

## Lab environment
| Host | IP | Role |
|---|---|---|
| servera.meridian.lab | 192.168.226.156 | App server (app01) |
| serverb.meridian.lab | 192.168.226.157 | Infra server: repo, NFS, time (infra01) |
Hypervisor: VMware. OS: RHEL 10. See LAB-ENVIRONMENT.md.

## Modules
| # | Module | Skills demonstrated | Status |
|---|---|---|---|
| 01 | Essential tools | redirection, grep/regex, ssh, tar, links, permissions | In progress |
| 02 | Software management | DNF repos, internal HTTP repo, Flatpak | Not started |
| 03 | Shell scripting | conditionals, loops, args, automation | Not started |
| 04 | Operate running systems | boot targets, root recovery, tuned, journald | Not started |
| 05 | Local storage | GPT, LVM, swap, UUID mounts | Not started |
| 06 | File systems | XFS/ext4/VFAT, NFS, autofs, LV growth | Not started |
| 07 | Deploy & maintain | cron, at, systemd timers, chrony, GRUB | Not started |
| 08 | Networking | nmcli IPv4/IPv6, DNS resolution, firewalld | Not started |
| 09 | Users & groups | accounts, password aging, sudo | Not started |
| 10 | Security | SELinux, SSH keys, umask | Not started |
| -- | Capstone | Timed mock exam with automated grader | Not started |

## How to read a module
Each module folder has: README.md (ticket, approach, commands, verification,
lessons learned), scripts/ (anything I automated), evidence/ (real command output).

## Certification target
Red Hat Certified System Administrator (EX200, RHEL 10) — target date: December 2026
