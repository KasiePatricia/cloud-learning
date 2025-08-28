# Cloud Computing Quiz with Answers  

**Name:** Ugwu Kasie  
**Date:** 14 August 2025  

---

## Q1  
A company is using Amazon Web Services (AWS) to host its website. AWS ensures the physical servers, networking, and data centers are secure. However, the company must still manage user access, application security, and data encryption.  

**Which principle is illustrated in this situation?**  
- Cloud provider handles everything, including applications  
- Customer is fully responsible for all security measures  
- ✅ Shared responsibility between cloud provider and customer  
- Neither customer nor provider is responsible  

**Answer Explanation:**  
This is an example of the **Shared Responsibility Model** in cloud computing.  
- **AWS (the provider)** is responsible for securing the **infrastructure of the cloud**: physical servers, networking, hardware, and global data centers.  
- **The company (the customer)** is responsible for security **in the cloud**, which includes managing **user accounts, application security, encryption of sensitive data, and identity/access management**.  

In short, AWS secures the **foundation**, while the customer secures what they build on top of it.  

---

## Q2  
Sarah’s team deployed an app on Microsoft Azure. During a security audit, they discovered weak passwords and poor access control policies. The Azure provider confirmed that their infrastructure is safe.  

**Who is responsible for fixing the weak access controls?**  
- Only Microsoft Azure  
- Both Sarah’s team and Microsoft Azure equally  
- ✅ Sarah’s team (the customer)  
- No one, because it’s a cloud issue  

**Answer Explanation:**  
Under the **Shared Responsibility Model**, Azure secures the infrastructure, networking, and physical hardware. However, customers are responsible for what they put into the cloud:  
- Configuring **strong password policies**  
- Implementing **multi-factor authentication (MFA)**  
- Setting up **role-based access control (RBAC)**  
- Encrypting sensitive data  

Since the issue is weak passwords and poor access control, the **responsibility lies with Sarah’s team** to strengthen their security configuration.  

---

## Q3  
A university IT department needs to run multiple operating systems (Windows, Linux, and Ubuntu) on a single physical server. They achieve this by creating multiple virtual machines, each behaving as an independent system.  

**Which cloud computing concept allows this setup?**  
- ✅ Virtualization  
- Shared responsibility  
- Networking  
- Cloud storage  

**Answer Explanation:**  
This setup demonstrates **virtualization**. With virtualization:  
- A single physical server can run multiple **virtual machines (VMs)**.  
- Each VM acts as if it is its own separate physical machine, with its own OS and applications.  
- This improves **efficiency** (maximizes use of hardware resources), provides **isolation** (problems in one VM don’t affect others), and supports **flexibility** (running different OS types simultaneously).  

---

## Q4  
An organization had 10 separate physical servers, each underutilized. By virtualizing them into one powerful physical machine hosting 10 virtual servers, they reduced hardware costs and improved efficiency.  

**What is the main benefit achieved through virtualization here?**  
- Increased hardware purchases  
- ✅ Better resource utilization and cost savings  
- Reduced need for operating systems  
- No need for backup solutions  

**Answer Explanation:**  
The main benefit is **better resource utilization and cost savings**. Virtualization allows:  
- Consolidation of workloads into fewer machines, which reduces hardware expenses.  
- Lower **electricity consumption** and **cooling costs** in the data center.  
- Easier **server management** and scalability compared to multiple separate physical servers.  

It does **not** eliminate the need for backups or operating systems — each virtual machine still requires its own OS and data protection strategies.  

---

## Q5  
A startup installs VMware ESXi on their server to manage and run multiple virtual machines. This software allocates resources (CPU, memory, storage) to each VM and ensures isolation between them.  

**What is VMware ESXi an example of?**  
- Cloud storage system  
- ✅ Hypervisor  
- Firewall  
- Shared responsibility  

**Answer Explanation:**  
VMware ESXi is a **Type-1 hypervisor (bare-metal hypervisor)**. A hypervisor is software (sometimes built into hardware) that:  
- Sits between the physical hardware and the virtual machines.  
- Divides resources such as CPU, memory, and storage across VMs.  
- Ensures **isolation** so one VM doesn’t interfere with another.  

This is different from **cloud storage** (data storage service), **firewalls** (security devices), and **shared responsibility** (a security model).  

---

## Q6  
Company A runs Microsoft Hyper-V on top of their Windows operating system to create and manage virtual machines. Company B runs VMware ESXi directly on the hardware without an underlying OS.  

**Which statement is correct about these hypervisors?**  
- Hyper-V is Type 1 and ESXi is Type 2  
- ✅ Hyper-V is Type 2 and ESXi is Type 1  
- Both are Type 1 hypervisors  
- Both are Type 2 hypervisors  

**Answer Explanation:**  
There are two types of hypervisors:  
- **Type-1 (bare-metal):** Runs directly on hardware (e.g., VMware ESXi). These are highly efficient and used in data centers.  
- **Type-2 (hosted):** Runs on top of a host OS (e.g., Hyper-V when installed on Windows, VirtualBox, VMware Workstation). These are easier to install but less efficient.  

In this case:  
- Company A’s **Hyper-V on Windows** = **Type-2** hypervisor.  
- Company B’s **VMware ESXi** = **Type-1** hypervisor.  

---

## Q7  
A hospital moves its patient database to a virtualized environment managed by a hypervisor. The cloud provider secures the physical data center and network. The hospital IT team must configure access controls, encryption, and data backups.  

**This scenario demonstrates which two cloud concepts?**  
- ✅ Shared responsibility model and virtualization  
- Hypervisor and SaaS  
- IaaS and PaaS  
- Public cloud and community cloud  

**Answer Explanation:**  
This scenario involves **two key concepts**:  

1. **Virtualization**  
   - The hospital uses a hypervisor to create virtual machines for managing their patient database.  
   - Virtualization allows multiple isolated systems to run on shared hardware.  

2. **Shared Responsibility Model**  
   - The **cloud provider** secures the **data center, servers, and physical networking**.  
   - The **hospital IT team** is responsible for securing what runs in the cloud:  
     - **Access controls** (who can access data)  
     - **Encryption** (protecting sensitive patient data)  
     - **Data backups** (for disaster recovery).  

Together, these demonstrate how cloud computing distributes responsibilities while leveraging virtualization for efficiency.  

---
