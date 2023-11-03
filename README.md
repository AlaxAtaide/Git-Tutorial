
# Git-Tutorial

Aqui ensino como utilizar o **Git**, em um passo a passo! **Me siga em meu Github para novas atualizações de comandos e novidades!** 🧙	👌

## Introdução

O Git é uma poderosa ferramenta de controle de versão amplamente usada por desenvolvedores para atualizar e gerenciar as alterações em seus projetos de software. Este tutorial fornece um guia passo a passo para começar a usar o Git e trabalhar com repositórios Git no GitHub.

## Configuração Inicial

Primeiramente, antes de tudo, devemos abrir nosso projeto dentro do Git Bash (Terminal do Git). Dessa forma:
![280385981-ba903ee0-7075-4ef0-a6cd-4e09542f71d5](https://github.com/AlaxAtaide/Git-Tutorial/assets/100983643/5a0086da-fcf5-4223-b6de-80b41754a48b)


Feito isso, agora antes de começar, você deve configurar suas informações de usuário no Git. Isso permitirá que o Git registre suas alterações com seu nome e email. Execute os seguintes comandos:

```shell
git config --global user.email "seuemail@gmail.com"
git config --global user.name "Seu Nome"
```

Agora que você está configurado, vamos começar!

## Criando um Repositório

Primeiro, você precisará criar um repositório Git para seu projeto. No GitHub, vá para a página do seu perfil e clique em "New" para criar um novo repositório. Anote a URL do repositório criado, pois você a usará mais tarde.

## Inicializando o Git

Em seu terminal (Git Bash que haviamos aberto com nosso projeto no passo anterior), e execute o seguinte comando para inicializar o Git:

```shell
git init
```

Isso criará um repositório Git vazio em seu projeto.

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

Agora, você pode enviar suas alterações para o repositório remoto no GitHub:

```shell
git push -u origin master
```

Isso enviará seus commits para o GitHub, onde seu código será armazenado no repositório correspondente.

Agora você está pronto para começar a trabalhar com o Git e o GitHub. Continue a criar novos commits para atualizar e gerenciar seu projeto. Este tutorial é um guia inicial, e há muito mais a aprender sobre o Git.

```
Espero que este tutorial passo a passo atenda às suas necessidades.
E claro, lembre-se de me seguir para apoiar atitudes como essa! logo menos trago mais tutoriais!! 😉💯
