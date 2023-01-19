# **Lista de principais comandos GIT**

## Criar novo repositorio
  
git init

-----------
## Verificar Status dos arquivos/diretorios

git status

-----------
## Adicionar arquivo/diretorio

git add . 

-----------
## Comitar arquivo/diretorio

git commit meu_arquivo -m "mensagem"

-----------

## Remover arquivo/diretorio

git rm  meu_arquivo  
git rm -r diretorio

-----------
## Vizualizar historico

git log

-----------
## Eviar arquivos para repositorio remoto

git push -u origin main  
git push

-----------
## Clonar repositorio remoto existente 

git clone link_repositorio

-----------------

# **Branches**

## Cria novo branch

git branch nome_da_branch

-----------------

## Trocar para branch ja existente

git checkout nome_da_branch

----------

## Criar novo branch e trocar 

git checkout -b nome_da_branch

----------

## Mesclagem 

git merge nome_da_branch