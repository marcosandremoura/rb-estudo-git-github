
CURSO BÁSICO ENSINANDO A USAR GIT E GITHUB
==========================================










PASSO A PASSO DO APRENDIZADO
----------------------------

01 - Criar uma pasta no computador
02 - Abrir a pasta; Clicar com botão direito na pasta; clicar em "quick actions"; clicar em "open in vscode"
03 - Criar arquivo "Readme.md" 
04 - Escrever o titulo do projeto na primeira linha do arquivo "Readme.md"
05 - Ir na pasta; clicar com botão direito dentro da pasta; clicar em "services"; clicar em "new terminal at folder"
06 - { git branch -M "main" (SÓ SE TIVER NA MASTER) 
07 - { git init
08 - { git add .   [ou]    git add <nome-arquivo-1>  /  git add <nome-arquivo-2>  /  .......
09 - { git status
10 - { git commit -m "primeiro commit"
11 - { git status
12 - Entrar no GitHub
13 - Clicar em your profile; clicar em repositories; clicar em new; 
14 - Preencher repository name e description; clicar em create repository
15 - Copiar link do repositório (repositories / entra no repositorio / code / copiar)
16 - Ir para o Git Bash
17 - { git remote add origin <link-do-repositorio>  (SÓ USA UMA VEZ)   ("origin" --> Apelido.Repositório)
18 - { git push -u origin <main>  ("origin" --> Apelido.Repositório)
19 - Fazer login no GitHub, Autorizar credenciais OU fazer processo do video a seguir. https://www.youtube.com/watch?v=s-CN4RaNq8A
20 - Dar refresh na página; visualizar primeiro commit no repositório


APÓS ALTERAÇÕES OU CONTINUAÇAO DO PROJETO
01 - Criar os arquivos onde será desenvolvido o projeto (index.html, style.css, novobotao.html)
02 - git status
03 - { git add .   [ou]    git add <nome-arquivo-1>  E/OU  git add <nome-arquivo-2>  /  e por ai vai.....  
04 - { git status
05 - { git commit -m "<texto-informando-as-alterações>"
06 - { git push origin main  ("origin"-->Apelido.Repositório)


CRIANDO UM NOVO BOTÃO
01 - Ir na pasta onde está o projeto; clicar com botão direito na pasta; clicar em "quick actions"; clicar em "open in vscode"
02 - Criar arquivo "NovoBotao.html"
03 - Ir na pasta onde está o projeto; clicar com botão direito na pasta; clicar em "services"; clicar em "new terminal at folder"
04 - Realizar todo o projeto e após terminar.......
05 - { git checkout -b "<novo-botao>"
06 - { git add .
07 - { git commit -m "<novo botão>"
08 - { git push origin <novo-botao>   ("origin" --> Apelido.Repositório)
09 - Após ter feito todas as alterações, terminado o projeto e testado.......
10 - { git add .
11 - { git commit -m "<novo botão>"
12 - { git push origin <novo-botao>   ("origin" --> Apelido.Repositório)
13 - { git checkout main
14 - { git merge <novo-botao>
15 - { git push origin main


CLONAR UM REPOSITÓRIO
01 - Entrar no perfil que está o repositório que você quer clonar
02 - Clicar em "Repositories"; clicar no repositório; clicar no botão verde "Code"; Copiar o link "https"
03 - Criar uma pasta no computador para receber o repositório clonado
04 - Clicar com botão direito na pasta; clicar em "services"; clicar em "new terminal at folder"
05 - { git clone <link do repositório>
SE QUISER ATUALIZAR NA SUA MÁQUINA O REPOSITÓRIO CLONADO
01 - Abrir a pasta do repositório clonado; clicar com botão direito na pasta; clicar em "services"; clicar em "new terminal at folder"
02 - { git pull


FAZER UM PULL REQUEST EM UM REPOSITÓRIO DE ALGUÉM
01 - Entrar no perfil que está o repositório que você quer fazer o pull request
02 - Clicar em "Repositories"; clicar no repositório que você quer fazer o pull request; clicar no botão "Fork"
03 - Fazer o Fork do repositório que você quer fazer o pull request
04 - Clicar em your profile; entrar no repositório que você fez o Fork
05 - Fazer a alteração que você achou necessária
06 - Fazer o commit
07 - Clicar no nome do repositório; clicar em "contribute", clicar em "open a pull request"
08 - Clicar em "create pull request"
09 - Fazer comentário informando: qual alteração foi feita; o motivo da alteração; como testa essa alteração
10 - Clicar em "create pull request"

ACEITAR UM PULL REQUEST EM UM REPOSITÓRIO MEU
01 - Clicar em your profile; 
02 - Clicar em "Repositories"; clicar no repositório que você deseja; clica em "Pull requests"
03 - Clicar em um dos pull requests; clicar em "Merge pull request" OU "Close pull request"