# How to use

## development

vagrant up

vagrant provision

## staging

ansible-playbook server.yml -e env=staging

## production

ansible-playbook server.yml -e env=production
