# Comandos de Git e Github

## Principais comandos de Git e Github Aprendidos

### Configurações iniciais

- Registra o nome do autor do projeto:
```git
git config –-global user.name <nome>
```

- Registra o e-mail do autor do projeto:
```git
git config --global user.email <email>
```

### Comandos em um projeto

- Cria um novo .git:
```git
git init <nome do repositório>
```

- Adiciona o arquivo oo staging:
```git
git Add <nome do arquivo>
```

- Adiciona todos da pasta atual ao staging:
```git
git Add .
```

- Comita os arquivos:
```git
git commit -m "Novo Commit".
```

- Renomeia o ultimo commit feito:
```git
git commit --amend
```

Clona um repositório:
```git
git clone <URL do projeto>
```

Lista as ramificações do repositorio:
```git
git Branch
```

- Cria uma nova ramificação para o arquivo principal:
```git
git Checkout -b <nome da Branch>
```

- Apaga o Brach que não terá mais utilidade.
```git
git branch -d <nome da Branch>
```

- Muda de branch:
```git
git checkout <nome da Branch>
```

- Junta duas branchs fazendo um novo commit:
```git
git merge
```

- Envia o commit para um repositório remoto:
```git
git push 
```

- Recebe os commits de um remositório remoto:
```git
git pull 
```

- Guarda arquivos semparados dos commits:
```git
git Stash
```

- Lista todos os Stashs:
```git
Git Stash List
```

- Restaura alterações salvas nos Stashs:
```git
git Stash pop
```

- Faz a reversão de um Commit:
```git
git Revert <hash code>
```

- Exclussão de um commit:
```git
git Reset

```
