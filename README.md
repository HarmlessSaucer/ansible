# ansible

Ansible playbooks for use with both my infrastructure at home, and my personal computers.

These playbooks are in no way fancy.  If you want fancy, or you are new to Ansible, I highly encourage you to check out [Jeff Geerling](https://www.jeffgeerling.com/) and his [YouTube channel](https://www.youtube.com/channel/UCR-DXc1voovS8nhAvccRZhg).  He has some fantastic books, guides and tutorials on getting started with Ansible and he has some great playbooks for getting a new computer setup.

---

## Layout of this repo

### docker-host

This folder is for the playbooks that will be used with my VMs that run my applications in Docker.  These playbooks allow you to take a blank Ubuntu Cloud-Init VM and get them setup with everything I need.

### loki

'Loki' is the name of my main PC, my Linux desktop.  Currently (as of early 2022) running Pop!_OS 22.04.  This playbook installs all the software I like to use and changes a few settings in GNOME to tweak the experience how I like it.