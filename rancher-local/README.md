## Initial docker environment

start rancher server:
ansible-playbook rancher-servers.yml -i ansible_hosts -e @../common-vars.yml

add rancher host:
ansible-playbook rancher-local.yml -i ansible_hosts -e @../common-vars.yml
