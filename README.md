# Alura Ansible

Projeto de exemplo para o curso de Ansible da Alura

## Primeiro comando

```bash
ansible wordpress -u vagrant --private-key .vagrant/machines/wordpress/virtualbox/private_key  -i hosts -m shell -a 'echo "Hello, World"'
```