# TP3 - MLOps / DevOps

## Déploiement

### Prérequis

- Ansible
- Docker installé sur le serveur distant
- Accès SSH avec une clé

### Lancement

```bash
ansible-playbook -i ansible/inventories/setup.yml ansible/deploy.yml --limit prod
