# cloudbreak_deploy


## Prerequesites

You need to install ansible and have provided ssh access to the sudo "ssh_user"  where app will be deployed

```
pip install ansible
git clone https://github.com/PedroAndrade89/flask-deploy.git
cd cloudbreak_deploy
```

## Running the deployer

Edit the inventory file in cloudbreak-deploy and run:
```
ansible-playbook -u "ssh_user" --inventory-file=inventory cloudbreak_deploy.yml
```

