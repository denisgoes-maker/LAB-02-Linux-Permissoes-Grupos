# LAB 02 — Linux: Usuários, Grupos e Permissões

Laboratório prático de administração Linux utilizando Ubuntu Server 24.04 LTS, com foco em usuários, grupos, permissões de arquivos e diretórios, `chmod`, `chown` e controle de acesso.

---

## 🖥️ Ambiente

- **Sistema:** Ubuntu Server 24.04.5 LTS
- **Virtualização:** VMware Workstation
- **RAM:** 6 GB
- **CPU:** 2 vCPU
- **Disco:** 30 GB
- **Rede:** NAT
- **Shell:** Bash

---

## 🎯 Objetivos

- Criar e administrar usuários
- Criar e administrar grupos
- Adicionar e remover usuários de grupos
- Entender permissões `r`, `w` e `x`
- Utilizar `chmod`
- Utilizar `chown`
- Trabalhar com permissões `600`, `640`, `700`, `755` e `770`
- Diagnosticar erros de `Permission denied`
- Criar diretórios compartilhados por grupos
- Controlar acesso através de grupos Linux

---

# 1. 👤 Usuários e Grupos

Foi criado o usuário `suporte` para simular um usuário de suporte técnico.

Também foram realizados:

- Adição do usuário ao grupo `sudo`
- Remoção do usuário do grupo `users`
- Criação do grupo `suporte-ti`
- Adição dos usuários `denis` e `tecnico` ao grupo

### Comandos utilizados

```bash
sudo adduser suporte
