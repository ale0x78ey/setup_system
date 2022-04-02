## Setup system

It's just some ansible playbooks for local environment.

## Ubuntu

```bash
sudo apt update && sudo apt install -y python3 python3-pip python3-venv
python3 -m venv venv
. venv/bin/activate
pip install setuptools wheel ansible
ansible-playbook -i hosts setup_system.yml
./setup_vim
```
