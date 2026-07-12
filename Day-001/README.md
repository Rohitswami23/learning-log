# Day 001

**Date:** 12 July 2026

## Networking

### Topic
Quality of Service (QoS) Basics

### What I Learned

- Learned what QoS is and why it is used to prioritize network traffic.
- Understood the basics of IP Phones and how they communicate over IP networks instead of PSTN.
- Learned about Power over Ethernet (PoE).
- Studied TCP Global Synchronization.
- Learned about traffic characteristics such as bandwidth, delay, jitter, and packet loss.

---

## Linux

### Topics
Filesystem Hierarchy & Disk Management

### What I Learned

- Learned the purpose of the Linux Filesystem Hierarchy (FHS).
- Studied common directories like `/bin`, `/etc`, `/home`, `/usr`, `/var`, `/tmp`, `/proc`, and `/dev`.
- Learned about common filesystems such as `ext4`, `XFS`, `NTFS`, and the role of VFS.
- Understood journaling and why it helps recover after crashes.
- Learned basic disk anatomy: physical disks, partitions (`sda`, `sda1`, `sda2`), MBR vs GPT, and filesystem blocks.
- Practiced commands:
  - `lsblk`
  - `df -T`
  - `sudo parted`
- Learned the partitioning workflow:
  **Disk → Partition → Filesystem → Mount → Use Files**

---

## Bandit Challenge

### Level Completed
Level 12

### What I Practiced

- Used `xxd` to convert a hexdump back into binary.
- Extracted multiple compressed files using `tar`, `gzip`, and `bzip2`.
- Recovered the password after several decompression steps.

---

## Key Takeaways

Today I strengthened my understanding of Linux filesystems and disk management, learned the basics of QoS, and improved my Linux command-line skills by solving Bandit Level 12.
