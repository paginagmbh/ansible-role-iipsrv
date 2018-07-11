# Ansible Role: IIPImage - High Resolution Streaming Image Server

[![Build Status](https://travis-ci.org/paginagmbh/ansible-role-iipsrv.svg?branch=master)](https://travis-ci.org/paginagmbh/ansible-role-iipsrv)

An Ansible Role that installs [IIPImage/iipsrv](https://github.com/ruven/iipsrv/) on Linux.

## Example Playbook

``` yaml
- role: gremid.iipsrv
  iipsrv_data: "/mnt/storage//iiif-data"
```

## License

BSD

## Author Information

This role was created in 2018 by [Pagina GmbH](https://www.pagina.gmbh/).

It draws heavily from best practices as demonstrated in roles authored by [Jeff Geerling](https://www.jeffgeerling.com/), author of [Ansible for DevOps](https://www.ansiblefordevops.com/).
