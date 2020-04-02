# Cubic Code

[Video](https://www.youtube.com/watch?v=RomSuHEdDZg)

## Iniciando (Starting)

### PT-BR

Para executar este código, basta digitar os comandos a seguir no terminal:

```
yarn
yarn start
```

Rotas disponíveis:

### EN-US

To execute this code, just type the following commands at the terminal:

```
yarn
yarn start
```

## Como utilizar (How to use)

### PT-BR

As rotas disponíveis para uso são:

- GET: /products
  -- Lista todos os produtos disponíveis
- GET: /products/:id
  -- Lista o produto do id especificado
- POST: /products
  -- Cria e retorna o produto com id automático e com as informações do corpo abaixo:

```
{
  "name": "Product Name",
  "price": 1.11
}
```

### EN-US

The available routes for use are:

- GET: /products
  -- List all available products
- GET: /products/:id
  -- List a product with the id provided
- POST: /products
  -- Creates and returns a product with automatic id and with the body information below:

```
{
  "name": "Product Name",
  "price": 1.11
}
```
