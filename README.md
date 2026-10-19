# 🐧 Linux Advanced Administration – Practical Guide

Welcome to my Linux advanced administration practical repository! 🚀

This repository covers essential Linux system administration topics, including security management, network file sharing, storage administration, firewall configuration, task scheduling, access control, and process priority management.

These practicals are designed for Linux learners, system administrators, cloud engineers, and DevOps professionals who want to strengthen their hands-on Linux skills.

## 📚 Topics Covered

### 1. SELinux – Security-Enhanced Linux
- Understand SELinux modes: Enforcing, Permissive, and Disabled.
- Check the current SELinux status.
- Change SELinux modes using `setenforce`.
- Understand SELinux contexts and labels.
- Manage file contexts using `semanage` and `restorecon`.
- Troubleshoot SELinux access denials.
- Analyze SELinux logs using `ausearch`.

### 2. Samba – File Sharing
- Understand Samba and SMB/CIFS protocols.
- Install and configure Samba.
- Create shared directories.
- Configure Samba users and passwords.
- Set directory ownership and permissions.
- Configure shares in `/etc/samba/smb.conf`.
- Start and enable Samba services.
- Test access to shared folders from client machines.

### 3. NFS – Network File System
- Understand NFS architecture and remote file sharing.
- Install and configure NFS services.
- Export directories to authorized clients.
- Configure `/etc/exports`.
- Start and manage NFS services.
- Mount NFS shares on client machines.
- Configure persistent mounts using `/etc/fstab`.
- Verify exports and troubleshoot connectivity.

### 4. Disk Management
- List disks and partitions using `lsblk`.
- Check storage usage with `df` and `du`.
- Inspect disks using `fdisk` and `parted`.
- Create and manage partitions.
- Format partitions with filesystems.
- Mount and unmount filesystems.
- Configure persistent mounts.
- Check filesystem types and disk utilization.

### 5. LVM – Logical Volume Management
- Understand Physical Volumes (PV), Volume Groups (VG), and Logical Volumes (LV).
- Create physical volumes using `pvcreate`.
- Create volume groups using `vgcreate`.
- Create logical volumes using `lvcreate`.
- Format and mount logical volumes.
- Extend volume groups and logical volumes.
- Resize supported filesystems.
- Verify LVM configuration using `pvs`, `vgs`, and `lvs`.

### 6. Linux Firewall Management
- Understand firewall concepts and network traffic filtering.
- Configure firewall rules using `firewall-cmd`.
- Manage services and ports.
- Allow or remove network services.
- Inspect firewall configurations.
- Understand zones and runtime versus permanent rules.
- Verify connectivity after applying firewall changes.
- Learn basic `nftables` concepts.

### 7. Task Scheduling – Cron and At
- Understand scheduled and recurring tasks.
- Configure cron jobs using `crontab`.
- Schedule scripts at specific times.
- Manage user-specific scheduled jobs.
- Use the `at` command for one-time scheduling.
- Verify scheduling services and job status.
- Redirect job output to log files.
- Automate backups and system maintenance.

### 8. ACL – Access Control Lists
- Understand standard Linux permissions versus ACLs.
- Grant permissions to specific users and groups.
- Configure ACLs using `setfacl`.
- View ACL entries using `getfacl`.
- Configure default ACLs for directories.
- Modify and remove ACL permissions.
- Verify effective access permissions.
- Practice user-specific file access control.

### 9. Process Priority Management
- Understand process priority and scheduling.
- View process priorities using `ps` and `top`.
- Start processes with `nice`.
- Modify process priority using `renice`.
- Understand nice values from -20 to 19.
- Learn the relationship between nice values and scheduling priority.
- Monitor running processes.
- Understand the privileges required to increase process scheduling priority.

## 🎯 Learning Objectives

After completing these practicals, learners should be able to:

- Configure and troubleshoot SELinux security.
- Set up network file sharing using Samba and NFS.
- Partition, format, and manage Linux storage.
- Create and extend LVM logical volumes.
- Configure firewall rules to control network traffic.
- Automate tasks using cron and at.
- Manage file access using ACLs.
- Monitor processes and adjust their scheduling priority.
- Apply Linux administration skills in server and cloud environments.

## 💻 Recommended Lab Environment

- CentOS Stream or a compatible RHEL-based distribution
- Red Hat Enterprise Linux (RHEL)
- Two Linux virtual machines for Samba and NFS practicals
- A test disk or virtual disk for partitioning and LVM
- Root or sudo privileges for administrative tasks

**Important:** Test storage, firewall, SELinux, and permission changes in a lab environment before applying them to production servers. Incorrect configurations can affect system access, data, or network connectivity.

## ☁️ Relevance to Cloud and DevOps

These skills are useful for administering Linux servers in AWS and Microsoft Azure, configuring secure workloads, managing storage, troubleshooting access issues, and automating routine administration tasks.

They also provide a foundation for DevOps, infrastructure management, and server security.

## 👨‍💻 About the Author

**Gorakhnath Malusare**

Cloud Computing | AWS | Microsoft Azure | Linux | Networking | DevOps

I am passionate about cloud computing, Linux administration, networking, and DevOps. I create practical labs and documentation to strengthen technical knowledge and help learners build real-world skills.

🔗 GitHub Profile: https://github.com/gorakhhhh

## ⭐ Support

If you find this repository useful, consider giving it a star ⭐ and sharing it with other Linux learners.

**Learn by doing. Practice Linux. Build your cloud and DevOps skills.** 🚀
