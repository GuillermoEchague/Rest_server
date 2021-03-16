# Desarrollo Rest Server


## Instalar Dependencias

```
npm init -y
npm i express dotenv
npm i cors
npm i mongoose
npm i bcryptjs
npm i express-validator

```


## Ejecutar proyecto en desarrollo

```
nodemon app
```

## Recontruir modulos de Node

```
npm instal
```

## Generar Tags del proyecto

```
git tag -a v1.0.0 -m "Inicio WebServer"
git push --tags
git rm .env --cached (Borrar seguimiento)
```

## Subir a Heroku

```
heroku git:remote -a restserver001node


git branch
git push heroku main
```

## Crear, borrar variables de entorno Heroku
```
heroku --version
heroku config
heroku config:set nombre="Guillermo"
heroku config:unset nombre



```
## Producción

```
https://restserver001node.herokuapp.com/
```