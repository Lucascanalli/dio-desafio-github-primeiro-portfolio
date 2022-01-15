#  Desafio  de Projeto  sobre Git/Github da DIO.
Repositorio criado para o Desafio de Projeto.
## Links Úteis
[Sintaxe Básica Markdown](https://www.markdownguide.org/basic-syntax/)
[Guia do GitHub PT-BR](https://docs.github.com/pt)
# Ola essa é somente uma anotação do que aprendi no curso Introdução ao Git/Github da DIO 

- Introdução oa Git e Git Hub	

  # 												Git

  - Outros repositorios : Bitkeeper, Cus, Subversion " Linus Benedict Torvalds odeia ".

  - Outros serviços iguais ao Git Hub: Bitbucket e Git Lab.

###           Aprendi no curso
    - Controle de versao.

    - Armazenamento em nuvem.

    - Trabalho em equipe.

    - Melhorar o seu codigo.

    - Reconhecimento.

      - CLI = Comando line interface "nao tem interface grafica" -Git.

      - GUI= Graphical User Interface. "tem interface grafica" -=.

      # 							Comando Windows	

      - cd = Entra na pasta .

      - dir = Lista os diretorios que esta no momento .

      - mkdir = criar diretorios "pasta".

      - rmdir = exclui diretorio.

      - cls = limpa a tela .

      - del = remove somente o arquivo " se usado dento da pasta remove os arquivos mas a pasta continua".

      - ls = lista o que tem dentro do diretorio 

        # 					Objetos internos do git 

        - Objetos fundamentais (blobs) = Os arquivos ficam guardados dentro desse arquivo e esse objeto contem metadados dentro dele.

        - Tree = Armazena blocos, metadados e arquivos tambem aponta para outras arvores   

          - Tree > Readme > Blob..       Tree > Rakefile > Blob..      Tree > Lib > Tree > Simplegit.rb > Blob

          Commit .

          - Tree > Criptografia.  Parente > Criptografia.  Autor > "o que voçe nomeou".  Mensagem "O que voçe colocou" >Temestamp.

            # 							Chave SSH

            - É uma forma de estabelecer uma conexão segura e encriptada entre 2 maquinas .

            - Gerando um SSH > Abra o Git Bash > Use o comando > ssh-keygen -t ed25519 -C email "seu email do github". 

              ## 					Comando dentro do git bash

              - ls = lista o que tem dentro do diretorio .

              - cat id publico = gera uma chave para colocar no git hub.

              - eval $ (ssh -agente -s) = comando para estarta um processo, "o ss agente esta rodando de fundo ".

              - ssh - add  " passar a chave privada , tem que estar dentro da pasta do id, depois colocar a senha que cadastrou."

              - git init = Iniciar o repositorio do Git.

              - git add = mover e começar a dar inicio ao versionamento .

              - git commit = usado para criar o commit .

              - ls -a = mostra arquivos ocultos "exemplo .git etc..".

              - git config -- global user.email "email" > serve para ter um autor atrelado ao commit quando criado. email

              - git config -- global user.name "nome" >o nome que ira aparecer no commit 

              - git commit -m " mensagem para saber o que tem no commit"

              -  git config -- global --unset user.name > apaga o nome do usuario 

              -  git config -- global --unset user.email > apaga o email do git

              - git remote add origin > add o repositorio no git hub atraves do html do repositorio criado no site.

              - git push origin master > ira pedir autenticaçao de 2 passos ativo 

                ## 									repositorios

                - Servidor > Remote Repository

                ## 						Ambiente de desenvolvimento

                - Working cirectory 
                - Staging area
                - Local repository
