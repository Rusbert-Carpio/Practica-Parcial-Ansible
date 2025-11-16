# Práctica de Ansible + Docker

Este proyecto simula servidores usando contenedores Docker y configura automáticamente un servidor Nginx en cada uno utilizando Ansible.

## 📌 Tecnologías utilizadas
- Docker
- Docker Compose
- Ansible
- Ubuntu / WSL2

## 📁 Estructura del Proyecto

ansible-docker-lab/
├── Dockerfile
├── docker-compose.yml
├── inventory.ini
├── playbook.yml
└── site/
└── index.html


## 🚀 Cómo ejecutar

1. Construir los contenedores:
   ```bash
   docker compose up --build -d
