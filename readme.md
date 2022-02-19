Commandos Git:

git init

Inicia o versionamento no projeto

git add

coloca o(s) arquivo(s) para modo staging, aguardando a serem commitados

git commit -m 'mensagem do commit'

cria um ponto no versionamento, inserindo uma mensagem indicando o que foi feito até aquele momento nos arquivos do staging

git branch -M "nomeDaBranch"

Renomeia a branch atual para "nomeDaBranch"

git remote add origin {link}

vincula o repositório local a um repositório remoto, link = link do repositório remoto

git push {-u} origin {branch}

envia a branch atual para o repositório remoto, -u sómente usado na primeira vez

git checkout -b "nova-branch"

cria uma nova branch e direciona para ela

git merge {outra-branch}

traz o código da "outra-branch" para sua branch atual

git clone {link}

baixa um repositório remoto

git pull 

baixa atualizações do repositório remoto