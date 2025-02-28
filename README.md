# users-migration
This repo is a ansible repo for migration users with ansible

To run this repo fist upload the passwd and the group from the old server.
Then update the hosts inventory file.
Then run the playbook.
```
ansible-playbook -i hosts playbooks/playbook.yml
```
