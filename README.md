<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1. Clonar el repositorio

2. Ejecutar 
```
yarn install
```
3. Tener Nest CLI instalado, si no lo tienes, puedes ejecutar:
```
npm i -g @nestjs/cli
```
4. Levandar la base de datos
```
docker-compose up-d
```

5. Clonar el archivo __example.env__ y renombrar la copia a __.env__
```
docker-compose up-d
```

6. Llenar las variables de entorno definidas en el ```.env```


7. Ejecutar la aplicación en modo desarrollo:
```
yarn start:dev
```

8. Reconstruir la base de datos con la semilla
```
http://localhost:3000/api/v2/seed
```



# Stack usado
* MongoDB
* Nest
* Docker