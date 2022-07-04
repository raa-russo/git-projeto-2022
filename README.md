# git-projeto-2022

## git init
Inicializacao de um projeto:
```bash
git init

```
## configuracoes iniciais
Nome de usuario e email.
```bash

git config --global user.name "username"
git config --global user.email "user@email.com
```

## controle de alteracoes
para visualizar as alteracoes feitas usamos:

```bash
git status
```
## criando commits
primeiramente precisamos add as mudancas e enfim  'comitar':
>utilize o ponto para add todas as alteracoes do projeto.

```bash

git add .
git commit -m "descricao das alteracoes"

```

## Branches

Podemos ramificar o codigo usando branches para criar uma nova, executamos:
```bash
git switch -- create <nome-dapbranch>
or
git checkout -b <nome-dapbranch>
```

Listando branches criadas:
```bash
git branch
```

Apagando branch
```bash
git  branch -D<nome-da-branch>
```
## GitHub
-Adicioando um remote origin:
```bash
git remote add orig "https:github.com/user/repo-name.git
```
- subindo alteracoes:
```bash
git push origin <nome-da-branch>
# caso a branch nao exita no GitHub use:
git push -u origin <nome-da-branch> # ele criara a branch no GitHub
```

