
# Automatização de Testes em APIs REST com Postman

Implementação de cenários de teste, validação de respostas e automação de verificações em APIs públicas


## O que vamos usar?

Para os nossos exemplos, estarei utilizando, além da ferramenta *Postman*, a fake API *JSONPlaceholder*. 
LINK DA API: - https://jsonplaceholder.typicode.com/

- /posts	100 posts
- /comments	500 comments
- /albums	100 albums
- /photos	5000 photos
- /todos	200 todos
- /users	10 users

## 01 GET (todos os registros):
realizei uma requisição para obter todos os dados disponíveis, validando o status code e criando um script para verificar se a contagem de itens retornados estava correta.
<img width="1366" height="895" alt="01" src="https://github.com/user-attachments/assets/e0ea5a8e-dd6c-4503-b9ba-a78281e5dc2c" />

## 02 GET (por ID): 
testei a busca de um registro específico, garantindo que os dados retornados correspondessem ao ID solicitado.
<img width="1376" height="895" alt="02" src="https://github.com/user-attachments/assets/bb212b9d-c911-4e72-b24a-c49376a7af6a" />

## 03 PUT:
Efetuei a atualização de um recurso completo, modificando o campo body e validando a alteração.
<img width="1378" height="895" alt="03" src="https://github.com/user-attachments/assets/ca8dcae9-a52c-4f28-b139-e7b8be965ed4" />

## 04 PATCH:
Testei a atualização parcial, alterando apenas o campo desejado e enviando exclusivamente este no corpo da requisição.
<img width="1389" height="885" alt="04" src="https://github.com/user-attachments/assets/16a83121-c1d2-4696-9bf8-422f20d5af79" />

## 05 POST:
Criei um novo recurso enviando os dados no body, validando a criação e o retorno esperado.
<img width="1389" height="885" alt="05" src="https://github.com/user-attachments/assets/4be7376e-0e35-4c71-9d27-da4f94e4fca8" />

## 06 DELETE:
realizei a exclusão de um recurso específico a partir do ID, validando o status e confirmando que o item foi removido.
<img width="1389" height="885" alt="06" src="https://github.com/user-attachments/assets/75d2ba0a-60ab-4216-a96e-bc422865ce3e" />
