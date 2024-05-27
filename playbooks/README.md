# Ansible

## Prerequisites

- Install Ansible

```bash
python -m venv venv
source venv/bin/activate
pip install -U pip
pip install ansible
```

- Install `community.docker` module (This may not be necessary if you install the full `ansible` package)

```bash
ansible-galaxy collection install community.docker
```
