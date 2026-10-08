# Users Role

Manages Linux user accounts and their basic configuration.

## Features

- Create or remove Linux users
- Configure login shells
- Create home directories
- Manage supplementary groups
- Maintain idempotent user configuration

## Variables

The role uses the following variables:

    users_manage_users: true

    users:
      - name: devops
        shell: /bin/bash
        groups:
          - sudo
        append: true
        create_home: true
        state: present
