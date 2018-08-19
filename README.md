# Ansible Role: heartbeat

Ansible Role to install and configure Apache Zookeeper for Ubuntu.


## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `var/main-3.4.8-1.yml`).
You can overload the variables by creating a dictionary called "zookeeper", ex:

    zookeeper:
      version: 3.4.8-1

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - apolloclark.zookeeper

## License

MIT / BSD

## Author Information

This role was created in 2017 by [Apollo Clark](https://www.apolloclark.com/)
