# 👋 Hey, I'm Andrew

 Self-taught systems administrator  
 Homelab builder | Linux power user | Automation nerd  
 Focused on self-hosting, network security, and full-stack server management

---

## ⚙ What I’m Working On

- Building and maintaining a full-featured **Proxmox-based homelab**
- Automating **Plex**, **TrueNAS**, and **Pi-hole** management tasks
- Learning and scripting in **Bash** and **Python** to handle backups and monitoring
- Documenting and streamlining IT workflows for reliability and reproducibility

---

##  My Proxmox Setup

- **Host OS:** Proxmox VE 8.4.1  
- **CPU:** AMD Ryzen 5 3600  
- **RAM:** 32GB DDR4  
- **Boot Drive:** NVMe SSD  
- **Storage Pools:**
  - 2x SSD ZFS Mirror (VMs + Containers)
  - 2x HDD for bulk storage via TrueNAS

###  Running VMs + LXCs:
- TrueNAS SCALE – ZFS storage with NFS shares
- Pi-hole – DNS filtering for the entire LAN
- Debian – Plex Media Server
- Uptime Kuma – Self-hosted monitoring
- Ubuntu – Dev VM for script testing and automation

###  Networking:
- vmbr0 bridge with custom VLANs  
- WireGuard for encrypted remote access  
- DHCP via internal virtual router  
- DNS managed through Pi-hole

---

##  Monitoring & Automation

- **Grafana + Prometheus + InfluxDB** for dashboards
- Scheduled cron jobs for:
  - ZFS snapshots + backups
  - Plex updates
  - System uptime monitoring

---

##  Tools & Technologies I Use

- **Linux**: Debian, Fedora, Ubuntu, Rocky  
- **Virtualization**: Proxmox, KVM, VirtualBox  
- **Networking**: VLANs, WireGuard, DNS, NAT  
- **Storage**: ZFS, Samba, iSCSI, NFS  
- **Automation**: Bash scripting, Python basics  
- **Monitoring**: Grafana, Uptime Kuma, sensors, smartctl
