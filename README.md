# gcc2016-ansible
Ansible playbooks and roles from the Galaxy Community Conference 2016

Handy playbook run command:

```
script -q -c "ansible-playbook -i inventory -vv playbook.yml" /dev/null | tee ansible-build.log
```

On Ubuntu 16.04, needed to run these commands before playbook worked:

```
sudo apt-get install ansible
sudo apt-get install python-pip
sudo apt-get install postgresql-server-dev-all


```
