# Ansible playbook

This playbook installs the NVIDIA drivers and tools to work with GPU's within a VM. 
Currently its based on the Grid K2 and P100 setup im working with. 

Goals of this playbooks is to place drivers, benchmarks, examples and test environment. 

* Since packer sets starts the VM with an apt update after its initial boot, please be aware that the first step can fail due to dpkg db being in use. In the future packer builds will replace this.