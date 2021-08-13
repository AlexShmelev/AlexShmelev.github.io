# AlexShmel CV

Linux 6+ years expirience, mostly on Debian based OS

Scripting, deployment, networking

[Telegram] t.me/alexshmel

[Email] demigrant@protonmail.com

### Jobs
****
#### Cossack Labs / RockeTech 2019-...
Working as infrastructure engineer, main tasks is to build and maintain infrastructures for different projects.
Other tasks included development of internal tools and services, automation tasks, alert response.

#### Hacken 2018-2019
Support\monitoring of office network, Windows AD, local task tracker.
Security consulting and auditing, phishing awareness training, speeches at conferences as lookpicker

#### NOC service 2017-2018
Junior linux\network administrator, ELK setup and support for mikrotik netflow logs and events. Bash scripting for routine automation. 

#### Smartnet 2016-2017
Internship as network engineer. CISCO/mikrotik/fortinet setup, linux networking.

### **Skills**
**** 
- **IaC:** Chef cooboks, Ansible roles and terraform stuff. Also a bit of Packer
 - **Monitoring:** Prometheus, Grafana, alertmanager, ELK stack
 - **Development:** Internal tool for autotesting company product [acra-server](https://cossacklabs.com/acra). Linux  [tablets](https://3dmagic-innovations.com/wp-content/uploads/2019/11/studio.jpg) for cinema studio. RaspberryPi with a lot of magic inside them. Custom DDoS load testing tool using iperf3 and infinity amount of DigitalOcean droplets. Cloud filesystem LUKS encryption
 - **Automation:** Bash, Python, Ruby all purpose scripting
 - **Linux stuff:** Networking, routing (multiple route tables), iptables (firewalls and port forwarding), systemd (writing unit files), initramfs (rebuild with custom scripts), mdadm, LVM, LUKS, docker, nginx (also as load balancer)
 - **Cloud:** Digitalocean, Linode, Hetzner; Mass deploy of VMs using Terraform, Packer or API requests. 
 - **VM:** Ganeti cluster setup and VMs inside it using 1 public ip. Proxmox VMs setup for general use
 - **DB:** Mariadb and PostgreSQL clusters, replication and backup setup
 - **Tunneling:** Tinc, openvpn, ipsec strongswan
 - **Other:** Lockpicking, fast learning, good at teaching other people, confident public speaker. Used to spoke at cyber security conferencess as lokpicker.
 Admin of my own telegram channel [Infrastructure Engineer](https://t.me/cyber_shmel), Manager at Kyiv [DefCon8044](https://t.me/DC8044_Info) Radio station [44.WAV-E](https://radio.dc8044.com). Used to play some CTF challenges, also solwed few HackTheBox machines. Currently reading "Unix and Linux system administration handbook" at random capters.
 
### **Projects**
**** 
 - **[up.vision](https://up.vision):** Build infrastructure, prod/stage environments, nginx, docker, postgresql replications, ganeti cluster, tinc network.
 All managed by Chef, initial provisioning with Terraform + Ansible on Digitalocean droplets. All VM have LUKS encryption. 
 - **PeaceDDoS:** Internal tool for DDoS to load test our services using python iperf3 and infinite amount of DigitalOcean droplets
 - **Project (1,2):**: Build infrastructure for project that serves metrics from industrial tech in friendly web interface.
Pgsql + pgbouncer, DNS reqursive(unbound) and authoritative(gdnsd), HAproxy, rabbitmq, redis, ipsec, tinc, openvpn. Prometheus, Grafana, ELK.
Mass production of Raspberry Pi devices with preinstalled software, such as custom developed network balancing script, fulldisk encryption, ReadOnly filesystem, openvpn backconnet to main infra and other tricky stuff.
 - **Project (3):** Write internal tool for autotesting company product [acra-server](https://cossacklabs.com/acra).  Bash, python, ruby, makefile. 
 - **Project (4):** Design instrument for auto deploy a complex demo stand of Enterprise Edition [acra-server](https://cossacklabs.com/acra). Terraform, packer, ansible, bash, python, black magic, DigitalOcean API.
 - **Project (5):** Develop a tool for automation LUKS encryption of cloud VM, such as DigitalOcean, Hetzner, Linode. Terraform, Ansible, Bash
 - **Project (6):** Ansible + bash + python scripts for autogeneration openvpn configs for multiple clients. Fast vpn server setup
