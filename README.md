## Intro

This role based on https://github.com/idealista/zookeeper_role.

## Getting Started

These instructions will get you a copy of the role for your Ansible Playbook. Once launched, it will install an Apache ZooKeeper server.

### Prerequisites

#### To execute this role:

```

Use in a playbook:

```
---

- hosts: someserver
  roles:
    - zookeeper
```

## Usage

To set multiple versions

```
zookeeper_hosts:
  - host: zookeeper1
    id: 1
  - host: zookeeper2
    id: 2
  - host: zookeeper3
    id: 3


