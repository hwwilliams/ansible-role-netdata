# Ansible Role: Netdata

[![Build Status](https://travis-ci.org/hwwilliams/ansible-role-netdata.svg?branch=master)](https://travis-ci.org/hwwilliams/ansible-role-netdata)

Installs [Netdata](https://my-netdata.io/) on Debian/Ubuntu and CentOS/Fedora/Redhat based Linux servers.

This role installs and configures the latest version of Netdata from the offical [Netdata](https://github.com/netdata/netdata) Github repo.

Also on [Ansible Galaxy](https://galaxy.ansible.com/hwwilliams/netdata).

## Requirements

None.

## Role Variables

Available variables are listed below:

```yaml
netdata_root_install_dir: /opt
```

The root installation directory for Netdata, by default it is set to '/opt' which would install Netdata to '/opt/netdata'

```yaml
netdata_repo_version: master
```

The version of Netdata to clone from the official Github repo, by default it is set to master.

```yaml
netdata_repo_version: v1.12.0
```

If you would rather clone a specific release version of Netdata you can supply a version instead of the master branch.

## License

MIT