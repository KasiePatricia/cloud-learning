# Hypervisor  

## What is a Hypervisor?  
A **hypervisor** is special software (sometimes built into hardware) that allows you to run multiple **virtual machines (VMs)** on a single physical computer.  
Each VM can act like a completely separate computer, with its own operating system and apps, even though they all share the same underlying hardware.  

---

## Types of Hypervisors  

### 1. Type-1 Hypervisor (Bare-metal)  
- Runs directly on the hardware (**no host operating system in between**).  
- Offers better **performance, scalability, and security**.  
- Used mostly in **data centers and enterprise environments**.  

**Examples:** VMware ESXi, Microsoft Hyper-V (bare-metal), Citrix XenServer  

**Use-case:**  
A bank’s data center runs **VMware ESXi** on its servers. This allows them to securely host dozens of isolated VMs for different departments (transactions, payroll, analytics) while making full use of the hardware.  

---

### 2. Type-2 Hypervisor (Hosted)  
- Runs on top of a **host operating system** (like Windows, macOS, Linux).  
- Easier to set up, but **less efficient** than Type-1.  
- Commonly used by **developers, testers, and individuals**.  

**Examples:** Oracle VirtualBox, VMware Workstation, Parallels Desktop (for Mac)  

**Use-case:**  
A software developer uses **VirtualBox** on their laptop to run Ubuntu Linux as a VM while still using Windows as the host. This lets them test code in multiple operating systems without needing multiple physical machines.  

---

## In Conclusion  
- **Hypervisor = Virtual machine manager**  
- **Type-1 (bare-metal):** Enterprise/data center, maximum performance & security  
- **Type-2 (hosted):** Personal/development use, easier to install on laptops/desktops  
