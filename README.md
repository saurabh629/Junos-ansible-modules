# Junos-ansible-modules

This repository contains playbooks which demo the use of Junos ansible modules described below

* junos_install_config - Load a configuration file or snippet onto a device running Junos OS
* junos_shutdown - Shut down or reboot a device running Junos OS
* junos_zeroize - Erase all data, including configuration and log files, on a device running Junos OS
* junos_get_table - Retrieve data from a Junos device using Tables/Views
* junos_cli - Execute CLI on device and save the output locally
* junos_install_os - Install a Junos OS image
* junos_get_config - Retrieve configuration of device
* junos_rpc - run given rpc
* junos_ping - execute ping on junos devices
* junos_get_facts - Retrieve facts for a device running Junos OS.

### Getting started

### Prerequisites
The setup requires oracle virtualbox to spin up Junos routers with JunosOlive image. Three Junos routers 
are created as per the below topology. A Ubuntu based linux host machine is needed as Ansible host. 
Ansible is installed with other ansible related dependencies on linux machine

### Topology

Three Junos router vmx1, vmx2 and vmx3 and ubuntu based linux as Ansible host. Junos routers are connected
to each other and placed in separate AS for making eBGP connections
             
### Playbooks
##### pb.junos_ping.yml

##### pb.junos_get_config.yml

##### pb.junos_rpc.yml

##### pb.junos_cli.yml

##### pb.junos_install_config.yml

##### pb.junos_shutdown.yml

##### pb.junos_zeroize.yml

##### pb.junos_install_os.yml

##### pb.junos_delete_bgp.yml

##### pb.junos_get_os.yml
