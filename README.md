# Base de API

Base de archivos, carpetas e instalaciones para crear una API basica con Node.js

## Tech Stack
**dependencies**:
Node, Express, bcrypt, cors, dotenv, jsonwebtoken, morgan, sequelize, @hapi/boom.

**devDependencies**: nodemon, sequelize-cli

## Installation

Inicializacion de npm y paquetes necesarios.

```bash
mkdir my_directory_name
cd my_directory_name
npm init -y
npm i express bcryptjs cors dotenv jsonwebtoken morgan sequelize @hapi/boom
npm install nodemon sequelize-cli -D
```
Creacion de directorios y archivos.

```bash
mkdir src
cd src
mkdir router services controllers middlewares libs config db
cd ..
mkdir src/db/models/ src/db/migrations/ src/db/seeders/
cd src
touch index.js app.js db/config.js
cd ..
touch docker-compose.yml .env .sequelizerc .gitignore
```
## Installation Passport

Instalacion de Passport para autenticacion

```bash
npm i passport passport-local passport-jwt
```

## To deploy this project run

En modo desarrollo
```bash
  npm run dev
```


## License
[MIT](https://choosealicense.com/licenses/mit/)