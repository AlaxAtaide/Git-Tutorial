# Git-Tutorial
Aqui ensino como utilizar o Git, em um passo a passo!

Git comandos: 
Lógica: Primeiro de tudo precisamos entender a estrutura do git, primeiramente antes de tudo, abrimos nosso projeto dentro do Git Bash (Terminal do Git), dessa forma: 
 ![image](https://github.com/AlaxAtaide/Git-Tutorial/assets/100983643/ba903ee0-7075-4ef0-a6cd-4e09542f71d5)

APÓS ISSO, tudo que fizermos a seguir será colocar nossos arquivos no nosso primeiro controle de versão, isso é, iremos pegar os arquivos que queremos levar para o Github, e iremos alocar no servidor do Git, isso é, iremos listar tudo o que queremos, antes de subir para o repositório em questão. Após dizermos ao Git com os comandos utilizados, o que queremos de fato, quais arquivos queremos enviar, o que é para ser ignorado ou não no projeto etc. Após tudo isso feito, estará tudo armazenado no Git, com todos os passos que fizemos antes, agora é só dar nossos commit para realmente enviar esses arquivos para o servidor do GitHub, e depois disso, podemos assim usar por fim o “Git Push” que vai de fato enviar seu projeto/alterações feitas, para o seu repositório do Github de fato.
PRIMEIROS PASSOS: 
Caso você ainda não tenha configurado seu git, execute os seguintes comandos:
Git config --global user.email “meuemail@gmail.com”
Git config --global user.name “Seu Nome”

OBS: Isso é para que fique registrado seu usuário no Git, assim quando você fizer alguma alteração no repositório, estará registrado quem fez tal ação, com o nome/email do usuário.
SEGUNDO PASSO: 
Você deve ir primeiramente ao seu GitHub, ir ao repositório que deseja trabalhar e copiar a URL do repositório, feito isso, ir novamente ao GitBash/Terminal, e executar o seguinte comando com essa URL que você acabou de copiar, segue exemplo:
“Git remote add origin https://github.com/Usuario/Project” 
![image](https://github.com/AlaxAtaide/Git-Tutorial/assets/100983643/3ee96ed9-e43f-4526-bde6-33f18e3cba61)

 

Comandos iniciais:

“git init”** – Comando para iniciar o git em seu projeto/aplicação.
“git add “MeuArquivo.java”” – Comando para adicionar um arquivo específico do seu projeto ao controle de versão, (caso queira adicionar todos os arquivos do seu projeto uma única vez, segue o próximo passo, da pág 2).
“git status” – Comando para verificar o status da aplicação/comando anterior.

OBS: Como na maioria dos casos já queremos enviar todo o projeto para o nosso repositório, utilizamos mais o “git add .” que você verá logo a seguir...

“git add .” – Comando para adicionar todo o projeto (todos os arquivos do seu projeto de uma única vez) no controle de versão.
“git commit -m “primeiro commit”” – Assim como ao salvar um arquivo que foi editado, um commit registra alterações em um ou mais arquivos no seu Branch.
OBS: Este comando é de extrema importância, pois é ele que registra a primeira versão do seu projeto, e outras versões, então a cada mudança feita, você precisa dar o commit para criar um registro da nova versão, sempre utilizando as aspas “”, para dizer o que você está registrando com aquele commit. Esse (-m “primeiro commit”), é a mensagem do seu registro, “-m” significa mensagem. 
“commit -m add git” – Comando para fazer o “POST” o envio do projeto/alterações feitas nele, para o servidor de aplicação (Github).
“Git push –set-upstream origin master” 
Agora precisamos dizer ao git qual repositório queremos trabalhar, ele irá te pedir para logar em sua conta do Github que você quer trabalhar nesse caso, e pedirá para escolher qual o repositório que será trabalhado, veja só:

