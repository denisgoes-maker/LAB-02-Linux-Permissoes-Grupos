# Usuários e Grupos — LAB 02

## Criação do usuário suporte

Foi criado o usuário suporte para simular um profissional de suporte técnico.

Comandos:
sudo adduser suporte
id suporte

## Permissão administrativa

O usuário foi adicionado ao grupo sudo.

Comandos:
sudo usermod -aG sudo suporte
sudo -l -U suporte

## Remoção de grupo

O usuário suporte foi removido do grupo users.

Comandos:
sudo gpasswd -d suporte users
groups suporte

## Grupo suporte-ti

Foi criado o grupo suporte-ti para controlar o acesso a recursos compartilhados.

Comandos:
sudo groupadd suporte-ti
sudo usermod -aG suporte-ti denis
sudo usermod -aG suporte-ti tecnico

## Verificação

Comandos:
id suporte
groups suporte
groups tecnico

## Resultado

Foi praticado o gerenciamento de usuários e grupos no Linux, incluindo criação, associação, remoção de grupos e concessão de privilégios administrativos.
