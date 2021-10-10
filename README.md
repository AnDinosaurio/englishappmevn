# englishappmevn

## software a instalar en el PC

node.js

express

## opcionales

MongoDB compass (permite visualizar la BD y lo que se guarda en la misma, tambien ayuda saber el puerto local asignado: usualm/ 27017)

Postman (útil para hacer pruebas de peticiones al servidor y la base de datos)
si lo usan ver https://bluuweb.github.io/mevn/02-bases-datos/#postman

## Modulos a instalar y correr

npm init --yes

npm install express --save

npm install -g nodemon  (evita que tener que inicializar el server, así se actualiza y relanza ante cualquier cambio)

npm install -D @babel/core @babel/cli @babel/preset-env @babel/node (similar al anterior)

npm i morgan --save (pinta peticiones HTTP)

npm install cors --save (realizar solicitudes de un servidor externo)

npm install --save connect-history-api-fallback

npm install mongoose --save (gestionar esa DB)

npm i bcrypt --save (cifra las contraseñas)

## falta del backend(en ello pero pueden ir instalando)

npm install underscore --save

npm i jsonwebtoken --save


## para Vue

npm install --save axios vue-axios (creo será util) https://bluuweb.github.io/mevn/03-vue/#vue-axios

ayudó algo con backend pero syntaxis vieja(logica bien) https://www.youtube.com/watch?v=ARIzrNwA5HQ

npm run serve (en el navegador vemos nuestro proyecto, creo que puerto 8000 u 8080)
luego de que funcione todo se puede correr
npm run build
esto permite tener los archivos para montar en firebase o heroku, se crea la carpeta dist y todosu contenido se copia en la carpeta public antes de hacer el despliegue







## Montar el servidor

npm run devbabel (queda por defecto en el puerto 3000)

 



