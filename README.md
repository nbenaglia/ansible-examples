# ansible-examples
Examples in Ansible

Edit /etc/ansible/hosts with proper data:

```
[all:vars]
ansible_python_interpreter="/usr/bin/env python3"
ansible_ssh_private_key_file=/home/nicola/.ssh/mykey
ansible_ssh_user=ubuntu
```

Edit my_topology with IPs
