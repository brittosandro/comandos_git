!=======  Iniciando repositório com o git =====!

   comando:

     git init

!======  Verificando o status do seu documento ======!

   comando:

     git status

!====== Depois de verificarmos o status de um documento deveremos adicionar o documento ======!

   comando:

    git add "<nome-do-arquivo>"

Quando um documento é adicionado para que o git o reconheça esse arquivo pode ser então comitado.

!====== Comitando um arquivo =====!

   comando:

    git commit -m "<adiciondo um comentario>"

!===== Verificando as saidas de um arquivo com o log =====!

   comando:

    git log

    git log --graph

!===== As mudanças ocorridas em um arquivo podem ser vistas com o comando diff =====!

  comando:

   git diff

   observação: Esse comando deve ser usado antes de mandar as informações para o estado
               staged, ou seja, quando o estado do arquivo ainda é modified.      
