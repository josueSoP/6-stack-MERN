### Pasos a seguir

## 1. Clonar o bajar repositorio

## 2. Instalar las dependencias

 -backend:
    
    npm i cors dotenv express mongoose
    npm i nodemon -d

 -Frontend:

`npx create-react-app frontend` (este comando nos creara nuestro backend por default, solo haria falta crear los siguientes 3 modulos)
    
    npm i axios bootstrap timeago.js
O en caso de ya contar con la carpeta Frontend instalar los 3 modulos anteriores y los siguientes
    
    npm i react react-datepicker react-dom react-router-dom react-scripts

## 3. Correr nuestro programa
Para correr el backend se debera de usar en una terminal:
### `npm run dev`
http://localhost:4000/api/notes

Para correr el frontend se debera de usar en otra terminal dentro de la carpeta backend:
### `npm start`
http://localhost:3000
