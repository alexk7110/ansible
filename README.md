# ansible
My Ansible playbooks

### docker installation on ubuntu 20.04 focal from .deb files
Having to uninstall docker snap from an Ubuntu image and install it from .deb files for stability and user requested updates made me create this playbook found in docker_on_ubuntu_server directory.

This one installs:
- 20.10.13~3-0 ubuntu focal amd64 release of docker_ce
- 20.10.13~3-0 ubuntu focal amd64 release of docker_cli
- 1.4.13-1 amd64 version of containerd
- 2.3.3 docker-compose plugin ubuntu focal amd64 version

It also adds the user to the `docker` group and adds the docker-compose path to the `$PATH`
