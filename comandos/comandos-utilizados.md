# Comandos Utilizados — LAB 02

## Usuários

sudo adduser suporte
id suporte
sudo usermod -aG sudo suporte
sudo gpasswd -d suporte users
sudo adduser tecnico

## Grupos

sudo groupadd suporte-ti
sudo usermod -aG suporte-ti denis
sudo usermod -aG suporte-ti tecnico
groups

## Permissões

chmod 600 teste-permissao.txt
chmod 640 teste-permissao.txt
chmod 700 /home/suporte/lab-permissoes
chmod 755 /home/suporte/lab-permissoes
chmod 770 /lab-compartilhado

## Proprietário e Grupo

sudo chown denis:denis /home/suporte/lab-permissoes
sudo chown denis:suporte-ti teste-permissao.txt
sudo chown denis:suporte-ti /lab-compartilhado

## Testes

touch teste-permissao.txt
echo "teste" >> teste-permissao.txt
cat teste-permissao.txt

## Diretório Compartilhado

touch /lab-compartilhado/arquivo-tecnico.txt
echo "arquivo criado pelo tecnico" > /lab-compartilhado/arquivo-tecnico.txt
cat /lab-compartilhado/arquivo-tecnico.txt

## Verificação

ls -l
ls -ld
id
groups

## Troubleshooting

Erro encontrado: Permission denied

Causa: permissões insuficientes no arquivo ou em algum diretório do caminho.

Solução: verificar e ajustar chmod, chown e grupos de acesso.
