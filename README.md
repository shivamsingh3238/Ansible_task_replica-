# Ansible Task Replica-

## Few important command to run

## Run Ansible Playbook

```
ansible-playbook task.yml -i server.inv     ↲
```

## Ping all given server

```
ansible all -m ping -i server.inv     ↲
```

### To know abou host machine

```
ansible all -m setup -i server.inv ↲
```
