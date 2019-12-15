# Ansible Playbook: Setup my local Ubuntu

To setup my local Ubuntu machine, I use the following command which will run the `local.yml` Ansible playbook.
Run the following command on a shell of your choice.

```bash
ansible-playbook local.yml --ask-become-pass
```

## Requirements
The following tools need to be installed:
- Ansible
- Python