# Secure Linux: Virtualized Environment Setup and Server Configuration

## Introduction

In this project, I embarked on a journey to set up a virtualized environment, install Linux/Fedora, and configure various server services. Let's delve into the details of my experience and the steps I took.

---

## Part A: Installation of Linux/Fedora (23-25) Workstation

### Purpose and Objectives:

My objective was to introduce Linux to a virtualized environment, laying the groundwork for implementing the term project environment. This approach is pivotal as it mirrors the infrastructure of cloud computing, a prevalent model in modern businesses. Utilizing virtual machines is fundamental to this objective, as it forms the basis of cloud computing. Given its increasing prevalence in the business landscape, understanding and mastering virtualized environments is crucial. To achieve this, I set out to fulfill several success criteria, including installing a virtual machine player, creating a virtual machine, installing Linux OS, executing basic commands, installing applications, starting and testing Apache web server, and comprehending the Discretionary Access Control Mechanism. This not only serves the immediate goal of familiarizing with Linux but also equips me with skills essential for navigating the evolving landscape of cloud computing.
### My Journey:

I began by downloading VMware Workstation Player 16 and Fedora Workstation 23 ISO. These choices were based on their comprehensive security features and resource efficiency, aligning well with my project requirements.

Following the provided instructions, I installed VMware Workstation Player 16 and created a new virtual machine using default values. Then, I proceeded to install Fedora Workstation 23 on the virtual machine, fulfilling the installation process including specifying time and location, setting root password, and creating a new user account.

Once Fedora was installed, I explored the operating system environment, accessed the terminal, and executed various commands to navigate through directories, list files, and configure users & groups.

Finally, I delved into discretionary access control by creating files and managing their permissions, gaining a deeper understanding of Linux security mechanisms.

---

## Part B: SELinux Server Services

### Purpose and Objectives:

In this section, my aim was to gain experience in identifying the basic requirements for creating a virtualized e-commerce solution. I focused on installing and configuring various server services, including Apache web server, MySQL/MariaDB database, PHP interpreter, NTP server, FTP server, and enabling Multilevel Security (MLS) in SELinux.

### My Experience:

I followed the provided instructions to install and configure each server service. For example, I installed Apache web server, MySQL/MariaDB database, and PHP interpreter to set up a LAMP platform. I ensured that each service was operational and tested its functionality.

Additionally, I installed and configured pure-ftpd server in anonymous mode for FTP service. I also set up a Time Synchronization Server using NTP protocol and configured an email server with Postfix.

To enhance security, I generated PGP keys for myself and published them on the MIT PGP server. Furthermore, I enabled Multilevel Security (MLS) in SELinux to demonstrate its capabilities in enforcing access control policies.

---

## Conclusion

Through this project, I gained valuable experience in setting up and configuring a Linux/Fedora Workstation environment. I successfully installed various server services, explored Linux command line interface, and implemented security measures to protect my system.

This journey has expanded my knowledge and skills in IT environments, and I'm excited to apply them in future projects and endeavors.


