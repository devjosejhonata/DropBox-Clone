PROJETO DROPBOX CLONE

- O dropbox é fazer o upload de arquivo e armazenar na nuvem, e poder baixar o arquivo, organizar pasta, abrir diretório... Na pasta principal do projeto tem uma imagem explicando a arquitetura do dropbox.

- Nesse projeto, tive que instalar o bower.json, utilizando o npm install -g bower, depois de instalando, executei o comando bower install. O bower vai ler o arquivo json dele e baixar as dependencias do front-end.

- Express ja estava instalado de outro projeto, npm install express-generator. 
- Após certificar que estava instalado, executei o comando express --ejs, para criar as views, e o nome do aplicativo na frente, no caso app, ficando assim: express --ejs app.
- Ao gerar a pasta app, eu acessei a pasta e executei o comando: npm install, para gerar as dependencias.
- Dentro da pasta public, vai estar nossos css, bower components.
- O arquivo controller do projeto também esta na pasta public, dentro da pasta src.
- o arquivo html do projeto esta na pasta views com o nome de index.ejs.


-- Projeto utilizando o firebase como banco de dados.
-- Os arquivos fisicos serao armazenados no storage do firebase, nao é ideal armazenar arquivos fisicos em banco de dados por questão de performance, mas o firebase nao é só banco de dados e tem tambem serviço armazenamento de arquivos.

-- subir o arquivo no servidor localhost:3000 utilizando npm start.

-- Funcionalidades do projeto: upload, carregando, criando pastas, renomear, excluindo.



