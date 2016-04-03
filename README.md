# Ansible Role: Devuan 0.1

An Ansible role that convert Debian 7 Wheezy into Devuan.

## Notes
This role remove every repository in `/etc/apt/sources.list` and add only the Devuan repository. Everything else under `/etc/apt/sources.list.d/*` will be ignored.

## Download from Ansible Galaxy
```bash
ansible-galaxy install maruina.devuan
```

## Example Playbook
```yaml
    - hosts: all
      roles:
        - { role: maruina.devuan }
```

## License

MIT
