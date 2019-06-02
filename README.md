# Ansible Role: Netdata

[![Build Status](https://travis-ci.org/hwwilliams/ansible-role-netdata.svg?branch=master)](https://travis-ci.org/hwwilliams/ansible-role-netdata)

Installs [Netdata](https://my-netdata.io/) on Debian/Ubuntu and CentOS/Fedora/Redhat based Linux systems.

This role installs and configures the latest version of Netdata from the offical [Netdata](https://github.com/netdata/netdata) Github repo.

Also on [Ansible Galaxy](https://galaxy.ansible.com/hwwilliams/netdata).

## Requirements

[Netdata](https://my-netdata.io/) suggests having the Epel Repo enabled on RedHat based systems in order to have access to all dependencies.

Other dependencies are installed as needed by an official script designed by the [Netdata](https://my-netdata.io/) devs located [here](https://github.com/netdata/netdata-demo-site/blob/master/install-required-packages.sh).

## Role Variables

[defaults/main.yml](defaults/main.yml)

[vars/install-cmd-options.yml](vars/install-cmd-options.yml)

[vars/systemd.yml](vars/systemd.yml)

[vars/upstart.yml](vars/upstart.yml)

## License

MIT
