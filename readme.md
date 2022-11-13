comandos do bash

- pwd: ver onde estou no computador 
- touch: criar um arquivo vazio 
- cd: me mover para outro lugar/directorio 
- echo: comando para escrever algo no terminal ou em um arquivo 

# comandos git 

git config --global --list:ver en lista as configuraçoes globais
git config --global user.name "nome":definir nome global 
git config --global user.email "imail@gmail.com" : definir email global 
git init: inici pela primeira vez o git em um projeto /pasta
git branch -m nomebranch : inicia pela primera vez um branch no projeto
 git branch -v :periti visualizar os branch de um projeto 
 git branch -a : permite visualizar os branch remotos (github)
 git status : permite ver o que esta acontecendo com os arquivos no git 
 git add: adicona os arquivos que foram modificados para serem rastreados pelo git 
 git add. :adicona todos os arquivos da pasta que estamos(veja pelo pwd)
 git add arquivo1 arquivo2 arquivo3  : adiciona um arquivo no git de acordo com o nome 

 git commit -m "mensagem commit" : criar o salvamento de minha versao localmente com uma mensagem de atualizaçao 

 git remote add origin https://github.com/josbert30/gitaulacomandos.git
 adiciona o repositorio do github com o nome de "origin" no meu git  

 git -h :exive a juda geral do git posso utilizar outro comando para ter informaçoes especificas daquele comando. ex:git remote -h
