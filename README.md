# ApexOS2

**ApexOS2** is a custom live operating system based on Debian 12/13, aimed at developers and power users. It ships as a ready-to-boot hybrid ISO with preinstalled essentials and custom branding. Version 0.1.x is based on GNOME (older version) and acts as a solid foundation for future builds.

---

## 🚀 Features

- Debian-based live OS (hybrid ISO)  
- Clean GNOME desktop environment  
- Preinstalled Python tools and essential utilities  
- Custom wallpaper included  
- Fully bootable — try without installing to your system  
- Branding set (name, release metadata)  

---

## ⚙️ What’s Included in This Repo

- `live-image-amd64.hybrid.iso` — the bootable ISO you can run directly in a VM or burn to USB  
- `.gitattributes` — Git LFS configuration for large files  
- Build scripts/config files (once added) — to allow rebuilding/editing the OS

---

## 🧪 System Requirements & Compatibility

- A machine (physical or virtual) with support for booting from USB or ISO  
- At least 2–4 GB memory recommended for a smooth experience  
- Debian 12/13-compatible hardware (for newer builds)

---

## 🔧 Usage

### Booting the ISO

1. **In a Virtual Machine or Hypervisor**  
   - Use software such as VirtualBox, VMware, or QEMU  
   - Mount the `live-image-amd64.hybrid.iso` as a CD/boot media  
   - Boot, explore, test

2. **On Physical Hardware**  
   - Burn the ISO to a USB using tools like `dd` or utilities like Etcher, Rufus, etc.  
   - Boot from the USB drive to run ApexOS live

