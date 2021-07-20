# API Dev Finance Utilizando JSON Server

Aplicação backend para armazenar, consultar, atualizar e deletar dados.

## Tecnologia
- NodeJS
- JSON Server

Retorna um array de objetos contendo:
```js
    "transactions": [
    {
      "id": 1,
      "description": "Internet",
      "amount": -130,
      "date": "10/08/2021"
    },
    {
      "id": 2,
      "description": "Luz",
      "amount": -110,
      "date": "10/08/2021"
    },
    {
      "description": "Criação Site",
      "amount": 6000,
      "date": "12/12/2021",
      "id": 3
    }
  ]
```
Rota GET: "http://localhost:3000/transactions"

## Inicar projeto
Instalar as dependencias
```npm install```

Executar o projeto
```node server.js```