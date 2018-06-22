# Ansible example of using variables in template

Variables defined in a remote source.

try with 
```
ansible-playbook -i inventory/hosts playbook.yml  -e app_name=app1 -e app_env=prod
```

should write a file in /tmp/app.conf

This is just an example showing usage of vars defined else, per enviroment.
