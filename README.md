# homelab-vm-template
VM Provisioning on Proxmox VE uisng Packer, Terraform, and Ansible.

The initial work will be for provisioning a VM template, then building a VM, and finally fully configuring it.
The flow will be: Packer -> Terraform -> VM Template -> VM -> Ansible config automation on VM

### References
- Parrot Security/OS
  -[Parrot Security (Docs - Installation)](https://parrotsec.org/docs/category/installation)
  - [Parrot Securiyt - ISO/Download](https://parrotsec.org/download/)
- Blogs :-)
  - [britt.devlog - Homelab/Proxmox](https://devlog.brittg.com/posts/homelab-part-1-proxmox/)
- Ubuntu preseed, cloud-init
  - [autoinstall-generator](https://discourse.ubuntu.com/t/autoinstall-generator-tool-to-help-with-creation-of-autoinstall-files-based-on-preseed/21334)
