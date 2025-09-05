# MISP Ansible
## Setup
Install ansible
```shell
sudo apt install -y ansible
```

Install the roles
```shell
ansible-galaxy install -r requirements.yml
```

Run the playbook
```shell
ansible-playbook -i inventory.yml misp-setup.yml
```

## Logs
Watch logs of docker compose
```shell
# in the misp-docker folder
sudo docker compose logs -f
```
