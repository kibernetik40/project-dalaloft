
# ULTRA DevOps Project

## Features
- Full automation via Ansible
- Dockerized Laravel stack
- GitLab CI/CD auto-deploy
- HTTPS via Let's Encrypt
- Release-based deploy

## Run locally
cd docker
docker-compose up -d

## Deploy
ansible-playbook -i ansible/inventory/hosts.ini ansible/playbook.yml

## Notes
- Uses volumes (no rebuild)
- Secrets via vault
- Production-ready structure
