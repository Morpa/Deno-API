# Deno REST API
> This is a simple REST API using Deno and Oak. It is part of my YouTube crash course. I will be adding database functionality and JWT to it in the near future

## Run
```
deno run --allow-net server.ts
```

## Routes
```
GET      /api/products
GET      /api/products/:id
POST     /api/products
PUT      /api/products/:id
DELETE   /api/products/:id
```