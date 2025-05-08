# Bootcamp #001 Qualiters Club
Criação de testes de API utilizando Postman, manual e CI/CD

## O que é
Este repositório foi para criado para teste de API Rest com base no Bootcamp

## Tecnologia utilizadas

- Postman plugin vsCode ou Postman Web

- Noje.js v22.15.0

- NPM v.10.9.2

- Newman v.6.2.1

- Newman Report HTML
  
- Newman Report HTMLExtra

## Documentação
Documento da API: [consulte o Swagger](https://serverest.dev/#/)

## Como instalar o ambiente
1. Instale o plugin Postman [Link do Postman](https://marketplace.visualstudio.com/items/?itemName=Postman.postman-for-vscode "Postman for VSCode")
2. Instale o node.js baixando pelo o link ao lado [Link do Node.js](https://nodejs.org/en/download)
3. Instale o NewMan de forma global [Documentação para Instalar](https://www.npmjs.com/package/newman)
   
   `npm install -g newman`

4. Instale o NewMan Reporter HTML [Documentação para Instalar](https://www.npmjs.com/package/newman-reporter-html)

   `npm install -g newman-reporter-html`

5. Instale o NewMan Reporter HTMLExtra [Documentação para Instalar](https://www.npmjs.com/package/newman-reporter-htmlextra)

   `npm install -g newman-reporter-htmlextra`

## Como rodar os testes

### Pelo Postman Web ou vsCode
- Import o arquivo de environment
- Import o arquivo de collection
- Execute os teste de forma manual ou automatizada

### Pelo Newman
- Abra o Terminal/CMD
- Execute a linha de comando:
- `npm install -g newman-reporter-html`
- newman run ServerRest.postman_collection.json -e ServerRest.postman_environment.json -r cli
- Caso queria executar os testes com retorno de relatórios execute a linha de comando:
- newman run ServerRest.postman_collection.json -e ServerRest.postman_environment.json -r htmlextra

### Report
Caso utilize o Newman com HTMLEXTRA, os relatórios se encontram no diretório **"..\..\ServerRestAPI\newman"** do local da execução dos teste.

## Entre em contato

viih.faria@gmail.com
