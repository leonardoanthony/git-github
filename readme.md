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

#### Renomei a branch atual

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