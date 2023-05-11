# Projeto API serverless framework AWS 

## Exercício AWS Cloud bootcamp DIO.me
  <div align="center">
    <table>
      </tr>
            <td>
                <a  href="https://www.linkedin.com/in/robinsonbrz/">
                Implementação do exercício por Robinson Enedino
            </td>
        <td>
            <a  href="https://www.linkedin.com/in/robinsonbrz/">
            <img src="https://raw.githubusercontent.com/robinsonbrz/robinsonbrz/main/static/img/linkedin.png" width="30" height="30">
        </td>
        <td>
            <a  href="https://www.linkedin.com/in/robinsonbrz/">
            <img  src="https://avatars.githubusercontent.com/u/18150643?s=96&amp;v=4" alt="@robinsonbrz" width="30" height="30">
        </td>
        <td>
            <a href="mailto:robinsonbrz@gmail.com">
            <img src="https://raw.githubusercontent.com/robinsonbrz/robinsonbrz/main/static/img/gmail.png" width="30" height="30" ></a>
        </td>
      </tr>
    </table>
  </div>

Objetivos:
- Utilizar a plataforma AWS
- Implementar Roles em um serviços AWS
- Utilizar diferentes serviços AWS Cloud
    - API Gateway
    - AWS Cloud Formation
    - AWS Lambda
    - AWS DynamoDB

        <td>
            <a href="mailto:robinsonbrz@gmail.com">
            <img src="https://github.com/robinsonbrz/dio-aws/img/Aws-serverless.png" width="1260" height="255" ></a>
        </td>    
    Aws-serverless.png

Serviços AWS configurados e deploy gerenciados utilizando o framework serverless, infraestrutura como código

O resultado final é um CRUD com os principais verbos HTTP en uma API, que lê escreve e atualiza em um banco de dados NoSQL DynamoDB

___

Comando inicial teste da API
```bash
curl https://8ghetrhvik.execute-api.us-east-1.amazonaws.com/
```
endpoints:

  POST - Insert Items   - https://248bgyiy4c.execute-api.us-east-1.amazonaws.com/dev/item

  GET  - Lista Items   - https://248bgyiy4c.execute-api.us-east-1.amazonaws.com/dev/items

  GET  - Get 1 item     - https://248bgyiy4c.execute-api.us-east-1.amazonaws.com/dev/items/{id}

  PUT  - Update Items   - https://248bgyiy4c.execute-api.us-east-1.amazonaws.com/dev/items/{id}

  GET  - check endpoint - https://8ghetrhvik.execute-api.us-east-1.amazonaws.com/

lambda functions:

  api: dio-serverless-dev-api

  insertItem: dio-serverless-dev-insertItem

  fetchItems: dio-serverless-dev-fetchItems

  fetchItem: dio-serverless-dev-fetchItem

  updateItem: dio-serverless-dev-updateItem

 <h1 align="center"> Informações e contato </h1> 
  <div align="center">
    <table>
        </tr>
            <td>
                <a  href="https://www.linkedin.com/in/robinsonbrz/">
                <img src="https://raw.githubusercontent.com/robinsonbrz/robinsonbrz/main/static/img/linkedin.png" width="40" height="40">
            </td>
            <td>
                <a  href="https://www.linkedin.com/in/robinsonbrz/">
                <img  src="https://avatars.githubusercontent.com/u/18150643?s=96&amp;v=4" alt="@robinsonbrz" width="40" height="40">
            </td>
            <td>
                <a href="mailto:robinsonbrz@gmail.com">
                <img src="https://raw.githubusercontent.com/robinsonbrz/robinsonbrz/main/static/img/gmail.png" width="40" height="40" ></a>
            </td>
        </tr>
    </table> 
  </div>
  <br>
    dio-aws
</div>