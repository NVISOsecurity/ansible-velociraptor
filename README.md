# ansible-velociraptor
Ansible role for Velociraptor EDR

## OS Platforms

This role has been tested on the following operating systems:

- Ubuntu 18.04

## Usage

To use this role in your playbook to install the server, add the code below:

```
- name: Install Velociraptor EDR
  import_role:
    name: ansible-velociraptor
  vars:
    server: true
```

To use this role in your playbook to install the client, add the code below:

```
- name: Install Velociraptor EDR
  import_role:
    name: ansible-velociraptor
  vars:
    client: true
```

## Disclaimer

This role is meant for use in the SANS 699 course and is provided as is.

## License

[MIT](LICENSE)