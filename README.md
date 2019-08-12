Criação da API para Teste na Digitalk.

1.	Criei a pasta principal e dei o Npm Init, dei o nome de teste.
2.	Arquivo server.js criado.
3.	Instalei os pacotes http, express e debug, criando assim a pasta node_modules.
4.	Dentro do arquivo Server.js com o intuito de criar um servidor web, especifiquei a rota para o endereço localhost:3000/ e logo em seguida fiz a normalização da porta.
5.	Efetuei o teste via Postman e tive como retorno:
{
"title": "Node Store APi",
"version": "0.0.1"
}

6.	Acrescentei no arquivo Server.js a função: functionOn Error, para poder gerencia os erros.
7.	Ainda dentro do arquivo server.js acrescentei a função para ativar o Debug.
8.	Criei a pasta bin e dentro dela fiz um outro arquivo server.js, onde copiei o conteúdo do 1 arquivo server, e eliminei algumas linhas que ficarão desnecessárias.
9.	Criei a pasta src e dentro dela o arquivo app.js onde defini por hora a rota para o servidor.js.
10.	Dentro do arquivo Package.json configurei o npm start. Ate o momento estava usando o node + o arquivo.
11.	Logo em seguida fiz a instalação e a configuração do nodemon na versão dev, para efetuar a atualização dos arquivos de forma automática e não ter que ficar dando npm start.
12.	Acrescentei a linha de const create na rota post dentro do arquivo App.js, redirecionando para o localhost:3000/products.
13.	Instalei o body-parser para reconhecer as informações colocada nos postam via postman.
14.	Acrescentei a linha de const put na rota put no arquivo App.js.
15.	Acrescentei a linha de const del na rota delete no arquivo App.js.
16.	Dentro da pasta src criei a pasta routes, onde fiz o arquivo index.js. Coloquei a linha da rota do get e para deixar o arquivo app com menos linhas e mais simples de resolver algum problema.
17.	Dentro do app.js coloquei a const index para chamar a rota.
18.	Criei o arquivo products.js, onde anexei as rotas para o post, put e delete.
19.	Dentro do app.js coloquei a const products para chamar a rota.
20.	Para evitar confusão futuras, alterei os arquivos pra index-route e product-route.
21.	Criei a pasta controllers dentro do src e fiz o arquivo product-controllers, onde joguei as informações da rota do post, put e delete. Visando assim deixar o mais separado possível as rotas para um melhor controle e organização.
22.	Via site do mongodb criei um banco de dados para armazenar as informações.
23.	Via npm install, efetuei a instalacao do mongoose para a API conversar com o banco de dados.
24.	Dentro do arquivo app.js da pasta src, acrescentei a linha const mongoose, bem como o mongoose.connect, para efetuar a conexão com o banco de dados.

