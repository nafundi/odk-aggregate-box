This server will appear like any other machine on your network. This allows you to connect external devices to test the server. We assume your network hands out IP addresses over DHCP.

## Install requirements
1. Install [git lfs](https://git-lfs.github.com) v1.5.3 or later. 
1. Install [ansible](https://docs.ansible.com/ansible/intro_installation.html) v2.2.0 or later.
1. Install [vagrant](https://www.vagrantup.com/docs/installation) v1.9.1 or later.
	1. Install [vagrant-cachier](https://github.com/fgrehm/vagrant-cachier).
1. Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads) v5.1.12 or later.

## Provision and configure server
1. Clone this repository.
1. Run `vagrant up`. Select the interface you wish to use (e.g., Wi-Fi).
1. After the server is provisioned, vagrant will report the IP of your server.

## Default credentials
* Aggregate login: aggregate/aggregate
* MySQL database: aggregate
* MySQL user login: aggregate/aggregate
* MySQL root login: root/aggregate

## Notes
* Please don't use this server in production. It is not configured to be robust or safe.