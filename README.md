- What is virtualization?
A: Virtualization is a technology that creates virtual versions of computer resources like servers, storage, networks, and operating systems. It allows multiple virtual environments (like virtual machines or VMs) to run simultaneously on a single physical machine, maximizing resource utilization and efficiency.

- Two main virtualization software available:

* VmWare player - Runs over an operating system
* VmWare Hypervisor - Hypervisor runs upon an hardware without having any OS (BareMetal)

- Products of VmWare:
* VmWare workstation - Free for personal use
* VmWare vSphere Hypervisor (ESXi) - BareMetal

Note: Esxi is the name of the hypervisor of Vmware

* VmWare vSphere client:
  - It is an interface that allows you to connect with a hypervisor (putty, mobaxterm or RDP)

* VmWare vCenter:
  - Management tool to manage multiple hypervisors

 Vmware labs: https://labs.hol.vmware.com/HOL/catalog

 Terms:
 * OVA - Open virtual appliance
 * OVF - Open virtual format
 * OVA/OVF both are pre-packaged virtual machines that are given to you by different vendors or maybe vmware.
 * Vmotion: live migration of virtual machines it allows you to move an entire running virtual machine from one physical server to another with no downtime.

What is RTO and RPO requirements?

* RPO - Recovery point objective. Total amount of data that a business can loose. Let's say there is some disaster happend at a datacenter so the replication time from 1 DC to another DC is let's say 1 min. So there is a total loss of data is 1 minute. It depends on the backup or replicaton is scheduled

<img width="955" height="639" alt="image" src="https://github.com/user-attachments/assets/d4b5c565-744d-4f38-8d41-3d427a33e489" />

* RTO - Recovery Time objective. Total amount of time is needed to make the business up and running since the disaster.

<img width="956" height="664" alt="image" src="https://github.com/user-attachments/assets/85659f41-7cbd-494e-ab50-bf2f23e9520f" />

