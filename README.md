# ansible-ezmlm-idx
Ansible playbook for installing and configuring [ezmlm](https://untroubled.org/ezmlm/).
This role is based on [guilde ezmlm-idx](https://lab.uberspace.de/guide_ezmlm.html)


* works in userspace (no root needed)


## Requirements
[Ansible module makefile](https://docs.ansible.com/ansible/latest/collections/community/general/make_module.html) is required:

```
ansible-galaxy install -r requirements.yml
```


## Usage

```
ansible-playbook install-ezmlm.yaml -i <inventory>.yaml
```

## Config

[ezmlm-idx Manual](https://untroubled.org/ezmlm/manual/)