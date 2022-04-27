# networking

[![Build Status](https://drone.cryptic.systems/api/badges/volker.raschek/networking-role/status.svg)](https://drone.cryptic.systems/volker.raschek/networking-role)
[![Ansible Role](https://img.shields.io/ansible/role/d/58433)](https://galaxy.ansible.com/volker_raschek/networking)

With following role can the networking stack provided by systemd be configured.

## Supported distributions

- Arch Linux
- Ubuntu 20.04

## Features

- Installing systemd-networkd, systemd-resolved and systemd-timesyncd
- Configuring systemd networking services

## Configuring

In the default directory are examples how to configure the network stack. Copy the
defaults into your `host_vars` or `group_vars` and adapt the examples.
