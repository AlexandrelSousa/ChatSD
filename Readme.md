# ChatCafé

[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](http://forthebadge.com)

### Descrição do projeto
Neste projeto, desenvolvi um `sistema de chat distribuído`. Então será criado um servidor web que realizará o envio e recebimento de mensagens em tempo real. As informações dos usuários e as mensagens serão armazenadas na memória temporaria do navegador, sendo assim só estarão disponíveis enquanto o sistema estiver rodando. Para o desenvolvimento desta aplicação pretendo usar o `Node/JavaScript`, `Socket.io` e o `ReactJS/JavaScript` no front.
Usarei como base o vídeo tutorial do canal `Bruno Castro` da plataforma Youtube intitulado `Como fazer um CHAT EM TEMPO REAL utilizando WEBSOCKETS com REACT E NODE.JS`. https://youtu.be/Yi2crLU9WA0?si=2RBhfD9BhhNEEzw2.

### Tecnologias usadas
* JavaScript
* NodeJS 20.10.0
* npm 10.2.3

### Dependências
* express 4.18.2
* socket.io 4.7.2

### Clonar o repositório
* Para clonar o repositório, abra seu terminal e execute o comando `git clone https://github.com/AlexandrelSousa/ChatSD.git`

### Executar o projeto
#### Passo 1: Instalar o node
Para instalar o nodeJS na sua máquina basta ir até o site `https://nodejs.org/en`, selecionar seu navegador e seguir as instruções de instalação do site. Para verificar se está tudo devidamente instalado, abra um terminal e digite `npm -v`, se a mensagem for uma versão do npm é porque tudo foi instalado com êxito.
#### Passo 2: Instalando todas as dependências
Com o projeto devidamente clonado na sua máquina, abra um terminal e navegue por seus diretorios até a pasta do projeto, com ela aberta, digite no terminal `npm install .`, isso instalará todas as dependências necessárias para rodar o seu projeto.
#### Passo 3: Rodando o projeto
Ainda com a pasta do projeto aberta no seu terminal, rode o comando `npm run dev` e abra seu navegador com o localhost na porta em que seu projeto está rodando.

