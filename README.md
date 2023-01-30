# Next.js CpanaxJira App

Para correr localmente, se necesita la base de datos.

## Configurar las variables de entorno

Renombrar el archivo **.env.template** a **.env**

- MongoDB URL Mongo Atlas:

```
MONGO_URL=
```

- Reconstruir los módulos de node y levantar Next

```
yarn install
yarn dev
```

## Llenar la base de datos con información de pruebas

Llamara:

```
http://localhost:3000/api/seed
```
