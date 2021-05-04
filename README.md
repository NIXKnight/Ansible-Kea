# **Ansible-Kea**

Ansible-Kea is an Ansible role for installing and configuring Kea DHCP.

## **Requirements**

At the moment this role is being written for Debian based distributions e.g. Debian/Ubuntu. It may evolve to include other major distributions.

## **Dependencies**

This role doesn't depends on any other role for execution.

## **Example Playbook**

Facts gathering must be enabled.

An example of running the role is as follows:
```yaml
- hosts: servers
  gather_facts: True
  roles:
      - Ansible-Kea
```

## **License**

This playbook is licensed under MIT License (See the LICENSE file).

## **Author**

[Saad Ali](https://github.com/nixknight)
