
!====== Adicionando configuraçãoes iniciais ======!

   comandos:

     git config --global user.name  "<seu nome>"
     git config --global user.email "<seu email>"


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

   comandos:

    git log

    git log --graph

!===== As mudanças ocorridas em um arquivo podem ser vistas com o comando diff =====!

  comando:

   git diff

   observação: Esse comando deve ser usado antes de mandar as informações para o estado
               staged, ou seja, quando o estado do arquivo ainda é modified.

!===== Agora poderemos associar nosso repositório local ao repositório remoto  =====!

!==== É claro, se o repositório remoto já estiver sido criado, poderemos associar o
      repositório local com o remoto pelo comando abaixo                       =====!

  comando:
  
    git remote add origin https://{...} 


!===== Mandando arquivos para repositório GITHUB por exemplo ======!

   comando:

    git push -u origin master 


!===== Clonando repositórios online =====!

   comandos:

    git clone "<https do repositório remoto>" "<nome do arquivo/diretório>"

!===== Verificando status de um repositório remoto =====!

   comando:
    
    git remote show origin  

!===== Atualizando repositório local a partir de um repositório remoto =====!

  comando:

    git pull      
