# Erros e Soluções — LAB 02

## 1. Permission denied ao acessar diretório

### Problema

O usuário `denis` tentou acessar:

`/home/suporte/lab-permissoes`

e recebeu:

`Permission denied`

### Diagnóstico

```bash
ls -ld /home/suporte
ls -ld /home/suporte/lab-permissoes
