<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecturar en desarrollo 

1. clonar el proyecto. 
3. ejectuar el comando.

```
yarn install 
```
3. tener el nest CLI instalado en nuestra maquina.

```
npm i -g @nestjs/cli
```

4. levantar la base de datos.

```
docker-compose -d
```

5.Clonar el archivo __.env.template__ y renombrar la copia __.env__

6.Llenar las variables de entorno definidas en el __.env__

7.Ejectuar la apliacion en dev.
```
yarn start:dev
```


8.Reconstruir la base de datos con la semilla 

```
http://localhost:3000/api/v2/seed
```


## Stack usado 

*MongoDB
*Nest
