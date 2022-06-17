# Comandos de Git e Github

## Principais comandos de Git e Github Aprendidos

### Configurações iniciais
- Registra o nome do autor do projeto
```git
git config –-global user.name <nome>
```

- git config --global user.email <email>
Registra o e-mail do autor do projeto

### Início de um projeto

- git init <nome do repositório>
Cria um novo .git

- git Add <nome do arquivo>
Adiciona o arquivo oo staging.

- git Add .
Adiciona todos da pasta atual ao staging

- git commit -m "Novo Commit".
Comita os arquivos.

- git commit --amend
Renomeia o ultimo commit feito.

- Git clone <URL do projeto>
Clona um repositório.

- Git Branch
Lista as ramificações do repositorio.

- Git Checkout -b <nome da Branch>
Cria uma nova ramificação para o arquivo principal.


- Git branch -d <nome da Branch>
Apaga o Brach que não terá mais utilidade.

- Git checkout <nome da Branch>
Muda de branch.

- Git merge
junta duas branchs fazendo um novo commit.

- Git push 
envia o commit para um repositório remoto.

- Git pull 
recebe os commits de um remositório remoto.

- Git Stash
Guarda arquivos semparados dos commits

- Git Stash List
Lista todos os Stashs

- Git Stash pop
Restaura alterações salvas nos Stashs

- Git Revert <hash code>
Faz a reversão de um Commit.

- Git Reset
Faz a exclussão de um commit.
