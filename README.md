<div>
  <p align="center">
    <a
      href="http://nestjs.com/"
      target="blank">
        <img
          src="https://nestjs.com/img/logo-small.svg"
          width="200"
          alt="Nest Logo"/>
    </a>
  </p>
</div>

# Ejecutar en Desarrollo

1. Clonar Repo

```
git clone 
```

2. Ejecutar

```
  yarn install
```

3. Tener el Nest CLI instalado

```
  npm i -g @nest/cli
```

4. Levantar la base de datos

```
docker-compose up -d
```
5. Clonar el archivo  __.env.template__ y renombrarla a __.env__

6. Llenar las variables de entorno en el archivo __.env__

7. Correr el proyecto en modo desarrollo

```
yarn start:dev
```

8. Reconstruir la base de datos con el seed data

```
http://localhost:3000/api/v2/seed
```

## Stack Usado

* Mongo DB
* Nest
