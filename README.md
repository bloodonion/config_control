# config_control

# usage

ansible-playbook -i inventories/dev/hosts.yml main.yml -vv

ansible-playbook playbook.yml --become -l host1.example.com,host2.example.com -v

ansible-playbook playbook.yml --become -l host1.example.com --check -v