# Ansible Role: Homebrew

[![CI](https://github.com/DudeCalledBro/ansible-role-homebrew/actions/workflows/ci.yml/badge.svg)](https://github.com/DudeCalledBro/ansible-role-homebrew/actions/workflows/ci.yml)

Install Homebrew on MacOS (ARM).

## Prerequisites

- Ensure you have Ansible installed (e.g. `pip3 install ansible`)
- **Development**: Install the pip packages listed in [requirements.txt](requirements.txt)

## Role Variables

The default values for the variables are set in [defaults/main.yml](defaults/main.yml)

```yaml
- hosts: all
  roles:
  - role: dudecalledbro.homebrew
```

## License

Copyright © 2024 Niclas Spreng

Licensed under the [MIT license](LICENSE).
