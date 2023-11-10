
# Git-Tutorial

Aqui ensino como utilizar o **Git**, em um passo a passo! **Me siga em meu Github para novas atualizações de comandos e novidades!** 🧙	👌

## Introdução

O Git é uma poderosa ferramenta de controle de versão amplamente usada por desenvolvedores para atualizar e gerenciar as alterações em seus projetos de software. Este tutorial fornece um guia passo a passo para começar a usar o Git e trabalhar com repositórios Git no GitHub.

## Criando um Repositório

Primeiro, você precisará criar um repositório Git para seu projeto. No GitHub, vá para a página do seu perfil, na aba "**Repositories**", clique em "**New**" para criar um novo repositório. Após preencher com informações do Repositório, clique em "**Create Repository**" ao finalizar! Por fim, anote a URL do repositório criado, pois você a usará mais tarde.
![image](https://github.com/AlaxAtaide/Git-Tutorial/assets/100983643/4a202674-a877-44f5-83db-29dcdd88d354)

Após ter o repositório criado, vamos para os próximos passos para adicionar o seu projeto dentro dele! ⬇

## Configuração Inicial

Primeiramente, antes de tudo, devemos abrir nosso projeto dentro do Git Bash (Terminal do Git). Dessa forma:
![280385981-ba903ee0-7075-4ef0-a6cd-4e09542f71d5](https://github.com/AlaxAtaide/Git-Tutorial/assets/100983643/5a0086da-fcf5-4223-b6de-80b41754a48b)


Feito isso, agora antes de começar, você deve configurar suas informações de usuário no Git. Isso permitirá que o Git registre suas alterações com seu nome e email. Execute os seguintes comandos:

```shell
git config --global user.email "seuemail@gmail.com"
git config --global user.name "Seu Nome"
```

Agora que seu usuário está configurado, vamos começar!

## Inicializando o Git

Em seu terminal (Git Bash que haviamos aberto com nosso projeto no passo anterior), execute o seguinte comando para inicializar o Git:

```shell
git init
```

Isso criará um repositório Git vazio em seu projeto.

## Ignorando arquivos/pastas do projeto não utilizáveis

#### Antes de irmos para o passo de adicionar arquivos, o ideal é primeiro informar quais arquivos do nosso projeto não queremos levar para o repositório.
                                                                                                                                              
Para dizer ao GitHub que você não quer que algum arquivo ou pasta do seu projeto seja incluso no repositório do Github, você pode criar um arquivo ".gitignore". Neste arquivo você pode dizer exatamente os arquivos ou pastas que não serão enviados ao repositório!

### **Primeiramente crie o arquivo ".gitignore" dentro do seu projeto:**
```shell
nano .gitignore
```

### **Após a criação do arquivo ".gitignore" liste os arquivos ou pastas que deseja ignorar:**

![image](https://github.com/AlaxAtaide/Git-Tutorial/assets/100983643/7658da44-d582-4ac6-885e-b3dbdb34e5c4)

Feito isso pressione **CTRL + X**, irá aparecer uma mensagem **"Save modified buffer?"**, digite **"y"** e dê enter, ao fazer isso será criado o arquivo **".gitignore"** com os arquivos/pastas que você deseja ignorar! Prontinho, agora quando for feito novos commits do seu projeto estes arquivos dentro do ".gitignore" não serão inclusos! 

![image](https://github.com/AlaxAtaide/Git-Tutorial/assets/100983643/cd8d2d3d-b196-4eee-a0ce-0508ec60cfae)

#### • Comando para verificar quais arquivos ou pastas estão sendo ignorados (caso queira verificar pelo próprio terminal):

```shell
git check-ignore -v *
```

Feito todos esses passos, vamo prosseguir e finalmente adicionar os arquivos do nosso projeto ao repositório!

## Adicionando Arquivos

Agora você pode adicionar arquivos ao controle de versão do Git.  Se você deseja adicionar todos os arquivos do projeto de uma única vez, use:

```shell
git add .
```
Dessa forma adicionará todo o seu projeto ao repositório sem precisar adicionar um por um! 😏 

Em casos que você precise adicionar um arquivo **específico**, use o seguinte comando:

```shell
git add MeuArquivo.java
```
Dessa forma você irá adicionar somente esse arquivo ao repositório!


## Verificando o Status

Para verificar o status dos arquivos em seu projeto, execute o seguinte comando:

```shell
git status
```

Isso mostrará quais arquivos foram modificados e estão prontos para serem confirmados.

## Fazendo um Commit

Agora, é hora de fazer um commit para registrar suas alterações. Use o seguinte comando:

```shell
git commit -m "Mensagem do Commit"
```

Certifique-se de fornecer uma mensagem descritiva que explique as alterações realizadas neste commit.

## Conectando ao Repositório Remoto

Você precisará conectar seu repositório local ao repositório remoto no GitHub. Use a URL do repositório que você criou anteriormente com o seguinte comando:

```shell
git remote add origin https://github.com/Usuario/Project
```
![image](https://github.com/AlaxAtaide/Git-Tutorial/assets/100983643/3ee96ed9-e43f-4526-bde6-33f18e3cba61)

## Enviando as Alterações

Como pode ver no seu Github, dentro do seu repositório. Podemos ter duas branches, temos por padrão a "Main" e a "Master" que podemos criar com o comando **" git push -u origin master "**. Devemos escolher qual das duas branches queremos que fique armazenado nosso projeto!

![image](https://github.com/AlaxAtaide/Git-Tutorial/assets/100983643/f2c4c181-8c92-4a7b-b834-eaae352a0ce8)

### Mas o que exatamente é uma Branch?

Uma **"branch"** é uma ramificação, no **Git** **é como uma linha separada** de desenvolvimento em um projeto de software. Pense nisso como um **caminho isolado** onde **você pode fazer alterações no código sem afetar diretamente o trabalho principal**. Quando as mudanças em uma **branch** são testadas e estão prontas, elas podem ser combinadas de volta à "branch" principal, chamada de **"master"** ou **"main"**, para incorporar essas alterações ao projeto geral. Isso permite que diferentes partes do projeto evoluam independentemente antes de serem unidas.

Sabendo disso, agora você pode enviar suas alterações para o repositório remoto no GitHub, apenas escolha para qual branche é de sua escolha:

#### Enviando as Alterações para a branche Master
```shell
git push -u origin master
```

#### Enviando as Alterações para a branche principal, "Main"
```shell
git push -u origin main
```

(Após isso é provavel que apareça uma tela de Login do Github! logue sua conta que será trabalhado, após isso o comando deve funcionar).

#### Isso enviará seus commits para o GitHub, onde seu código será armazenado no repositório correspondente.

Agora você está pronto para começar a trabalhar com o Git e o GitHub. Continue a criar novos commits para atualizar e gerenciar seu projeto. Este tutorial é um guia inicial, e há muito mais a aprender sobre o Git.

```
Espero que este tutorial passo a passo atenda às suas necessidades.
E claro, lembre-se de me seguir para apoiar atitudes como essa! logo menos trago mais tutoriais!! 😉💯
