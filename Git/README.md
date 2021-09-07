# git

### Estudos
## DESCOMPLICANDO O GITLAB | CERTIFICAÇÃO GITLAB
## Primeria aula 
- https://www.youtube.com/watch?v=SMzaAP09BD4&list=RDCMUCJnKVGmXRXrH49Tvrx5X0Sw&start_radio=1

## Segunda Aula 
- https://www.youtube.com/watch?v=fkfWcPZUd4Y

## GITFLOW - SEJA O NINJA SUPREMO NO GIT! (super importante e prático!) 
- https://www.youtube.com/watch?v=dJjVr6Ya7B8

## Treinamento oficial Git 
- https://gitlab.edcast.com/pathways/copy-of-gitlab-certification/cards/1411246


## Curso de Git para iniciantes 
- https://www.youtube.com/watch?v=WVLhm1AMeYE&list=PLInBAd9OZCzzHBJjLFZzRl6DgUmOeG3H0

## Como usar Git e Github na prática 
- https://www.youtube.com/watch?v=2alg7MQ6_sI

## CURSO COMPLETO DE GIT (2 HORAS E 30 MINUTOS) 
- https://www.youtube.com/watch?v=OuOb1_qADBQ

## Link Git oficial 
- https://git-scm.com/book/pt-br/v2

### Entendendo os stages
Working Dir -> Não está sendo gerenciado pelo GIT 
Index/stage -> com o git add o arquivo já é visto pelo GIT cuidar
Head -> Commitar o arquivo para GIT 


### COMANDOS 

## git init // inicia a linha do tempo

## git add // adiciona ou atualiza mudanças para irem para a linha do tempoo

## git commit // adiciona um ponto na linha do tempo
- git commit -m = mensagem "nmomeedoarquivio"
- git commit -m = mensagem *
- git commit -am "arquivo" - já faz o add e o commit

## git log // visualiza os pontos na linha do tempo / commit
- git log -> p/ todos os logs
- git log -"qde logs" -> p/ a qde de logs que quer ver: ex: git log -1
- git log --oneline -> traz por linha (1 linha)
- git log --author="quem fez" -> por autor
- git log --graph --decorate -> traz separado os logs

## git status // informa o estado das alterações do nosso projeto

## git show // apresenta determinado ponto na história
- git show <commit>

## git branch // gerenciar novas linhas do tempo

## git checkout // manipula as linhas do tempo
- git checkout -- cart.html - recuprar o arquivo no ultimo ponto da historua
- git checkout -b <nova_branch>

## git merge // unir linhas do tempo

## git push // envia alterações locais para o repositório remoto
- git push -u origin <branch>
- git push origin <nova_branch>

## git clone // clonar um projeto / repositório
- git clone "nomedorepo" - Clona repositorios 

## git pull // puxa do repositório remoto

## git config
- git config --global core.editor "vim"
- git config credential.helper store
- git config --global "user.name"
- git config --global "user.email"
- git config --global core.editor

## git rm - Remove arquivo

## git checkout master

## git remote -v - para verificar repositorios remotos

## Criando um novo repo GIT
- Push an existing folder
- cd existing_folder
- git init -> inica o GIt para o track
- git remote add origin <<nome_do_repo> -> adicionar o servidor remoto
- git add .
- git commit -m "Initial commit"
- git push -u origin main

