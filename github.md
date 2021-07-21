# Dicas de Git e Github para Linux





## clonar um projeto remoto

$ git clone https://github.com/padoinedson/tips.git






## list servidor remoto

$ git remote -v



## copiar as modificações do servidor para o repositório local

$ git pull




## adicionando arquivo
 
$ echo "#include" >> a.c

$ git add a.c 

$ git status

$ git commit -m "criado arquivo a.c"

$ git push -u origin main



------------------------------------------------------------
alterando arquivos
------------------------------------------------------------
 


$ echo "# pp2021" >> README.md

$ git diff

$ git add README.md 

$ git commit -m "alterado c.c"

$ git push -u origin main





++++++++++++++++++++++++++++++++++++++++++++
branch
++++++++++++++++++++++++++++++++++++++++++++

$ git checkout -b "teste-de-funcionlidade"

cria arquivos
edita arquivos

$ git add d.c 

$ git commit -m "alterado d.c"

$ git push -u origin teste-de-funcionlidade


------------------------------------------------------------
trocar de branch
------------------------------------------------------------
$ git checkout main

trabalha

$ git checkout teste-de-funcionlidade





++++++++++++++++++++++++++++++++++++++++++++
branch
++++++++++++++++++++++++++++++++++++++++++++

deve estar trabalhando no main
$ git checkout main

$ $ git merge teste-de-funcionlidade