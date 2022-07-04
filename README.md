# git-academy22


## git init
Inicializa um projeto
```
git init
```

## Configurações inicias

```bash
git config --global user.name "username"
git config --global user.email "user@email.com"
```

## Controle de alterações 
Para visualizar as alterações feitas, vamos usar:

```bash
git status
```

## Criando commits
Primeiramente precisamos adicionar as mudanças e então 'commitar':
> Utilize o ponto para adicionar todas as alteraçoes do projeto
```bash
git add "nomeArquivo"
git commit -m "descricao das altearcoes"
```
- Para visualizar o histórico de commits realizados, use:
```bash
git log
```

## Branches 
Podemos ramificar nosso projeto através de branches. Para criar uma nova, executamos:

```bash 
git switch --create "nome_da_nova_branch"
#or
git checkout -b "nome_da_nova_branch"
```
- Listando branches criadas:
```bash
git branch
```

- Apagando uma branch:
```bash
git branch -D "nome_da_branch"
```

## GitHub
- Adicionando uma remote origin:
```bash
git remote add origin "https://github.com/user/repository-name.git"
```

- Subindo alterações:
```bash
git push origin "nome_da_branch"
# caso a branch nao exista no GitHub use:
git push -u origin "nome_da_branch"
