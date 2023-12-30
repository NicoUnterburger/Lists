# links.linux.md
URLs of all relevant stuff for Linux Server

## System-Administration
 - https://bytefreaks.net/gnulinux/how-to-set-a-static-ip-address-from-the-command-line-in-gnulinux-using-ip-addr-and-ip-route
 - Besser Leben mit SSH (https://martin.leyrer.priv.at/downloads/talks/2022/2022-05%20-%20gpn20%20-%20Besser%20leben%20mit%20SSH.pdf)
 - SSH agent on KDE (https://kcore.org/2022/05/18/ssh-passphrases-kde/)
 - Reset $PATH (https://askubuntu.com/questions/113419/how-can-i-reset-path-to-its-default-value-in-ubuntu)

## Proxmox
### Cluster
 - https://daniel-ziegler.com/proxmox-ve/computer/netzwerk/linux/2018/04/27/Proxmox-Virtual-Environment-Clustering/
 - https://pve.proxmox.com/pve-docs/pve-admin-guide.html#_remove_a_cluster_node

### CloudInit
 - Create own Template (https://pycvala.de/blog/proxmox/create-your-own-debian-12-cloud-init-template/)
 - Bookworm Images (https://cloud.debian.org/images/cloud/bookworm/20231013-1532/)
 - CLI commands (https://cloudinit.readthedocs.io/en/latest/reference/cli.html)
 - CloudInit with Ansible (https://ronamosa.io/docs/engineer/LAB/proxmox-cloudinit/)

### Backup 
 - https://blog.unixa.de/proxmox-backup-server/

### Proxmox on Hetzner with VM-bases-Firewall
 - https://community.hetzner.com/tutorials/install-and-configure-proxmox_ve/de
 - https://dominicpratt.de/hetzner-proxmox-opnsense/
 - https://administrator.de/forum/zuweisen-der-haupt-ip-vom-dedicated-hetzner-server-der-pfsense-vm-655068.html
 - https://forum.netgate.com/topic/58492/multiple-wan-esxi-5-1-bei-hetzner-pfsense-2-03-nicht-mehr-erreichbar/8
 - https://administrator.de/forum/oeffentliche-ip-adresse-dem-wan-interface-einer-firewall-vm-zuweisen-276295.html

### MacOS on Proxmox
 - https://www.nicksherlock.com/2019/10/installing-macos-catalina-10-15-on-proxmox-6/
 - https://www.nicksherlock.com/2020/04/installing-macos-catalina-on-proxmox-with-opencore/

### other 
 - https://schroederdennis.de/tutorial-howto/proxmox-monitoring-einrichten-installieren-influxdb-grafana/
 - https://www.reddit.com/r/Proxmox/comments/lcnn5w/proxmox_pcie_passthrough_in_2_minutes/
 - Subscription Plans (https://www.proxmox.com/en/proxmox-virtual-environment/pricing)

## Ansible Automation
 - Module, Proxmox (https://docs.ansible.com/ansible/latest/collections/community/general/proxmox_module.html)
 - Module, Proxmox KVM (https://docs.ansible.com/ansible/latest/collections/community/general/proxmox_kvm_module.html)
 - Module, Proxmox DISK (https://docs.ansible.com/ansible/latest/collections/community/general/proxmox_disk_module.html)
 - Module, Netbox IPAM (https://docs.ansible.com/ansible/latest/collections/netbox/netbox/netbox_ip_address_module.html)
 - Module, Zabbux Host (https://docs.ansible.com/ansible/latest/collections/community/zabbix/zabbix_host_module.html#ansible-collections-community-zabbix-zabbix-host-module)
 - Platform, RouterOS (https://docs.ansible.com/ansible/latest/network/user_guide/platform_routeros.html)
 - Intro Ansible Collections (https://blog.networktocode.com/post/ansible-collections/)
 - HomeLabGuied, Proxmox Automation with Ansible (https://elijahliedtke.medium.com/home-lab-guides-proxmox-6-automation-with-ansible-feca34f56ee3)
 - Get DHCP-Adress of new Proxmox VM (https://www.reddit.com/r/ansible/comments/16fnyz2/get_dhcp_ip_address_of_a_new_proxmox_vm_in_ansible/)
 - Ansible switch Hosts within a Playbook (https://stackoverflow.com/questions/47644962/how-to-switch-ansible-playbook-to-another-host-when-calling-second-playbook)
 - github, vm-deploy task (https://github.com/kasper5/ansible-proxmox-vm-deploy/blob/master/roles/proxmox/tasks/vm_deploy.yml)
 - Provision Proxmox VM from template (https://forum.proxmox.com/threads/provision-vm-from-template-using-ansible.130596/)

## VMware 
 - ESXi Update Tracker (https://esxi-patches.v-front.de/)
 - ESXi read out SMART (https://kb.vmware.com/s/article/2040405)
 - ghettoVCB (https://communities.vmware.com/t5/VI-VMware-ESX-3-5-Documents/ghettoVCB-sh-Free-alternative-for-backing-up-VM-s-for-ESX-i-3-5/ta-p/2773570)

## TrueNAS
 - iSCSI & VMware 7.x (https://www.virtualbytes.io/truenas-scale-vmware-vsphere-7-x/)
 - PVE & ZFS over iSCSI (https://forum.proxmox.com/threads/proxmox-ve-and-zfs-over-iscsi-on-truenas-scale-my-steps-to-make-it-work.125387/)
   
## Mailserver
 - https://thomas-leister.de/mailserver-debian-buster/
 - https://docs.mailcow.email/prerequisite/prerequisite-system/

## Run a Server at Home without public IPv4
 - https://blog.wirelessmoves.com/2019/06/how-to-run-a-server-at-home-without-an-ipv4-address.html

## Universal FCC-Unlock for Quectel EM05-G
 - https://github.com/longsleep/t14g3amd-linux#fixing-wwan-4g-modem-quectel-em05-g#fixing-wwan-4g-modem-quectel-em05-g

## Docker
 - Simple curl install (https://docs.sevenbridges.com/docs/install-docker-on-linux)

## Zabbix 
 - HTML Mail Template (https://github.com/devolabs/zabbix-email-templates)
 - Template for UniFi (https://www.reddit.com/r/Ubiquiti/comments/12aebv3/zabbix_template_for_unifi_network/)
