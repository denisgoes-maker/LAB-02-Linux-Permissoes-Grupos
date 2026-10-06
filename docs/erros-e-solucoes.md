# Erros e Soluções — LAB 02

## Permission denied

Durante o laboratório ocorreram erros de Permission denied ao acessar diretórios e escrever em arquivos.

## Diagnóstico

Foram utilizados os comandos ls -l, ls -ld, id e groups para identificar permissões, proprietários e grupos.

## Causa

As permissões do arquivo ou de algum diretório no caminho não permitiam o acesso necessário ao usuário.

## Soluções

Foram utilizados chmod, chown, usermod e gpasswd para corrigir permissões, proprietários e grupos.

## Diretório compartilhado

Foi criado o diretório /lab-compartilhado.

O diretório foi configurado com o grupo suporte-ti e permissão 770.

O usuário tecnico, pertencente ao grupo suporte-ti, conseguiu acessar o diretório, criar arquivos, escrever e ler.

## Resultado

Os problemas de permissão foram identificados e corrigidos através da análise de usuários, grupos, proprietários e permissões Linux.
