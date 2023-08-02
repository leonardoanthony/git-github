# Commandos Git:

## 📍 Local

#### Inicia o versionamento

    git init

#### Verifica os arquivos modificados

    git status

#### Adiciona os arquivos para "staging"

    git add (nome do arquivo) / *

#### Cria o commit
    
    git commit -m "mensagem"

### 🌿 Branches

#### Lista as branches

    git branch

#### Renomeia a branch atual

    git branch -M "nome da branch"

#### Cria uma nova branch e redireciona pra ela

    git checkout -b "nome da branch"

#### Direciona pra a branch

    git checkout "nome da branch"

#### Traz o código da "outra branch" para a atual

    git merge {outra branch} 

### 🛰️ Remoto

#### Vincula o repositorio local ao remoto

    git remote add origin "link do repositório"

#### Sobe os arquivos para o github na primeira vez

    git push -u origin main

#### Sobe os arquivos nas demais vezes

    git push 

#### Clona o repositório remoto para o local

    git clone "link do repositorio"

#### Traz as alterações do repositório remoto pra o local

    git pull 

### 🔄 Atualização e Desfazendo

#### Desfaz as alterações não "staged" em um arquivo

```bash
git checkout -- (nome do arquivo)
```

#### Desfaz as alterações "staged" (preparadas para o commit) em um arquivo

```bash
git reset HEAD (nome do arquivo)
```

#### Desfaz o último commit mantendo as alterações no código

```bash
git reset HEAD~1
```

#### Desfaz o último commit e reverte as alterações no código

```bash
git reset --hard HEAD~1
```

#### Reverte um commit específico por meio de um novo commit

```bash
git revert (hash do commit)
```

### 🔎 Histórico

#### Mostra o histórico de commits

```bash
git log
```

#### Mostra o histórico de commits com informações resumidas

```bash
git log --oneline
```

#### Mostra o histórico de commits graficamente

```bash
git log --graph --oneline --all
```

### 🔄 Trabalhando com Tags

#### Lista todas as tags

```bash
git tag
```

#### Cria uma nova tag leve (apenas um marcador)

```bash
git tag nome-da-tag
```

#### Cria uma nova tag com uma mensagem anotada

```bash
git tag -a nome-da-tag -m "mensagem da tag"
```

#### Envia todas as tags para o repositório remoto

```bash
git push --tags
```

### 🔄 Stash (Armazenando modificações temporariamente)

#### Armazena alterações temporariamente em um stash

```bash
git stash save "mensagem"
```

#### Lista todos os stashes

```bash
git stash list
```

#### Aplica as alterações de um stash específico e o remove da lista

```bash
git stash pop stash@{num_stash}
```

#### Remove um stash específico da lista

```bash
git stash drop stash@{num_stash}
```

### 🔄 Configurações Globais

#### Configura o nome de usuário global

```bash
git config --global user.name "Seu Nome"
```

#### Configura o email global

```bash
git config --global user.email "seuemail@example.com"
```

#### Configura o editor de texto padrão para mensagens de commit

```bash
git config --global core.editor "nome do editor"
```
