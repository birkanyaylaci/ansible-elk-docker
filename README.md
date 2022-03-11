# ansible-elk-docker
## Roles
clean / docker / elasticsearch / kibana / logstash /nginx 
## Requirement
* Docker
* Pip sudo apt-get install python-pip
* Ansible Docker module sudo su; pip install docker

## Deployment

Test connection

`ansible all -m ping -i inventory`

Deploy elk stack

`ansible-playbook -i inventory elk.yml`

