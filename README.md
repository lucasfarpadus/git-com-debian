git-com-debian
==============

Primeiro projeto para code.education
------------------------------------

###Passos para chegar até o primeiro *push*

1. Configuração local do GIT:  
   Considera-se o GIT já configurado com o nome de usuário, email e repositório
   local na pasta "git-com-debian" com os comandos na seguinte ordem:

   ```
   git config --global user.name "Lucas Espinosa"
   git config --global user.email l_b_e@live.com
   mkdir git-com-debian
   cd git-com-debian
   git init

   ```

2. Comandos até o primeiro commit:  
   Considera-se o diretório atual sendo "git-com-debian".

   ```
   touch README.md
   nano README.md
   ```
+ Nesse ponto edita-se o arquivo incluindo o conteúdo do documento presente.  
+ Logo após ser salvo com as devidas edições, passa-se para a série de comandos para chegar até o primeiro *commit*

   ```
   git add .
   git commit -m "Adicionando o Arquivo README.md"
   ```

3. Chegando ao *push*  
   Nessa parte considera-se criada a conta no GitHub com a devida chave de autenticação criada no Git.  

  1. Cria-se um novo repositório no GitHub com o nome "git-com-debian".  

  2. Com o seguinte comando, cria-se o vínculo do repositório local com o GitHub.  

   ```
   git remote add origin https://github.com/lucasfarpadus/git-com-debian.git  
   ```

  3. Com esse último comando chega-se ao objetivo.  

   ```
   git push origin master
   ```

